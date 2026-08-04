# Truv (truv)

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

Truv provides consumer-permissioned access to payroll, income, and employment data. Its platform lets applicants connect their payroll accounts to instantly verify income and employment, retrieve pay statements, and switch direct deposit, replacing manual document collection and legacy verification services across lending, background screening, and fintech workflows.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/truv/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/truv/refs/heads/main/apis.yml)

## Tags

- Income Verification
- Employment Verification
- Payroll
- Direct Deposit
- Consumer Permissioned Data
- Fintech

## Timestamps

- **Created:** 2026-07-01
- **Modified:** 2026-07-01

## APIs

### Truv Users API

Create and manage the end users (consumers) whose payroll, income, and employment data will be connected and verified through Truv.

- **Human URL:** [https://docs.truv.com/reference/users_create](https://docs.truv.com/reference/users_create)
- **Base URL:** `https://prod.truv.com/v1`

#### Tags

- Users
- Consumers

#### Properties

- [Documentation](https://docs.truv.com/reference/users_create)
- [OpenAPI](openapi/truv-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/truv.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/truv.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Truv Bridge Tokens API

Mint short-lived bridge tokens that initialize the Truv Bridge front-end widget, plus link-access tokens for embedding connect flows.

- **Human URL:** [https://docs.truv.com/reference/users_tokens_create](https://docs.truv.com/reference/users_tokens_create)
- **Base URL:** `https://prod.truv.com/v1`

#### Tags

- Bridge Token
- Truv Bridge
- Access Tokens

#### Properties

- [Documentation](https://docs.truv.com/reference/users_tokens_create)
- [OpenAPI](openapi/truv-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/truv.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/truv.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Truv Links API

List, retrieve, and delete links that represent a consumer's connection to a payroll or financial data source, and trigger refresh tasks to pull fresh data.

- **Human URL:** [https://docs.truv.com/reference/links_list](https://docs.truv.com/reference/links_list)
- **Base URL:** `https://prod.truv.com/v1`

#### Tags

- Links
- Connections
- Refresh

#### Properties

- [Documentation](https://docs.truv.com/reference/links_list)
- [OpenAPI](openapi/truv-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/truv.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/truv.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Truv Employment Verification API

Retrieve verification-of-employment data and reports for a connected link, including employer, job title, status, and tenure.

- **Human URL:** [https://docs.truv.com/reference/links_employment_retrieve](https://docs.truv.com/reference/links_employment_retrieve)
- **Base URL:** `https://prod.truv.com/v1`

#### Tags

- Employment Verification
- VOE

#### Properties

- [Documentation](https://docs.truv.com/reference/links_employment_retrieve)
- [OpenAPI](openapi/truv-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/truv.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/truv.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Truv Income Verification API

Retrieve income reports, income transaction reports, and income insights derived from a consumer's connected payroll and financial accounts.

- **Human URL:** [https://docs.truv.com/reference/links_income_report_retrieve](https://docs.truv.com/reference/links_income_report_retrieve)
- **Base URL:** `https://prod.truv.com/v1`

#### Tags

- Income Verification
- VOI
- Income Insights

#### Properties

- [Documentation](https://docs.truv.com/reference/links_income_report_retrieve)
- [OpenAPI](openapi/truv-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/truv.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/truv.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Truv Pay Statements API

Retrieve individual pay statements (paystub documents) associated with a connected payroll link.

- **Human URL:** [https://docs.truv.com/reference/links_statements_retrieve](https://docs.truv.com/reference/links_statements_retrieve)
- **Base URL:** `https://prod.truv.com/v1`

#### Tags

- Pay Statements
- Paystubs
- Documents

#### Properties

- [Documentation](https://docs.truv.com/reference/links_statements_retrieve)
- [OpenAPI](openapi/truv-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/truv.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/truv.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Truv Direct Deposit Switch API

Retrieve direct deposit and deposit switch reports that let consumers move or update the account where their paycheck is deposited.

- **Human URL:** [https://docs.truv.com/reference/links_direct_deposit_report_retrieve](https://docs.truv.com/reference/links_direct_deposit_report_retrieve)
- **Base URL:** `https://prod.truv.com/v1`

#### Tags

- Direct Deposit
- Deposit Switch

#### Properties

- [Documentation](https://docs.truv.com/reference/links_direct_deposit_report_retrieve)
- [OpenAPI](openapi/truv-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/truv.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/truv.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Truv Payroll & Shifts API

Retrieve shift-level payroll data from connected platforms, supporting gig and hourly worker income and employment use cases.

- **Human URL:** [https://docs.truv.com/reference/links_shifts_retrieve](https://docs.truv.com/reference/links_shifts_retrieve)
- **Base URL:** `https://prod.truv.com/v1`

#### Tags

- Payroll
- Shifts
- Gig

#### Properties

- [Documentation](https://docs.truv.com/reference/links_shifts_retrieve)
- [OpenAPI](openapi/truv-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/truv.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/truv.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Truv Insurance API

Retrieve insurance reports for a connected link, including auto and home insurance policy data pulled with consumer permission.

- **Human URL:** [https://docs.truv.com/reference/links_insurance_report_retrieve](https://docs.truv.com/reference/links_insurance_report_retrieve)
- **Base URL:** `https://prod.truv.com/v1`

#### Tags

- Insurance
- Auto Insurance
- Home Insurance

#### Properties

- [Documentation](https://docs.truv.com/reference/links_insurance_report_retrieve)
- [OpenAPI](openapi/truv-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/truv.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/truv.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Truv Orders API

Create and manage verification orders end to end - lookup, update, cancel, add employers, and retrieve order events and certifications for fulfillment-style verification workflows.

- **Human URL:** [https://docs.truv.com/reference/orders_create](https://docs.truv.com/reference/orders_create)
- **Base URL:** `https://prod.truv.com/v1`

#### Tags

- Orders
- Verifications
- Certifications

#### Properties

- [Documentation](https://docs.truv.com/reference/orders_create)
- [OpenAPI](openapi/truv-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/truv.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/truv.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Truv Identity & Banking API

Retrieve consumer identity plus verification-of-assets banking data - auth, balances, bank accounts and statements, transactions, investments, and liabilities - from connected accounts.

- **Human URL:** [https://docs.truv.com/reference/links_identity_retrieve](https://docs.truv.com/reference/links_identity_retrieve)
- **Base URL:** `https://prod.truv.com/v1`

#### Tags

- Identity
- Banking
- VOA
- Transactions

#### Properties

- [Documentation](https://docs.truv.com/reference/links_identity_retrieve)
- [OpenAPI](openapi/truv-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/truv.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/truv.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Truv Webhooks API

Register and manage webhook endpoints to receive HMAC-signed event notifications as links, orders, and reports complete asynchronously.

- **Human URL:** [https://docs.truv.com/reference/webhooks_list](https://docs.truv.com/reference/webhooks_list)
- **Base URL:** `https://prod.truv.com/v1`

#### Tags

- Webhooks
- Events
- Notifications

#### Properties

- [Documentation](https://docs.truv.com/reference/webhooks_list)
- [OpenAPI](openapi/truv-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/truv.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/truv.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [GitHub Organization](https://github.com/truvhq)
- [LinkedIn](https://www.linkedin.com/company/truvhq)
- [Website](https://truv.com)
- [Documentation](https://docs.truv.com)
- [Plans](plans/truv-plans-pricing.yml)
- [Rate Limits](rate-limits/truv-rate-limits.yml)
- [Fin Ops](finops/truv-finops.yml)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
