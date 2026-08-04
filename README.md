# Red Hat 3scale (red-hat-3scale)

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
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

Red Hat 3scale API Management is an enterprise-grade API management platform that enables organizations to share, secure, distribute, control, and monetize APIs across internal and external teams. It provides a developer portal, analytics, access control, policy enforcement, and billing for REST, SOAP, GraphQL, and other API types. 3scale runs on-premises via OpenShift or as a hosted managed service, and is fully Kubernetes-native.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/red-hat-3scale/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/red-hat-3scale/refs/heads/main/apis.yml)

## Scope

- **Type:** Index

## Tags

- API Gateway
- API Management
- Developer Portal
- Enterprise
- Red Hat

## Timestamps

- **Created:** 2026-03-16
- **Modified:** 2026-05-19

## APIs

### Red Hat 3scale Service Management API

The 3scale Service Management API allows API providers to control and manage access to their APIs, track usage, and enforce traffic policies. It is used by the API gateway (APIcast) to authorize and report API calls in real time. The API supports both API key and OAuth 2.0 based authorization flows. Calls are made from the API gateway on behalf of the API consumer application.

- **Human URL:** [https://access.redhat.com/documentation/en-us/red_hat_3scale_api_management](https://access.redhat.com/documentation/en-us/red_hat_3scale_api_management)
- **Base URL:** `https://su1.3scale.net`

#### Tags

- Access Control
- API Management
- Authorization
- Traffic Management

#### Properties

- [Documentation](https://access.redhat.com/documentation/en-us/red_hat_3scale_api_management/2.14/html/api_authentication/index)
- [Reference](https://access.redhat.com/documentation/en-us/red_hat_3scale_api_management/2.14/html/admin_portal_guide/index)
- [OpenAPI](openapi/red-hat-3scale-service-management-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/red-hat-3scale-service-management.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/red-hat-3scale-service-management.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Red Hat 3scale Account Management API

The 3scale Account Management API provides programmatic access to manage developer accounts, applications, application plans, keys, and API subscriptions within the 3scale platform. It enables automation of developer onboarding, subscription management, and application lifecycle operations from external systems or scripts. The API is accessible on the admin domain and requires admin API credentials.

- **Human URL:** [https://access.redhat.com/documentation/en-us/red_hat_3scale_api_management/2.14/html/admin_portal_guide/index](https://access.redhat.com/documentation/en-us/red_hat_3scale_api_management/2.14/html/admin_portal_guide/index)
- **Base URL:** `https://{your-domain}-admin.3scale.net`

#### Tags

- Account Management
- API Management
- Applications
- Developer Portal

#### Properties

- [Documentation](https://access.redhat.com/documentation/en-us/red_hat_3scale_api_management/2.14/html/admin_portal_guide/index)
- [Reference](https://access.redhat.com/documentation/en-us/red_hat_3scale_api_management/2.14/html/admin_portal_guide/accounts)
- [OpenAPI](openapi/red-hat-3scale-account-management-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/red-hat-3scale-account-management.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/red-hat-3scale-account-management.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Red Hat 3scale Analytics API

The 3scale Analytics API provides access to API usage data, traffic metrics, hit counts, and reporting for APIs managed through the 3scale platform. It enables operators to retrieve usage statistics, query by time period and granularity, and integrate analytics data into external dashboards or monitoring systems.

- **Human URL:** [https://access.redhat.com/documentation/en-us/red_hat_3scale_api_management/2.14/html/admin_portal_guide/analytics](https://access.redhat.com/documentation/en-us/red_hat_3scale_api_management/2.14/html/admin_portal_guide/analytics)
- **Base URL:** `https://{your-domain}-admin.3scale.net`

#### Tags

- Analytics
- API Management
- Metrics
- Reporting

#### Properties

- [Documentation](https://access.redhat.com/documentation/en-us/red_hat_3scale_api_management/2.14/html/admin_portal_guide/analytics)
- [OpenAPI](openapi/red-hat-3scale-analytics-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/red-hat-3scale-analytics.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/red-hat-3scale-analytics.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Red Hat 3scale Billing API

The 3scale Billing API enables management of billing and invoicing for API usage within the 3scale platform. It supports creating and managing invoices, payment transactions, and monetization of API subscriptions based on usage plans and application metrics. Billing is integrated with the account management system.

- **Human URL:** [https://access.redhat.com/documentation/en-us/red_hat_3scale_api_management/2.14/html/admin_portal_guide/billing](https://access.redhat.com/documentation/en-us/red_hat_3scale_api_management/2.14/html/admin_portal_guide/billing)
- **Base URL:** `https://{your-domain}-admin.3scale.net`

#### Tags

- API Management
- Billing
- Invoices
- Monetization

#### Properties

- [Documentation](https://access.redhat.com/documentation/en-us/red_hat_3scale_api_management/2.14/html/admin_portal_guide/billing)
- [OpenAPI](openapi/red-hat-3scale-billing-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/red-hat-3scale-billing.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/red-hat-3scale-billing.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Red Hat 3scale Webhooks

3scale Webhooks allow API providers to receive real-time HTTP callbacks about account, application, user, and plan events within the 3scale platform. Webhooks can be configured to trigger external systems when subscriptions change, new developers sign up, applications are updated, or keys are created or deleted.

- **Human URL:** [https://access.redhat.com/documentation/en-us/red_hat_3scale_api_management/2.14/html/admin_portal_guide/webhooks](https://access.redhat.com/documentation/en-us/red_hat_3scale_api_management/2.14/html/admin_portal_guide/webhooks)

#### Tags

- API Management
- Events
- Notifications
- Webhooks

#### Properties

- [Documentation](https://access.redhat.com/documentation/en-us/red_hat_3scale_api_management/2.14/html/admin_portal_guide/webhooks)
- [Postman Collection](collections/red-hat-3scale-account-management.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/red-hat-3scale-account-management.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/red-hat-3scale-analytics.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/red-hat-3scale-analytics.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/red-hat-3scale-apicast-management.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/red-hat-3scale-apicast-management.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/red-hat-3scale-billing.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/red-hat-3scale-billing.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/red-hat-3scale-service-management.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/red-hat-3scale-service-management.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Red Hat 3scale APIcast Management API

The APIcast Management API is an HTTP REST interface exposed by the APIcast API gateway on port 8090 for debugging and runtime configuration. It provides endpoints to retrieve and update the gateway configuration, inspect DNS cache, trigger boot/initialization, and check readiness and liveness health status. Access is controlled via the APICAST_MANAGEMENT_API environment variable.

- **Human URL:** [https://github.com/3scale/APIcast/blob/master/doc/management-api.md](https://github.com/3scale/APIcast/blob/master/doc/management-api.md)
- **Base URL:** `http://localhost:8090`

#### Tags

- API Gateway
- Configuration
- Health Checks
- Management

#### Properties

- [Documentation](https://github.com/3scale/APIcast/blob/master/doc/management-api.md)
- [OpenAPI](openapi/red-hat-3scale-apicast-management-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/red-hat-3scale-apicast-management.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/red-hat-3scale-apicast-management.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Red Hat 3scale Toolbox CLI

The 3scale Toolbox is a command-line interface for automating 3scale configuration tasks. It wraps the 3scale Admin REST API to support copying APIs between tenants, promoting configurations between staging and production environments, importing OpenAPI specifications, and managing application plans and policies from the command line or CI/CD pipelines.

- **Human URL:** [https://access.redhat.com/documentation/en-us/red_hat_3scale_api_management/2.14/html/operating_3scale/the-threescale-toolbox](https://access.redhat.com/documentation/en-us/red_hat_3scale_api_management/2.14/html/operating_3scale/the-threescale-toolbox)

#### Tags

- API Management
- Automation
- CLI
- DevOps

#### Properties

- [Documentation](https://access.redhat.com/documentation/en-us/red_hat_3scale_api_management/2.14/html/operating_3scale/the-threescale-toolbox)
- [Git Hub](https://github.com/3scale/3scale_toolbox)
- [Postman Collection](collections/red-hat-3scale-account-management.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/red-hat-3scale-account-management.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/red-hat-3scale-analytics.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/red-hat-3scale-analytics.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/red-hat-3scale-apicast-management.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/red-hat-3scale-apicast-management.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/red-hat-3scale-billing.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/red-hat-3scale-billing.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/red-hat-3scale-service-management.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/red-hat-3scale-service-management.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [LinkedIn](https://www.linkedin.com/company/3scale)
- [Website](https://www.redhat.com/en/technologies/jboss-middleware/3scale)
- [Documentation](https://access.redhat.com/documentation/en-us/red_hat_3scale_api_management)
- [Getting Started](https://access.redhat.com/documentation/en-us/red_hat_3scale_api_management/2.14/html/getting_started/index)
- [Portal](https://access.redhat.com/products/red-hat-3scale-api-management)
- [GitHub Organization](https://github.com/3scale)
- [GitHub Repository](https://github.com/3scale/APIcast)
- [GitHub Repository](https://github.com/3scale/porta)
- [GitHub Repository](https://github.com/3scale/3scale_toolbox)
- [Blog](https://www.redhat.com/en/blog/channel/red-hat-middleware)
- [Support](https://access.redhat.com/support)
- [Terms of Service](https://www.redhat.com/en/about/agreements)
- [Privacy Policy](https://www.redhat.com/en/about/privacy-policy)
- [Status Page](https://status.redhat.com/)
- [Changelog](https://access.redhat.com/documentation/en-us/red_hat_3scale_api_management/2.14/html/release_notes/index)
- [OpenAPI](openapi/red-hat-3scale-service-management-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [OpenAPI](openapi/red-hat-3scale-account-management-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [OpenAPI](openapi/red-hat-3scale-analytics-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [OpenAPI](openapi/red-hat-3scale-billing-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [OpenAPI](openapi/red-hat-3scale-apicast-management-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [J S O N L D Context](json-ld/red-hat-3scale-context.jsonld)
- [JSON Schema](json-schema/red-hat-3scale-account-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/red-hat-3scale-application-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Structure](json-structure/red-hat-3scale-account-structure.json)
- [Spectral Ruleset](rules/red-hat-3scale-rules.yml)
- [Vocabulary](vocabulary/red-hat-3scale-vocabulary.yml)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
