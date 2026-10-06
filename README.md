# Wai-Siu Lai

**Software engineer building systems in Rust and Go, and AI tooling in Python.** I care about the boring parts that keep things up: checked arithmetic, all-or-nothing state changes, rate limits, failover, and measuring before claiming.

📍 Diamond Bar, CA · 📧 [wzltmp@gmail.com](mailto:wzltmp@gmail.com) · 💼 [LinkedIn](https://www.linkedin.com/in/wai-siu-lai-109422412/)

---

## Systems

| Project | What it is |
|---|---|
| [**rust-edge-gateway**](https://github.com/wzltmp/rust-edge-gateway) | Cloudflare-inspired edge gateway in Rust: async reverse proxy, host/path routing, TTL response cache, token-bucket rate limiting, health checks with failover, tracing and Prometheus metrics. Every feature justified by a measurement; failure-injection tests and a written incident report. |
| [**LedgerModels**](https://github.com/wzltmp/LedgerModels) | Account, UTXO and double-entry ledgers in Rust behind one shared trait, cross-checked on the same scenarios. `Amount` has no `+`, so every sum goes through `checked_add`; rejected transfers leave state untouched; deterministic Merkle state roots. |
| [**penumbra**](https://github.com/wzltmp/penumbra) | MCP gateway in Go that sits in front of many MCP servers and exposes only the task-relevant tools to the agent, without breaking prompt caching. |

## AI tooling

| Project | What it is | Live |
|---|---|---|
| [**mcp-automations**](https://github.com/wzltmp/mcp-automations) | MCP server with 4 typed tools, stdio + streamable-HTTP transports, per-call cost telemetry; listed on the official MCP Registry | [Playground](https://mcp-automations-5vgea2ynuyrvbzkcxm6yoh.streamlit.app/) · [MCP HTTP](https://mcp-automations.fly.dev/mcp) · [Registry](https://registry.modelcontextprotocol.io/v0/servers?search=mcp-automations) |
| [**TokenSmith**](https://github.com/wzltmp/TokenSmith) | Provider-agnostic toolkit for prompt-cache optimization and context engineering; zero core dependencies, 25 tests in CI | |
| [**langgraph-research-agent**](https://github.com/wzltmp/langgraph-research-agent) | Stateful research agent that beat a Claude+web_search baseline on citation quality (3.45 vs 1.85, 20-query LLM-judged eval) | [Demo](https://langgraph-research-agent.streamlit.app/) |
| [**rag-eval-harness**](https://github.com/wzltmp/rag-eval-harness) | pgvector RAG with an LLM-as-judge harness; shipped the honest negative result that reranking didn't help on this corpus | [Demo](https://rag-eval-harness.streamlit.app/) |

## Stack

**Systems:** `Rust` · `Go` · async networking · HTTP · Prometheus · `cargo` / Clippy (pedantic) / `unsafe` forbidden
**Backend & AI:** `Python` · `TypeScript` · `FastAPI` · `PostgreSQL` / `pgvector` · `Anthropic SDK` · `MCP` · `LangGraph` · `AWS` (Lambda, Bedrock, Textract) · `Docker` · `Fly.io`

## Reach out

Looking for software engineering internships and new-grad roles in backend, systems, and infrastructure: [wzltmp@gmail.com](mailto:wzltmp@gmail.com).
