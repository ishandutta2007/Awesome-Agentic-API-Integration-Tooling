# Awesome-Agentic-API-Integration-Tooling

## Top Agentic API Integration Tooling Ecosystem



**Curated List of SaaS Products & Open-Source GitHub Projects**  

*Focused on Tool Calling, Auth Gateways & Agent Function Execution*  

**Last updated: March 2026**



This repository tracks notable **SaaS platforms** and **open-source projects** for **Agentic API Integration Tooling**. These tools enable AI agents to securely discover, authenticate, and execute software functions across SaaS providers—bridging the gap between LLM reasoning and real-world API actions.



**Examples** include Composio, Pipedream Connect, Toolhouse, LangChain Hub, Smithery, Trigger.dev, Zapier MCP, Superface, Apideck, and CloudQuery (the category leaders).



**Open-source emphasis**: This section is heavily expanded with every major active project for self-hosting, auth gateways, and open tool execution—ideal for AI engineers, platform teams, and developers seeking transparent, vendor-independent agent integration.



Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.



## Table of Contents

- [SaaS/Hosted Platforms](#saas-hosted-platforms)

- [Open-Source GitHub Projects](#open-source-github-projects)

- [How to Contribute](#how-to-contribute)

- [Disclaimer](#disclaimer)



## SaaS/Hosted Platforms



- **[Composio](https://composio.dev/)**  

  Tool integration platform connecting AI agents to 100+ tools with managed authentication, execution, and observability. Features tool discovery, credential management, and LangChain/LlamaIndex integration.



- **[Pipedream Connect](https://pipedream.com/connect)**  

  Embedded integration platform for AI agents and SaaS products. Enables end-users to connect 2,000+ APIs with managed OAuth, and agents to execute actions programmatically.



- **[Toolhouse](https://toolhouse.ai/)**  

  Cloud platform for deploying and managing agent tools. Features tool marketplace, execution sandbox, and SDK for popular agent frameworks.



- **[LangChain Hub](https://smith.langchain.com/hub)**  

  Repository for sharing and discovering LangChain prompts, chains, and agents. Includes tool definitions and integration examples.



- **[Smithery](https://smithery.ai/)**  

  Registry and installer for Model Context Protocol (MCP) servers. Features discovery, quality scoring, and CLI installation across 23 clients including Claude, Cursor, and Windsurf .



- **[Trigger.dev](https://trigger.dev/)**  

  Background jobs and workflow platform for developers. Features long-running tasks, webhooks, and integrations for agent-triggered automation.



- **[Zapier MCP](https://zapier.com/mcp)**  

  Exposes Zapier's 6,000+ app integrations as MCP tools for AI agents. Enables agents to trigger Zaps and execute actions via natural language.



- **[Superface](https://superface.ai/)**  

  Integration platform for AI agents with pre-built connectors and API orchestration.



- **[Apideck](https://www.apideck.com/)**  

  Unified API platform for SaaS integrations. Provides normalized APIs for accounting, CRM, HRIS, and more.



- **[CloudQuery](https://www.cloudquery.io/)**  

  Data integration platform for cloud and security data. Extracts from APIs to warehouses with declarative configurations.



## Open-Source GitHub Projects



- **[OpenConnector](https://github.com/oomol-lab/open-connector)**  

  Open-source auth gateway connecting 1,500+ SaaS providers to AI agents through SDK, CLI, MCP, HTTP, and OpenAPI (Apache-2.0). Positioned as a Pipedream/Composio alternative. Features **credential and OAuth boundary** keeping provider secrets behind the runtime, **1,000+ providers with 10,000+ predefined Actions**, token/scope/allow-block policy, run logs, and Web Console for provider browsing, Action debugging, and usage review . Self-hosted via Docker Compose or Kubernetes Helm chart. Uses SQLite or PostgreSQL for state .



- **[Windmill](https://github.com/windmill-labs/windmill)**  

  Open-source developer platform to turn scripts into internal apps, workflows, and integrations (AGPL-3.0). Positioned as an open-source alternative to Airplane and Pipedream. Features **scripts in Python, TypeScript, Go, Bash, and SQL** automatically converted to apps and no-code modules. Usable as self-hosted AWS Lambda. Flow builder for multi-step workflows, webhooks, and schedules .



- **[Activepieces](https://github.com/activepieces/activepieces)**  

  Open-source, AI-first automation platform (MIT) with 23k+ GitHub stars. Features 280+ integrations ("pieces") in TypeScript, drag-and-drop builder, AI agents, human-in-the-loop steps, and **every piece automatically exposed as an MCP server**—roughly 400 tools for Claude Desktop, Cursor, and Windsurf . Self-hosted on Railway for unlimited tasks at flat compute cost.



- **[gen-mcp](https://github.com/genmcp/gen-mcp)**  

  Open-source tool to convert OpenAPI specs to MCP servers (Go). Features **`genmcp convert`** transforming existing APIs into MCP tools, TLS encryption and OAuth/OIDC auth built-in, background processing with detached server mode, and fine-grained endpoint configuration . Builds multi-architecture container images from MCP file configurations.



- **[openapi-mcp](https://github.com/ubermorgenland/openapi-mcp)**  

  Open-source server exposing OpenAPI specs as MCP tools (Go). Features multi-mount endpoints for multiple specs, dynamic endpoint management via `spec-manager` CLI, database-backed spec storage, and HTTP API wrapper for remote management .



- **[Automatisch MCP Server](https://github.com/milisp/automatisch-mcp-server)**  

  Open-source MCP server providing AI assistants access to Automatisch workflow automation (MIT). Features workflow management (create, read, update, delete, test), connection management, execution monitoring, and app discovery . Integrates with Claude Desktop via npx.



- **[django-apcore](https://pypi.org/project/django-apcore/)**  

  Open-source framework turning Django APIs into agent-callable functions with **built-in ACL**. Features scan/list/describe endpoints programmatically, MCP serving with `app.serve(transport="streamable-http")`, OpenAI tools export, and auto-generated CLI from Django routes . **ACL YAML** declares rules mapping Django Groups to apcore roles—no permission code required.



- **[cat-agent](https://pypi.org/project/cat-agent/)**  

  Python framework for LLM-powered agents (open-source). Features function calling, RAG with vector/keyword/hybrid search, code interpreter sandbox (Docker or WASM), MCP support, multiple LLM backends (OpenAI, LlamaCpp, MLX-LM), and observability hooks .



- **[Observal](https://github.com/BlazeUp-AI/Observal)**  

  Self-hosted AI agent registry with built-in observability (Apache-2.0). Features **`observal scan`** auto-detecting and instrumenting MCP servers, agent pulling across IDEs (Claude Code, Kiro, Cursor, Gemini CLI), telemetry pipeline with ClickHouse and Grafana, and eval engine scoring agent sessions .



- **[GenXAI Framework](https://pypi.org/project/genxai-framework/)**  

  Open-source framework for building LLM agents with pluggable tools, multi-agent workflows, and governance (open-source). Features CLI for tool management (`genxai tool search`, `genxai tool create`), RBAC, policy engine, audit logging, guardrails, and secrets encryption .



- **[squad](https://pkg.go.dev/github.com/cowdogmoo/squad)**  

  Model-agnostic agent workflow CLI (Go, open-source). Features MCP server integration, multi-agent pipelines with cost budgets, OpenTelemetry tracing, and skills catalog via `squad skill add` .



### Additional Strong Open-Source Options



- **[MCP Hub](https://mcp-hub.com/)** — Open-source self-hosted registry for 4,400+ MCP servers with community ratings .

- **[Pulse MCP](https://pulsemcp.com/)** — Directory for MCP server discovery and comparisons .

- **[awesome-mcp-servers](https://github.com/bgizdov/awesome-mcp-servers)** — Auto-generated curated list of MCP servers .

- **[awesome-mcp](https://github.com/abordage/awesome-mcp)** — Curated list of MCP servers, clients, and frameworks updated daily .

- **[Zeline](https://pypi.org/project/zeline/)** — Cross-platform agent gateway with Telegram, WhatsApp, and webhook support (open-source) .

- Community **n8n** workflows for agent tool orchestration and API chaining.



**Frameworks for building custom systems**: Combine **OpenConnector** as the auth gateway with **Activepieces** for workflow automation and MCP tool exposure, **Windmill** for script-to-app conversion, **gen-mcp** or **openapi-mcp** for converting existing APIs to MCP tools, and **Observal** for agent registry and observability—creating a fully self-hosted, enterprise-grade agentic API integration platform.



## How to Contribute



1. Fork the repo.

2. Add/edit entries in `README.md` (follow existing format).

3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.

4. Submit PR with a short explanation.



Star the repo if you find it useful!



## Disclaimer



- This is a **community-curated** list — not exhaustive and not an endorsement.

- Agent integration platforms handling credentials and executing functions must follow security best practices (least privilege, credential rotation, audit logging) and comply with applicable regulations.

- Self-hosted open-source solutions require proper security hardening, OAuth app configuration, and ongoing maintenance. **Provider secrets must never reach the agent process**—auth gateways like OpenConnector keep credentials behind the runtime boundary while agents receive only metadata and execution results . Tool execution without proper sandboxing can expose host systems to arbitrary code execution.



---



**Made for AI engineers, platform teams, and developers building transparent agent integration solutions.**  

Let's make Agentic API Integration Tooling more open, data-driven, and secure.
