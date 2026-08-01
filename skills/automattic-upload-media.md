---
name: Upload media and attach it to a post
description: Upload a file to a WordPress.com site's media library and set it as a post's featured image.
api: openapi/automattic-wordpress-com-rest-v1-1-openapi.yml
operations: [getMeSites, postSitesBySiteMediaNew, getSitesBySiteMedia, getSitesBySiteMediaByMediaId, postSitesBySitePostsByPostId]
generated: '2026-07-31'
method: generated
---

# Upload media and attach it to a post

## Before you start

- OAuth 2.1 bearer token with the `media` scope (plus `posts` for step 4). See
  `authentication/automattic-authentication.yml`.
- Base URL: `https://public-api.wordpress.com/rest/v1.1`.

## Steps

1. **Pick the site** — `getMeSites` (`GET /me/sites`). Check `quota` on the site object first
   (`getSitesBySite`, `GET /sites/{site}`) — uploads fail once space is exhausted.

2. **Upload** — `postSitesBySiteMediaNew` (`POST /sites/{site}/media/new`).
   Accepts either a `media` file upload (multipart) or a `media_urls` list for remote fetch, plus
   an `attrs` array carrying per-item `title`, `caption`, `alt` and `description`.

3. **Read back the media object** — `getSitesBySiteMediaByMediaId`
   (`GET /sites/{site}/media/{media_ID}`). Keep `ID`, `URL`, `mime_type`, `width`, `height` and
   `thumbnails`.

4. **Attach it** — `postSitesBySitePostsByPostId` (`POST /sites/{site}/posts/{post_ID}`) with
   `featured_image` set to the media `ID` from step 3.

5. **Audit** — `getSitesBySiteMedia` (`GET /sites/{site}/media/`) with `mime_type` and `number`
   to list what is in the library.

## Rules that matter here

- Uploads are **not idempotent**. A retried upload creates a duplicate media item with a new `ID`.
  Before retrying, list `getSitesBySiteMedia` with a `search` on the filename.
- The media object's `post_ID` links it back to the post it was uploaded against, and `author_ID`
  to the uploading user — see `data-model/automattic-data-model.yml`.
- Video items carry `videopress_guid` and `videopress_processing_done`; do not treat an upload as
  ready for embedding until processing is done.
- `404 unknown_blog` on this family almost always means the `{site}` segment is a domain the token
  cannot see, not that the media is missing.
