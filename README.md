# Salesforce Flow

The Salesforce Flow API enables developers to interact with and manage Salesforce Flow automation processes programmatically. This includes creating, updating, querying, and executing flows within Salesforce using the REST API, Tooling API, and Invocable Actions framework.

**URL:** https://developer.salesforce.com/docs/atlas.en-us.api_rest.meta/api_rest/resources_flow.htm

**Tags:** Automation, Business Process, CRM, Flow, Process Builder, Salesforce, Workflow

## APIs

### Salesforce Flow REST API

REST API for managing and executing Salesforce Flows programmatically. Enables creating, updating, querying, and executing flow automation processes, flow interviews, and invocable actions within Salesforce.

- **Base URL:** https://yourInstance.salesforce.com/services/data/v59.0
- **Documentation:** https://developer.salesforce.com/docs/atlas.en-us.api_rest.meta/api_rest/resources_flow.htm
- **OpenAPI:** [salesforce-flow-rest-api-openapi.yml](openapi/salesforce-flow-rest-api-openapi.yml)
- **Authentication:** https://developer.salesforce.com/docs/atlas.en-us.api_rest.meta/api_rest/intro_oauth_and_connected_apps.htm

### Salesforce Tooling API (Flow)

Tooling API endpoints for managing Flow definitions and metadata. Supports deployment, retrieval, and management of Flow versions.

- **Base URL:** https://yourInstance.salesforce.com/services/data/v59.0/tooling
- **Documentation:** https://developer.salesforce.com/docs/atlas.en-us.api_tooling.meta/api_tooling/tooling_api_objects_flow.htm

### Salesforce Flow Interviews API

API for executing and managing Flow interviews (instances). Provides endpoints to start, resume, pause, and monitor flow execution state.

- **Base URL:** https://yourInstance.salesforce.com/services/data/v59.0/actions/custom/flow
- **Documentation:** https://developer.salesforce.com/docs/atlas.en-us.api_rest.meta/api_rest/resources_actions_invocable_flow.htm

## Common Resources

| Type | URL |
|------|-----|
| Portal | https://developer.salesforce.com/ |
| Getting Started | https://trailhead.salesforce.com/content/learn/modules/flow-builder |
| Authentication | https://developer.salesforce.com/docs/atlas.en-us.api_rest.meta/api_rest/intro_oauth_and_connected_apps.htm |
| Rate Limits | https://developer.salesforce.com/docs/atlas.en-us.salesforce_app_limits_cheatsheet.meta/salesforce_app_limits_cheatsheet/salesforce_app_limits_platform_api.htm |
| Status | https://status.salesforce.com/ |
| Terms of Service | https://www.salesforce.com/company/legal/agreements/ |
| Privacy Policy | https://www.salesforce.com/company/privacy/ |
| Trailhead Learning | https://trailhead.salesforce.com/content/learn/modules/flow-builder |
| GitHub Organization | https://github.com/salesforce |

## Artifacts

### OpenAPI Specifications

| Spec | Description |
|------|-------------|
| [salesforce-flow-rest-api-openapi.yml](openapi/salesforce-flow-rest-api-openapi.yml) | Salesforce Flow REST API — flow definitions, interviews, and invocable actions |

### Spectral Rules

| Ruleset | Description |
|---------|-------------|
| [salesforce-flow-rules.yml](rules/salesforce-flow-rules.yml) | Spectral rules enforcing Salesforce Flow API conventions |

### Capabilities

| Capability | Description |
|------------|-------------|
| [flow-automation.yaml](capabilities/flow-automation.yaml) | Unified workflow capability for Flow automation management (10 tools) |

**Shared Definitions:**

| Shared | Description |
|--------|-------------|
| [flow-rest-api.yaml](capabilities/shared/flow-rest-api.yaml) | Salesforce Flow REST API consumed definition |

### JSON Schemas

| Schema | Description |
|--------|-------------|
| [salesforce-flow-flow-definition-schema.json](json-schema/salesforce-flow-flow-definition-schema.json) | Schema for Salesforce Flow definition objects |
| [salesforce-flow-flow-interview-schema.json](json-schema/salesforce-flow-flow-interview-schema.json) | Schema for Salesforce Flow Interview (running instance) objects |

### JSON Structures

| Structure | Description |
|-----------|-------------|
| [salesforce-flow-flow-definition-structure.json](json-structure/salesforce-flow-flow-definition-structure.json) | Structural documentation for the Flow definition resource |

### JSON-LD Context

| Context | Description |
|---------|-------------|
| [salesforce-flow-context.jsonld](json-ld/salesforce-flow-context.jsonld) | JSON-LD context mapping Salesforce Flow vocabulary to schema.org |

### Examples

| Example | Description |
|---------|-------------|
| [salesforce-flow-list-flows-example.json](examples/salesforce-flow-list-flows-example.json) | Example request/response for listing Flow definitions |
| [salesforce-flow-invoke-flow-example.json](examples/salesforce-flow-invoke-flow-example.json) | Example request/response for invoking a Flow action |

### Vocabulary

| Vocabulary | Description |
|------------|-------------|
| [salesforce-flow-vocabulary.yml](vocabulary/salesforce-flow-vocabulary.yml) | Domain vocabulary and taxonomy for Salesforce Flow automation |

## Maintainers

- Kin Lane (kin@apievangelist.com)
