# Automattic

Automattic is the company behind WordPress.com, Jetpack, WooCommerce, Tumblr, Gravatar, Akismet,
WordPress VIP, Pocket Casts, Day One, Beeper and Simplenote.

Its developer platform centres on the **WordPress.com REST API** at `public-api.wordpress.com`,
which serves three parallel namespaces behind one OAuth 2.1 / OpenID Connect authorization server:

| Namespace | Base | Operations |
|---|---|---|
| `/rest/v1.1` (plus additive v1.2 and v1.3) | `https://public-api.wordpress.com/rest/v1.1` | 253 (+38, +19) |
| `/wp/v2` — WordPress core shape, site-scoped | `https://public-api.wordpress.com/wp/v2` | 348 |
| `/wpcom/v2` — WordPress.com and Jetpack extensions | `https://public-api.wordpress.com/wpcom/v2` | 1,716 |

Plus the hosted **WordPress.com MCP server**, the **Akismet API**, the **Jetpack AI-Plugin API**,
and the **WordPress VIP Platform API** (GraphQL, introspection auth-gated).

## Contract provenance

Automattic does not ship OpenAPI for the WordPress.com REST API, but the whole surface is
self-describing:

- `https://public-api.wordpress.com/rest/{v1|v1.1|v1.2|v1.3}/help` with `Accept: application/json`
  returns every endpoint's method, path, description, parameters **and response fields**.
- `https://public-api.wordpress.com/wp/v2/` and `/wpcom/v2/` return WordPress route indexes.

The OpenAPI documents in `openapi/` are derived from those published documents. Two specs are
Automattic's own, saved verbatim: `automattic-akismet-openapi.yml`
(github.com/Automattic/akismet-api) and `automattic-jetpack-ai-plugin-openapi.yaml`
(linked from `/.well-known/ai-plugin.json`).

## Notes for agents

- **No idempotency key** on any namespace — a retried POST duplicates.
- Errors are **not** RFC 9457: `/rest/v1.x` returns `{error, message}`; `/wp/v2` and `/wpcom/v2`
  return `{code, message, data:{status}}`.
- `http_envelope=true` forces HTTP 200 and moves the real status into the body.
- No rate-limit headers and no published quota.
- No A2A agent card is published on any Automattic host.

- https://developer.wordpress.com/docs/api/
- https://developer.wordpress.com/docs/mcp/
- https://automattic.com/
