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

Automattic is the company behind WordPress.com, Jetpack, WooCommerce, Tumblr, Gravatar, Akismet, WordPress VIP, Pocket Casts, Day One, Beeper and Simplenote. Its developer platform centres on the WordPress.com REST API at public-api.wordpress.com, which serves three parallel namespaces — the WordPress.com-native /rest/v1.x family, the WordPress-core-compatible /wp/v2 family, and the WordPress.com and Jetpack platform extensions in /wpcom/v2 — all behind a single OAuth 2.1 and OpenID Connect authorization server with PKCE, dynamic client registration and resource indicators. Every /rest/ version publishes a machine-readable help document and every /wp/ and /wpcom/ namespace publishes a route index, so the whole surface is self-describing even though Automattic does not ship OpenAPI for it. Automattic also runs a hosted Model Context Protocol server for WordPress.com, publishes OpenAPI for Akismet and for the Jetpack ai-plugin surface, and exposes a GraphQL Platform API for the enterprise WordPress VIP product.

**Areas:** Company · Content Management · Publishing · Blogging · Website Hosting · Web Publishing · Content · Comments · Spam Filtering · Media · Analytics · Domains

## Automattic on APIs.io

Everything profiled for Automattic is published on APIs.io rather than in this repository. Start at the provider page — **[apis.io/providers/automattic/](https://apis.io/providers/automattic/)** — or go straight to one of the APIs or properties below.

### APIs (385)

- [WordPress.com MCP Server](https://apis.io/apis/automattic/wordpresscom-mcp-server/) — Automattic's hosted Model Context Protocol server for WordPress.com. Streamable HTTP transport secured with OAuth 2.1 (PKCE S256, dynamic client…
- [WordPress VIP Platform API](https://apis.io/apis/automattic/wordpress-vip-platform-api/) — The GraphQL API for WordPress VIP, Automattic's enterprise WordPress and Node.js platform. Documented operation categories cover apps, domains,…
- [Automattic A8c Lore API](https://apis.io/apis/automattic/automattic-a8c-lore-api/) — The a8c-lore API from Automattic — 2 operation(s) for a8c-lore.
- [Automattic A8cmentorship API](https://apis.io/apis/automattic/automattic-a8cmentorship-api/) — The a8cmentorship API from Automattic — 1 operation(s) for a8cmentorship.
- [Automattic Abilities API](https://apis.io/apis/automattic/automattic-abilities-api/) — The abilities API from Automattic — 1 operation(s) for abilities.
- [Automattic Activity API](https://apis.io/apis/automattic/automattic-activity-api/) — The activity API from Automattic — 8 operation(s) for activity.
- [Automattic Activity Log Events API](https://apis.io/apis/automattic/automattic-activity-log-events-api/) — The activity-log-events API from Automattic — 4 operation(s) for activity-log-events.
- [Automattic Activitypub API](https://apis.io/apis/automattic/automattic-activitypub-api/) — The activitypub API from Automattic — 1 operation(s) for activitypub.
- [Automattic Adflow API](https://apis.io/apis/automattic/automattic-adflow-api/) — The adflow API from Automattic — 1 operation(s) for adflow.
- [Automattic Admin Bar API](https://apis.io/apis/automattic/automattic-admin-bar-api/) — The admin-bar API from Automattic — 1 operation(s) for admin-bar.
- [Automattic Admin Color API](https://apis.io/apis/automattic/automattic-admin-color-api/) — The admin-color API from Automattic — 1 operation(s) for admin-color.
- [Automattic Admin Menu API](https://apis.io/apis/automattic/automattic-admin-menu-api/) — The admin-menu API from Automattic — 1 operation(s) for admin-menu.
- [Automattic Agency API](https://apis.io/apis/automattic/automattic-agency-api/) — The agency API from Automattic — 88 operation(s) for agency.
- [Automattic Agency Client API](https://apis.io/apis/automattic/automattic-agency-client-api/) — The agency-client API from Automattic — 8 operation(s) for agency-client.
- [Automattic Agents Manager API](https://apis.io/apis/automattic/automattic-agents-manager-api/) — The agents-manager API from Automattic — 1 operation(s) for agents-manager.
- [Automattic AI Agents Settings API](https://apis.io/apis/automattic/automattic-ai-agents-settings-api/) — The ai-agents-settings API from Automattic — 1 operation(s) for ai-agents-settings.
- [Automattic AI API](https://apis.io/apis/automattic/automattic-ai-api/) — The ai API from Automattic — 17 operation(s) for ai.
- [Automattic AI Image API](https://apis.io/apis/automattic/automattic-ai-image-api/) — The ai-image API from Automattic — 1 operation(s) for ai-image.
- [Automattic AI Launchpad API](https://apis.io/apis/automattic/automattic-ai-launchpad-api/) — The ai-launchpad API from Automattic — 6 operation(s) for ai-launchpad.
- [Automattic Akismet API](https://apis.io/apis/automattic/automattic-akismet-api/) — The akismet API from Automattic — 1 operation(s) for akismet.
- [Automattic Alerts API](https://apis.io/apis/automattic/automattic-alerts-api/) — The alerts API from Automattic — 3 operation(s) for alerts.
- [Automattic Alternates API](https://apis.io/apis/automattic/automattic-alternates-api/) — The alternates API from Automattic — 1 operation(s) for alternates.
- [Automattic Analytics API](https://apis.io/apis/automattic/automattic-analytics-api/) — The analytics API from Automattic — 25 operation(s) for analytics.
- [Automattic Analyze URL API](https://apis.io/apis/automattic/automattic-analyze-url-api/) — The analyze-url API from Automattic — 1 operation(s) for analyze-url.
- [Automattic App Media API](https://apis.io/apis/automattic/automattic-app-media-api/) — The app-media API from Automattic — 1 operation(s) for app-media.
- [Automattic Articles API](https://apis.io/apis/automattic/automattic-articles-api/) — The articles API from Automattic — 1 operation(s) for articles.
- [Automattic Atomic API](https://apis.io/apis/automattic/automattic-atomic-api/) — The atomic API from Automattic — 2 operation(s) for atomic.
- [Automattic Atomic Migration Status API](https://apis.io/apis/automattic/automattic-atomic-migration-status-api/) — The atomic-migration-status API from Automattic — 3 operation(s) for atomic-migration-status.
- [Automattic Auth API](https://apis.io/apis/automattic/automattic-auth-api/) — The auth API from Automattic — 8 operation(s) for auth.
- [Automattic Automated Migration API](https://apis.io/apis/automattic/automattic-automated-migration-api/) — The automated-migration API from Automattic — 6 operation(s) for automated-migration.
- [Automattic Backup API](https://apis.io/apis/automattic/automattic-backup-api/) — The backup API from Automattic — 1 operation(s) for backup.
- [Automattic Batch API](https://apis.io/apis/automattic/automattic-batch-api/) — The batch API from Automattic — 1 operation(s) for batch.
- [Automattic Big Sky API](https://apis.io/apis/automattic/automattic-big-sky-api/) — The big-sky API from Automattic — 11 operation(s) for big-sky.
- [Automattic Blaze API](https://apis.io/apis/automattic/automattic-blaze-api/) — The blaze API from Automattic — 5 operation(s) for blaze.
- [Automattic Block Directory API](https://apis.io/apis/automattic/automattic-block-directory-api/) — The block-directory API from Automattic — 1 operation(s) for block-directory.
- [Automattic Block Editor API](https://apis.io/apis/automattic/automattic-block-editor-api/) — The block-editor API from Automattic — 6 operation(s) for block-editor.
- [Automattic Block Layouts API](https://apis.io/apis/automattic/automattic-block-layouts-api/) — The block-layouts API from Automattic — 1 operation(s) for block-layouts.
- [Automattic Block Patterns API](https://apis.io/apis/automattic/automattic-block-patterns-api/) — The block-patterns API from Automattic — 2 operation(s) for block-patterns.
- [Automattic Block Previews API](https://apis.io/apis/automattic/automattic-block-previews-api/) — The block-previews API from Automattic — 2 operation(s) for block-previews.
- [Automattic Block Recipes API](https://apis.io/apis/automattic/automattic-block-recipes-api/) — The block-recipes API from Automattic — 2 operation(s) for block-recipes.
- [Automattic Block Renderer API](https://apis.io/apis/automattic/automattic-block-renderer-api/) — The block-renderer API from Automattic — 4 operation(s) for block-renderer.
- [Automattic Block Types API](https://apis.io/apis/automattic/automattic-block-types-api/) — The block-types API from Automattic — 3 operation(s) for block-types.
- [Automattic Blocks API](https://apis.io/apis/automattic/automattic-blocks-api/) — The blocks API from Automattic — 6 operation(s) for blocks.
- [Automattic Blog Stats API](https://apis.io/apis/automattic/automattic-blog-stats-api/) — The blog-stats API from Automattic — 1 operation(s) for blog-stats.
- [Automattic Blogging Prompts API](https://apis.io/apis/automattic/automattic-blogging-prompts-api/) — The blogging-prompts API from Automattic — 2 operation(s) for blogging-prompts.
- [Automattic Blueprint Archive API](https://apis.io/apis/automattic/automattic-blueprint-archive-api/) — The blueprint-archive API from Automattic — 1 operation(s) for blueprint-archive.
- [Automattic Blueprint Archive Import API](https://apis.io/apis/automattic/automattic-blueprint-archive-import-api/) — The blueprint-archive-import API from Automattic — 1 operation(s) for blueprint-archive-import.
- [Automattic Breakingbot API](https://apis.io/apis/automattic/automattic-breakingbot-api/) — The breakingbot API from Automattic — 2 operation(s) for breakingbot.
- [Automattic Business Hours API](https://apis.io/apis/automattic/automattic-business-hours-api/) — The business-hours API from Automattic — 1 operation(s) for business-hours.
- [Automattic Calypso Slack Channel Status API](https://apis.io/apis/automattic/automattic-calypso-slack-channel-status-api/) — The calypso-slack-channel-status API from Automattic — 1 operation(s) for calypso-slack-channel-status.
- [Automattic Categories API](https://apis.io/apis/automattic/automattic-categories-api/) — The categories API from Automattic — 2 operation(s) for categories.
- [Automattic Ceo Voice Agent API](https://apis.io/apis/automattic/automattic-ceo-voice-agent-api/) — The ceo-voice-agent API from Automattic — 3 operation(s) for ceo-voice-agent.
- [Automattic Check Google Doc Visibility API](https://apis.io/apis/automattic/automattic-checkgoogledocvisibility-api/) — The checkGoogleDocVisibility API from Automattic — 1 operation(s) for checkgoogledocvisibility.
- [Automattic Ciab API](https://apis.io/apis/automattic/automattic-ciab-api/) — The ciab API from Automattic — 1 operation(s) for ciab.
- [Automattic Cmp API](https://apis.io/apis/automattic/automattic-cmp-api/) — The cmp API from Automattic — 3 operation(s) for cmp.
- [Automattic Colors API](https://apis.io/apis/automattic/automattic-colors-api/) — The colors API from Automattic — 4 operation(s) for colors.
- [Automattic Coming Soon API](https://apis.io/apis/automattic/automattic-coming-soon-api/) — The coming-soon API from Automattic — 1 operation(s) for coming-soon.
- [Automattic Comments API](https://apis.io/apis/automattic/automattic-comments-api/) — The comments API from Automattic — 14 operation(s) for comments.
- [Automattic Comments Tree API](https://apis.io/apis/automattic/automattic-comments-tree-api/) — The comments-tree API from Automattic — 1 operation(s) for comments-tree.
- [Automattic Commercial Classification API](https://apis.io/apis/automattic/automattic-commercial-classification-api/) — The commercial-classification API from Automattic — 1 operation(s) for commercial-classification.
- [Automattic Common Block Layouts API](https://apis.io/apis/automattic/automattic-common-block-layouts-api/) — The common-block-layouts API from Automattic — 1 operation(s) for common-block-layouts.
- [Automattic Common Starter Site Designs API](https://apis.io/apis/automattic/automattic-common-starter-site-designs-api/) — The common-starter-site-designs API from Automattic — 1 operation(s) for common-starter-site-designs.
- [Automattic Concierge API](https://apis.io/apis/automattic/automattic-concierge-api/) — The concierge API from Automattic — 11 operation(s) for concierge.
- [Automattic Content Research API](https://apis.io/apis/automattic/automattic-content-research-api/) — The content-research API from Automattic — 2 operation(s) for content-research.
- [Automattic Copy From Site API](https://apis.io/apis/automattic/automattic-copy-from-site-api/) — The copy-from-site API from Automattic — 1 operation(s) for copy-from-site.
- [Automattic Country Codes API](https://apis.io/apis/automattic/automattic-country-codes-api/) — The country-codes API from Automattic — 1 operation(s) for country-codes.
- [Automattic Courses API](https://apis.io/apis/automattic/automattic-courses-api/) — The courses API from Automattic — 2 operation(s) for courses.
- [Automattic Currency Overrides API](https://apis.io/apis/automattic/automattic-currency-overrides-api/) — The currency-overrides API from Automattic — 1 operation(s) for currency-overrides.
- [Automattic Dashboard API](https://apis.io/apis/automattic/automattic-dashboard-api/) — The dashboard API from Automattic — 5 operation(s) for dashboard.
- [Automattic Dashboards API](https://apis.io/apis/automattic/automattic-dashboards-api/) — The dashboards API from Automattic — 3 operation(s) for dashboards.
- [Automattic Deepl API](https://apis.io/apis/automattic/automattic-deepl-api/) — The deepl API from Automattic — 1 operation(s) for deepl.
- [Automattic Dictation Client Secret API](https://apis.io/apis/automattic/automattic-dictation-client-secret-api/) — The dictation-client-secret API from Automattic — 3 operation(s) for dictation-client-secret.
- [Automattic Discount API](https://apis.io/apis/automattic/automattic-discount-api/) — The discount API from Automattic — 1 operation(s) for discount.
- [Automattic Do It For Me API](https://apis.io/apis/automattic/automattic-do-it-for-me-api/) — The do-it-for-me API from Automattic — 1 operation(s) for do-it-for-me.
- [Automattic Domain Connect API](https://apis.io/apis/automattic/automattic-domain-connect-api/) — The domain-connect API from Automattic — 5 operation(s) for domain-connect.
- [Automattic Domains API](https://apis.io/apis/automattic/automattic-domains-api/) — The domains API from Automattic — 25 operation(s) for domains.
- [Automattic Editor API](https://apis.io/apis/automattic/automattic-editor-api/) — The editor API from Automattic — 1 operation(s) for editor.
- [Automattic Editor Assets API](https://apis.io/apis/automattic/automattic-editor-assets-api/) — The editor-assets API from Automattic — 1 operation(s) for editor-assets.
- [Automattic Email Like API](https://apis.io/apis/automattic/automattic-email-like-api/) — The email-like API from Automattic — 1 operation(s) for email-like.
- [Automattic Email Preview API](https://apis.io/apis/automattic/automattic-email-preview-api/) — The email-preview API from Automattic — 1 operation(s) for email-preview.
- [Automattic Emails API](https://apis.io/apis/automattic/automattic-emails-api/) — The emails API from Automattic — 10 operation(s) for emails.
- [Automattic Enterpret Webhook API](https://apis.io/apis/automattic/automattic-enterpret-webhook-api/) — The enterpret-webhook API from Automattic — 1 operation(s) for enterpret-webhook.
- [Automattic Experiments API](https://apis.io/apis/automattic/automattic-experiments-api/) — The experiments API from Automattic — 29 operation(s) for experiments.
- [Automattic External Contributors API](https://apis.io/apis/automattic/automattic-external-contributors-api/) — The external-contributors API from Automattic — 3 operation(s) for external-contributors.
- [Automattic External Media API](https://apis.io/apis/automattic/automattic-external-media-api/) — The external-media API from Automattic — 7 operation(s) for external-media.
- [Automattic External Services API](https://apis.io/apis/automattic/automattic-external-services-api/) — The external-services API from Automattic — 1 operation(s) for external-services.
- [Automattic Feedback API](https://apis.io/apis/automattic/automattic-feedback-api/) — The feedback API from Automattic — 14 operation(s) for feedback.
- [Automattic Follow API](https://apis.io/apis/automattic/automattic-follow-api/) — The follow API from Automattic — 4 operation(s) for follow.
- [Automattic Following API](https://apis.io/apis/automattic/automattic-following-api/) — The following API from Automattic — 2 operation(s) for following.
- [Automattic Font Collections API](https://apis.io/apis/automattic/automattic-font-collections-api/) — The font-collections API from Automattic — 2 operation(s) for font-collections.
- [Automattic Font Families API](https://apis.io/apis/automattic/automattic-font-families-api/) — The font-families API from Automattic — 4 operation(s) for font-families.
- [Automattic Freshly Pressed API](https://apis.io/apis/automattic/automattic-freshly-pressed-api/) — The freshly-pressed API from Automattic — 1 operation(s) for freshly-pressed.
- [Automattic Fsor Airtable Report API](https://apis.io/apis/automattic/automattic-fsor-airtable-report-api/) — The fsor-airtable-report API from Automattic — 1 operation(s) for fsor-airtable-report.
- [Automattic General API](https://apis.io/apis/automattic/automattic-general-api/) — The general API from Automattic — 5 operation(s) for general.
- [Automattic Github API](https://apis.io/apis/automattic/automattic-github-api/) — The github API from Automattic — 2 operation(s) for github.
- [Automattic Global Styles API](https://apis.io/apis/automattic/automattic-global-styles-api/) — The global-styles API from Automattic — 6 operation(s) for global-styles.
- [Automattic Global Styles Variation API](https://apis.io/apis/automattic/automattic-global-styles-variation-api/) — The global-styles-variation API from Automattic — 5 operation(s) for global-styles-variation.
- [Automattic Glossary API](https://apis.io/apis/automattic/automattic-glossary-api/) — The glossary API from Automattic — 2 operation(s) for glossary.
- [Automattic Goodreads API](https://apis.io/apis/automattic/automattic-goodreads-api/) — The goodreads API from Automattic — 1 operation(s) for goodreads.
- [Automattic Google Drive API](https://apis.io/apis/automattic/automattic-google-drive-api/) — The google-drive API from Automattic — 2 operation(s) for google-drive.
- [Automattic Grafana API](https://apis.io/apis/automattic/automattic-grafana-api/) — The grafana API from Automattic — 1 operation(s) for grafana.
- [Automattic Gravatar API](https://apis.io/apis/automattic/automattic-gravatar-api/) — The gravatar API from Automattic — 13 operation(s) for gravatar.
- [Automattic Gravatar Upload API](https://apis.io/apis/automattic/automattic-gravatar-upload-api/) — The gravatar-upload API from Automattic — 1 operation(s) for gravatar-upload.
- [Automattic Guidelines API](https://apis.io/apis/automattic/automattic-guidelines-api/) — The guidelines API from Automattic — 6 operation(s) for guidelines.
- [Automattic Gutenberg API](https://apis.io/apis/automattic/automattic-gutenberg-api/) — The gutenberg API from Automattic — 3 operation(s) for gutenberg.
- [Automattic Gutenpen API](https://apis.io/apis/automattic/automattic-gutenpen-api/) — The gutenpen API from Automattic — 3 operation(s) for gutenpen.
- [Automattic Hello API](https://apis.io/apis/automattic/automattic-hello-api/) — The hello API from Automattic — 1 operation(s) for hello.
- [Automattic Help API](https://apis.io/apis/automattic/automattic-help-api/) — The help API from Automattic — 22 operation(s) for help.
- [Automattic Home API](https://apis.io/apis/automattic/automattic-home-api/) — The home API from Automattic — 2 operation(s) for home.
- [Automattic Host Partners API](https://apis.io/apis/automattic/automattic-host-partners-api/) — The host-partners API from Automattic — 39 operation(s) for host-partners.
- [Automattic Hosting API](https://apis.io/apis/automattic/automattic-hosting-api/) — The hosting API from Automattic — 23 operation(s) for hosting.
- [Automattic Hosting Provider API](https://apis.io/apis/automattic/automattic-hosting-provider-api/) — The hosting-provider API from Automattic — 1 operation(s) for hosting-provider.
- [Automattic Iap API](https://apis.io/apis/automattic/automattic-iap-api/) — The iap API from Automattic — 3 operation(s) for iap.
- [Automattic Icon Collections API](https://apis.io/apis/automattic/automattic-icon-collections-api/) — The icon-collections API from Automattic — 2 operation(s) for icon-collections.
- [Automattic Icons API](https://apis.io/apis/automattic/automattic-icons-api/) — The icons API from Automattic — 3 operation(s) for icons.
- [Automattic Import API](https://apis.io/apis/automattic/automattic-import-api/) — The import API from Automattic — 4 operation(s) for import.
- [Automattic Imports API](https://apis.io/apis/automattic/automattic-imports-api/) — The imports API from Automattic — 2 operation(s) for imports.
- [Automattic Individual Subscriber Stats API](https://apis.io/apis/automattic/automattic-individual-subscriber-stats-api/) — The individual-subscriber-stats API from Automattic — 1 operation(s) for individual-subscriber-stats.
- [Automattic Insights API](https://apis.io/apis/automattic/automattic-insights-api/) — The insights API from Automattic — 2 operation(s) for insights.
- [Automattic Instagram API](https://apis.io/apis/automattic/automattic-instagram-api/) — The instagram API from Automattic — 3 operation(s) for instagram.
- [Automattic Instagram Gallery API](https://apis.io/apis/automattic/automattic-instagram-gallery-api/) — The instagram-gallery API from Automattic — 3 operation(s) for instagram-gallery.
- [Automattic Introductory Offers API](https://apis.io/apis/automattic/automattic-introductory-offers-api/) — The introductory-offers API from Automattic — 1 operation(s) for introductory-offers.
- [Automattic Invites API](https://apis.io/apis/automattic/automattic-invites-api/) — The invites API from Automattic — 7 operation(s) for invites.
- [Automattic Ip To Geo API](https://apis.io/apis/automattic/automattic-ip-to-geo-api/) — The ip-to-geo API from Automattic — 1 operation(s) for ip-to-geo.
- [Automattic Jetpack About API](https://apis.io/apis/automattic/automattic-jetpack-about-api/) — The jetpack-about API from Automattic — 1 operation(s) for jetpack-about.
- [Automattic Jetpack Active Connected Plugins API](https://apis.io/apis/automattic/automattic-jetpack-active-connected-plugins-api/) — The jetpack-active-connected-plugins API from Automattic — 1 operation(s) for jetpack-active-connected-plugins.
- [Automattic Jetpack Agency API](https://apis.io/apis/automattic/automattic-jetpack-agency-api/) — The jetpack-agency API from Automattic — 8 operation(s) for jetpack-agency.
- [Automattic Jetpack AI API](https://apis.io/apis/automattic/automattic-jetpack-ai-api/) — The jetpack-ai API from Automattic — 6 operation(s) for jetpack-ai.
- [Automattic Jetpack AI Image API](https://apis.io/apis/automattic/automattic-jetpack-ai-image-api/) — The jetpack-ai-image API from Automattic — 1 operation(s) for jetpack-ai-image.
- [Automattic Jetpack AI Query API](https://apis.io/apis/automattic/automattic-jetpack-ai-query-api/) — The jetpack-ai-query API from Automattic — 1 operation(s) for jetpack-ai-query.
- [Automattic Jetpack AI Transcription API](https://apis.io/apis/automattic/automattic-jetpack-ai-transcription-api/) — The jetpack-ai-transcription API from Automattic — 1 operation(s) for jetpack-ai-transcription.
- [Automattic Jetpack API](https://apis.io/apis/automattic/automattic-jetpack-api/) — The jetpack API from Automattic — 2 operation(s) for jetpack.
- [Automattic Jetpack Boost API](https://apis.io/apis/automattic/automattic-jetpack-boost-api/) — The jetpack-boost API from Automattic — 13 operation(s) for jetpack-boost.
- [Automattic Jetpack Boost Proxy API](https://apis.io/apis/automattic/automattic-jetpack-boost-proxy-api/) — The jetpack-boost-proxy API from Automattic — 4 operation(s) for jetpack-boost-proxy.
- [Automattic Jetpack Clone Settings API](https://apis.io/apis/automattic/automattic-jetpack-clone-settings-api/) — The jetpack-clone-settings API from Automattic — 1 operation(s) for jetpack-clone-settings.
- [Automattic Jetpack Connect API](https://apis.io/apis/automattic/automattic-jetpack-connect-api/) — The jetpack-connect API from Automattic — 1 operation(s) for jetpack-connect.
- [Automattic Jetpack Connection Health API](https://apis.io/apis/automattic/automattic-jetpack-connection-health-api/) — The jetpack-connection-health API from Automattic — 1 operation(s) for jetpack-connection-health.
- [Automattic Jetpack Forms API](https://apis.io/apis/automattic/automattic-jetpack-forms-api/) — The jetpack-forms API from Automattic — 8 operation(s) for jetpack-forms.
- [Automattic Jetpack Global Styles API](https://apis.io/apis/automattic/automattic-jetpack-global-styles-api/) — The jetpack-global-styles API from Automattic — 1 operation(s) for jetpack-global-styles.
- [Automattic Jetpack Golden Token API](https://apis.io/apis/automattic/automattic-jetpack-golden-token-api/) — The jetpack-golden-token API from Automattic — 2 operation(s) for jetpack-golden-token.
- [Automattic Jetpack Licensing API](https://apis.io/apis/automattic/automattic-jetpack-licensing-api/) — The jetpack-licensing API from Automattic — 24 operation(s) for jetpack-licensing.
- [Automattic Jetpack Manage API](https://apis.io/apis/automattic/automattic-jetpack-manage-api/) — The jetpack-manage API from Automattic — 2 operation(s) for jetpack-manage.
- [Automattic Jetpack Marketing API](https://apis.io/apis/automattic/automattic-jetpack-marketing-api/) — The jetpack-marketing API from Automattic — 2 operation(s) for jetpack-marketing.
- [Automattic Jetpack Monitor Incidents API](https://apis.io/apis/automattic/automattic-jetpack-monitor-incidents-api/) — The jetpack-monitor-incidents API from Automattic — 1 operation(s) for jetpack-monitor-incidents.
- [Automattic Jetpack Monitor Settings API](https://apis.io/apis/automattic/automattic-jetpack-monitor-settings-api/) — The jetpack-monitor-settings API from Automattic — 2 operation(s) for jetpack-monitor-settings.
- [Automattic Jetpack Monitor Status API](https://apis.io/apis/automattic/automattic-jetpack-monitor-status-api/) — The jetpack-monitor-status API from Automattic — 1 operation(s) for jetpack-monitor-status.
- [Automattic Jetpack Monitor Uptime API](https://apis.io/apis/automattic/automattic-jetpack-monitor-uptime-api/) — The jetpack-monitor-uptime API from Automattic — 1 operation(s) for jetpack-monitor-uptime.
- [Automattic Jetpack Openai Query API](https://apis.io/apis/automattic/automattic-jetpack-openai-query-api/) — The jetpack-openai-query API from Automattic — 1 operation(s) for jetpack-openai-query.
- [Automattic Jetpack Package Versions API](https://apis.io/apis/automattic/automattic-jetpack-package-versions-api/) — The jetpack-package-versions API from Automattic — 1 operation(s) for jetpack-package-versions.
- [Automattic Jetpack Partner API](https://apis.io/apis/automattic/automattic-jetpack-partner-api/) — The jetpack-partner API from Automattic — 4 operation(s) for jetpack-partner.
- [Automattic Jetpack Partners API](https://apis.io/apis/automattic/automattic-jetpack-partners-api/) — The jetpack-partners API from Automattic — 14 operation(s) for jetpack-partners.
- [Automattic Jetpack Pinghub API](https://apis.io/apis/automattic/automattic-jetpack-pinghub-api/) — The jetpack-pinghub API from Automattic — 1 operation(s) for jetpack-pinghub.
- [Automattic Jetpack Product Data API](https://apis.io/apis/automattic/automattic-jetpack-product-data-api/) — The jetpack-product-data API from Automattic — 1 operation(s) for jetpack-product-data.
- [Automattic Jetpack Protect Global Stats API](https://apis.io/apis/automattic/automattic-jetpack-protect-global-stats-api/) — The jetpack-protect-global-stats API from Automattic — 1 operation(s) for jetpack-protect-global-stats.
- [Automattic Jetpack Protect Send Verification Code API](https://apis.io/apis/automattic/automattic-jetpack-protect-send-verification-code-api/) — The jetpack-protect-send-verification-code API from Automattic — 1 operation(s) for jetpack-protect-send-verification-code.
- [Automattic Jetpack Protect Status API](https://apis.io/apis/automattic/automattic-jetpack-protect-status-api/) — The jetpack-protect-status API from Automattic — 1 operation(s) for jetpack-protect-status.
- [Automattic Jetpack Protect Weak Password API](https://apis.io/apis/automattic/automattic-jetpack-protect-weak-password-api/) — The jetpack-protect-weak-password API from Automattic — 1 operation(s) for jetpack-protect-weak-password.
- [Automattic Jetpack Recommendations API](https://apis.io/apis/automattic/automattic-jetpack-recommendations-api/) — The jetpack-recommendations API from Automattic — 4 operation(s) for jetpack-recommendations.
- [Automattic Jetpack Refresh Blog Token API](https://apis.io/apis/automattic/automattic-jetpack-refresh-blog-token-api/) — The jetpack-refresh-blog-token API from Automattic — 1 operation(s) for jetpack-refresh-blog-token.
- [Automattic Jetpack Remote Connect User API](https://apis.io/apis/automattic/automattic-jetpack-remote-connect-user-api/) — The jetpack-remote-connect-user API from Automattic — 1 operation(s) for jetpack-remote-connect-user.
- [Automattic Jetpack Report Error API](https://apis.io/apis/automattic/automattic-jetpack-report-error-api/) — The jetpack-report-error API from Automattic — 1 operation(s) for jetpack-report-error.
- [Automattic Jetpack Search API](https://apis.io/apis/automattic/automattic-jetpack-search-api/) — The jetpack-search API from Automattic — 6 operation(s) for jetpack-search.
- [Automattic Jetpack Social API](https://apis.io/apis/automattic/automattic-jetpack-social-api/) — The jetpack-social API from Automattic — 2 operation(s) for jetpack-social.
- [Automattic Jetpack Start Webhooks API](https://apis.io/apis/automattic/automattic-jetpack-start-webhooks-api/) — The jetpack-start-webhooks API from Automattic — 1 operation(s) for jetpack-start-webhooks.
- [Automattic Jetpack Stats API](https://apis.io/apis/automattic/automattic-jetpack-stats-api/) — The jetpack-stats API from Automattic — 2 operation(s) for jetpack-stats.
- [Automattic Jetpack Stats Dashboard API](https://apis.io/apis/automattic/automattic-jetpack-stats-dashboard-api/) — The jetpack-stats-dashboard API from Automattic — 3 operation(s) for jetpack-stats-dashboard.
- [Automattic Jetpack Sync Actions API](https://apis.io/apis/automattic/automattic-jetpack-sync-actions-api/) — The jetpack-sync-actions API from Automattic — 1 operation(s) for jetpack-sync-actions.
- [Automattic Jetpack Token Health API](https://apis.io/apis/automattic/automattic-jetpack-token-health-api/) — The jetpack-token-health API from Automattic — 3 operation(s) for jetpack-token-health.
- [Automattic Jetpack User Attributes API](https://apis.io/apis/automattic/automattic-jetpack-user-attributes-api/) — The jetpack-user-attributes API from Automattic — 1 operation(s) for jetpack-user-attributes.
- [Automattic Jetpack User Tracking API](https://apis.io/apis/automattic/automattic-jetpack-user-tracking-api/) — The jetpack-user-tracking API from Automattic — 1 operation(s) for jetpack-user-tracking.
- [Automattic Jetpack Wpcom User Data API](https://apis.io/apis/automattic/automattic-jetpack-wpcom-user-data-api/) — The jetpack-wpcom-user-data API from Automattic — 1 operation(s) for jetpack-wpcom-user-data.
- [Automattic Jitm API](https://apis.io/apis/automattic/automattic-jitm-api/) — The jitm API from Automattic — 1 operation(s) for jitm.
- [Automattic Jp Pay Order API](https://apis.io/apis/automattic/automattic-jp-pay-order-api/) — The jp_pay_order API from Automattic — 4 operation(s) for jp_pay_order.
- [Automattic Jp Pay Product API](https://apis.io/apis/automattic/automattic-jp-pay-product-api/) — The jp_pay_product API from Automattic — 4 operation(s) for jp_pay_product.
- [Automattic Jurassic Ninja API](https://apis.io/apis/automattic/automattic-jurassic-ninja-api/) — The jurassic-ninja API from Automattic — 8 operation(s) for jurassic-ninja.
- [Automattic Key Usage API](https://apis.io/apis/automattic/automattic-key-usage-api/) — Check which sites use your API key and how many requests are being made
- [Automattic Key Verification API](https://apis.io/apis/automattic/automattic-key-verification-api/) — Verify Akismet API key
- [Automattic Knowledge API](https://apis.io/apis/automattic/automattic-knowledge-api/) — The knowledge API from Automattic — 7 operation(s) for knowledge.
- [Automattic Lasagna API](https://apis.io/apis/automattic/automattic-lasagna-api/) — The lasagna API from Automattic — 1 operation(s) for lasagna.
- [Automattic Launch API](https://apis.io/apis/automattic/automattic-launch-api/) — The launch API from Automattic — 1 operation(s) for launch.
- [Automattic Launch Site API](https://apis.io/apis/automattic/automattic-launch-site-api/) — The launch-site API from Automattic — 1 operation(s) for launch-site.
- [Automattic Launchpad API](https://apis.io/apis/automattic/automattic-launchpad-api/) — The launchpad API from Automattic — 2 operation(s) for launchpad.
- [Automattic Legal API](https://apis.io/apis/automattic/automattic-legal-api/) — The legal API from Automattic — 1 operation(s) for legal.
- [Automattic Liked Posts API](https://apis.io/apis/automattic/automattic-liked-posts-api/) — The liked-posts API from Automattic — 1 operation(s) for liked-posts.
- [Automattic Linear Solver API](https://apis.io/apis/automattic/automattic-linear-solver-api/) — The linear-solver API from Automattic — 8 operation(s) for linear-solver.
- [Automattic Linearmattic API](https://apis.io/apis/automattic/automattic-linearmattic-api/) — The linearmattic API from Automattic — 2 operation(s) for linearmattic.
- [Automattic Mailchimp API](https://apis.io/apis/automattic/automattic-mailchimp-api/) — The mailchimp API from Automattic — 3 operation(s) for mailchimp.
- [Automattic Mailpoet API](https://apis.io/apis/automattic/automattic-mailpoet-api/) — The mailpoet API from Automattic — 1 operation(s) for mailpoet.
- [Automattic Manual Payments API](https://apis.io/apis/automattic/automattic-manual-payments-api/) — The manual-payments API from Automattic — 2 operation(s) for manual-payments.
- [Automattic Mapbox API](https://apis.io/apis/automattic/automattic-mapbox-api/) — The mapbox API from Automattic — 1 operation(s) for mapbox.
- [Automattic Mapkit API](https://apis.io/apis/automattic/automattic-mapkit-api/) — The mapkit API from Automattic — 1 operation(s) for mapkit.
- [Automattic Marketing API](https://apis.io/apis/automattic/automattic-marketing-api/) — The marketing API from Automattic — 2 operation(s) for marketing.
- [Automattic Marketplace API](https://apis.io/apis/automattic/automattic-marketplace-api/) — The marketplace API from Automattic — 20 operation(s) for marketplace.
- [Automattic MCP Abilities API](https://apis.io/apis/automattic/automattic-mcp-abilities-api/) — The mcp-abilities API from Automattic — 1 operation(s) for mcp-abilities.
- [Automattic Me API](https://apis.io/apis/automattic/automattic-me-api/) — The me API from Automattic — 17 operation(s) for me.
- [Automattic Media API](https://apis.io/apis/automattic/automattic-media-api/) — The media API from Automattic — 14 operation(s) for media.
- [Automattic Memberships API](https://apis.io/apis/automattic/automattic-memberships-api/) — The memberships API from Automattic — 10 operation(s) for memberships.
- [Automattic Menu Items API](https://apis.io/apis/automattic/automattic-menu-items-api/) — The menu-items API from Automattic — 4 operation(s) for menu-items.
- [Automattic Menu Locations API](https://apis.io/apis/automattic/automattic-menu-locations-api/) — The menu-locations API from Automattic — 2 operation(s) for menu-locations.
- [Automattic Menus API](https://apis.io/apis/automattic/automattic-menus-api/) — The menus API from Automattic — 6 operation(s) for menus.
- [Automattic Meta API](https://apis.io/apis/automattic/automattic-meta-api/) — The meta API from Automattic — 6 operation(s) for meta.
- [Automattic Migrate From API](https://apis.io/apis/automattic/automattic-migrate-from-api/) — The migrate-from API from Automattic — 1 operation(s) for migrate-from.
- [Automattic Migrate Provision API](https://apis.io/apis/automattic/automattic-migrate-provision-api/) — The migrate-provision API from Automattic — 1 operation(s) for migrate-provision.
- [Automattic Migration Enabled API](https://apis.io/apis/automattic/automattic-migration-enabled-api/) — The migration-enabled API from Automattic — 1 operation(s) for migration-enabled.
- [Automattic Migration Flow API](https://apis.io/apis/automattic/automattic-migration-flow-api/) — The migration-flow API from Automattic — 1 operation(s) for migration-flow.
- [Automattic Migration Provider Notifications API](https://apis.io/apis/automattic/automattic-migration-provider-notifications-api/) — The migration-provider-notifications API from Automattic — 1 operation(s) for migration-provider-notifications.
- [Automattic Migration Provider Redirect API](https://apis.io/apis/automattic/automattic-migration-provider-redirect-api/) — The migration-provider-redirect API from Automattic — 1 operation(s) for migration-provider-redirect.
- [Automattic Migration Status API](https://apis.io/apis/automattic/automattic-migration-status-api/) — The migration-status API from Automattic — 1 operation(s) for migration-status.
- [Automattic Migrations API](https://apis.io/apis/automattic/automattic-migrations-api/) — The migrations API from Automattic — 2 operation(s) for migrations.
- [Automattic Mobile API](https://apis.io/apis/automattic/automattic-mobile-api/) — The mobile API from Automattic — 6 operation(s) for mobile.
- [Automattic Mobile Support API](https://apis.io/apis/automattic/automattic-mobile-support-api/) — The mobile-support API from Automattic — 6 operation(s) for mobile-support.
- [Automattic Navigation API](https://apis.io/apis/automattic/automattic-navigation-api/) — The navigation API from Automattic — 6 operation(s) for navigation.
- [Automattic Newsletter Categories API](https://apis.io/apis/automattic/automattic-newsletter-categories-api/) — The newsletter-categories API from Automattic — 5 operation(s) for newsletter-categories.
- [Automattic Newsletter Email Sent Status API](https://apis.io/apis/automattic/automattic-newsletter-email-sent-status-api/) — The newsletter-email-sent-status API from Automattic — 1 operation(s) for newsletter-email-sent-status.
- [Automattic Newspack Blocks Posts API](https://apis.io/apis/automattic/automattic-newspack-blocks-posts-api/) — The newspack-blocks-posts API from Automattic — 1 operation(s) for newspack-blocks-posts.
- [Automattic Newspack Blocks Specific Posts API](https://apis.io/apis/automattic/automattic-newspack-blocks-specific-posts-api/) — The newspack-blocks-specific-posts API from Automattic — 1 operation(s) for newspack-blocks-specific-posts.
- [Automattic Newspack Gpt API](https://apis.io/apis/automattic/automattic-newspack-gpt-api/) — The newspack-gpt API from Automattic — 1 operation(s) for newspack-gpt.
- [Automattic Newspack Manager API](https://apis.io/apis/automattic/automattic-newspack-manager-api/) — The newspack-manager API from Automattic — 1 operation(s) for newspack-manager.
- [Automattic Notifications API](https://apis.io/apis/automattic/automattic-notifications-api/) — The notifications API from Automattic — 3 operation(s) for notifications.
- [Automattic Nudge API](https://apis.io/apis/automattic/automattic-nudge-api/) — The nudge API from Automattic — 1 operation(s) for nudge.
- [Automattic Odie API](https://apis.io/apis/automattic/automattic-odie-api/) — The odie API from Automattic — 5 operation(s) for odie.
- [Automattic Odie Search API](https://apis.io/apis/automattic/automattic-odie-search-api/) — The odie-search API from Automattic — 1 operation(s) for odie-search.
- [Automattic Oembed Proxy API](https://apis.io/apis/automattic/automattic-oembed-proxy-api/) — The oembed-proxy API from Automattic — 2 operation(s) for oembed-proxy.
- [Automattic Onboarding API](https://apis.io/apis/automattic/automattic-onboarding-api/) — The onboarding API from Automattic — 1 operation(s) for onboarding.
- [Automattic Onboarding Customization API](https://apis.io/apis/automattic/automattic-onboarding-customization-api/) — The onboarding-customization API from Automattic — 1 operation(s) for onboarding-customization.
- [Automattic P2 API](https://apis.io/apis/automattic/automattic-p2-api/) — The p2 API from Automattic — 2 operation(s) for p2.
- [Automattic Pages API](https://apis.io/apis/automattic/automattic-pages-api/) — The pages API from Automattic — 6 operation(s) for pages.
- [Automattic Pagespeed API](https://apis.io/apis/automattic/automattic-pagespeed-api/) — The pagespeed API from Automattic — 1 operation(s) for pagespeed.
- [Automattic Partners API](https://apis.io/apis/automattic/automattic-partners-api/) — The partners API from Automattic — 1 operation(s) for partners.
- [Automattic Pattern Assembler API](https://apis.io/apis/automattic/automattic-pattern-assembler-api/) — The pattern-assembler API from Automattic — 6 operation(s) for pattern-assembler.
- [Automattic Pattern Directory API](https://apis.io/apis/automattic/automattic-pattern-directory-api/) — The pattern-directory API from Automattic — 1 operation(s) for pattern-directory.
- [Automattic Pending Blog Subscriptions API](https://apis.io/apis/automattic/automattic-pending-blog-subscriptions-api/) — The pending-blog-subscriptions API from Automattic — 3 operation(s) for pending-blog-subscriptions.
- [Automattic People API](https://apis.io/apis/automattic/automattic-people-api/) — The people API from Automattic — 2 operation(s) for people.
- [Automattic Photodna API](https://apis.io/apis/automattic/automattic-photodna-api/) — The photodna API from Automattic — 1 operation(s) for photodna.
- [Automattic Pigeon API](https://apis.io/apis/automattic/automattic-pigeon-api/) — The pigeon API from Automattic — 2 operation(s) for pigeon.
- [Automattic Plans API](https://apis.io/apis/automattic/automattic-plans-api/) — The plans API from Automattic — 4 operation(s) for plans.
- [Automattic Playground API](https://apis.io/apis/automattic/automattic-playground-api/) — The playground API from Automattic — 2 operation(s) for playground.
- [Automattic Plugins API](https://apis.io/apis/automattic/automattic-plugins-api/) — The plugins API from Automattic — 4 operation(s) for plugins.
- [Automattic Podcast API](https://apis.io/apis/automattic/automattic-podcast-api/) — The podcast API from Automattic — 1 operation(s) for podcast.
- [Automattic Podcast Distribution API](https://apis.io/apis/automattic/automattic-podcast-distribution-api/) — The podcast-distribution API from Automattic — 1 operation(s) for podcast-distribution.
- [Automattic Podcast Player API](https://apis.io/apis/automattic/automattic-podcast-player-api/) — The podcast-player API from Automattic — 2 operation(s) for podcast-player.
- [Automattic Podcast Stats API](https://apis.io/apis/automattic/automattic-podcast-stats-api/) — The podcast-stats API from Automattic — 4 operation(s) for podcast-stats.
- [Automattic Portfolio Dashboard Agent API](https://apis.io/apis/automattic/automattic-portfolio-dashboard-agent-api/) — The portfolio-dashboard-agent API from Automattic — 2 operation(s) for portfolio-dashboard-agent.
- [Automattic Post Comment Subscriptions API](https://apis.io/apis/automattic/automattic-post-comment-subscriptions-api/) — The post-comment-subscriptions API from Automattic — 4 operation(s) for post-comment-subscriptions.
- [Automattic Post Counts API](https://apis.io/apis/automattic/automattic-post-counts-api/) — The post-counts API from Automattic — 1 operation(s) for post-counts.
- [Automattic Post Types API](https://apis.io/apis/automattic/automattic-post-types-api/) — The post-types API from Automattic — 1 operation(s) for post-types.
- [Automattic Posts API](https://apis.io/apis/automattic/automattic-posts-api/) — The posts API from Automattic — 34 operation(s) for posts.
- [Automattic Posts To Podcast API](https://apis.io/apis/automattic/automattic-posts-to-podcast-api/) — The posts-to-podcast API from Automattic — 4 operation(s) for posts-to-podcast.
- [Automattic Presales API](https://apis.io/apis/automattic/automattic-presales-api/) — The presales API from Automattic — 1 operation(s) for presales.
- [Automattic Preview Links API](https://apis.io/apis/automattic/automattic-preview-links-api/) — The preview-links API from Automattic — 2 operation(s) for preview-links.
- [Automattic Pricing Dashboard API](https://apis.io/apis/automattic/automattic-pricing-dashboard-api/) — The pricing-dashboard API from Automattic — 5 operation(s) for pricing-dashboard.
- [Automattic Privacy Policy API](https://apis.io/apis/automattic/automattic-privacy-policy-api/) — The privacy-policy API from Automattic — 2 operation(s) for privacy-policy.
- [Automattic Private API](https://apis.io/apis/automattic/automattic-private-api/) — The private API from Automattic — 1 operation(s) for private.
- [Automattic Private Podcasts API](https://apis.io/apis/automattic/automattic-private-podcasts-api/) — The private-podcasts API from Automattic — 4 operation(s) for private-podcasts.
- [Automattic Products API](https://apis.io/apis/automattic/automattic-products-api/) — The products API from Automattic — 1 operation(s) for products.
- [Automattic Profile API](https://apis.io/apis/automattic/automattic-profile-api/) — The profile API from Automattic — 1 operation(s) for profile.
- [Automattic Protect API](https://apis.io/apis/automattic/automattic-protect-api/) — The protect API from Automattic — 3 operation(s) for protect.
- [Automattic Publicize API](https://apis.io/apis/automattic/automattic-publicize-api/) — The publicize API from Automattic — 15 operation(s) for publicize.
- [Automattic Push Notifications API](https://apis.io/apis/automattic/automattic-push-notifications-api/) — The push-notifications API from Automattic — 1 operation(s) for push-notifications.
- [Automattic Read API](https://apis.io/apis/automattic/automattic-read-api/) — The read API from Automattic — 52 operation(s) for read.
- [Automattic Reader API](https://apis.io/apis/automattic/automattic-reader-api/) — The reader API from Automattic — 106 operation(s) for reader.
- [Automattic Reader Chat Settings API](https://apis.io/apis/automattic/automattic-reader-chat-settings-api/) — The reader-chat-settings API from Automattic — 1 operation(s) for reader-chat-settings.
- [Automattic Recovery Mode Status API](https://apis.io/apis/automattic/automattic-recovery-mode-status-api/) — The recovery-mode-status API from Automattic — 1 operation(s) for recovery-mode-status.
- [Automattic Related Posts API](https://apis.io/apis/automattic/automattic-related-posts-api/) — The related-posts API from Automattic — 3 operation(s) for related-posts.
- [Automattic Reset Migration API](https://apis.io/apis/automattic/automattic-reset-migration-api/) — The reset-migration API from Automattic — 1 operation(s) for reset-migration.
- [Automattic Reset Site API](https://apis.io/apis/automattic/automattic-reset-site-api/) — The reset-site API from Automattic — 3 operation(s) for reset-site.
- [Automattic Restore Site API](https://apis.io/apis/automattic/automattic-restore-site-api/) — The restore-site API from Automattic — 1 operation(s) for restore-site.
- [Automattic Rewind API](https://apis.io/apis/automattic/automattic-rewind-api/) — The rewind API from Automattic — 34 operation(s) for rewind.
- [Automattic Rtc API](https://apis.io/apis/automattic/automattic-rtc-api/) — The rtc API from Automattic — 2 operation(s) for rtc.
- [Automattic Rtc Notices API](https://apis.io/apis/automattic/automattic-rtc-notices-api/) — The rtc-notices API from Automattic — 3 operation(s) for rtc-notices.
- [Automattic Scan API](https://apis.io/apis/automattic/automattic-scan-api/) — The scan API from Automattic — 5 operation(s) for scan.
- [Automattic Scheduled Updates API](https://apis.io/apis/automattic/automattic-scheduled-updates-api/) — The scheduled-updates API from Automattic — 2 operation(s) for scheduled-updates.
- [Automattic Search API](https://apis.io/apis/automattic/automattic-search-api/) — The search API from Automattic — 1 operation(s) for search.
- [Automattic Search Stats API](https://apis.io/apis/automattic/automattic-search-stats-api/) — The search-stats API from Automattic — 1 operation(s) for search-stats.
- [Automattic Search Suggestions API](https://apis.io/apis/automattic/automattic-search-suggestions-api/) — The search-suggestions API from Automattic — 1 operation(s) for search-suggestions.
- [Automattic Seen Posts API](https://apis.io/apis/automattic/automattic-seen-posts-api/) — The seen-posts API from Automattic — 6 operation(s) for seen-posts.
- [Automattic Segmentation Survey API](https://apis.io/apis/automattic/automattic-segmentation-survey-api/) — The segmentation-survey API from Automattic — 4 operation(s) for segmentation-survey.
- [Automattic Segments API](https://apis.io/apis/automattic/automattic-segments-api/) — The segments API from Automattic — 1 operation(s) for segments.
- [Automattic Seller Footer API](https://apis.io/apis/automattic/automattic-seller-footer-api/) — The seller_footer API from Automattic — 1 operation(s) for seller_footer.
- [Automattic Send API](https://apis.io/apis/automattic/automattic-send-api/) — The send API from Automattic — 3 operation(s) for send.
- [Automattic Send Email Continue Site Build API](https://apis.io/apis/automattic/automattic-send-email-continue-site-build-api/) — The send-email-continue-site-build API from Automattic — 1 operation(s) for send-email-continue-site-build.
- [Automattic Send Email Preview API](https://apis.io/apis/automattic/automattic-send-email-preview-api/) — The send-email-preview API from Automattic — 1 operation(s) for send-email-preview.
- [Automattic Service API Keys API](https://apis.io/apis/automattic/automattic-service-api-keys-api/) — The service-api-keys API from Automattic — 1 operation(s) for service-api-keys.
- [Automattic Settings API](https://apis.io/apis/automattic/automattic-settings-api/) — The settings API from Automattic — 1 operation(s) for settings.
- [Automattic Shares Count API](https://apis.io/apis/automattic/automattic-shares-count-api/) — The shares-count API from Automattic — 1 operation(s) for shares-count.
- [Automattic Sharing API](https://apis.io/apis/automattic/automattic-sharing-api/) — The sharing API from Automattic — 15 operation(s) for sharing.
- [Automattic Shipstation API](https://apis.io/apis/automattic/automattic-shipstation-api/) — The shipstation API from Automattic — 1 operation(s) for shipstation.
- [Automattic Sidebars API](https://apis.io/apis/automattic/automattic-sidebars-api/) — The sidebars API from Automattic — 2 operation(s) for sidebars.
- [Automattic Simple Payments API](https://apis.io/apis/automattic/automattic-simple-payments-api/) — The simple-payments API from Automattic — 2 operation(s) for simple-payments.
- [Automattic Site API](https://apis.io/apis/automattic/automattic-site-api/) — The site API from Automattic — 5 operation(s) for site.
- [Automattic Site Assembler API](https://apis.io/apis/automattic/automattic-site-assembler-api/) — The site-assembler API from Automattic — 1 operation(s) for site-assembler.
- [Automattic Site Goals API](https://apis.io/apis/automattic/automattic-site-goals-api/) — The site-goals API from Automattic — 1 operation(s) for site-goals.
- [Automattic Site Has Never Published Post API](https://apis.io/apis/automattic/automattic-site-has-never-published-post-api/) — The site-has-never-published-post API from Automattic — 1 operation(s) for site-has-never-published-post.
- [Automattic Site Importer API](https://apis.io/apis/automattic/automattic-site-importer-api/) — The site-importer API from Automattic — 5 operation(s) for site-importer.
- [Automattic Site Intent API](https://apis.io/apis/automattic/automattic-site-intent-api/) — The site-intent API from Automattic — 1 operation(s) for site-intent.
- [Automattic Site Migration Status Sticker API](https://apis.io/apis/automattic/automattic-site-migration-status-sticker-api/) — The site-migration-status-sticker API from Automattic — 1 operation(s) for site-migration-status-sticker.
- [Automattic Site Owner Transfer API](https://apis.io/apis/automattic/automattic-site-owner-transfer-api/) — The site-owner-transfer API from Automattic — 3 operation(s) for site-owner-transfer.
- [Automattic Site Suggestions API](https://apis.io/apis/automattic/automattic-site-suggestions-api/) — The site-suggestions API from Automattic — 1 operation(s) for site-suggestions.
- [Automattic Site Type API](https://apis.io/apis/automattic/automattic-site-type-api/) — The site-type API from Automattic — 1 operation(s) for site-type.
- [Automattic Site Vertical API](https://apis.io/apis/automattic/automattic-site-vertical-api/) — The site-vertical API from Automattic — 1 operation(s) for site-vertical.
- [Automattic Sites API](https://apis.io/apis/automattic/automattic-sites-api/) — The sites API from Automattic — 25 operation(s) for sites.
- [Automattic Slack API](https://apis.io/apis/automattic/automattic-slack-api/) — The slack API from Automattic — 1 operation(s) for slack.
- [Automattic Spam API](https://apis.io/apis/automattic/automattic-spam-api/) — Check for spam, and submit spam or ham (false positives)
- [Automattic Ssh Migration API](https://apis.io/apis/automattic/automattic-ssh-migration-api/) — The ssh-migration API from Automattic — 5 operation(s) for ssh-migration.
- [Automattic Staging Site API](https://apis.io/apis/automattic/automattic-staging-site-api/) — The staging-site API from Automattic — 7 operation(s) for staging-site.
- [Automattic Starter Designs API](https://apis.io/apis/automattic/automattic-starter-designs-api/) — The starter-designs API from Automattic — 2 operation(s) for starter-designs.
- [Automattic Stats API](https://apis.io/apis/automattic/automattic-stats-api/) — The stats API from Automattic — 43 operation(s) for stats.
- [Automattic Statuses API](https://apis.io/apis/automattic/automattic-statuses-api/) — The statuses API from Automattic — 2 operation(s) for statuses.
- [Automattic Studio App API](https://apis.io/apis/automattic/automattic-studio-app-api/) — The studio-app API from Automattic — 14 operation(s) for studio-app.
- [Automattic Subscribers API](https://apis.io/apis/automattic/automattic-subscribers-api/) — The subscribers API from Automattic — 19 operation(s) for subscribers.
- [Automattic Subscribers By User Type API](https://apis.io/apis/automattic/automattic-subscribers-by-user-type-api/) — The subscribers_by_user_type API from Automattic — 1 operation(s) for subscribers_by_user_type.
- [Automattic Support Interactions API](https://apis.io/apis/automattic/automattic-support-interactions-api/) — The support-interactions API from Automattic — 4 operation(s) for support-interactions.
- [Automattic Supportforums API](https://apis.io/apis/automattic/automattic-supportforums-api/) — The supportforums API from Automattic — 1 operation(s) for supportforums.
- [Automattic Sync API](https://apis.io/apis/automattic/automattic-sync-api/) — The sync API from Automattic — 1 operation(s) for sync.
- [Automattic Tags API](https://apis.io/apis/automattic/automattic-tags-api/) — The tags API from Automattic — 3 operation(s) for tags.
- [Automattic Taxonomies API](https://apis.io/apis/automattic/automattic-taxonomies-api/) — The taxonomies API from Automattic — 2 operation(s) for taxonomies.
- [Automattic Taxonomy API](https://apis.io/apis/automattic/automattic-taxonomy-api/) — The taxonomy API from Automattic — 13 operation(s) for taxonomy.
- [Automattic Telegram Bot API](https://apis.io/apis/automattic/automattic-telegram-bot-api/) — The telegram-bot API from Automattic — 8 operation(s) for telegram-bot.
- [Automattic Template Loader API](https://apis.io/apis/automattic/automattic-template-loader-api/) — The template-loader API from Automattic — 1 operation(s) for template-loader.
- [Automattic Template Parts API](https://apis.io/apis/automattic/automattic-template-parts-api/) — The template-parts API from Automattic — 7 operation(s) for template-parts.
- [Automattic Templates API](https://apis.io/apis/automattic/automattic-templates-api/) — The templates API from Automattic — 7 operation(s) for templates.
- [Automattic Test API](https://apis.io/apis/automattic/automattic-test-api/) — The test API from Automattic — 1 operation(s) for test.
- [Automattic Tests API](https://apis.io/apis/automattic/automattic-tests-api/) — The tests API from Automattic — 3 operation(s) for tests.
- [Automattic Text Completion API](https://apis.io/apis/automattic/automattic-text-completion-api/) — The text-completion API from Automattic — 2 operation(s) for text-completion.
- [Automattic Theme Headstart API](https://apis.io/apis/automattic/automattic-theme-headstart-api/) — The theme-headstart API from Automattic — 1 operation(s) for theme-headstart.
- [Automattic Theme Setup API](https://apis.io/apis/automattic/automattic-theme-setup-api/) — The theme-setup API from Automattic — 1 operation(s) for theme-setup.
- [Automattic Theme Support API](https://apis.io/apis/automattic/automattic-theme-support-api/) — The theme-support API from Automattic — 1 operation(s) for theme-support.
- [Automattic Themes API](https://apis.io/apis/automattic/automattic-themes-api/) — The themes API from Automattic — 11 operation(s) for themes.
- [Automattic Timezones API](https://apis.io/apis/automattic/automattic-timezones-api/) — The timezones API from Automattic — 1 operation(s) for timezones.
- [Automattic Titan API](https://apis.io/apis/automattic/automattic-titan-api/) — The titan API from Automattic — 1 operation(s) for titan.
- [Automattic Top Posts API](https://apis.io/apis/automattic/automattic-top-posts-api/) — The top-posts API from Automattic — 1 operation(s) for top-posts.
- [Automattic Tortuga API](https://apis.io/apis/automattic/automattic-tortuga-api/) — The tortuga API from Automattic — 1 operation(s) for tortuga.
- [Automattic Traffic Guide Download API](https://apis.io/apis/automattic/automattic-traffic-guide-download-api/) — The traffic-guide-download API from Automattic — 1 operation(s) for traffic-guide-download.
- [Automattic Transfer API](https://apis.io/apis/automattic/automattic-transfer-api/) — The transfer API from Automattic — 1 operation(s) for transfer.
- [Automattic Transients API](https://apis.io/apis/automattic/automattic-transients-api/) — The transients API from Automattic — 1 operation(s) for transients.
- [Automattic Trello Callback API](https://apis.io/apis/automattic/automattic-trellocallback-api/) — The trelloCallback API from Automattic — 1 operation(s) for trellocallback.
- [Automattic Trends Agent API](https://apis.io/apis/automattic/automattic-trends-agent-api/) — The trends-agent API from Automattic — 3 operation(s) for trends-agent.
- [Automattic Tumblr Smtp API](https://apis.io/apis/automattic/automattic-tumblr-smtp-api/) — The tumblr-smtp API from Automattic — 1 operation(s) for tumblr-smtp.
- [Automattic Twilio Notification API](https://apis.io/apis/automattic/automattic-twilio-notification-api/) — The twilio-notification API from Automattic — 1 operation(s) for twilio-notification.
- [Automattic Twitter API](https://apis.io/apis/automattic/automattic-twitter-api/) — The twitter API from Automattic — 1 operation(s) for twitter.
- [Automattic Typekit Fonts API](https://apis.io/apis/automattic/automattic-typekit-fonts-api/) — The typekit-fonts API from Automattic — 5 operation(s) for typekit-fonts.
- [Automattic Types API](https://apis.io/apis/automattic/automattic-types-api/) — The types API from Automattic — 2 operation(s) for types.
- [Automattic Ucp API](https://apis.io/apis/automattic/automattic-ucp-api/) — The ucp API from Automattic — 15 operation(s) for ucp.
- [Automattic Unauth File Upload API](https://apis.io/apis/automattic/automattic-unauth-file-upload-api/) — The unauth-file-upload API from Automattic — 4 operation(s) for unauth-file-upload.
- [Automattic Update Schedules API](https://apis.io/apis/automattic/automattic-update-schedules-api/) — The update-schedules API from Automattic — 5 operation(s) for update-schedules.
- [Automattic Upgrades API](https://apis.io/apis/automattic/automattic-upgrades-api/) — The upgrades API from Automattic — 1 operation(s) for upgrades.
- [Automattic User Type API](https://apis.io/apis/automattic/automattic-user-type-api/) — The user-type API from Automattic — 1 operation(s) for user-type.
- [Automattic Users API](https://apis.io/apis/automattic/automattic-users-api/) — The users API from Automattic — 27 operation(s) for users.
- [Automattic Verticals API](https://apis.io/apis/automattic/automattic-verticals-api/) — The verticals API from Automattic — 5 operation(s) for verticals.
- [Automattic Vibehost API](https://apis.io/apis/automattic/automattic-vibehost-api/) — The vibehost API from Automattic — 3 operation(s) for vibehost.
- [Automattic Videopress API](https://apis.io/apis/automattic/automattic-videopress-api/) — The videopress API from Automattic — 9 operation(s) for videopress.
- [Automattic Videos API](https://apis.io/apis/automattic/automattic-videos-api/) — The videos API from Automattic — 7 operation(s) for videos.
- [Automattic View Config API](https://apis.io/apis/automattic/automattic-view-config-api/) — The view-config API from Automattic — 1 operation(s) for view-config.
- [Automattic Vip API](https://apis.io/apis/automattic/automattic-vip-api/) — The vip API from Automattic — 2 operation(s) for vip.
- [Automattic Vouchers API](https://apis.io/apis/automattic/automattic-vouchers-api/) — The vouchers API from Automattic — 3 operation(s) for vouchers.
- [Automattic Waf Rules API](https://apis.io/apis/automattic/automattic-waf-rules-api/) — The waf-rules API from Automattic — 1 operation(s) for waf-rules.
- [Automattic Wc API](https://apis.io/apis/automattic/automattic-wc-api/) — The wc API from Automattic — 20 operation(s) for wc.
- [Automattic Wcai Pa API](https://apis.io/apis/automattic/automattic-wcai-pa-api/) — The wcai-pa API from Automattic — 6 operation(s) for wcai-pa.
- [Automattic Wcbazaar API](https://apis.io/apis/automattic/automattic-wcbazaar-api/) — The wcbazaar API from Automattic — 9 operation(s) for wcbazaar.
- [Automattic Wccom API](https://apis.io/apis/automattic/automattic-wccom-api/) — The wccom API from Automattic — 4 operation(s) for wccom.
- [Automattic Webhook Airtable Create API](https://apis.io/apis/automattic/automattic-webhook-airtable-create-api/) — The webhook-airtable-create API from Automattic — 3 operation(s) for webhook-airtable-create.
- [Automattic Whats New API](https://apis.io/apis/automattic/automattic-whats-new-api/) — The whats-new API from Automattic — 2 operation(s) for whats-new.
- [Automattic Widget Modules API](https://apis.io/apis/automattic/automattic-widget-modules-api/) — The widget-modules API from Automattic — 1 operation(s) for widget-modules.
- [Automattic Widget Types API](https://apis.io/apis/automattic/automattic-widget-types-api/) — The widget-types API from Automattic — 4 operation(s) for widget-types.
- [Automattic Widgets API](https://apis.io/apis/automattic/automattic-widgets-api/) — The widgets API from Automattic — 2 operation(s) for widgets.
- [Automattic Woo API](https://apis.io/apis/automattic/automattic-woo-api/) — The woo API from Automattic — 3 operation(s) for woo.
- [Automattic Woo Mobile AI API](https://apis.io/apis/automattic/automattic-woo-mobile-ai-api/) — The woo-mobile-ai API from Automattic — 1 operation(s) for woo-mobile-ai.
- [Automattic Woocommerce API](https://apis.io/apis/automattic/automattic-woocommerce-api/) — The woocommerce API from Automattic — 5 operation(s) for woocommerce.
- [Automattic Wordads API](https://apis.io/apis/automattic/automattic-wordads-api/) — The wordads API from Automattic — 5 operation(s) for wordads.
- [Automattic Wordcamp Coupons API](https://apis.io/apis/automattic/automattic-wordcamp-coupons-api/) — The wordcamp-coupons API from Automattic — 1 operation(s) for wordcamp-coupons.
- [Automattic Work With Us API](https://apis.io/apis/automattic/automattic-work-with-us-api/) — The work-with-us API from Automattic — 2 operation(s) for work-with-us.
- [Automattic Wp Abilities API](https://apis.io/apis/automattic/automattic-wp-abilities-api/) — The wp-abilities API from Automattic — 5 operation(s) for wp-abilities.
- [Automattic Wp Admin Sidebar API](https://apis.io/apis/automattic/automattic-wp-admin-sidebar-api/) — The wp-admin-sidebar API from Automattic — 1 operation(s) for wp-admin-sidebar.
- [Automattic Wp Guideline Type API](https://apis.io/apis/automattic/automattic-wp-guideline-type-api/) — The wp_guideline_type API from Automattic — 2 operation(s) for wp_guideline_type.
- [Automattic Wp Knowledge Type API](https://apis.io/apis/automattic/automattic-wp-knowledge-type-api/) — The wp_knowledge_type API from Automattic — 2 operation(s) for wp_knowledge_type.
- [Automattic Wp Pattern Category API](https://apis.io/apis/automattic/automattic-wp-pattern-category-api/) — The wp_pattern_category API from Automattic — 2 operation(s) for wp_pattern_category.
- [Automattic Wp V2 API](https://apis.io/apis/automattic/automattic-wp-v2-api/) — The wp-v2 API from Automattic — 2 operation(s) for wp-v2.
- [Automattic Wpcom API](https://apis.io/apis/automattic/automattic-wpcom-api/) — The Wpcom API from Automattic — 3 operation(s) for wpcom.
- [Automattic Wpcom V2 API](https://apis.io/apis/automattic/automattic-wpcom-v2-api/) — The wpcom-v2 API from Automattic — 2 operation(s) for wpcom-v2.
- [Automattic Wrangler API](https://apis.io/apis/automattic/automattic-wrangler-api/) — The wrangler API from Automattic — 2 operation(s) for wrangler.
- [Automattic Xposts API](https://apis.io/apis/automattic/automattic-xposts-api/) — The xposts API from Automattic — 1 operation(s) for xposts.
- [Automattic Zendesk API](https://apis.io/apis/automattic/automattic-zendesk-api/) — The zendesk API from Automattic — 1 operation(s) for zendesk.
- [Automattic Zendesk Notification API](https://apis.io/apis/automattic/automattic-zendesk-notification-api/) — The zendesk-notification API from Automattic — 9 operation(s) for zendesk-notification.
- [Automattic Zendesk Notification Staging API](https://apis.io/apis/automattic/automattic-zendesk-notification-staging-api/) — The zendesk-notification-staging API from Automattic — 1 operation(s) for zendesk-notification-staging.
- [Automattic Oauth2 API](https://apis.io/apis/automattic/automattic-oauth2-api/) — The oauth2 API from Automattic — 1 operation(s) for oauth2.

### Published properties

Each property below is a page on APIs.io carrying the machine-readable artifact and what it says.

#### AsyncAPI (1)

Event-driven and webhook contracts.

- [Automattic Wordpress Com Webhooks](https://apis.io/asyncapis/automattic/automattic-wordpress-com-webhooks/)

#### MCP servers (1)

Model Context Protocol servers that expose the API to agents.

- [wordpress-com](https://apis.io/servers/automattic/wordpress-com/)

#### Agentic access (1)

Which operations an agent can call, which act, and which need a human in the loop.

- [Automattic Agentic Access](https://apis.io/agentic-access/automattic/automattic-agentic-access/)

#### Collections (6)

Postman and Open Collection request collections.

- [Open Automattic Akismet](https://apis.io/collections/automattic/open-automattic-akismet/)
- [Open Automattic Wordpress Com Rest V1 1](https://apis.io/collections/automattic/open-automattic-wordpress-com-rest-v1-1/)
- [Open Automattic Wordpress Com Rest V1 2](https://apis.io/collections/automattic/open-automattic-wordpress-com-rest-v1-2/)
- [Open Automattic Wordpress Com Rest V1 3](https://apis.io/collections/automattic/open-automattic-wordpress-com-rest-v1-3/)
- [Open Automattic Wordpress Com Wp V2](https://apis.io/collections/automattic/open-automattic-wordpress-com-wp-v2/)
- [Open Automattic Wordpress Com Wpcom V2](https://apis.io/collections/automattic/open-automattic-wordpress-com-wpcom-v2/)

#### Overlays (7)

OpenAPI overlays, including conversational phrasing for each operation.

- [Automattic Akismet Overlay](https://apis.io/overlays/automattic/automattic-akismet-overlay/)
- [Automattic Jetpack Ai Plugin Overlay](https://apis.io/overlays/automattic/automattic-jetpack-ai-plugin-overlay/)
- [Automattic Wordpress Com Rest V1 1 Overlay](https://apis.io/overlays/automattic/automattic-wordpress-com-rest-v1-1-overlay/)
- [Automattic Wordpress Com Rest V1 2 Overlay](https://apis.io/overlays/automattic/automattic-wordpress-com-rest-v1-2-overlay/)
- [Automattic Wordpress Com Rest V1 3 Overlay](https://apis.io/overlays/automattic/automattic-wordpress-com-rest-v1-3-overlay/)
- [Automattic Wordpress Com Wp V2 Overlay](https://apis.io/overlays/automattic/automattic-wordpress-com-wp-v2-overlay/)
- [Automattic Wordpress Com Wpcom V2 Overlay](https://apis.io/overlays/automattic/automattic-wordpress-com-wpcom-v2-overlay/)

#### Security (4)

Authentication, trust centre, and vulnerability disclosure.

- [Automattic Authentication](https://apis.io/security/automattic/automattic-authentication/)
- [Automattic Domain Security](https://apis.io/security/automattic/automattic-domain-security/)
- [Automattic Trust Center](https://apis.io/security/automattic/automattic-trust-center/)
- [Automattic Vulnerability Disclosure](https://apis.io/security/automattic/automattic-vulnerability-disclosure/)

#### OAuth scopes (1)

The permissions the API asks for.

- [Automattic Scopes](https://apis.io/scopes/automattic/automattic-scopes/)

## Where to find this API

Links to the company's own pages. This repository publishes no copy of their specifications — the canonical document is theirs and lives at the URLs below.

- [Website](https://automattic.com/)
- [Documentation](https://developer.wordpress.com/docs/api/)
- [Getting started](https://developer.wordpress.com/docs/api/getting-started/)
- [API reference](https://developer.wordpress.com/docs/api/rest-api-reference/)
- [Pricing](https://wordpress.com/pricing/)
- [Sign up](https://developer.wordpress.com/apps/new/)
- [Support](https://wordpress.com/support/)
- [Blog](https://automattic.com/news/)
- [Security](https://automattic.com/security/)
- [Compliance](https://wpvip.com/trust/)
- [Terms of service](https://wordpress.com/tos/)
- [Privacy policy](https://automattic.com/privacy/)
- [GitHub](https://github.com/Automattic)
- [Status](https://automatticstatus.com/)

## API Evangelist rating

**Kin Score 54.5** — strong · rubric 0.25.0 · scored 2026-10-23

| Facet | Score |
|---|---|
| Discoverability | 75.0 |
| Contract quality | 23.9 |
| Contract governance | 18.2 |
| Operational transparency | 52.6 |
| Developer ergonomics | 80.4 |
| Access clarity | 60.5 |

**Agent readiness 57.9** — agent-ready (gated down from agent-native)

| Agent-readiness dimension | Result |
|---|---|
| Spec Presence | yes |
| Agentic Access | derived (partial credit) |
| Reversibility Documented | documented (partial credit) |
| MCP Server | verified |
| Auth Clarity | served (partial credit) |
| Idempotency | — |
| Error Semantics | verified |
| OpenAPI Examples | partial |
| Rate Limit Signal | — |
| Event Surface Described | yes |
| Agent Skills | derived (partial credit) |
| Well Known Catalog | — |
| Consent Identity | — |
| Agent Card | — |
| Dry Run Mode | yes |
| Delegated Identity | served (partial credit) |
| Protected Resource Metadata | verified |
| Dynamic Client Registration | yes |
| Agentic Commerce | — |
| Pagination Ratio | — |
| Operation Distinctiveness | mostly |

**Regulatory alignment 45.1** — Horizontal (data, software, accessibility, platform)

The rubric is published at [github.com/api-evangelist/kin-score](https://github.com/api-evangelist/kin-score). The per-check breakdown behind these numbers — which checks were earned, partial or missed — along with score history and how this provider compares to its peers, is available at [apis.io/providers/automattic/](https://apis.io/providers/automattic/).

## How this profile is made

API Evangelist profiles a company's public API surface the way a developer would find it: the website, developer portal and documentation, the specifications it publishes, its public repositories, and its pricing, status and changelog pages. From that it derives the properties above — contracts split per API, workflows, schemas, collections, governance rules, plans and rate limits — and scores them against the published [Kin Score rubric](https://github.com/api-evangelist/kin-score).

The artifacts are published on [APIs.io](https://apis.io), not in this repository. This repository is the public record for Automattic: the place to say something is wrong, missing or out of date, and to ask for a re-score or a removal.

## Open an issue

- **Something about this listing** — a wrong description, a missing API, a stale artifact or a question about the rating: [open an issue on this repository](https://github.com/api-evangelist/automattic/issues/new).
- **A new API, or one that is not in the catalog yet** — [submit it on APIs.io](https://apis.io/add/).
- **Anything else** — [the APIs.io inbox](https://github.com/api-search/inbox/issues/new) or [info@apievangelist.com](mailto:info@apievangelist.com).
