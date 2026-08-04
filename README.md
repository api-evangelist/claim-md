# Claim.MD (claim-md)

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

Claim.MD is a medical-claims clearinghouse that connects healthcare providers and software vendors to thousands of payers. Its REST API (authenticated with an AccountKey) supports electronic claim submission (837P/837I), claim status tracking, electronic remittance advice (835 ERA), real-time eligibility (270/271), and file upload/download workflows.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/claim-md/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/claim-md/refs/heads/main/apis.yml)

## Tags

- Healthcare
- Medical Claims
- Clearinghouse
- EDI
- X12
- Revenue Cycle

## Timestamps

- **Created:** 2026-06-21
- **Modified:** 2026-06-21

## APIs

### Claim.MD Claim Submission API

Upload batches of 1-2000 claims in 837P, 837I, CSV, JSON, XML, XLS, or XLSX format for scrubbing and routing to payers, then list and reconcile uploaded files.

- **Human URL:** [https://docs.claim.md/docs/api](https://docs.claim.md/docs/api)
- **Base URL:** `https://svc.claim.md/services`

#### Tags

- Claims
- 837
- 837P
- 837I
- EDI

#### Properties

- [Documentation](https://docs.claim.md/docs/api)
- [API Reference](https://api.claim.md/)
- [OpenAPI](openapi/claim-md-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/claim-md.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/claim-md.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Claim.MD Claim Status API

Incrementally retrieve claim status responses, acknowledgements, and claim modification and note history using ResponseID-based polling.

- **Human URL:** [https://docs.claim.md/docs/api](https://docs.claim.md/docs/api)
- **Base URL:** `https://svc.claim.md/services`

#### Tags

- Claim Status
- Tracking
- Acknowledgements

#### Properties

- [Documentation](https://docs.claim.md/docs/api)
- [API Reference](https://api.claim.md/)
- [OpenAPI](openapi/claim-md-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/claim-md.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/claim-md.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Claim.MD ERA / Remits API

List electronic remittance advice (ERA) and retrieve remittance detail as raw 835 X12, structured XML/JSON, or a printable PDF.

- **Human URL:** [https://docs.claim.md/docs/api](https://docs.claim.md/docs/api)
- **Base URL:** `https://svc.claim.md/services`

#### Tags

- ERA
- 835
- Remittance
- Payments

#### Properties

- [Documentation](https://docs.claim.md/docs/api)
- [API Reference](https://api.claim.md/)
- [OpenAPI](openapi/claim-md-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/claim-md.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/claim-md.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Claim.MD Eligibility API

Run real-time eligibility and benefit verification by submitting an X12 270 file or structured field data, returning a 271 response in XML or JSON (one request per patient).

- **Human URL:** [https://docs.claim.md/docs/api](https://docs.claim.md/docs/api)
- **Base URL:** `https://svc.claim.md/services`

#### Tags

- Eligibility
- 270
- 271
- Benefits

#### Properties

- [Documentation](https://docs.claim.md/docs/api)
- [API Reference](https://api.claim.md/)
- [OpenAPI](openapi/claim-md-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/claim-md.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/claim-md.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Claim.MD Responses & Files API

Look up the payer directory, manage provider enrollment and appeals, and receive asynchronous enrollment and appeal updates via webhook.

- **Human URL:** [https://docs.claim.md/docs/api](https://docs.claim.md/docs/api)
- **Base URL:** `https://svc.claim.md/services`

#### Tags

- Files
- Responses
- Payers
- Enrollment

#### Properties

- [Documentation](https://docs.claim.md/docs/api)
- [API Reference](https://api.claim.md/)
- [OpenAPI](openapi/claim-md-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/claim-md.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/claim-md.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [LinkedIn](https://www.linkedin.com/company/claim.md)
- [Website](https://www.claim.md)
- [Documentation](https://docs.claim.md/docs/index)
- [Plans](plans/claim-md-plans-pricing.yml)
- [Rate Limits](rate-limits/claim-md-rate-limits.yml)
- [Fin Ops](finops/claim-md-finops.yml)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
