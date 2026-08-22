# Zeal (zeal-hq)

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
