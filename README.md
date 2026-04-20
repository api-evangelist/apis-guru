# APIs.guru (apis-guru)
APIs.guru is an open source, community-driven directory of public REST API definitions in OpenAPI 2.0/3.x format, described as the Wikipedia for Web APIs. The project searches for public API definitions, converts various formats to OpenAPI 3.0, corrects errors in approximately 80% of definitions, and enriches entries with logos, categories, and metadata. It catalogs over 2,500 API descriptions with 100,000+ endpoints, updating definitions weekly from original sources. The platform is licensed under CC0-1.0 for contributed definitions and welcomes community contributions through GitHub.

**URL:** [Visit APIs.json URL](https://raw.githubusercontent.com/api-evangelist/apis-guru/refs/heads/main/apis.yml)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=company-api-evangelist&utm_content=repo)

## Tags:

 - API Catalog, API Directory, API Discovery, Community, GraphQL, Open Source, OpenAPI

## Timestamps

- **Created:** 2026-03-25
- **Modified:** 2026-04-19

## APIs

### APIs.guru REST API
The APIs.guru REST API provides programmatic access to the directory of public API definitions, allowing developers to search, browse, and retrieve OpenAPI specifications from the catalog. The API is public and requires no authentication. It provides endpoints to list all APIs, fetch metrics, retrieve provider lists, and access specific API version details including direct links to OpenAPI specs in JSON and YAML formats.

**Human URL:** [https://apis.guru/api-doc](https://apis.guru/api-doc)

#### Tags:

 - API Catalog, API Directory, API Discovery, OpenAPI

#### Properties

- [Documentation](https://apis.guru/api-doc)
- [OpenAPI](https://raw.githubusercontent.com/api-evangelist/apis-guru/refs/heads/main/openapi/apis-guru-openapi.yaml)
- [Postman Collection](https://www.postman.com/api-evangelist/apis-guru/documentation/wtbfnfn/apis-guru)
- [JSONSchema - API Schema](https://raw.githubusercontent.com/api-evangelist/apis-guru/refs/heads/main/json-schema/apis-guru-api-schema.json)
- [JSONSchema - API Version Schema](https://raw.githubusercontent.com/api-evangelist/apis-guru/refs/heads/main/json-schema/apis-guru-api-version-schema.json)
- [JSONSchema - Metrics Schema](https://raw.githubusercontent.com/api-evangelist/apis-guru/refs/heads/main/json-schema/apis-guru-metrics-schema.json)

## Common Properties

- [Website](https://apis.guru)
- [About](https://apis.guru/about)
- [Documentation](https://apis.guru/api-doc)
- [Blog](https://apis.guru/blog)
- [GitHub Organization](https://github.com/APIs-guru)
- [GitHub Repository](https://github.com/APIs-guru/openapi-directory)
- [GitHub Repository - AsyncAPI Directory](https://github.com/APIs-guru/asyncapi-directory)
- [GitHub Repository - GraphQL Voyager](https://github.com/APIs-guru/graphql-voyager)
- [GitHub Repository - Awesome OpenAPI 3](https://github.com/APIs-guru/awesome-openapi3)
- [GitHub Repository - AWS to OpenAPI Converter](https://github.com/APIs-guru/aws2openapi)
- [GitHub Repository - Google Discovery to OpenAPI Converter](https://github.com/APIs-guru/google-discovery-to-swagger)
- [GitHub Repository - GraphQL Faker](https://github.com/APIs-guru/graphql-faker)
- [GitHub Repository - Public GraphQL APIs Directory](https://github.com/APIs-guru/graphql-apis)
- [X](https://x.com/APIs_guru)
- [Support](https://github.com/APIs-guru/openapi-directory/issues)

## Features

| Name | Description |
|------|-------------|
| OpenAPI Directory | Comprehensive directory of over 2,500 public API definitions in OpenAPI 2.0 and 3.x format, updated weekly from original sources. |
| Format Conversion | Converts various API description formats (RAML, Google Discovery, AWS, etc.) to OpenAPI 3.0 standard for consistency and compatibility. |
| Quality Control | Corrects errors in approximately 80% of API definitions and validates all specifications before inclusion in the directory. |
| AsyncAPI Directory | Companion directory of asynchronous API specifications in AsyncAPI format for event-driven and message-based APIs. |
| GraphQL Voyager | Visual tool that represents any GraphQL API as an interactive graph, making schema exploration intuitive and visual. |
| REST API Access | Public REST API at api.apis.guru/v2 for programmatic access to the directory, metrics, provider lists, and individual API specs. |
| RSS Feeds | RSS feeds for both newly added and recently updated API definitions, allowing developers to stay current with directory changes. |
| Metadata Enrichment | Enriches API definitions with logos, categories, provider names, and other metadata to improve discoverability and browsability. |

## Use Cases

| Name | Description |
|------|-------------|
| API Discovery | Developers can search and browse the directory to discover public APIs across thousands of providers by category, provider, or keyword. |
| SDK Generation | OpenAPI specs from the directory can be used with tools like Microsoft Kiota and Speakeasy to generate API client SDKs. |
| API Documentation | ReDoc and other documentation tools use the directory specs to generate beautiful, interactive API documentation automatically. |
| API Testing | HTTP Toolkit and other testing tools leverage the directory for debugging and mocking API requests against standardized specs. |
| Schema Exploration | GraphQL Voyager allows teams to visually explore GraphQL schema relationships to understand API structure quickly. |
| API Catalog Building | Organizations can use the directory as a foundation for building their own internal API catalogs and governance programs. |

## Integrations

| Name | Description |
|------|-------------|
| HTTP Toolkit | HTTP debugging and testing platform that integrates with API definitions from the APIs.guru directory for request interception. |
| Microsoft Kiota | Microsoft's API client generator that uses OpenAPI specs from APIs.guru to generate typed API clients in multiple languages. |
| Speakeasy | SDK generation platform that pulls OpenAPI definitions from the directory to generate production-ready SDKs for API providers. |
| ReDoc | API documentation generation tool that uses OpenAPI specs from APIs.guru to create beautiful, customizable documentation sites. |
| Open Collective | Community funding platform where APIs.guru receives financial support from sponsors who benefit from the open directory. |

## Artifacts

Machine-readable API specifications organized by format.

### OpenAPI

- [APIs.guru REST API](openapi/apis-guru-openapi.yaml)

### JSON Schema

- [API Schema](json-schema/apis-guru-api-schema.json)
- [APIs Schema](json-schema/apis-guru-ap-is-schema.json)
- [API Version Schema](json-schema/apis-guru-api-version-schema.json)
- [Metrics Schema](json-schema/apis-guru-metrics-schema.json)

### JSON Structure

- [API Structure](json-structure/apis-guru-api-structure.json)
- [APIs Structure](json-structure/apis-guru-ap-is-structure.json)
- [API Version Structure](json-structure/apis-guru-api-version-structure.json)
- [Metrics Structure](json-structure/apis-guru-metrics-structure.json)

### JSON-LD

- [APIs.guru Context](json-ld/apis-guru-context.jsonld)

### Examples

- [API Example](examples/apis-guru-api-example.json)
- [APIs Example](examples/apis-guru-ap-is-example.json)
- [API Version Example](examples/apis-guru-api-version-example.json)
- [Metrics Example](examples/apis-guru-metrics-example.json)

## Capabilities

Naftiko capabilities organized as shared per-API definitions composed into customer-facing workflows.

### Shared Per-API Definitions

- [APIs.guru REST API](capabilities/shared/apis-guru-api.yaml) — 7 operations for API discovery and catalog access

### Workflow Capabilities

| Workflow | APIs Combined | Tools | Persona |
|----------|--------------|-------|---------|
| [API Discovery](capabilities/api-discovery.yaml) | APIs.guru REST API | 7 | API Developer, Platform Engineer |

## Vocabulary

- [APIs.guru Vocabulary](vocabulary/apis-guru-vocabulary.yaml) — Unified taxonomy mapping 5 resources, 2 actions, 1 workflow, and 2 personas across operational (OpenAPI) and capability (Naftiko) dimensions

## Rules

- [APIs.guru Spectral Rules](rules/apis-guru-spectral-rules.yml) — 30 rules across 10 categories enforcing APIs.guru API conventions

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
