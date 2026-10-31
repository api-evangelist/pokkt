# Pokkt

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

Pokkt is a mobile-first advertising and app monetization platform, part of AnyMind Group, serving app publishers and game developers with SDK-based ad monetization (rewarded video, interstitial, and video advertising) and serving advertisers with performance campaigns, remarketing, and connected-TV (CTV) inventory across India, Southeast Asia, and MENA. Its public API surface is entirely ad-tech: a supply-side Ad Server API at vdo.pokkt.com serving JSON, HTML and VAST responses, a mobile-web rewarded video surface, a server-to-server rewarded-video gratification callback, and a demand-side OpenRTB 2.5/2.6 bid endpoint with global, APAC and US regional hosts. Pokkt publishes an llms.txt-indexed developer wiki and an IAB Tech Lab sellers.json, but no OpenAPI, no OAuth, and no public pricing; the console GraphQL API at api.pokkt.com is authentication-gated and its client SDKs have not been republished since October 2021.

**Areas:** Company · Advertising · Monetization · Mobile · Video Advertising · AdTech · Remarketing · OpenRTB · Programmatic Advertising · Rewarded Video · Mobile SDK · Ad Serving

## Pokkt on APIs.io

Everything profiled for Pokkt is published on APIs.io rather than in this repository. Start at the provider page — **[apis.io/providers/pokkt/](https://apis.io/providers/pokkt/)** — or go straight to one of the APIs or properties below.

### APIs (6)

- [POKKT Ad Server API](https://apis.io/apis/pokkt/ad-server-api/) — Supply-side ad request API. A single GET to /api/AdServer returns one or more ad objects for a full-screen interstitial or banner placement, as a JSON array…
- [POKKT VAST Video API](https://apis.io/apis/pokkt/vast-video-api/) — Video ad request API for supply-side platforms. The same /api/AdServer endpoint called with response_format=1 responds with a VAST XML tag rather than a…
- [POKKT DSP OpenRTB API](https://apis.io/apis/pokkt/dsp-openrtb-api/) — Demand-side bidding endpoint. Exchanges POST an OpenRTB bid request object as application/json to /api/rtb/<appid> with an x-openrtb-version header; POKKT…
- [POKKT Mobile Web Video API](https://apis.io/apis/pokkt/mobile-web-video-api/) — Hosted rewarded-video surface for mobile web. The publisher opens /videoWap with its appId, a format selector and a URL-encoded `encodedparams` bag carrying…
- [POKKT Gratification API](https://apis.io/apis/pokkt/gratification-api/) — Server-to-server rewarded-video confirmation callback. When a user completes a rewarded video, POKKT issues a GET to a publisher-hosted URL configured in…
- [POKKT Console GraphQL API](https://apis.io/apis/pokkt/console-graphql-api/) — The GraphQL API behind the POKKT campaign-management console, live at api.pokkt.com/graphql and referenced directly by the console's own JavaScript bundle.…

### Published properties

Each property below is a page on APIs.io carrying the machine-readable artifact and what it says.

#### AsyncAPI (1)

Event-driven and webhook contracts.

- [Pokkt Webhooks](https://apis.io/asyncapis/pokkt/pokkt-webhooks/)

#### Security (2)

Authentication, trust centre, and vulnerability disclosure.

- [Pokkt Authentication](https://apis.io/security/pokkt/pokkt-authentication/)
- [Pokkt Domain Security](https://apis.io/security/pokkt/pokkt-domain-security/)

#### Plans and pricing (1)

Published plans, tiers and prices.

- [Pokkt Plans Pricing](https://apis.io/plans/pokkt/pokkt-plans-pricing/)

#### Rate limits (1)

Published request limits.

- [Pokkt Rate Limits](https://apis.io/rate-limits/pokkt/pokkt-rate-limits/)

## Where to find this API

Links to the company's own pages. This repository publishes no copy of their specifications — the canonical document is theirs and lives at the URLs below.

- [Website](https://pokkt.com)
- [Documentation](https://wiki.pokkt.com)
- [Getting started](https://wiki.pokkt.com/pokkt-sdk)
- [API reference](https://wiki.pokkt.com/api-guide)
- [Privacy policy](https://anymindgroup.com/privacy-policy/)
- [GitHub](https://github.com/AnyMindGroup)

## API Evangelist rating

**Kin Score 36.8** — thin · rubric 0.24.0 · scored 2026-10-17

| Facet | Score |
|---|---|
| Discoverability | 78.6 |
| Contract quality | 39.0 |
| Contract governance | 18.2 |
| Operational transparency | 10.5 |
| Developer ergonomics | 57.1 |
| Access clarity | 17.1 |

**Agent readiness 25.2** — agent-aware

| Agent-readiness dimension | Result |
|---|---|
| Spec Presence | yes |
| Agentic Access | — |
| Reversibility Documented | — |
| MCP Server | — |
| Auth Clarity | bearer (partial credit) |
| Idempotency | — |
| Error Semantics | documented (partial credit) |
| OpenAPI Examples | — |
| Rate Limit Signal | documented (partial credit) |
| Event Surface Described | yes |
| Agent Skills | — |
| Well Known Catalog | — |
| Consent Identity | — |
| Agent Card | — |
| Dry Run Mode | — |
| Delegated Identity | — |
| Protected Resource Metadata | — |
| Dynamic Client Registration | — |
| Agentic Commerce | — |

**Regulatory alignment 20.6** — Horizontal (data, software, accessibility, platform)

The rubric is published at [github.com/api-evangelist/kin-score](https://github.com/api-evangelist/kin-score). The per-check breakdown behind these numbers — which checks were earned, partial or missed — along with score history and how this provider compares to its peers, is available at [apis.io/providers/pokkt/](https://apis.io/providers/pokkt/).

## How this profile is made

API Evangelist profiles a company's public API surface the way a developer would find it: the website, developer portal and documentation, the specifications it publishes, its public repositories, and its pricing, status and changelog pages. From that it derives the properties above — contracts split per API, workflows, schemas, collections, governance rules, plans and rate limits — and scores them against the published [Kin Score rubric](https://github.com/api-evangelist/kin-score).

The artifacts are published on [APIs.io](https://apis.io), not in this repository. This repository is the public record for Pokkt: the place to say something is wrong, missing or out of date, and to ask for a re-score or a removal.

## Open an issue

- **Something about this listing** — a wrong description, a missing API, a stale artifact or a question about the rating: [open an issue on this repository](https://github.com/api-evangelist/pokkt/issues/new).
- **A new API, or one that is not in the catalog yet** — [submit it on APIs.io](https://apis.io/add/).
- **Anything else** — [the APIs.io inbox](https://github.com/api-search/inbox/issues/new) or [info@apievangelist.com](mailto:info@apievangelist.com).
