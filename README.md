# Bifrost (bifrost)

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

Bifrost is a high-performance open-source AI gateway that unifies access to 20+ AI providers through a single OpenAI-compatible API. It supports 1,000+ models with adaptive load balancing, automatic failover, semantic caching, and enterprise observability features. Bifrost is open-source under Apache 2.0.

**URL:** [https://docs.getbifrost.ai](https://docs.getbifrost.ai)

## Tags:

 - AI Gateway, LLM, Load Balancing, Open Source, OpenAI Compatible, MCP

## Timestamps

- **Created:** 2026-03-16
- **Modified:** 2026-04-19

## APIs

### Bifrost HTTP Gateway API
The Bifrost HTTP Gateway API provides an OpenAI-compatible RESTful interface that routes requests to any of 20+ supported AI providers. Requests specify the provider and model using provider/model-name in the model field, enabling seamless provider switching without client code changes.

**Human URL:** [https://docs.getbifrost.ai/quickstart/gateway/setting-up](https://docs.getbifrost.ai/quickstart/gateway/setting-up)

#### Tags:

 - AI Gateway, LLM, OpenAI Compatible, REST

#### Properties

- [Documentation](https://docs.getbifrost.ai/quickstart/gateway/setting-up)
- [OpenAPI](openapi/bifrost-http-gateway-api.yaml)

### Bifrost Go SDK
The Bifrost Go SDK provides a native Go client for embedding the Bifrost AI gateway directly into Go applications using the github.com/maximhq/bifrost/core package.

**Human URL:** [https://docs.getbifrost.ai/quickstart/go-sdk/setting-up](https://docs.getbifrost.ai/quickstart/go-sdk/setting-up)

#### Tags:

 - AI Gateway, Go, LLM, SDK

### Bifrost MCP Gateway
The Bifrost Model Context Protocol (MCP) Gateway enables AI agents to discover and execute external tools through a standardized protocol, with OAuth 2.0 authentication and tool approval controls.

**Human URL:** [https://docs.getbifrost.ai/features/mcp](https://docs.getbifrost.ai/features/mcp)

#### Tags:

 - AI Agents, MCP, OAuth, Tool Execution

## Common Properties

- [Portal](https://www.getmaxim.ai/bifrost/enterprise)
- [Documentation](https://docs.getbifrost.ai)
- [GettingStarted](https://docs.getbifrost.ai/quickstart/gateway/setting-up)
- [GitHubRepository](https://github.com/maximhq/bifrost)
- [GitHubOrganization](https://github.com/maximhq)
- [ChangeLog](https://github.com/maximhq/bifrost/releases)
- [Community](https://discord.gg/exN5KAydbU)

## Features

| Name | Description |
|------|-------------|
| OpenAI-Compatible API | Single API interface compatible with OpenAI SDK for all 20+ providers. |
| Adaptive Load Balancing | Distribute requests across providers and models based on availability and performance. |
| Automatic Failover | Automatically retry failed requests on alternative providers without client changes. |
| Semantic Caching | Cache semantically similar prompts to reduce latency and API costs. |
| MCP Gateway | Model Context Protocol gateway for AI agent tool discovery and execution. |
| Go SDK | Native Go library for embedding Bifrost gateway directly into applications. |
| Enterprise Observability | Built-in metrics, tracing, and logging for production AI gateway deployments. |
| Provider Key Management | Centralized API key management for all connected AI providers. |

## Use Cases

| Name | Description |
|------|-------------|
| Multi-Provider AI Applications | Build applications that can seamlessly switch between OpenAI, Anthropic, and other providers. |
| Cost Optimization | Route requests to cheaper providers during peak costs or use caching to reduce API spend. |
| High Availability AI | Ensure AI features remain available by failing over across multiple provider accounts. |
| AI Agent Tooling | Enable AI agents to discover and execute tools through the MCP gateway protocol. |
| LLM Provider Evaluation | A/B test different models and providers without changing application code. |

## Integrations

| Name | Description |
|------|-------------|
| OpenAI | Route to OpenAI GPT-4o, GPT-4, and other OpenAI models. |
| Anthropic | Route to Claude 3.5 Sonnet, Claude 3 Opus, and other Anthropic models. |
| Cohere | Route to Cohere Command and other Cohere models. |
| AWS Bedrock | Route to models hosted on AWS Bedrock including Titan and Claude. |
| Azure OpenAI | Route to Azure-hosted OpenAI deployments. |
| Google Vertex AI | Route to Gemini and other models on Google Vertex AI. |

## Artifacts

### OpenAPI

- [Bifrost HTTP Gateway API](openapi/bifrost-http-gateway-api.yaml)

### JSON Schema

- [bifrost-chat-completion-request-schema.json](json-schema/bifrost-chat-completion-request-schema.json)
- [bifrost-chat-completion-response-schema.json](json-schema/bifrost-chat-completion-response-schema.json)
- [bifrost-chat-message-schema.json](json-schema/bifrost-chat-message-schema.json)
- [bifrost-chat-choice-schema.json](json-schema/bifrost-chat-choice-schema.json)
- [bifrost-usage-stats-schema.json](json-schema/bifrost-usage-stats-schema.json)
- [bifrost-health-response-schema.json](json-schema/bifrost-health-response-schema.json)
- [bifrost-provider-status-schema.json](json-schema/bifrost-provider-status-schema.json)

## Capabilities

### Shared Per-API Definitions

- [Bifrost HTTP Gateway API](capabilities/shared/bifrost.yaml) — 3 operations for chat completions and health

### Workflow Capabilities

| Workflow | APIs Combined | Tools | Persona |
|----------|--------------|-------|---------|
| [AI Chat Routing](capabilities/ai-chat-routing.yaml) | Bifrost | 3 | AI Engineer, Platform Engineer |

## Vocabulary

- [Bifrost Vocabulary](vocabulary/bifrost-vocabulary.yaml) — Unified taxonomy mapping 2 resources, 3 actions, 1 workflow, and 2 personas

## Rules

- [Bifrost Spectral Rules](rules/bifrost-spectral-rules.yml) — 24 rules across 9 categories enforcing Bifrost API conventions

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
