---
name: Publish a post to a WordPress.com site
description: Authenticate against WordPress.com, pick the target site, create a post, and verify it published.
api: openapi/automattic-wordpress-com-rest-v1-1-openapi.yml
operations: [getMe, getMeSites, postSitesBySitePostsNew, getSitesBySitePostsByPostId, postSitesBySitePostsByPostId]
generated: '2026-07-31'
method: generated
---

# Publish a post to a WordPress.com site

## Before you start

- Get an OAuth 2.1 access token from `https://public-api.wordpress.com/oauth2-1/token`
  (authorization code + PKCE `S256`). Discovery:
  `https://public-api.wordpress.com/.well-known/openid-configuration`.
- Send it as `Authorization: Bearer <token>` on every call.
- You need the `posts` scope to write, and `sites` to enumerate sites. `global` covers both.
- Base URL: `https://public-api.wordpress.com/rest/v1.1`.

## Steps

1. **Confirm the identity behind the token** — `getMe` (`GET /me`).
   Read `token_scope` and `token_site_id` off the response. If `token_site_id` is set, the token is
   scoped to a single site and step 2 is unnecessary — use that site ID.

2. **Find the target site** — `getMeSites` (`GET /me/sites`).
   Each entry carries `ID`, `URL` and `capabilities`. Only continue with a site whose
   `capabilities.publish_posts` is true. Every site-scoped path accepts either the numeric `ID`
   or the domain in the `{site}` segment.

3. **Create the post** — `postSitesBySitePostsNew` (`POST /sites/{site}/posts/new`).
   Useful body fields: `title`, `content`, `excerpt`, `status` (`publish`, `draft`, `pending`,
   `private`, `future`), `date`, `slug`, `categories`, `tags`, `featured_image`, `format`.
   Set `status: draft` first when the content is agent-authored and a human should review it.

4. **Verify** — `getSitesBySitePostsByPostId` (`GET /sites/{site}/posts/{post_ID}`) with the `ID`
   returned in step 3. Check `status` and `URL`.

5. **Amend if needed** — `postSitesBySitePostsByPostId`
   (`POST /sites/{site}/posts/{post_ID}`) applies a partial update to an existing post.

## Rules that matter here

- **There is no idempotency key.** Retrying step 3 after a timeout creates a *second* post. On an
  ambiguous failure, do **not** blind-retry: call `getSitesBySitePosts`
  (`GET /sites/{site}/posts/`) filtered by `search` or `after` and check whether the post landed.
- **Read the body, not just the status**, if any caller set `http_envelope=true` — that parameter
  forces HTTP 200 and moves the real status into the JSON body.
- Errors on this namespace are `{"error": "...", "message": "..."}` — not RFC 9457. `403
  authorization_required` means the token is missing or unscoped; `404 unknown_blog` means the
  `{site}` segment is wrong. See `errors/automattic-problem-types.yml`.
- Use `fields=ID,title,URL,status` to trim large post payloads, and `meta=site,likes` to inline
  related resources.
- No rate-limit headers are published. Back off on your own schedule and honour
  https://developer.wordpress.com/docs/api/guidelines-for-responsible-use-of-automattics-apis/.
