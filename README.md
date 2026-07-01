# AccelByte (accelbyte)

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
