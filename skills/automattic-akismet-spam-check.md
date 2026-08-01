---
name: Classify content with Akismet and train the model
description: Verify an Akismet key, check a comment for spam, and submit missed spam or false positives.
api: openapi/automattic-akismet-openapi.yml
operations: [postVerifyKey, postCommentCheck, postSubmitSpam, postSubmitHam, getUsageLimit, getKeySites]
generated: '2026-07-31'
method: generated
---

# Classify content with Akismet and train the model

## Before you start

- An Akismet API key (https://akismet.com/development/). Authentication is the key itself, sent as
  a request field — there is no OAuth on this API.
- Base URL: `https://rest.akismet.com`.
- Every request must identify the site it is acting for via the `blog` field.

## Steps

1. **Verify the key once at startup** — `postVerifyKey` (`POST /1.1/verify-key`) with `key` and
   `blog`. The response body is the bare string `valid` or `invalid` — **not JSON**. An invalid key
   still returns HTTP 200, so branch on the body, never on the status code.

2. **Classify** — `postCommentCheck` (`POST /1.1/comment-check`) with `blog`, `user_ip`,
   `user_agent`, `comment_type`, `comment_author`, `comment_author_email`, `comment_content` and
   as much request context as you can honestly supply. The body is `true` (spam) or `false` (ham).

3. **When you disagree, train it.**
   - Missed spam that was let through → `postSubmitSpam` (`POST /1.1/submit-spam`).
   - A legitimate message that was flagged → `postSubmitHam` (`POST /1.1/submit-ham`).
   Resubmit the *same* field set you sent in step 2 so the correction is attributable.

4. **Watch your quota** — `getUsageLimit` (`GET /1.2/usage-limit`) and `getKeySites`
   (`GET /1.2/key-sites`) report usage and the sites using the key.

## Rules that matter here

- Akismet does not return a JSON error envelope. Failure detail arrives in the
  `X-akismet-debug-help` response header — log it, because the body alone will not explain a
  rejection.
- There is no test-mode key and no sandbox host: every call counts against the key's usage.
- Accuracy depends on passing through the *original* commenter's IP and user agent, not your
  server's. Do not substitute your own.
- Akismet is a separate product on a separate host; it is **not** exposed through the
  WordPress.com MCP server (see `mcp/automattic-tool-crosswalk.yml`).
