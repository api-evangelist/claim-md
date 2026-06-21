# Claim.MD (claim-md)

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
