---
name: Triage and moderate comments
description: List a site's pending comments, inspect one, approve or unapprove it, and delete spam.
api: openapi/automattic-wordpress-com-rest-v1-1-openapi.yml
operations: [getSitesBySiteComments, getSitesBySiteCommentsByCommentId, postSitesBySiteCommentsByCommentId, postSitesBySiteCommentsByCommentIdDelete, getSitesBySiteCommentsTree]
generated: '2026-07-31'
method: generated
---

# Triage and moderate comments

## Before you start

- OAuth 2.1 bearer token with the `comments` scope, on an account with moderation capability on
  the target site.
- Base URL: `https://public-api.wordpress.com/rest/v1.1`.

## Steps

1. **List what needs attention** — `getSitesBySiteComments` (`GET /sites/{site}/comments/`).
   Filter with `status` (`approved`, `unapproved`, `spam`, `trash`, `all`), `number`, `page`,
   `after`. The response carries a `found` total alongside the `comments` array.

2. **Inspect one** — `getSitesBySiteCommentsByCommentId`
   (`GET /sites/{site}/comments/{comment_ID}`). `can_moderate` on the response tells you whether
   the token holder may act; check it before attempting a write. `raw_content` gives the
   unprocessed body, `content` the display-formatted HTML.

3. **Decide.** For thread context use `getSitesBySiteCommentsTree`
   (`GET /sites/{site}/comments-tree`) to see parents and replies.

4. **Act** — `postSitesBySiteCommentsByCommentId`
   (`POST /sites/{site}/comments/{comment_ID}`) to change `status` (approve / unapprove / spam /
   trash) or edit `content`.

5. **Delete** — `postSitesBySiteCommentsByCommentIdDelete`
   (`POST /sites/{site}/comments/{comment_ID}/delete`) for a permanent removal. This is
   destructive and has no undo — require explicit human confirmation before calling it.

## Rules that matter here

- Marking a comment as spam here does **not** teach Akismet. To train the classifier, pair this
  with the Akismet skill (`skills/automattic-akismet-spam-check.md`) and call `postSubmitSpam` /
  `postSubmitHam`.
- `can_moderate: false` will surface as `403 authorization_required` if you write anyway.
- Comments are addressed per site; a comment `ID` is not globally unique across WordPress.com.
- No idempotency key: a repeated delete after a timeout returns an error rather than silently
  succeeding — re-read the comment with step 2 to establish state instead of retrying blind.
