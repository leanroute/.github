## Leanroute

**The agent-native AI gateway.** One OpenAI-compatible API for 100+ models across 14 providers, built for AI agents and apps.

- **Cost per agent run:** every model and tool call grouped by run, with cost, models and tools called
- **MCP tools on any model:** the gateway runs the tool loop, only on MCP servers you approve
- **Hard spend caps and rate limits** per organization and per API key
- **Guardrails:** redact PII and block secrets before prompts reach a provider
- **Your keys or ours:** bring your own provider keys for a flat monthly fee, or pay as you go
- **Hosted in Singapore**, with first-class APAC and India providers

[Website](https://leanroute.dev) · [Docs](https://leanroute.dev/docs) · [Models and prices](https://leanroute.dev/models) · [Blog](https://leanroute.dev/blog)

### Open source

Our SDKs, framework integrations and MCP server live in **[leanroute/integrations](https://github.com/leanroute/integrations)**:

| Package | Install |
| --- | --- |
| LangChain / LangGraph (Python) | `pip install langchain-leanroute` |
| LangChain (TypeScript) | `npm install @leanroute/langchain` |
| Vercel AI SDK | `npm install @leanroute/vercel-ai-sdk` |
| MCP server for Claude Code, Cursor, Cline | `npx @leanroute/mcp-server` |
| Starter app (Next.js or Node) | `npx create-leanroute-app` |
| n8n community node | [leanroute/n8n-nodes-leanroute](https://github.com/leanroute/n8n-nodes-leanroute) |
| Chain-aware agent authorization (OPA) | [leanroute/opa-sidecar-a2a](https://github.com/leanroute/opa-sidecar-a2a) |

New accounts get 100 free requests, no card needed: [leanroute.dev](https://leanroute.dev)
