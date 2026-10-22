<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0D1117,50:1F6FEB,100:A371F7&height=180&section=header&text=Arun&fontSize=70&fontColor=FFFFFF&animation=fadeIn&fontAlignY=32&desc=Backend%20%7C%20AI%20Engineer&descAlignY=55&descSize=18" width="100%" alt="banner" />

<a href="https://readme-typing-svg.demolab.com">
<img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=600&size=24&duration=3000&pause=800&color=1F6FEB&center=true&vCenter=true&width=900&lines=Backend+%7C+AI+Engineer;B.Tech+CSE+%40+IIIT+Sri+City+%7C+2023-2027;LLM+Agents+%E2%80%A2+RAG+Pipelines+%E2%80%A2+Distributed+Backends;I+build+AI+systems+with+guardrails%2C+not+vibes." alt="Typing SVG" />
</a>

<br/>

<a href="https://www.linkedin.com/in/arun-52094b297"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"/></a>
<a href="https://github.com/arungujjar123"><img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white" alt="GitHub"/></a>
<a href="mailto:officialarunbadgujja@gmail.com"><img src="https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"/></a>

</div>

---

## <img src="https://media.giphy.com/media/WUlplcMpOCEmTGBtBW/giphy.gif" width="28"> About Me

```yaml
name:        Arun
role:        Fullstack-developer & AI Engineer
education:   B.Tech, Computer Science — IIIT Sri City (2023 – 2027)
location:    Sri City, Andhra Pradesh, India

focus:
  - LLM agents with deterministic guardrails & human-in-the-loop controls
  - RAG pipelines, embeddings, semantic caching
  - Production backends: REST APIs, auth, ledgers, observability

currently:
  - Shipping an LLM gateway with circuit-breaker failover + semantic cache
  - Privacy-preserving ML (Shamir Secret Sharing + Federated Learning)
  - 200+ DSA problems solved across competitive platforms

philosophy: "If an LLM can silently be wrong, the rules — not the model — decide."
open_to:    AI / ML Engineer · Backend Engineer · SDE-1
```

---

## <img src="https://media.giphy.com/media/iY8CRBdQXODJSCERIr/giphy.gif" width="28"> Experience

<table>
<tr>
<td width="50%" valign="top">

### 🧑‍💻 Unified Mentor Pvt. Ltd.
**Full-Stack Web Development Intern**
`Jul 2026 – Oct 2026`

- Built an **Admin & SuperAdmin Control Center** for a full-stack LMS spanning **3 user roles**
- Engineered **RBAC + JWT** middleware securing admin-only APIs
- Designed a **cascading soft-delete & restore engine** preserving referential integrity across MongoDB schemas
- Shipped a **Teacher Verification Workflow** + Recharts analytics dashboard

`Node.js` `Express` `MongoDB` `React` `JWT`

</td>
<td width="50%" valign="top">

### 🔐 IIIT Sri City
**AI / Full-Stack Engineer Intern** — *under Prof. Kartik Sutradhar*
`Jan 2026 – Apr 2026`

- Architected a **PPML pipeline** integrating **Shamir's Secret Sharing** with **Federated Learning** for secure multi-party gradient aggregation
- Built an **Agentic Cryptography Copilot** with custom function calling to verify `(t, n)` threshold security parameters
- Engineered an **NL → MPC engine** compiling confidentiality constraints into executable SSS protocols
- Implemented polynomial generation, share computation & **Lagrange interpolation** with BigInt arithmetic

`Next.js` `TypeScript` `LangChain` `Vercel AI SDK` `Jest`

</td>
</tr>
</table>

---

## <img src="https://media.giphy.com/media/dWesBcTLavkZuG35MI/giphy.gif" width="28"> Tech Stack

<div align="center">

**Languages**

<img src="https://skillicons.dev/icons?i=python,js,ts,java,c,cpp&theme=dark" alt="languages" />

**Backend & APIs**

<img src="https://skillicons.dev/icons?i=nodejs,express,fastapi,redis,postman&theme=dark" alt="backend" />

**AI / LLM Engineering**

<img src="https://img.shields.io/badge/LangChain-1C3C3C?style=flat-square&logo=langchain&logoColor=white" />
<img src="https://img.shields.io/badge/Agno_Multi--Agent-5A3FD6?style=flat-square" />
<img src="https://img.shields.io/badge/Groq-F55036?style=flat-square&logo=groq&logoColor=white" />
<img src="https://img.shields.io/badge/OpenAI_GPT--4o-412991?style=flat-square&logo=openai&logoColor=white" />
<img src="https://img.shields.io/badge/Pinecone-000000?style=flat-square" />
<img src="https://img.shields.io/badge/ChromaDB-FFC107?style=flat-square&logoColor=black" />
<img src="https://img.shields.io/badge/RAG_Pipelines-1F6FEB?style=flat-square" />
<img src="https://img.shields.io/badge/Function_Calling-A371F7?style=flat-square" />
<img src="https://img.shields.io/badge/Semantic_Caching-00897B?style=flat-square" />
<img src="https://img.shields.io/badge/Federated_Learning-D81B60?style=flat-square" />

