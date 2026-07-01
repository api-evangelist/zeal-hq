# Zeal (zeal-hq)

Zeal is an embedded, payroll-as-a-service platform. Its API lets software companies build their own payroll products - onboarding companies, employees, and 1099 contractors, running pay runs, disbursing pay, and handling tax calculation, filing, and compliance across all US jurisdictions - without becoming a payroll company themselves.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/zeal-hq/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/zeal-hq/refs/heads/main/apis.yml)

## Tags

- Payroll
- Embedded Finance
- Fintech
- Tax Compliance
- Contractors
- Human Resources

## Timestamps

- **Created:** 2026-07-01
- **Modified:** 2026-07-01

## APIs

### Zeal Companies API

Create and manage employer companies on the platform - company profile, onboarding links and status, authorization documents, and company bank accounts with micro-deposit verification.

- **Human URL:** [https://docs.zeal.com/reference/create-company](https://docs.zeal.com/reference/create-company)
- **Base URL:** `https://api.zeal.com`

#### Tags

- Companies
- Onboarding
- Bank Accounts

#### Properties

- [Documentation](https://docs.zeal.com/docs/what-is-zeal)
- [API Reference](https://docs.zeal.com/reference/create-company)
- [OpenAPI](openapi/zeal-hq-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/zeal-hq.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/zeal-hq.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Zeal Employees API

Create, retrieve, and update W-2 employees, upload government IDs, check onboarding requirements, and manage employee tax parameters and withholding.

- **Human URL:** [https://docs.zeal.com/reference/create-employee](https://docs.zeal.com/reference/create-employee)
- **Base URL:** `https://api.zeal.com`

#### Tags

- Employees
- W-2
- Workers

#### Properties

- [Documentation](https://docs.zeal.com/docs/employee-onboarding-guide)
- [API Reference](https://docs.zeal.com/reference/create-employee)
- [OpenAPI](openapi/zeal-hq-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/zeal-hq.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/zeal-hq.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Zeal Contractors API

Create, retrieve, and update 1099 contractors, upload government IDs, generate contractor onboarding links, and set onboarded status.

- **Human URL:** [https://docs.zeal.com/reference/create-contractor](https://docs.zeal.com/reference/create-contractor)
- **Base URL:** `https://api.zeal.com`

#### Tags

- Contractors
- 1099
- Workers

#### Properties

- [Documentation](https://docs.zeal.com/docs/contractor-onboarding-guide)
- [API Reference](https://docs.zeal.com/reference/create-contractor)
- [OpenAPI](openapi/zeal-hq-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/zeal-hq.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/zeal-hq.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Zeal Employee Check (Payroll Run) API

Create single and bulk employee checks (paychecks), attach and edit shifts, preview payroll, download paystub PDFs, and run pay runs that calculate gross-to-net and taxes.

- **Human URL:** [https://docs.zeal.com/reference/create-employee-check](https://docs.zeal.com/reference/create-employee-check)
- **Base URL:** `https://api.zeal.com`

#### Tags

- Payroll
- Paychecks
- Pay Runs

#### Properties

- [Documentation](https://docs.zeal.com/docs/regular-payroll)
- [API Reference](https://docs.zeal.com/reference/create-employee-check)
- [OpenAPI](openapi/zeal-hq-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/zeal-hq.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/zeal-hq.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Zeal Contractor Payments API

Create, retrieve, update, and delete contractor payments and trigger their disbursement to worker bank accounts.

- **Human URL:** [https://docs.zeal.com/reference/create-contractor-payment](https://docs.zeal.com/reference/create-contractor-payment)
- **Base URL:** `https://api.zeal.com`

#### Tags

- Contractor Payments
- Disbursement
- 1099

#### Properties

- [Documentation](https://docs.zeal.com/docs/contractor-onboarding-guide)
- [API Reference](https://docs.zeal.com/reference/create-contractor-payment)
- [OpenAPI](openapi/zeal-hq-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/zeal-hq.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/zeal-hq.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Zeal Pay Schedules API

Retrieve reporting periods, upcoming regular payroll, and the next available check and pay dates that drive the company's pay frequency and schedule.

- **Human URL:** [https://docs.zeal.com/reference/get-all-reporting-periods](https://docs.zeal.com/reference/get-all-reporting-periods)
- **Base URL:** `https://api.zeal.com`

#### Tags

- Pay Schedules
- Reporting Periods
- Check Dates

#### Properties

- [Documentation](https://docs.zeal.com/reference/pay-frequency-reporting-periods-and-check-dates)
- [API Reference](https://docs.zeal.com/reference/get-all-reporting-periods)
- [OpenAPI](openapi/zeal-hq-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/zeal-hq.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/zeal-hq.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Zeal Worker Onboarding API

Generate hosted onboarding links for employees and contractors - account setup, bank account collection, ID upload, W-4, I-9, and custom paperwork - so workers can complete compliant onboarding themselves.

- **Human URL:** [https://docs.zeal.com/reference/generate-employee-onboarding-link](https://docs.zeal.com/reference/generate-employee-onboarding-link)
- **Base URL:** `https://api.zeal.com`

#### Tags

- Onboarding
- Hosted Flows
- Compliance Paperwork

#### Properties

- [Documentation](https://docs.zeal.com/docs/employee-onboarding-guide)
- [API Reference](https://docs.zeal.com/reference/generate-employee-onboarding-link)
- [OpenAPI](openapi/zeal-hq-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/zeal-hq.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/zeal-hq.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Zeal Tax and Compliance API

Set and retrieve employee tax parameters and definitions, resolve taxable work locations, and look up minimum wage rules for automated, jurisdiction-aware payroll tax handling.

- **Human URL:** [https://docs.zeal.com/reference/get-employee-tax-parameter-definitions](https://docs.zeal.com/reference/get-employee-tax-parameter-definitions)
- **Base URL:** `https://api.zeal.com`

#### Tags

- Tax
- Compliance
- Minimum Wage

#### Properties

- [Documentation](https://docs.zeal.com/reference/introduction)
- [API Reference](https://docs.zeal.com/reference/get-employee-tax-parameter-definitions)
- [OpenAPI](openapi/zeal-hq-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/zeal-hq.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/zeal-hq.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Zeal Reports API

Generate asynchronous payroll reports - payroll journal, cash requirements, labor allocation, payment/worker summaries, quarter- and year-to-date - then poll job status and download the finished report.

- **Human URL:** [https://docs.zeal.com/reference/create-payroll-journal-report](https://docs.zeal.com/reference/create-payroll-journal-report)
- **Base URL:** `https://api.zeal.com`

#### Tags

- Reports
- Payroll Journal
- Analytics

#### Properties

- [Documentation](https://docs.zeal.com/reference/introduction)
- [API Reference](https://docs.zeal.com/reference/create-payroll-journal-report)
- [OpenAPI](openapi/zeal-hq-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/zeal-hq.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/zeal-hq.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Zeal Funding and Journal API

Inspect the reserve/provider balance funding payroll and build a payroll journal via the custom payroll journal report for accounting reconciliation.

- **Human URL:** [https://docs.zeal.com/reference/get-provider-balance](https://docs.zeal.com/reference/get-provider-balance)
- **Base URL:** `https://api.zeal.com`

#### Tags

- Funding
- Journal
- Accounting

#### Properties

- [Documentation](https://docs.zeal.com/reference/introduction)
- [API Reference](https://docs.zeal.com/reference/get-provider-balance)
- [OpenAPI](openapi/zeal-hq-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/zeal-hq.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/zeal-hq.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Zeal Webhooks and Events API

Subscribe to platform events - company, employee, contractor, bank account, employee-check and employer-check processed events - delivered as webhooks so consumers can react to payroll lifecycle changes.

- **Human URL:** [https://docs.zeal.com/reference/webhook-events](https://docs.zeal.com/reference/webhook-events)
- **Base URL:** `https://api.zeal.com`

#### Tags

- Webhooks
- Events
- Notifications

#### Properties

- [Documentation](https://docs.zeal.com/reference/webhook-events)
- [API Reference](https://docs.zeal.com/reference/webhook-events)
- [OpenAPI](openapi/zeal-hq-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/zeal-hq.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/zeal-hq.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [LinkedIn](https://www.linkedin.com/company/zeal-holdings)
- [Website](https://www.zeal.com)
- [Documentation](https://docs.zeal.com)
- [Plans](plans/zeal-hq-plans-pricing.yml)
- [Rate Limits](rate-limits/zeal-hq-rate-limits.yml)
- [Fin Ops](finops/zeal-hq-finops.yml)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
