# Bifrost (bifrost)
Bifrost is a high-performance open-source AI gateway that unifies access to 20+ AI providers through a single OpenAI-compatible API. It supports 1,000+ models with adaptive load balancing, automatic failover, semantic caching, and enterprise observability features.

**URL:** [Visit APIs.json URL](https://raw.githubusercontent.com/api-evangelist/bifrost/refs/heads/main/apis.yml)

## Scope

- **Type:** Index 
- **Position:** Consuming 
- **Access:** 3rd-Party 

## Tags:

 - AI Gateway, LLM, Open Source, Load Balancing

## Timestamps

- **Created:** 2026-03-16 
- **Modified:** 2026-03-18 

## APIs

### Bifrost HTTP Gateway API
The Bifrost HTTP Gateway API provides an OpenAI-compatible RESTful interface that routes requests to any of 20+ supported AI providers. Requests specify the provider and model in the model field using the format provider/model-name, enabling unified access to chat completions and other AI endpoints without changing client code.

**Human URL:** [https://docs.getbifrost.ai/quickstart/gateway/setting-up](https://docs.getbifrost.ai/quickstart/gateway/setting-up)


#### Tags:

 - AI Gateway, REST, OpenAI Compatible, LLM

#### Properties

- [Documentation](https://docs.getbifrost.ai/quickstart/gateway/setting-up)
- [Getting Started](https://docs.getbifrost.ai/quickstart/gateway/setting-up)
- [Reference](https://docs.getbifrost.ai/features/unified-interface)
- [Authentication](https://docs.getbifrost.ai/quickstart/gateway/provider-configuration)
- [GitHubRepository](https://github.com/maximhq/bifrost)

### Bifrost Go SDK
The Bifrost Go SDK provides a native Go client for embedding the Bifrost AI gateway directly into Go applications. It implements the same unified provider interface as the HTTP gateway, allowing applications to switch between AI providers without code changes using the github.com/maximhq/bifrost/core package.

**Human URL:** [https://docs.getbifrost.ai/quickstart/go-sdk/setting-up](https://docs.getbifrost.ai/quickstart/go-sdk/setting-up)


#### Tags:

 - Go, SDK, LLM, AI Gateway

#### Properties

- [Documentation](https://docs.getbifrost.ai/quickstart/go-sdk/setting-up)
- [Getting Started](https://docs.getbifrost.ai/quickstart/go-sdk/setting-up)
- [GitHubRepository](https://github.com/maximhq/bifrost)

### Bifrost MCP Gateway
The Bifrost Model Context Protocol (MCP) Gateway enables AI agents to discover and execute external tools through a standardized protocol. It supports OAuth 2.0 authentication, tool approval controls, agent mode for autonomous operations, and code mode for AI-orchestrated workflows.

**Human URL:** [https://docs.getbifrost.ai/features/mcp](https://docs.getbifrost.ai/features/mcp)


#### Tags:

 - MCP, AI Agents, Tool Execution, OAuth

#### Properties

- [Documentation](https://docs.getbifrost.ai/features/mcp)
- [GitHubRepository](https://github.com/maximhq/bifrost)

## Common Properties

- [Website](https://www.getmaxim.ai/bifrost/enterprise)
- [Documentation](https://docs.getbifrost.ai)
- [Getting Started](https://docs.getbifrost.ai/quickstart/gateway/setting-up)
- [GitHubRepository](https://github.com/maximhq/bifrost)
- [GitHub Organization](https://github.com/maximhq)
- [Change Log](https://github.com/maximhq/bifrost/releases)
- [Community](https://discord.gg/exN5KAydbU)

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