**Frontend**

<img src="https://skillicons.dev/icons?i=react,nextjs,redux,tailwind,vite,html,css&theme=dark" alt="frontend" />

**Databases**

<img src="https://skillicons.dev/icons?i=mongodb,postgres,redis&theme=dark" alt="databases" />

**MLOps, Cloud & DevOps**

<img src="https://skillicons.dev/icons?i=docker,kubernetes,aws,gcp,githubactions,grafana,prometheus,git,linux,vercel&theme=dark" alt="devops" />

</div>

---

## <img src="https://media.giphy.com/media/LnQjpWaON8nhr21vNW/giphy.gif" width="28"> Featured Projects

<table>
<tr>
<td width="50%" valign="top">

### 🛡️ [SentinelAI](https://github.com/arungujjar123/Sentinel-AI)
**Production LLM Gateway**

A reliability & cost-control layer that sits in front of Groq and Gemini so your app never calls a raw provider API.

- 3-stage control layer: **prompt routing → semantic cache → circuit-breaker provider abstraction**
- 3-state circuit breaker (`closed → open → half-open`) with automatic **Groq → Gemini** failover
- **98%+ latency cut** (15–50 ms cached vs. 1.5–2.5 s direct) at a **57% cache-hit rate** under concurrent load
- Real-time Next.js observability dashboard, Dockerised

`Python` `FastAPI` `pgvector` `Celery` `Redis` `Next.js` `Docker`

</td>
<td width="50%" valign="top">

### ⚡ [Dynamic Pricing Agent](https://github.com/arungujjar123/Dynamic-prize-agent)
**Autonomous Decisions + Hard Guardrails**

An autonomous GPT-4o pricing engine that reasons over competitor prices, demand signals and inventory — on a schedule.

- APScheduler-driven **60-minute cycle** selecting from **5 pricing strategies**
- Hard guardrails (**15% margin floor, 20% velocity cap**) with automatic correction when the LLM contradicts its own strategy
- **4-pillar Prometheus suite** (agent health, token economics, decision quality, business impact) + Grafana dashboard & 8 alert rules
- 5-service Docker Compose stack, Swagger-documented REST API

`Python` `FastAPI` `GPT-4o` `PostgreSQL` `Prometheus` `Grafana` `Docker`

</td>
</tr>
<tr>
<td width="50%" valign="top">

### 🧾 [Payroll Anomaly Detector](https://github.com/arungujjar123/payroll-anomoly-detector)
**Multi-Agent Workflow + Deterministic Controls**

A 5-agent payroll audit pipeline running against live ERPNext data — where the LLM never decides anything financial.

- LLM restricted to **explanation text only**; deterministic rules alone govern anomaly categorisation
- **Human-in-the-loop checkpoint** pauses the pipeline for HR confirmation before any report is finalised
- Compares current vs. previous payroll cycles to surface missing deductions, salary jumps & missing slips

`Python` `FastAPI` `Agno Multi-Agent` `ERPNext REST API`

</td>
<td width="50%" valign="top">

### 🛒 [Quick Bazar](https://github.com/arungujjar123/Quick-bazar-backend)
**AI-Powered Enterprise Support System**

A conversational commerce platform with a two-pass agentic engine wired straight into live database actions.

- Groq **Llama 3.3** two-pass agentic engine executing **9 real-time DB actions**
- Cloud-hosted **Pinecone RAG** (1024-d `multilingual-e5-large`) over **5,000+ vectors**, retrieval **< 80 ms**
- **Llama-3.2-Vision** for image-based product matching
- Atomic MongoDB `bulkWrite` eliminating stock race conditions · ~**500 ms** end-to-end

