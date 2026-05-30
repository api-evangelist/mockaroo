# Mockaroo (mockaroo)

Realistic mock data generation as a service — JSON, CSV, TXT, custom-delimited,
SQL, and XML — backed by 150+ built-in field types, saved schemas, named
lookup datasets, hosted mock APIs, formulas, and a Docker-deployed Enterprise
tier.

- **Website:** <https://www.mockaroo.com>
- **Documentation:** <https://www.mockaroo.com/docs>
- **Base URL:** `https://api.mockaroo.com`
- **APIs.yml:** [apis.yml](apis.yml)

## Type

- **x-type:** company
- **x-tier:** 3 (bulk-registered from public-apis)
- **source:** [public-apis/public-apis](https://github.com/public-apis/public-apis) — category: Test Data

## API

### Mockaroo API
Generates realistic mock records on demand in JSON, CSV, TXT, custom-delimited,
SQL, and XML formats from either saved schemas or inline field specifications.

- **Documentation:** <https://www.mockaroo.com/docs>
- **OpenAPI:** [openapi/mockaroo-openapi.yml](openapi/mockaroo-openapi.yml)

#### Operations

| Tag | Method | Path | Operation |
|---|---|---|---|
| Types | GET | /api/types | List Field Types |
| Generate | POST | /api/generate.json | Generate Records As JSON |
| Generate | POST | /api/generate.csv | Generate Records As CSV |
| Generate | POST | /api/generate.txt | Generate Records As Tab-Separated Text |
| Generate | POST | /api/generate.custom | Generate Records With A Custom Delimiter |
| Generate | POST | /api/generate.sql | Generate Records As SQL Inserts |
| Generate | POST | /api/generate.xml | Generate Records As XML |
| Datasets | POST | /api/datasets/{name} | Upload Or Replace A Dataset |
| Datasets | DELETE | /api/datasets/{name} | Delete A Dataset |
| Downloads | GET | /api/downloads/{id} | Get Background Download Status |
| Downloads | DELETE | /api/downloads/{id} | Cancel Background Download |

#### Naftiko Capabilities

- [capabilities/mockaroo-generate.yaml](capabilities/mockaroo-generate.yaml)
- [capabilities/mockaroo-types.yaml](capabilities/mockaroo-types.yaml)
- [capabilities/mockaroo-datasets.yaml](capabilities/mockaroo-datasets.yaml)
- [capabilities/mockaroo-downloads.yaml](capabilities/mockaroo-downloads.yaml)

#### JSON Schema

- [json-schema/mockaroo-field-spec-schema.json](json-schema/mockaroo-field-spec-schema.json)
- [json-schema/mockaroo-field-type-schema.json](json-schema/mockaroo-field-type-schema.json)
- [json-schema/mockaroo-download-schema.json](json-schema/mockaroo-download-schema.json)
- [json-schema/mockaroo-dataset-schema.json](json-schema/mockaroo-dataset-schema.json)

#### JSON Structure

- [json-structure/mockaroo-field-spec-structure.json](json-structure/mockaroo-field-spec-structure.json)
- [json-structure/mockaroo-field-type-structure.json](json-structure/mockaroo-field-type-structure.json)
- [json-structure/mockaroo-download-structure.json](json-structure/mockaroo-download-structure.json)
- [json-structure/mockaroo-dataset-structure.json](json-structure/mockaroo-dataset-structure.json)

#### Examples

- [examples/mockaroo-list-types-example.json](examples/mockaroo-list-types-example.json)
- [examples/mockaroo-generate-json-example.json](examples/mockaroo-generate-json-example.json)
- [examples/mockaroo-generate-csv-example.json](examples/mockaroo-generate-csv-example.json)
- [examples/mockaroo-generate-txt-example.json](examples/mockaroo-generate-txt-example.json)
- [examples/mockaroo-generate-custom-example.json](examples/mockaroo-generate-custom-example.json)
- [examples/mockaroo-generate-sql-example.json](examples/mockaroo-generate-sql-example.json)
- [examples/mockaroo-generate-xml-example.json](examples/mockaroo-generate-xml-example.json)
- [examples/mockaroo-upload-dataset-example.json](examples/mockaroo-upload-dataset-example.json)
- [examples/mockaroo-delete-dataset-example.json](examples/mockaroo-delete-dataset-example.json)
- [examples/mockaroo-get-download-example.json](examples/mockaroo-get-download-example.json)
- [examples/mockaroo-cancel-download-example.json](examples/mockaroo-cancel-download-example.json)
- [examples/mockaroo-field-spec-example.json](examples/mockaroo-field-spec-example.json)
- [examples/mockaroo-field-type-example.json](examples/mockaroo-field-type-example.json)
- [examples/mockaroo-download-example.json](examples/mockaroo-download-example.json)
- [examples/mockaroo-dataset-example.json](examples/mockaroo-dataset-example.json)

## Common Properties

- **Plans:** [plans/mockaroo-plans-pricing.yml](plans/mockaroo-plans-pricing.yml)
- **Rate Limits:** [rate-limits/mockaroo-rate-limits.yml](rate-limits/mockaroo-rate-limits.yml)
- **FinOps:** [finops/mockaroo-finops.yml](finops/mockaroo-finops.yml)
- **Spectral Rules:** [rules/mockaroo-rules.yml](rules/mockaroo-rules.yml)
- **Vocabulary:** [vocabulary/mockaroo-vocabulary.yml](vocabulary/mockaroo-vocabulary.yml)
- **JSON-LD Context:** [json-ld/mockaroo-context.jsonld](json-ld/mockaroo-context.jsonld)
- **GitHub:** <https://github.com/mockaroo>

### SDKs

| Language | Package | Source |
|---|---|---|
| Node.js (official) | `mockaroo` | <https://github.com/mockaroo/mockaroo-node> |
| C# | NMockaroo | <https://github.com/amogram/NMockaroo> |
| C# | Mockaroo.NET | <https://github.com/Ackara/Mockaroo.NET> |
| Python | mockaroo-python | <https://github.com/Scarvy/mockaroo-python> |
| R | mockaRoo | <https://github.com/lockedata/mockaRoo> |
| Java | mockaroo.api | <https://github.com/djhvscf/mockaroo.api> |
| MuleSoft | mockaroo-connector | <https://github.com/djuang1/mockaroo-connector> |

### MCP

- `miqui/mockaroo-mcp` — community MCP server exposing Mockaroo's generate surface to LLM agents (<https://github.com/miqui/mockaroo-mcp>).

## Plans And Pricing

| Tier | Annual | Records / File | Records / Day | Hosting |
|---|---|---|---|---|
| Free | $0 | 1,000 | 200 requests/day | mockaroo.com |
| Silver | $60 | 100,000 | 1,000,000 | mockaroo.com |
| Gold | $500 | 10,000,000 | 10,000,000 | mockaroo.com |
| Enterprise | $7,500 | Unlimited | Unlimited | Self-hosted Docker |

## Tags

Test Data, Mock Data, API Mocking, Data Generation, Developer Tools, QA Testing,
Realistic Data, Schemas, Datasets, Public APIs

## Timestamps

- **Created:** 2026-05-28
- **Modified:** 2026-05-30

## Maintainers

- **Kin Lane** — kin@apievangelist.com
- **Mockaroo, LLC** — support@mockaroo.com
