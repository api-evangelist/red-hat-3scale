# Red Hat 3scale API Management

Red Hat 3scale API Management is an enterprise-grade API management platform that enables organizations to share, secure, distribute, control, and monetize APIs across internal and external teams. It provides a developer portal, analytics, access control, policy enforcement, and billing for REST, SOAP, GraphQL, and other API types. 3scale runs on-premises via OpenShift or as a hosted managed service, and is fully Kubernetes-native.

**URL:** [https://raw.githubusercontent.com/api-evangelist/red-hat-3scale/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/red-hat-3scale/refs/heads/main/apis.yml)

## Tags

API Gateway, API Management, Developer Portal, Enterprise, Red Hat

## APIs

### [Red Hat 3scale Service Management API](openapi/red-hat-3scale-service-management-openapi.yml)
The 3scale Service Management API allows API providers to control and manage access to their APIs, track usage, and enforce traffic policies. Used by the APIcast gateway to authorize and report API calls in real time.

**Base URL:** `https://su1.3scale.net`

- [Documentation](https://access.redhat.com/documentation/en-us/red_hat_3scale_api_management/2.14/html/api_authentication/index)
- [OpenAPI](openapi/red-hat-3scale-service-management-openapi.yml)

### [Red Hat 3scale Account Management API](openapi/red-hat-3scale-account-management-openapi.yml)
The 3scale Account Management API provides programmatic access to manage developer accounts, applications, application plans, keys, and API subscriptions within the 3scale platform.

**Base URL:** `https://{domain}-admin.3scale.net/admin/api`

- [Documentation](https://access.redhat.com/documentation/en-us/red_hat_3scale_api_management/2.14/html/admin_portal_guide/index)
- [OpenAPI](openapi/red-hat-3scale-account-management-openapi.yml)

### [Red Hat 3scale Analytics API](openapi/red-hat-3scale-analytics-openapi.yml)
The 3scale Analytics API provides access to API usage data, traffic metrics, hit counts, and reporting for APIs managed through the 3scale platform.

**Base URL:** `https://{domain}-admin.3scale.net/stats`

- [Documentation](https://access.redhat.com/documentation/en-us/red_hat_3scale_api_management/2.14/html/admin_portal_guide/analytics)
- [OpenAPI](openapi/red-hat-3scale-analytics-openapi.yml)

### [Red Hat 3scale Billing API](openapi/red-hat-3scale-billing-openapi.yml)
The 3scale Billing API enables management of billing and invoicing for API usage including invoices, payment transactions, and monetization of API subscriptions.

**Base URL:** `https://{domain}-admin.3scale.net/api`

- [Documentation](https://access.redhat.com/documentation/en-us/red_hat_3scale_api_management/2.14/html/admin_portal_guide/billing)
- [OpenAPI](openapi/red-hat-3scale-billing-openapi.yml)

### [Red Hat 3scale APIcast Management API](openapi/red-hat-3scale-apicast-management-openapi.yml)
The APIcast Management API is an HTTP REST interface exposed by the APIcast gateway for debugging and runtime configuration. Provides configuration management, DNS cache inspection, and health check endpoints.

**Base URL:** `http://localhost:8090`

- [Documentation](https://github.com/3scale/APIcast/blob/master/doc/management-api.md)
- [OpenAPI](openapi/red-hat-3scale-apicast-management-openapi.yml)

### Red Hat 3scale Webhooks
3scale Webhooks deliver real-time HTTP callbacks for account, application, and subscription events. Configurable to trigger external systems on developer signups, application changes, and key lifecycle events.

- [Documentation](https://access.redhat.com/documentation/en-us/red_hat_3scale_api_management/2.14/html/admin_portal_guide/webhooks)

### Red Hat 3scale Toolbox CLI
The 3scale Toolbox is a CLI for automating 3scale configuration tasks including copying APIs between tenants, promoting configurations, and importing OpenAPI specifications.

- [Documentation](https://access.redhat.com/documentation/en-us/red_hat_3scale_api_management/2.14/html/operating_3scale/the-threescale-toolbox)
- [GitHub](https://github.com/3scale/3scale_toolbox)

## Capabilities

### Workflow Capabilities

| Capability | Description |
|-----------|-------------|
| [API Management](capabilities/api-management.yaml) | Unified capability combining traffic authorization and developer account lifecycle management (8 MCP tools) |

### Shared Definitions

| File | API |
|------|-----|
| [service-management-api.yaml](capabilities/shared/service-management-api.yaml) | 3scale Service Management API |
| [account-management-api.yaml](capabilities/shared/account-management-api.yaml) | 3scale Account Management API |

## Artifacts

| Type | File |
|------|------|
| JSON Schema | [Account](json-schema/red-hat-3scale-account-schema.json) |
| JSON Schema | [Application](json-schema/red-hat-3scale-application-schema.json) |
| JSON Structure | [Account Structure](json-structure/red-hat-3scale-account-structure.json) |
| JSON-LD Context | [3scale Context](json-ld/red-hat-3scale-context.jsonld) |
| Spectral Rules | [3scale Rules](rules/red-hat-3scale-rules.yml) |
| Vocabulary | [3scale Vocabulary](vocabulary/red-hat-3scale-vocabulary.yml) |

## Examples

- [Authorize Transaction](examples/red-hat-3scale-authorize-transaction-example.json)
- [Create Account](examples/red-hat-3scale-create-account-example.json)
- [List Applications](examples/red-hat-3scale-list-applications-example.json)

## Common Properties

- [Website](https://www.redhat.com/en/technologies/jboss-middleware/3scale)
- [Documentation](https://access.redhat.com/documentation/en-us/red_hat_3scale_api_management)
- [Getting Started](https://access.redhat.com/documentation/en-us/red_hat_3scale_api_management/2.14/html/getting_started/index)
- [Portal](https://access.redhat.com/products/red-hat-3scale-api-management)
- [GitHub Organization](https://github.com/3scale)
- [Blog](https://www.redhat.com/en/blog/channel/red-hat-middleware)
- [Support](https://access.redhat.com/support)
- [Status](https://status.redhat.com/)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
