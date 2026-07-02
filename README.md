# Kinde (kinde-so)

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
