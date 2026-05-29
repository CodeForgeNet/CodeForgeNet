<div align="center">

# Lalu Kumar
### AI Systems Engineer · Full Stack · MCP Specialist

*I build LLM infrastructure that ships — evaluation frameworks, multi-agent systems, and AI-native SaaS at production scale.*

[![Org](https://img.shields.io/badge/CodeForgeNet-0C447C?style=flat-square&logo=github&logoColor=white)](https://github.com/CodeForgeNet)
[![Email](https://img.shields.io/badge/connect.lalukumar%40gmail.com-BA7517?style=flat-square&logo=gmail&logoColor=white)](mailto:connect.lalukumar@gmail.com)
[![MCP Certified](https://img.shields.io/badge/MCP_Specialist-Anthropic-1D9E75?style=flat-square)](https://github.com/CodeForgeNet)
[![AWS](https://img.shields.io/badge/Solutions_Architect-AWS-FF9900?style=flat-square&logo=amazonaws&logoColor=white)](https://github.com/CodeForgeNet)

</div>

---

## Shipped

| Project | What it does | Impact |
|---|---|---|
| **[TunePrompt](https://github.com/CodeForgeNet/tuneprompt)** | LLM evaluation framework — automated prompt testing + cost analysis across Claude / GPT / Gemini | 800+ npm installs · `Node.js` `LangChain` `OpenAI SDK` |
| **[Genesis Forge](https://github.com/CodeForgeNet/genesis-forge)** | Multi-agent orchestration — 24 agents, 79 skills, 13 workflows. MCP-native, Claude CLI + Gemini CLI + Cline | Production MCP system · `TypeScript` `MCP` `multi-agent` |
| **[OpenContext (PCSL)](https://github.com/CodeForgeNet/opencontext)** | Self-hosted context sovereignty layer — JWT-authenticated FastAPI server for secure AI context delivery | Open protocol · `FastAPI` `JWT` `Python` |
| **Real Estate SaaS** *(in build)* | AI voice calling + lead filtration with CRM. WhatsApp API, Redis-backed queuing, Cloud Run deployment | 3-month MVP · `MERN` `360Dialog` `Telnyx` `Cloud Run` |

---

## Open Source

| Repo | PR | What I fixed |
|---|---|---|
| [openClaw](https://github.com/openclaw/openclaw/releases/tag/v2026.4.12) | [#52513](https://github.com/openclaw/openclaw/pull/52513) | Async gateway auth false negatives — SecretRef blocking legit requests |
| [openClaw](https://github.com/openclaw/openclaw/releases/tag/v2026.4.12) | [#52921](https://github.com/openclaw/openclaw/pull/52921) | Session auto-bootstrap — eliminated cold-start auth failures |
| [modelcontextprotocol/servers](https://github.com/modelcontextprotocol/servers) | [#3678](https://github.com/modelcontextprotocol/servers/pull/3678) | Configurable `--follow-symlinks` depth flag for MCP filesystem server |
| [microsoft/promptflow](https://github.com/microsoft/promptflow) | [#4100](https://github.com/microsoft/promptflow/pull/4100) | JSONL UTF-8-BOM encoding failure in eval SDK — silent data corruption fix |

---

## Technical Depth

**AI & LLM Infrastructure**
RAG systems with semantic chunking — 95% retrieval precision in production. Prompt caching reducing inference cost by 25%. Multi-agent orchestration (LangGraph, CrewAI). MCP server design and integration. Multimodal RAG with Gemini Embedding 2.

**Backend**
Microservices on Spring Boot + NestJS. High-load event handling (1000+ concurrent). PostgreSQL schema design, Redis/Upstash queuing, async concurrency patterns. REST + event-driven architecture.

**Frontend**
TypeScript-first React / Next.js 15. Server components, Redux Toolkit, Zustand, real-time UIs with Socket.IO.

**Cloud & Infra**
Google Cloud Run · AWS Lambda · Docker multi-stage builds · GitHub Actions CI/CD · Serverless RAG on Lambda + Upstash Redis.

---

## Stack

```
Languages     TypeScript · Java · Python · JavaScript
Backend       Node.js · NestJS · Spring Boot · FastAPI
Frontend      React · Next.js 15 · Redux Toolkit · Zustand
AI / LLM      LangChain · LangGraph · Pinecone · OpenAI SDK · MCP
Databases     PostgreSQL · MongoDB · Redis · Upstash
Cloud / Infra Docker · Cloud Run · AWS Lambda · GitHub Actions
Real-time     Socket.IO · WebSockets
```

---

<div align="center">

*Every repo under [CodeForgeNet](https://github.com/CodeForgeNet) is production-intent, not a tutorial.*

</div>
