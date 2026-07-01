# Truv (truv)

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