`Node.js` `Express` `Groq` `Pinecone` `MongoDB` `JWT`
[Frontend →](https://github.com/arungujjar123/Quick-bazar-frontend)

</td>
</tr>
<tr>
<td width="50%" valign="top">

### 🏦 [Banking Ledger System](https://github.com/arungujjar123/Banking-ledger-transaction-management-system)
**Double-Entry Transaction Management**

An immutable, ACID-compliant ledger where balances are *derived*, never stored.

- **Double-entry ledger engine** across 5 Mongoose schemas with MongoDB sessions
- **10-step transfer pipeline** with idempotency-key validation preventing duplicate transactions
- Dual User/Admin portals over **12+ REST APIs** with RBAC approval workflows
- JWT HTTP-only cookies, bcrypt hashing, **TTL-indexed token blacklisting**

`Node.js` `Express` `MongoDB` `React` `Tailwind` `JWT`

</td>
<td width="50%" valign="top">

### 🚚 [CargoLink](https://github.com/arungujjar123/Cargo-link)
**Full-Stack Logistics Marketplace**

An 11-service marketplace connecting shippers with truck owners and drivers through live competitive bidding.

- MongoDB schemas for Customers, Transporters, Orders, Bids & Fleets supporting real-time bidding
- Dockerised **Redis caching layer** with safe fallback behaviour
- **Razorpay** payments + **Google Maps** routing integration
- CI/CD on **GCP** (Cloud Build, App Engine) with independently deployable services

`React` `Node.js` `Express` `MongoDB` `Redis` `Docker` `GCP`

</td>
</tr>
</table>

<div align="center">

### 🔬 Also worth a look

[![Shamir MPC Visualizer](https://img.shields.io/badge/🔐_Shamir_MPC_Visualizer-Next.js_·_TypeScript_·_KaTeX-1F6FEB?style=for-the-badge)](https://github.com/arungujjar123/Multiparty-Summation)
[![AI Support System](https://img.shields.io/badge/🤖_RAG_Support_Agent-FastAPI_·_LangChain_·_Groq-A371F7?style=for-the-badge)](https://github.com/arungujjar123/Ai-support-system)
[![LMS](https://img.shields.io/badge/🎓_Learning_Management_System-Node_·_React_·_RBAC-00897B?style=for-the-badge)](https://github.com/arungujjar123/Learning-management-system-backend)

</div>

---

## <img src="https://media.giphy.com/media/QssGEmpkyEOhBCb7e1/giphy.gif" width="28"> Achievements

- 🏛️ **Technical Team Member** — Abhisarga College Technical Team, IIIT Sri City *(Dec 2024 – May 2025)*
  Deployed the Abhisarga event platform supporting **1,000+ concurrent users**; improved Core Web Vitals and cut server response time under peak load.
- 🧩 **Hackathon Organizer & Problem Setter** — IIIT Sri City *(2024)*
  Authored **25+ algorithmic challenges** for **300+ participants**; automated evaluation pipelines cut judging time by **60%**.
- ⚔️ **Competitive Programming** — Solved **200+ DSA problems** across competitive coding platforms.
- 🔐 **Research Internship** — Privacy-Preserving ML under Prof. Kartik Sutradhar, IIIT Sri City.

---

## <img src="https://media.giphy.com/media/VgCDAzcKvsR6OM0uWg/giphy.gif" width="28"> GitHub Analytics

<div align="center">

<img height="165" src="https://github-readme-stats.vercel.app/api?username=arungujjar123&show_icons=true&include_all_commits=true&count_private=true&theme=tokyonight&hide_border=true&bg_color=0D1117&title_color=1F6FEB&icon_color=A371F7&text_color=C9D1D9" alt="GitHub Stats" />
<img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=arungujjar123&layout=compact&langs_count=8&theme=tokyonight&hide_border=true&bg_color=0D1117&title_color=1F6FEB&text_color=C9D1D9" alt="Top Languages" />

<br/><br/>

<img src="https://streak-stats.demolab.com?user=arungujjar123&theme=tokyonight&hide_border=true&background=0D1117&ring=1F6FEB&fire=A371F7&currStreakLabel=1F6FEB" alt="GitHub Streak" />

<br/><br/>

<img src="https://github-profile-trophy.vercel.app/?username=arungujjar123&theme=tokyonight&no-frame=true&no-bg=true&column=7&margin-w=10&margin-h=10" alt="Trophies" />

</div>

### 🐍 Contribution Graph

<div align="center">

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/arungujjar123/arungujjar123/output/github-snake-dark.svg" />
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/arungujjar123/arungujjar123/output/github-snake.svg" />
  <img alt="github contribution snake animation" src="https://raw.githubusercontent.com/arungujjar123/arungujjar123/output/github-snake.svg" />
</picture>

<br/><br/>

<img src="https://github-readme-activity-graph.vercel.app/graph?username=arungujjar123&theme=tokyo-night&hide_border=true&bg_color=0D1117&color=1F6FEB&line=A371F7&point=C9D1D9&area=true" alt="Activity Graph" width="100%" />

</div>

---

## <img src="https://media.giphy.com/media/du3J3cXyzhj75IOgvA/giphy.gif" width="28"> Let's Connect

<div align="center">

I'm open to **AI / ML Engineer**, **Backend Engineer** and **SDE-1** roles — and always happy to talk about agent guardrails, RAG, or anything that keeps an LLM honest.

<a href="https://www.linkedin.com/in/arun-52094b297"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"/></a>
<a href="mailto:officialarunbadgujja@gmail.com"><img src="https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"/></a>
<a href="https://github.com/arungujjar123"><img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white" alt="GitHub"/></a>

<br/><br/>

> ### *"If an LLM can silently be wrong, the rules — not the model — decide."*

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:A371F7,50:1F6FEB,100:0D1117&height=120&section=footer" width="100%" alt="footer"/>

</div>
