# Wai-Siu Lai

**AI Engineer building production LLM systems on AWS Bedrock.** Author of [`io.github.wzltmp/mcp-automations`](https://registry.modelcontextprotocol.io/v0/servers?search=mcp-automations) on the official Anthropic MCP Registry.

📍 Diamond Bar, CA · 📧 [wzltmp@gmail.com](mailto:wzltmp@gmail.com) · 💼 [LinkedIn](https://www.linkedin.com/in/wai-siu-lai-109422412/)

---

## Featured projects

| Project | What it is | Live |
|---|---|---|
| [**mcp-automations**](https://github.com/wzltmp/mcp-automations) | Production-grade MCP server: 4 typed tools, stdio + streamable-HTTP transports, per-call cost telemetry on every Pydantic response, listed on the official MCP Registry | [Playground](https://mcp-automations-5vgea2ynuyrvbzkcxm6yoh.streamlit.app/) · [MCP HTTP](https://mcp-automations.fly.dev/mcp) · [Registry](https://registry.modelcontextprotocol.io/v0/servers?search=mcp-automations) |
| [**langgraph-research-agent**](https://github.com/wzltmp/langgraph-research-agent) | Stateful LangGraph research agent that beats Claude+web_search baseline on citation quality by ~86% (3.45 vs 1.85, 20-query Sonnet-judged eval) | [Demo](https://langgraph-research-agent.streamlit.app/) |
| [**rag-eval-harness**](https://github.com/wzltmp/rag-eval-harness) | pgvector RAG over 28 Paul Graham essays with an LLM-as-judge eval harness; shipped the honest negative result that reranking didn't help on this corpus | [Demo](https://rag-eval-harness.streamlit.app/) |

## What I work on

- **GenAI infrastructure** on AWS Bedrock — Knowledge Bases, Agents, Guardrails, plus Textract for document AI pipelines
- **Anthropic MCP** — building servers, not just consuming them
- **Eval-first design** — cost telemetry, A/B harnesses, honest negative results over fabricated wins
- **Cost-aware model routing** — Haiku 4.5 for cheap tasks, Sonnet 4.6 for high-stakes ones, prompt caching everywhere

## Stack

`Python 3.13` · `FastAPI` · `FastMCP` · `LangGraph` · `Pydantic` · `pgvector` · `Anthropic SDK` · `AWS Bedrock + Textract + Lambda` · `Docker` · `Fly.io` · `Streamlit Cloud`

## Reach out

If you're hiring for a Generative AI Engineer / Prompt Engineer / AI Engineer role and the projects above look like the kind of work you do — [wzltmp@gmail.com](mailto:wzltmp@gmail.com).
