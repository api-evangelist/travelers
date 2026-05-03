# Travelers

Travelers is one of the largest property casualty insurance companies in the United States and a Fortune 500 company. Through their developer portal, Travelers provides APIs for business insurance claim reporting, commercial quoting, and policy management to enable agents, brokers, and partners to programmatically manage insurance workflows.

**URL:** [Visit APIs.json URL](https://raw.githubusercontent.com/api-evangelist/travelers/refs/heads/main/apis.yml)

## Scope

- **Type:** Index
- **Position:** Consuming
- **Access:** 3rd-Party

## Tags

Insurance, Property Casualty, Commercial Insurance, Claims, Fintech, Fortune 500

## Timestamps

- **Created:** 2026-05-03
- **Modified:** 2026-05-03

## APIs

### Travelers API
Business insurance APIs for claim reporting, commercial lines quoting, and policy management across property, casualty, workers compensation, and commercial auto lines.

**Human URL:** [https://developer.travelers.com/s/](https://developer.travelers.com/s/)

**Base URL:** `https://api.travelers.com/v1`

#### Tags

Insurance, Property Casualty, Commercial Insurance, Claims, Quoting, Fortune 500

#### Properties

- [Documentation](https://developer.travelers.com/s/apis)
- [OpenAPI](openapi/travelers-openapi.yml)
- [JSON Schema - Claim](json-schema/travelers-claim-schema.json)
- [JSON Structure](json-structure/travelers-claim-structure.json)
- [JSON-LD Context](json-ld/travelers-context.jsonld)
- [Spectral Rules](rules/travelers-rules.yml)
- [Naftiko Capabilities](capabilities/commercial-insurance-workflow.yaml)
- [Vocabulary](vocabulary/travelers-vocabulary.yml)
- [Sign Up](https://developer.travelers.com/s/)

## Policy Types

| Policy Type | Description |
|---|---|
| Property | Commercial property damage coverage |
| Casualty | Liability coverage for business operations |
| Workers Compensation | Employee injury and lost wage coverage |
| Commercial Auto | Business vehicle fleet coverage |
| General Liability | Bodily injury and property damage protection |
| Business Owner Policy | Bundled property and liability for small businesses |

## OpenAPI Specifications

| API | File |
|---|---|
| Travelers API | [openapi/travelers-openapi.yml](openapi/travelers-openapi.yml) |

## Capabilities

### Workflow Capabilities

| Workflow | Description |
|---|---|
| [Commercial Insurance Workflow](capabilities/commercial-insurance-workflow.yaml) | Full lifecycle: quoting, policy management, claim reporting, and status tracking |

### Shared Definitions

| API | File |
|---|---|
| [Travelers](capabilities/shared/travelers.yaml) | Core Travelers API consumed definitions |

## Examples

| Example | Description |
|---|---|
| [Report Claim](examples/travelers-report-claim-example.json) | Submit a commercial auto insurance claim |
| [Request Quote](examples/travelers-request-quote-example.json) | Get a Business Owner Policy quote |

## Rules

| Ruleset | Description |
|---|---|
| [travelers-rules.yml](rules/travelers-rules.yml) | Spectral ruleset for Travelers API conventions |

## JSON Schemas

| Schema | Description |
|---|---|
| [travelers-claim-schema.json](json-schema/travelers-claim-schema.json) | Insurance claim |

## JSON Structures

| Structure | Description |
|---|---|
| [travelers-claim-structure.json](json-structure/travelers-claim-structure.json) | Claim fields |

## JSON-LD

| Context | Description |
|---|---|
| [travelers-context.jsonld](json-ld/travelers-context.jsonld) | Linked data context for insurance data |

## Vocabulary

| Vocabulary | Description |
|---|---|
| [travelers-vocabulary.yml](vocabulary/travelers-vocabulary.yml) | Insurance domain vocabulary |

## Common Properties

- [Website](https://www.travelers.com/)
- [Developer Portal](https://developer.travelers.com/s/)
- [Documentation](https://developer.travelers.com/s/apis)
- [Sign Up](https://developer.travelers.com/s/)

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
