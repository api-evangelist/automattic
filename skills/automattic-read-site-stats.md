---
name: Read a WordPress.com site's traffic stats
description: Pull a site's summary stats, top posts and search terms for a reporting window.
api: openapi/automattic-wordpress-com-rest-v1-1-openapi.yml
operations: [getSitesBySite, getSitesBySiteStats, getSitesBySiteStatsTopPosts, getSitesBySiteStatsSearchTerms, getMeSites]
generated: '2026-07-31'
method: generated
---

# Read a WordPress.com site's traffic stats

## Before you start

- OAuth 2.1 bearer token with the `stats` scope, on an account that can view stats for the site.
- Base URL: `https://public-api.wordpress.com/rest/v1.1`.

## Steps

1. **Resolve the site** — `getMeSites` (`GET /me/sites`), then `getSitesBySite`
   (`GET /sites/{site}`) for `name`, `URL`, `post_count`, `subscribers_count` and `plan`.
   Some stats surfaces are plan-gated; read `plan` before promising a metric.

2. **Summary** — `getSitesBySiteStats` (`GET /sites/{site}/stats`). Returns visit/view rollups
   plus a `stats` block. Use `fields` to trim the payload.

3. **Top content** — `getSitesBySiteStatsTopPosts` (`GET /sites/{site}/stats/top-posts`) with
   `period` (`day`, `week`, `month`, `year`), `date` and `num` to walk a window.

4. **Search terms** — `getSitesBySiteStatsSearchTerms`
   (`GET /sites/{site}/stats/search-terms`), same `period`/`date`/`num` shape.

## Rules that matter here

- These are read-only endpoints — safe for an agent to call without escalation.
- The `{site}` segment takes a numeric site ID or a domain; prefer the numeric ID when a site may
  have moved domains, because stats are keyed to the site, not the URL.
- WordPress.com publishes **no rate-limit headers and no quota**. When walking a long window,
  pace requests yourself rather than parallelising, per Automattic's responsible-use policy.
- All stats windows are relative to the site's configured timezone, not UTC — anchor the `date`
  parameter explicitly instead of relying on "today".
