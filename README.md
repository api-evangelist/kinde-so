# Kinde (kinde-so)

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

Kinde is an authentication and user management platform for SaaS and B2B applications - handling sign-up and login, multi-factor authentication, organizations, roles and permissions, feature flags, and usage-based billing. The Kinde Management API programmatically manages a Kinde business over a subdomain-scoped base URL (`https://{yourbusiness}.kinde.com/api/v1`), authenticated with a Bearer JWT obtained via the OAuth2 `client_credentials` flow from a machine-to-machine (M2M) application. Almost everything available in the Kinde admin UI is available through the API.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/kinde-so/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/kinde-so/refs/heads/main/apis.yml)

## Tags

- Authentication
- User Management
- Identity
- Authorization
- SaaS
- CIAM

## Timestamps

- **Created:** 2026-07-02
- **Modified:** 2026-07-02

## APIs

### Kinde Users API

Create, list, get, update, and delete users, plus manage their identities, sessions, passwords, MFA factors, per-user properties, and feature-flag overrides. Includes user search and refresh-claims.

- **Human URL:** [https://docs.kinde.com/kinde-apis/management/#tag/users](https://docs.kinde.com/kinde-apis/management/#tag/users)
- **Base URL:** `https://{yourbusiness}.kinde.com/api/v1`

#### Tags

- Users
- Identities
- Sessions

#### Properties

- [Documentation](https://docs.kinde.com/kinde-apis/management/)
- [API Reference](https://docs.kinde.com/kinde-apis/management/#tag/users)
- [OpenAPI](openapi/kinde-so-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/kinde-so.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/kinde-so.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Kinde Organizations API

Manage organizations (tenants) and their membership - create and update orgs, add and remove users, assign org-scoped roles, permissions, and feature flags, manage invites, connections, properties, logos, passkeys, MFA, and sessions for each organization.

- **Human URL:** [https://docs.kinde.com/kinde-apis/management/#tag/organizations](https://docs.kinde.com/kinde-apis/management/#tag/organizations)
- **Base URL:** `https://{yourbusiness}.kinde.com/api/v1`

#### Tags

- Organizations
- B2B
- Multi-Tenancy

#### Properties

- [API Reference](https://docs.kinde.com/kinde-apis/management/#tag/organizations)
- [OpenAPI](openapi/kinde-so-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/kinde-so.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/kinde-so.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Kinde Roles API

Define role-based access control - create, list, update, and delete roles, and attach permissions, API scopes, and users to each role.

- **Human URL:** [https://docs.kinde.com/kinde-apis/management/#tag/roles](https://docs.kinde.com/kinde-apis/management/#tag/roles)
- **Base URL:** `https://{yourbusiness}.kinde.com/api/v1`

#### Tags

- Roles
- RBAC
- Authorization

#### Properties

- [API Reference](https://docs.kinde.com/kinde-apis/management/#tag/roles)
- [OpenAPI](openapi/kinde-so-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/kinde-so.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/kinde-so.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Kinde Permissions API

Create, list, update, and delete the granular permissions that are grouped into roles and enforced across your applications and APIs.

- **Human URL:** [https://docs.kinde.com/kinde-apis/management/#tag/permissions](https://docs.kinde.com/kinde-apis/management/#tag/permissions)
- **Base URL:** `https://{yourbusiness}.kinde.com/api/v1`

#### Tags

- Permissions
- Authorization
- RBAC

#### Properties

- [API Reference](https://docs.kinde.com/kinde-apis/management/#tag/permissions)
- [OpenAPI](openapi/kinde-so-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/kinde-so.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/kinde-so.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Kinde Feature Flags API

Create and delete feature flags and set their values at the environment, organization, and individual-user levels for progressive rollouts and per-tenant configuration.

- **Human URL:** [https://docs.kinde.com/kinde-apis/management/#tag/feature-flags](https://docs.kinde.com/kinde-apis/management/#tag/feature-flags)
- **Base URL:** `https://{yourbusiness}.kinde.com/api/v1`

#### Tags

- Feature Flags
- Rollouts
- Configuration

#### Properties

- [API Reference](https://docs.kinde.com/kinde-apis/management/#tag/feature-flags)
- [OpenAPI](openapi/kinde-so-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/kinde-so.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/kinde-so.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Kinde Applications API

Manage the OAuth applications (clients) registered in your business - create, get, update, and delete apps, wire up their connections and properties, configure token customization, and manage authorized redirect and logout callback URLs.

- **Human URL:** [https://docs.kinde.com/kinde-apis/management/#tag/applications](https://docs.kinde.com/kinde-apis/management/#tag/applications)
- **Base URL:** `https://{yourbusiness}.kinde.com/api/v1`

#### Tags

- Applications
- OAuth Clients
- Callbacks

#### Properties

- [API Reference](https://docs.kinde.com/kinde-apis/management/#tag/applications)
- [OpenAPI](openapi/kinde-so-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/kinde-so.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/kinde-so.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Kinde Connections API

Manage authentication connections - social and enterprise SSO identity providers, connected third-party apps (OAuth token exchange), and SCIM directories used to provision users into your organizations.

- **Human URL:** [https://docs.kinde.com/kinde-apis/management/#tag/connections](https://docs.kinde.com/kinde-apis/management/#tag/connections)
- **Base URL:** `https://{yourbusiness}.kinde.com/api/v1`

#### Tags

- Connections
- SSO
- Directories

#### Properties

- [API Reference](https://docs.kinde.com/kinde-apis/management/#tag/connections)
- [OpenAPI](openapi/kinde-so-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/kinde-so.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/kinde-so.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Kinde APIs and Scopes API

Register the APIs your applications protect, define and assign their scopes, authorize applications against them, and issue and verify API keys for machine-to-machine access.

- **Human URL:** [https://docs.kinde.com/kinde-apis/management/#tag/apis](https://docs.kinde.com/kinde-apis/management/#tag/apis)
- **Base URL:** `https://{yourbusiness}.kinde.com/api/v1`

#### Tags

- APIs
- Scopes
- API Keys

#### Properties

- [API Reference](https://docs.kinde.com/kinde-apis/management/#tag/apis)
- [OpenAPI](openapi/kinde-so-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/kinde-so.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/kinde-so.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Kinde Subscribers API

List, get, and create subscribers - the marketing contacts captured by your Kinde business, distinct from authenticated users.

- **Human URL:** [https://docs.kinde.com/kinde-apis/management/#tag/subscribers](https://docs.kinde.com/kinde-apis/management/#tag/subscribers)
- **Base URL:** `https://{yourbusiness}.kinde.com/api/v1`

#### Tags

- Subscribers
- Marketing
- Contacts

#### Properties

- [API Reference](https://docs.kinde.com/kinde-apis/management/#tag/subscribers)
- [OpenAPI](openapi/kinde-so-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/kinde-so.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/kinde-so.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Kinde Business API

Read and update business-level settings and environment configuration (logos, feature flags, environment variables, passkey policy), plus reference data endpoints for industries and timezones.

- **Human URL:** [https://docs.kinde.com/kinde-apis/management/#tag/business](https://docs.kinde.com/kinde-apis/management/#tag/business)
- **Base URL:** `https://{yourbusiness}.kinde.com/api/v1`

#### Tags

- Business
- Environment
- Reference Data

#### Properties

- [API Reference](https://docs.kinde.com/kinde-apis/management/#tag/business)
- [OpenAPI](openapi/kinde-so-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/kinde-so.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/kinde-so.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Kinde Properties API

Define custom properties and property categories used to attach structured metadata to users, organizations, and applications, and surface it in tokens.

- **Human URL:** [https://docs.kinde.com/kinde-apis/management/#tag/properties](https://docs.kinde.com/kinde-apis/management/#tag/properties)
- **Base URL:** `https://{yourbusiness}.kinde.com/api/v1`

#### Tags

- Properties
- Metadata
- Custom Data

#### Properties

- [API Reference](https://docs.kinde.com/kinde-apis/management/#tag/properties)
- [OpenAPI](openapi/kinde-so-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/kinde-so.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/kinde-so.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Kinde Webhooks API

Create, list, update, and delete webhook endpoints that receive Kinde events (user, organization, and other lifecycle events), enumerate the available event types, and retrieve individual delivered events.

- **Human URL:** [https://docs.kinde.com/kinde-apis/management/#tag/webhooks](https://docs.kinde.com/kinde-apis/management/#tag/webhooks)
- **Base URL:** `https://{yourbusiness}.kinde.com/api/v1`

#### Tags

- Webhooks
- Events
- Eventing

#### Properties

- [API Reference](https://docs.kinde.com/kinde-apis/management/#tag/webhooks)
- [OpenAPI](openapi/kinde-so-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/kinde-so.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/kinde-so.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Kinde Billing API

Kinde's own usage-based billing product - read customer entitlements, create and list billing agreements, and record metered usage for plan-gated features.

- **Human URL:** [https://docs.kinde.com/kinde-apis/management/#tag/billing-entitlements](https://docs.kinde.com/kinde-apis/management/#tag/billing-entitlements)
- **Base URL:** `https://{yourbusiness}.kinde.com/api/v1`

#### Tags

- Billing
- Entitlements
- Metering

#### Properties

- [API Reference](https://docs.kinde.com/kinde-apis/management/#tag/billing-entitlements)
- [OpenAPI](openapi/kinde-so-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/kinde-so.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/kinde-so.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [GitHub Organization](https://github.com/kinde-oss)
- [LinkedIn](https://www.linkedin.com/company/kinde)
- [Website](https://kinde.com)
- [Documentation](https://docs.kinde.com)
- [Plans](plans/kinde-so-plans-pricing.yml)
- [Rate Limits](rate-limits/kinde-so-rate-limits.yml)
- [Fin Ops](finops/kinde-so-finops.yml)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
