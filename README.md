# Hyperline (hyperline)

Hyperline is a usage-based billing and subscription platform that helps B2B SaaS companies manage their entire quote-to-cash workflow. Its REST API covers customers, a product and plan catalog, subscriptions, real-time usage and event ingestion, invoicing, payments, credit notes, and webhooks for hybrid pricing models combining subscription and metered charges.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/hyperline/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/hyperline/refs/heads/main/apis.yml)

## Tags

- Billing
- Subscriptions
- Usage-Based
- Metering
- Payments
- Invoicing
- FinOps

## Timestamps

- **Created:** 2026-06-20
- **Modified:** 2026-06-20

## APIs

### Hyperline Customers API

Create, list, update, archive, and manage customers along with their payment methods, credits, features, segments, tax rates, valuation, and the self-serve customer portal.

- **Human URL:** [https://docs.hyperline.co/api-reference/endpoints/customers](https://docs.hyperline.co/api-reference/endpoints/customers)
- **Base URL:** `https://api.hyperline.co/v1`

#### Tags

- Customers
- Accounts
- Credits

#### Properties

- [Documentation](https://docs.hyperline.co/api-reference/docs/getting-started)
- [API Reference](https://docs.hyperline.co/api-reference/endpoints/customers)
- [OpenAPI](openapi/hyperline-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/hyperline.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/hyperline.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Hyperline Products & Plans API

Manage the product and pricing catalog - products, price books, price configurations, features, coupons, and promotion codes - including draft and versioned catalog publishing.

- **Human URL:** [https://docs.hyperline.co/api-reference/endpoints/products](https://docs.hyperline.co/api-reference/endpoints/products)
- **Base URL:** `https://api.hyperline.co/v1`

#### Tags

- Products
- Plans
- Catalog
- Pricing

#### Properties

- [Documentation](https://docs.hyperline.co/api-reference/endpoints/products)
- [API Reference](https://docs.hyperline.co/api-reference/endpoints/products)
- [OpenAPI](openapi/hyperline-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/hyperline.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/hyperline.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Hyperline Subscriptions API

Create and manage subscriptions across their full lifecycle - activate, pause, cancel, renew, reinstate, schedule updates and phase transitions - plus subscription templates, transitions, and quotes (CPQ).

- **Human URL:** [https://docs.hyperline.co/api-reference/endpoints/subscriptions](https://docs.hyperline.co/api-reference/endpoints/subscriptions)
- **Base URL:** `https://api.hyperline.co/v1`

#### Tags

- Subscriptions
- Lifecycle
- Quotes

#### Properties

- [Documentation](https://docs.hyperline.co/api-reference/endpoints/subscriptions)
- [API Reference](https://docs.hyperline.co/api-reference/endpoints/subscriptions)
- [OpenAPI](openapi/hyperline-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/hyperline.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/hyperline.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Hyperline Usage & Events API

Ingest billable events (single or batch), retrieve and delete events, simulate prices, and read aggregated customer usage via aggregators with grouped, timeseries, and per-event breakdowns.

- **Human URL:** [https://docs.hyperline.co/api-reference/endpoints/billable-events](https://docs.hyperline.co/api-reference/endpoints/billable-events)
- **Base URL:** `https://api.hyperline.co/v1`

#### Tags

- Usage
- Events
- Metering
- Ingestion

#### Properties

- [Documentation](https://docs.hyperline.co/api-reference/endpoints/billable-events)
- [API Reference](https://docs.hyperline.co/api-reference/endpoints/billable-events)
- [OpenAPI](openapi/hyperline-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/hyperline.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/hyperline.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Hyperline Invoices API

Create, list, update, charge, void, and download invoices; manage invoice transactions, mark uncollectible, validate, and issue credit notes against invoices.

- **Human URL:** [https://docs.hyperline.co/api-reference/endpoints/invoices](https://docs.hyperline.co/api-reference/endpoints/invoices)
- **Base URL:** `https://api.hyperline.co/v1`

#### Tags

- Invoices
- Credit Notes
- Billing

#### Properties

- [Documentation](https://docs.hyperline.co/api-reference/endpoints/invoices)
- [API Reference](https://docs.hyperline.co/api-reference/endpoints/invoices)
- [OpenAPI](openapi/hyperline-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/hyperline.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/hyperline.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Hyperline Payments API

Record payments and refund transactions across native payment provider integrations (Stripe, GoCardless, Mollie, Airwallex), plus bank accounts and customer wallets.

- **Human URL:** [https://docs.hyperline.co/api-reference/endpoints/payments](https://docs.hyperline.co/api-reference/endpoints/payments)
- **Base URL:** `https://api.hyperline.co/v1`

#### Tags

- Payments
- Transactions
- Refunds

#### Properties

- [Documentation](https://docs.hyperline.co/api-reference/endpoints/payments)
- [API Reference](https://docs.hyperline.co/api-reference/endpoints/payments)
- [OpenAPI](openapi/hyperline-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/hyperline.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/hyperline.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Hyperline Webhooks API

Register and manage webhook endpoints and inspect delivered webhook messages to receive real-time notifications of billing lifecycle events.

- **Human URL:** [https://docs.hyperline.co/api-reference/endpoints/webhooks](https://docs.hyperline.co/api-reference/endpoints/webhooks)
- **Base URL:** `https://api.hyperline.co/v1`

#### Tags

- Webhooks
- Events
- Notifications

#### Properties

- [Documentation](https://docs.hyperline.co/api-reference/endpoints/webhooks)
- [API Reference](https://docs.hyperline.co/api-reference/endpoints/webhooks)
- [OpenAPI](openapi/hyperline-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/hyperline.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/hyperline.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [LinkedIn](https://www.linkedin.com/company/hyperline)
- [Website](https://www.hyperline.co)
- [Documentation](https://docs.hyperline.co)
- [Plans](plans/hyperline-plans-pricing.yml)
- [Rate Limits](rate-limits/hyperline-rate-limits.yml)
- [Fin Ops](finops/hyperline-finops.yml)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
