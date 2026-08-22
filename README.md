# Automattic

<!-- API-EVANGELIST-PROVENANCE:BEGIN -->
> ### About this repository
>
> **This is not our API.** This repository is an independent, third-party profile of a company's
> **publicly available** API surface, maintained by [API Evangelist](https://apievangelist.com).
> API Evangelist does not operate, host, resell, or support this company's APIs, and is not
> affiliated with or endorsed by the company unless stated on the profile.
>
> **Where the information came from.** Everything here is assembled from material a member of the
> public can reach with a browser and no credentials — the company's own website, developer portal
> and documentation, the specifications it publishes for public use (OpenAPI, AsyncAPI, JSON Schema,
> `apis.json`, `llms.txt` and similar), its public repositories, and its public status, pricing and
> changelog pages. **Nothing here is obtained by breaching a system, defeating an access control, or
> using credentials of any kind.**
>
> **The rating is an independent assessment.** The Kin Score and Agent Readiness rating are
> independently calculated scores of a company's *public* API artifacts, produced by API Evangelist
> against a published rubric. They are not certifications, endorsements, security assessments, or
> audits, and they score published artifacts — not the quality, safety, or security of the software.
>
> **Corrections, re-scores, and removal are free.** No partnership, contract, or purchase is
> required, and you do not need to justify the request.
>
> - **Something wrong?** Open an issue on this repository, or email
>   [info@apievangelist.com](mailto:info@apievangelist.com).
> - **Published something new?** Ask for a re-score and we will re-run the rating.
> - **Want the listing taken down?** Say so and we will honor it. The profile is reduced to your
>   company name, a factual description, and a link to your own site, and the company is recorded as
>   **unrated** — never scored zero for having asked.
>
> **Response times.** Acknowledgement within **one business day**; removal or restriction within
> **two business days**; corrections and re-scores within **five business days**.
>
> **Not from the company, and here with a question?** You are welcome here — we would rather be the
> front line and point you the right way than have a good report go nowhere. What this repository
> can answer is narrow, though, so it is worth knowing who you are actually looking for:
>
> - **A question about how the API works, an account, billing, or a bug in the service** — that is
>   the company's own support, not us. We profile this API; we do not operate it and cannot see
>   your account.
> - **A bug in an open-source project we only catalog** — file it on that project's own repository.
>   This has happened with a real and correct bug report that reached us instead of the people who
>   could fix it, which helped nobody.
> - **Anything about this listing itself** — the description, the tags, the rating, a missing or
>   wrong artifact — is ours. Open an issue here.
> - **Not sure, or something general about API Evangelist or APIs.io** — open an issue on the
>   [APIs.io Inbox](https://github.com/api-search/inbox) and we will route it.
>
> **This repository contains no software, and we will never ask you to download anything.** There is
> no build, release, installer, or binary here — only text and machine-readable API descriptions, so
> there is nothing here that can be "corrupt" or need "repairing". Any issue, comment, or email
> claiming otherwise and offering a download link is not from us and is hostile. Do not follow the
> link; it is a lure. Report it to GitHub and, if you like, tell us at
> [info@apievangelist.com](mailto:info@apievangelist.com) so we can take it down.
>
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

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
