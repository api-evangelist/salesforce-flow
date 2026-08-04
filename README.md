# Salesforce Flow (salesforce-flow)

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

The Salesforce Flow API enables developers to interact with and manage Salesforce Flow automation processes programmatically. This includes creating, updating, querying, and executing flows within Salesforce using the REST API, Tooling API, and Invocable Actions framework.

**APIs.json:** [https://developer.salesforce.com/docs/atlas.en-us.api_rest.meta/api_rest/resources_flow.htm](https://developer.salesforce.com/docs/atlas.en-us.api_rest.meta/api_rest/resources_flow.htm)

## Tags

- Automation
- Business Process
- CRM
- Flow
- Process Builder
- Salesforce
- Workflow

## Timestamps

- **Created:** Sun Jan 14 2024 19:00:00 GMT-0500 (Eastern Standard Time)
- **Modified:** 2026-05-19

## APIs

### Salesforce Flow REST API

REST API for managing and executing Salesforce Flows programmatically. Enables creating, updating, querying, and executing flow automation processes, flow interviews, and invocable actions within Salesforce.

- **Human URL:** [https://developer.salesforce.com/docs/atlas.en-us.api_rest.meta/api_rest/resources_flow.htm](https://developer.salesforce.com/docs/atlas.en-us.api_rest.meta/api_rest/resources_flow.htm)
- **Base URL:** `https://yourInstance.salesforce.com/services/data/v59.0`

#### Tags

- Automation
- Flow
- REST

#### Properties

- [Documentation](https://developer.salesforce.com/docs/atlas.en-us.api_rest.meta/api_rest/resources_flow.htm)
- [OpenAPI](openapi/salesforce-flow-rest-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/salesforce-flow-rest-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/salesforce-flow-rest-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Authentication](https://developer.salesforce.com/docs/atlas.en-us.api_rest.meta/api_rest/intro_oauth_and_connected_apps.htm)

### Salesforce Tooling API (Flow)

Tooling API endpoints for managing Flow definitions and metadata. Supports deployment, retrieval, and management of Flow versions.

- **Human URL:** [https://developer.salesforce.com/docs/atlas.en-us.api_tooling.meta/api_tooling/](https://developer.salesforce.com/docs/atlas.en-us.api_tooling.meta/api_tooling/)
- **Base URL:** `https://yourInstance.salesforce.com/services/data/v59.0/tooling`

#### Tags

- Flow Definition
- Metadata
- Tooling

#### Properties

- [Documentation](https://developer.salesforce.com/docs/atlas.en-us.api_tooling.meta/api_tooling/tooling_api_objects_flow.htm)
- [Postman Collection](collections/salesforce-flow-rest-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/salesforce-flow-rest-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Salesforce Flow Interviews API

API for executing and managing Flow interviews (instances). Provides endpoints to start, resume, pause, and monitor flow execution state.

- **Human URL:** [https://developer.salesforce.com/docs/atlas.en-us.api_rest.meta/api_rest/resources_actions_invocable_flow.htm](https://developer.salesforce.com/docs/atlas.en-us.api_rest.meta/api_rest/resources_actions_invocable_flow.htm)
- **Base URL:** `https://yourInstance.salesforce.com/services/data/v59.0/actions/custom/flow`

#### Tags

- Execution
- Flow Interview
- Runtime

#### Properties

- [Documentation](https://developer.salesforce.com/docs/atlas.en-us.api_rest.meta/api_rest/resources_actions_invocable_flow.htm)
- [Postman Collection](collections/salesforce-flow-rest-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/salesforce-flow-rest-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [Portal](https://developer.salesforce.com/)
- [Getting Started](https://trailhead.salesforce.com/content/learn/modules/flow-builder)
- [Authentication](https://developer.salesforce.com/docs/atlas.en-us.api_rest.meta/api_rest/intro_oauth_and_connected_apps.htm)
- [Rate Limits](https://developer.salesforce.com/docs/atlas.en-us.salesforce_app_limits_cheatsheet.meta/salesforce_app_limits_cheatsheet/salesforce_app_limits_platform_api.htm)
- [Status Page](https://status.salesforce.com/)
- [Terms of Service](https://www.salesforce.com/company/legal/agreements/)
- [Privacy Policy](https://www.salesforce.com/company/privacy/)
- [Documentation](https://developer.salesforce.com/docs/atlas.en-us.flow.meta/flow/)
- [Trailhead  Learning](https://trailhead.salesforce.com/content/learn/modules/flow-builder)
- [GitHub Organization](https://github.com/salesforce)
- [Spectral  Rules](rules/salesforce-flow-rules.yml)
- [Capabilities](capabilities/flow-automation.yaml)
- [J S O N  Schema](json-schema/salesforce-flow-flow-definition-schema.json)
- [J S O N  Schema](json-schema/salesforce-flow-flow-interview-schema.json)
- [J S O N- L D  Context](json-ld/salesforce-flow-context.jsonld)
- [Vocabulary](vocabulary/salesforce-flow-vocabulary.yml)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
