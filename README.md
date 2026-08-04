# Mockaroo (mockaroo)

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

Mockaroo is a realistic mock data generator and API mocking service used by developers and QA teams to produce JSON, CSV, TXT, custom-delimited, SQL, and XML test data. The platform combines a schema designer, 150+ built-in field types (Name, Internet, Address, Business, Date, Currency, Geographic, Phone, Health, Technology, and more), named datasets used as lookup sources, hosted mock APIs, formulas, projects, AI-assisted field generation, de-identification, and a REST API for programmatic generation. Mockaroo ships in four tiers (Free, Silver, Gold, Enterprise), with the Enterprise tier available as a Docker image for self-hosted, unlimited generation.

**APIs.json:** [https://www.mockaroo.com/docs](https://www.mockaroo.com/docs)

## Scope

- **Type:** Index
- **Access:** 3rd-Party

## Tags

- Test Data
- Mock Data
- API Mocking
- Data Generation
- Developer Tools
- QA Testing
- Realistic Data
- Schemas
- Datasets
- Public APIs

## Timestamps

- **Created:** 2026-05-28
- **Modified:** 2026-05-30

## APIs

### Mockaroo API

REST API for generating realistic mock data records in JSON, CSV, TXT, custom-delimited, SQL, and XML formats. Supports saved schemas, inline field specifications, 150+ built-in field types, named datasets as lookup sources, and asynchronous background generation jobs for large requests.

- **Human URL:** [https://www.mockaroo.com/docs](https://www.mockaroo.com/docs)
- **Base URL:** `https://api.mockaroo.com`

#### Tags

- Test Data
- Mock Data
- Data Generation
- REST API

#### Properties

- [Documentation](https://www.mockaroo.com/docs)
- [API Reference](https://www.mockaroo.com/docs)
- [OpenAPI](openapi/mockaroo-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/mockaroo.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/mockaroo.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Authentication](https://www.mockaroo.com/docs)
- [Rate Limits](rate-limits/mockaroo-rate-limits.yml)
- [JSON Schema](json-schema/mockaroo-field-spec-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/mockaroo-field-type-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/mockaroo-download-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/mockaroo-dataset-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Structure](json-structure/mockaroo-field-spec-structure.json)
- [JSON Structure](json-structure/mockaroo-field-type-structure.json)
- [JSON Structure](json-structure/mockaroo-download-structure.json)
- [JSON Structure](json-structure/mockaroo-dataset-structure.json)
- [Example](examples/mockaroo-list-types-example.json)
- [Example](examples/mockaroo-generate-json-example.json)
- [Example](examples/mockaroo-generate-csv-example.json)
- [Example](examples/mockaroo-generate-txt-example.json)
- [Example](examples/mockaroo-generate-custom-example.json)
- [Example](examples/mockaroo-generate-sql-example.json)
- [Example](examples/mockaroo-generate-xml-example.json)
- [Example](examples/mockaroo-upload-dataset-example.json)
- [Example](examples/mockaroo-delete-dataset-example.json)
- [Example](examples/mockaroo-get-download-example.json)
- [Example](examples/mockaroo-cancel-download-example.json)
- [Example](examples/mockaroo-field-spec-example.json)
- [Example](examples/mockaroo-field-type-example.json)
- [Example](examples/mockaroo-download-example.json)
- [Example](examples/mockaroo-dataset-example.json)

## Common Properties

- [Website](https://www.mockaroo.com)
- [Documentation](https://www.mockaroo.com/docs)
- [Sign Up](https://www.mockaroo.com/users/sign_up)
- [Login](https://www.mockaroo.com/users/sign_in)
- [Pricing](https://www.mockaroo.com/pricing)
- [Plans](plans/mockaroo-plans-pricing.yml)
- [Rate Limits](rate-limits/mockaroo-rate-limits.yml)
- [Terms of Service](https://www.mockaroo.com/terms)
- [Privacy Policy](https://www.mockaroo.com/privacy)
- [Support](https://www.mockaroo.com/support)
- [GitHub Organization](https://github.com/mockaroo)
- [GitHub Repository](https://github.com/mockaroo/mockaroo-node)
- [GitHub Repository](https://github.com/mockaroo/mockaroo-enterprise)
- [SDK](https://github.com/mockaroo/mockaroo-node)
- [SDK](https://github.com/amogram/NMockaroo)
- [SDK](https://github.com/Ackara/Mockaroo.NET)
- [SDK](https://github.com/Scarvy/mockaroo-python)
- [SDK](https://github.com/lockedata/mockaRoo)
- [SDK](https://github.com/djhvscf/mockaroo.api)
- [SDK](https://github.com/djuang1/mockaroo-connector)
- [Spectral Rules](rules/mockaroo-rules.yml)
- [Vocabulary](vocabulary/mockaroo-vocabulary.yml)
- [JSON-LD](json-ld/mockaroo-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)
- [Features](undefined)
- [Use Cases](undefined)
- [Integrations](undefined)
- [Solutions](undefined)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
**Email:** support@mockaroo.com
**URL:** https://www.mockaroo.com
