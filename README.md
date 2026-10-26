# AccelByte (accelbyte)

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

AccelByte provides AccelByte Gaming Services (AGS), a modular backend platform for live games. Its REST services cover player accounts and IAM, player profiles, cloud save, statistics and leaderboards, matchmaking, lobby and session, commerce and monetization, seasons and battle pass, achievements, dedicated server management (Armada/DSMC), analytics and telemetry, and user-generated content, all secured with OAuth2 client credentials and namespace-scoped IAM.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/accelbyte/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/accelbyte/refs/heads/main/apis.yml)

## Tags

- Gaming
- Backend
- BaaS
- Live Services
- Player Accounts
- Commerce

## Timestamps

- **Created:** 2026-07-01
- **Modified:** 2026-07-01

## APIs

### AccelByte IAM API

Identity and Access Management - user registration and login, OAuth2 token issuance (client credentials, authorization code, platform token exchange), JWT verification, roles, permissions, and third-party platform account linking, all scoped to a namespace.

- **Human URL:** [https://docs.accelbyte.io/gaming-services/services/access/](https://docs.accelbyte.io/gaming-services/services/access/)
- **Base URL:** `https://demo.accelbyte.io/iam`

#### Tags

- IAM
- Identity
- OAuth2
- Authentication

#### Properties

- [Documentation](https://docs.accelbyte.io/gaming-services/services/access/)
- [API Reference](https://docs.accelbyte.io/api-explorer/)
- [OpenAPI](openapi/accelbyte-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/accelbyte.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/accelbyte.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### AccelByte Basic (Player Profile) API

Player profiles, namespaces, files/avatar storage, and misc user-facing metadata that games attach to a player identity.

- **Human URL:** [https://docs.accelbyte.io/gaming-services/services/social/basic/](https://docs.accelbyte.io/gaming-services/services/social/basic/)
- **Base URL:** `https://demo.accelbyte.io/basic`

#### Tags

- Player Profile
- Basic
- User Data

#### Properties

- [Documentation](https://docs.accelbyte.io/gaming-services/services/social/basic/)
- [OpenAPI](openapi/accelbyte-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/accelbyte.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/accelbyte.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### AccelByte Cloud Save API

Stores and retrieves game and player data as JSON records - player records, game records, and public/private key-value state that persists across sessions and devices.

- **Human URL:** [https://docs.accelbyte.io/gaming-services/services/engagement/cloudsave/](https://docs.accelbyte.io/gaming-services/services/engagement/cloudsave/)
- **Base URL:** `https://demo.accelbyte.io/cloudsave`

#### Tags

- Cloud Save
- Player Data
- Records

#### Properties

- [Documentation](https://docs.accelbyte.io/gaming-services/services/engagement/cloudsave/)
- [OpenAPI](openapi/accelbyte-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/accelbyte.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/accelbyte.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### AccelByte Statistics & Leaderboard API

Defines stat configurations, records player stat items, and exposes ranked leaderboards (all-time, weekly, monthly) built on top of tracked statistics.

- **Human URL:** [https://docs.accelbyte.io/gaming-services/services/engagement/statistics/](https://docs.accelbyte.io/gaming-services/services/engagement/statistics/)
- **Base URL:** `https://demo.accelbyte.io/social`

#### Tags

- Statistics
- Leaderboard
- Stats

#### Properties

- [Documentation](https://docs.accelbyte.io/gaming-services/services/engagement/statistics/)
- [Documentation](https://docs.accelbyte.io/gaming-services/services/engagement/leaderboard/)
- [OpenAPI](openapi/accelbyte-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/accelbyte.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/accelbyte.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### AccelByte Matchmaking API

Rule-based matchmaking (Matchmaking V2) - create and manage match pools, submit match tickets, and produce balanced match sessions handed off to the session service.

- **Human URL:** [https://docs.accelbyte.io/gaming-services/services/play/matchmaking/](https://docs.accelbyte.io/gaming-services/services/play/matchmaking/)
- **Base URL:** `https://demo.accelbyte.io/match2`

#### Tags

- Matchmaking
- Match
- Sessions

#### Properties

- [Documentation](https://docs.accelbyte.io/gaming-services/services/play/matchmaking/)
- [OpenAPI](openapi/accelbyte-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/accelbyte.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/accelbyte.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### AccelByte Lobby & Session API

Game sessions and parties (Session V2) plus lobby features - party management, friends, presence, and chat coordination for players before and during a match.

- **Human URL:** [https://docs.accelbyte.io/gaming-services/services/play/session/](https://docs.accelbyte.io/gaming-services/services/play/session/)
- **Base URL:** `https://demo.accelbyte.io/session`

#### Tags

- Session
- Lobby
- Party
- Presence

#### Properties

- [Documentation](https://docs.accelbyte.io/gaming-services/services/play/session/)
- [Documentation](https://docs.accelbyte.io/gaming-services/services/play/lobby/)
- [OpenAPI](openapi/accelbyte-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/accelbyte.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/accelbyte.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### AccelByte Commerce (Platform) API

In-game commerce and monetization - catalog/stores, items, entitlements, wallets and virtual currencies, orders and checkout, fulfillment, and integrations with real-money payment gateways.

- **Human URL:** [https://docs.accelbyte.io/gaming-services/services/monetization/](https://docs.accelbyte.io/gaming-services/services/monetization/)
- **Base URL:** `https://demo.accelbyte.io/platform`

#### Tags

- Commerce
- Monetization
- Store
- Entitlement
- Wallet

#### Properties

- [Documentation](https://docs.accelbyte.io/gaming-services/services/monetization/)
- [OpenAPI](openapi/accelbyte-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/accelbyte.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/accelbyte.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### AccelByte Seasons & Battle Pass API

Season Pass / Battle Pass - define seasons, tiers, passes, and rewards, grant experience, and track player progression and claimed rewards across a season.

- **Human URL:** [https://docs.accelbyte.io/gaming-services/services/engagement/season-pass/](https://docs.accelbyte.io/gaming-services/services/engagement/season-pass/)
- **Base URL:** `https://demo.accelbyte.io/seasonpass`

#### Tags

- Seasons
- Battle Pass
- Rewards

#### Properties

- [Documentation](https://docs.accelbyte.io/gaming-services/services/engagement/season-pass/)
- [OpenAPI](openapi/accelbyte-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/accelbyte.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/accelbyte.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### AccelByte Achievement API

Achievement definitions (incremental and standard), player unlock tracking, and tie-ins with statistics so achievements progress automatically as stats change.

- **Human URL:** [https://docs.accelbyte.io/gaming-services/services/engagement/achievement/](https://docs.accelbyte.io/gaming-services/services/engagement/achievement/)
- **Base URL:** `https://demo.accelbyte.io/achievement`

#### Tags

- Achievements
- Trophies
- Progression

#### Properties

- [Documentation](https://docs.accelbyte.io/gaming-services/services/engagement/achievement/)
- [OpenAPI](openapi/accelbyte-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/accelbyte.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/accelbyte.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### AccelByte Dedicated Server (Armada/DSMC) API

Dedicated Server Manager (Armada/DSMC) - register and manage dedicated game server fleets, claim and release server sessions, and orchestrate multi-region server scaling for session-based games.

- **Human URL:** [https://docs.accelbyte.io/gaming-services/services/ags-cloud/armada/](https://docs.accelbyte.io/gaming-services/services/ags-cloud/armada/)
- **Base URL:** `https://demo.accelbyte.io/dsmcontroller`

#### Tags

- Dedicated Servers
- DSMC
- Armada
- Fleet

#### Properties

- [Documentation](https://docs.accelbyte.io/gaming-services/services/ags-cloud/armada/)
- [OpenAPI](openapi/accelbyte-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/accelbyte.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/accelbyte.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### AccelByte Analytics & Telemetry API

Game Telemetry - ingest gameplay and client telemetry events (single and batched) for the analytics pipeline, feeding dashboards and downstream data exports.

- **Human URL:** [https://docs.accelbyte.io/gaming-services/services/analytics/game-telemetry/](https://docs.accelbyte.io/gaming-services/services/analytics/game-telemetry/)
- **Base URL:** `https://demo.accelbyte.io/game-telemetry`

#### Tags

- Analytics
- Telemetry
- Events

#### Properties

- [Documentation](https://docs.accelbyte.io/gaming-services/services/analytics/game-telemetry/)
- [OpenAPI](openapi/accelbyte-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/accelbyte.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/accelbyte.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### AccelByte UGC API

User-Generated Content - lets players create, upload, tag, share, like, and download content (channels, contents, and metadata) with moderation hooks.

- **Human URL:** [https://docs.accelbyte.io/gaming-services/services/engagement/ugc/](https://docs.accelbyte.io/gaming-services/services/engagement/ugc/)
- **Base URL:** `https://demo.accelbyte.io/ugc`

#### Tags

- UGC
- User Generated Content
- Content

#### Properties

- [Documentation](https://docs.accelbyte.io/gaming-services/services/engagement/ugc/)
- [OpenAPI](openapi/accelbyte-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/accelbyte.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/accelbyte.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [GitHub Organization](https://github.com/AccelByte)
- [LinkedIn](https://www.linkedin.com/company/accelbyte)
- [Website](https://accelbyte.io/)
- [Documentation](https://docs.accelbyte.io/)
- [Plans](plans/accelbyte-plans-pricing.yml)
- [Rate Limits](rate-limits/accelbyte-rate-limits.yml)
- [Fin Ops](finops/accelbyte-finops.yml)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
