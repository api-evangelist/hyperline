# Hyperline (hyperline)

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
