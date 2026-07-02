<h1 align="center">Hi, I'm Nan 👋</h1>
<h3 align="center">I build production AI agents & automation that prioritize accuracy and safety over flashy demos</h3>

<p align="center">
  Answers grounded in real data, with cited sources. Guardrails and human-in-the-loop review where the stakes are high, so the AI never acts unilaterally — because in production, <b>being wrong quietly is worse than saying "I'm not sure."</b> Deployed to the cloud, not left as a demo.
</p>

<p align="center">
  LangGraph workflows · multi-agent orchestration · RAG pipelines · voice agents · MCP servers · full-stack Next.js/TypeScript
</p>

<p align="center">
  <a href="https://caseflowmb.site"><img src="https://img.shields.io/badge/▶_Try_My_Live_App-CaseFlow_MB-16A34A?style=for-the-badge" alt="Live demo"/></a>
  <a href="https://nanxu.site"><img src="https://img.shields.io/badge/Portfolio-nanxu.site-2563EB?style=for-the-badge&logo=vercel&logoColor=white" alt="Portfolio"/></a>
  <!-- TODO: paste your Upwork profile URL between the quotes below -->
  <a href="https://www.linkedin.com/in/n-xu"><img src="https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"/></a>
</p>

---

### ⭐ See my work live

**[CaseFlow MB](https://caseflowmb.site)** is a real, deployed product you can open right now: an AI intake agent for law firms where a human approves every output before anything touches the database. It runs on AWS with database-level tenant isolation, real auth, observability, and zero-downtime deploys.

> 👉 **Open it:** [caseflowmb.site](https://caseflowmb.site) — this is the standard I hold every project to.

---

### 🧭 How I build AI systems

- **Grounded, not guessed** — answers tied to real data with cited sources; the system refuses to answer rather than hallucinate a gap-filler.
- **Human-in-the-loop where it matters** — the agent pauses for review before any high-stakes action. The AI never acts unilaterally.
- **Verified, not vibes** — automated eval harnesses and regression tests that assert correctness (values *and* citations), plus Langfuse tracing so behaviour is observable in production.
- **Shipped end to end** — auth, payments, databases, frontend, Docker, CI/CD, AWS. You get a working system, not a notebook.

---

### 💼 What I can build for you

- 🤖 **AI agents & automated workflows** — multi-step assistants that take real actions, with human approval where it matters
- 📞 **Voice AI agents** — real-time phone assistants that book appointments and trigger backend automations
- 🔍 **"Chat with your documents" (RAG)** — accurate answers from your own files, with sources cited
- 💬 **Messaging & WhatsApp agents** — customer service in the channels your customers already use, with escalation to humans
- 🧰 **MCP servers & custom tools** — connect your data and systems to AI assistants
- ☁️ **Backend & deployment** — FastAPI services, databases, Dockerized and shipped to AWS

<p align="center">
  <b>✅ Available now for freelance & contract work.</b><br/>
  <a href="https://nanxu.site"><img src="https://img.shields.io/badge/💬_Let's_talk_about_your_project-2563EB?style=for-the-badge" alt="Contact"/></a>
</p>

---

### 📌 Featured projects

**🏛️ CaseFlow MB — Multi-tenant AI case management for traffic-defense law firms**  ·  [Live](https://caseflowmb.site) · [Code](https://github.com/nxu22/CaseFlow-MB)

- **Human-in-the-loop intake agent** (4-node **LangGraph**): extract document details → look up real HTA statutes → retrieve similar past cases → draft a legal memo, then **pause for lawyer review before any DB write**. The AI never acts unilaterally on legal work.
- **Database-level multi-tenancy** via PostgreSQL Row-Level Security, verified by **36 cross-tenant isolation tests** — even a compromised query can't leak another firm's data.
- **Persistent agent state** with PostgresSaver on RDS — survives restarts across Gunicorn workers.
- **MCP server** (FastMCP) exposing case data as callable tools in Claude Desktop.
- **Zero-downtime CI/CD** — every push to main auto-deploys to EC2 via GitHub Actions + Docker Compose.

`LangGraph` · `FastAPI` · `PostgreSQL` · `Next.js` · `Docker` · `AWS`

**📊 SalesPilot — Multi-agent assistant with source-gated answers**

Answers sales questions from two sources at once — a PostgreSQL database and a library of contract documents — **with every claim cited to its exact source**.

- **Multi-agent LangGraph pipeline** — an Orchestrator classifies each question and routes it to the SQL Agent, the RAG Agent, or both; a Synthesis node assembles the final answer.
- **Source-gated answers** — every number is tied to a specific table or document, and the system **refuses to answer when neither agent returns supporting data**. No hallucinated gap-filling.
- **Correctness verified by an automated eval harness** that asserts both answer values *and* their citations end-to-end. Langfuse tracing throughout.

`LangGraph` · `Claude` · `PostgreSQL` · `ChromaDB` · `Langfuse`

---

### 🔧 More production work

**📞 River — Real-time voice agent for a vet clinic**
Answers the phone, books appointments, sub-second responses. **Retell + ElevenLabs + Claude**, signature-verified webhooks, n8n post-call automation to email + CRM.
`Voice AI` · `Retell` · `ElevenLabs` · `n8n`

**🎥 WildWatch — Multimodal vision agent**
Watches wildlife footage, identifies species, and flags unusual behaviour. Perceive → Decide → Act loop with **Claude Vision + OpenCV** motion filtering, and a repeatable eval harness. *Code walkthrough available on request.*
`Computer Vision` · `Claude Vision` · `Evals`

**🤖 BuildRight — RAG chatbot for a renovation business**  ·  [Code](https://github.com/nxu22/Buildright_construction)
Answers from a custom knowledge base, captures leads, and auto-emails an AI-summarized transcript.
`RAG` · `ChromaDB` · `Claude API` · `FastAPI`

**💬 Luminary Goods — WhatsApp customer-service agent**
Order / returns / refund handling on the **Meta Cloud API**, per-user memory, and **auto-escalation to humans** when the AI shouldn't decide alone.
`WhatsApp` · `Meta Cloud API` · `Claude` · `FastAPI`

> 👉 More on my portfolio: **[nanxu.site](https://nanxu.site)** · [all repos](https://github.com/nxu22?tab=repositories)

---

### 🛠️ Tech Stack

**Languages**

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat-square&logo=postgresql&logoColor=white)

**AI / Agents**

![LangGraph](https://img.shields.io/badge/LangGraph-1C3C3C?style=flat-square&logo=langchain&logoColor=white)
![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=flat-square&logo=langchain&logoColor=white)
![Claude API](https://img.shields.io/badge/Claude_API-D97757?style=flat-square&logo=anthropic&logoColor=white)
![OpenAI](https://img.shields.io/badge/OpenAI_API-412991?style=flat-square&logo=openai&logoColor=white)
![ChromaDB](https://img.shields.io/badge/ChromaDB-FF6B6B?style=flat-square)
![MCP](https://img.shields.io/badge/MCP-000000?style=flat-square)
![RAG](https://img.shields.io/badge/RAG-5A67D8?style=flat-square)
![Langfuse](https://img.shields.io/badge/Langfuse-0A0A0A?style=flat-square)
![Retell](https://img.shields.io/badge/Retell_Voice_AI-3B82F6?style=flat-square)
![ElevenLabs](https://img.shields.io/badge/ElevenLabs-000000?style=flat-square)

**Backend & Frontend**

![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white)
![React](https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![Supabase](https://img.shields.io/badge/Supabase-3FCF8E?style=flat-square&logo=supabase&logoColor=white)

**Cloud & Tooling**

![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat-square&logo=amazonwebservices&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white)
![n8n](https://img.shields.io/badge/n8n-EA4B71?style=flat-square&logo=n8n&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)

---

### 📫 Get in touch

- ▶️ **Try my live app** — [caseflowmb.site](https://caseflowmb.site)
- 🌐 **Portfolio** — [nanxu.site](https://nanxu.site)
- 💼 **Upwork** — *add your profile URL*
- 🔗 **LinkedIn** — [linkedin.com/in/n-xu](https://www.linkedin.com/in/n-xu)

<p align="center"><i>Have a project in mind? Send me a message — I usually reply the same day.</i></p>
