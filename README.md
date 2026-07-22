<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&height=220&color=0:0f172a,30:312e81,70:4f46e5,100:06b6d4&text=Boggavarapu%20Yuva%20Satya%20Kunaal&fontColor=ffffff&fontSize=42&fontAlignY=38&animation=fadeIn" />

</div>

<div align="center">

<a href="https://www.linkedin.com/in/boggavarapu-yuva-satya-kunaal-127817290/">
  <img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" />
</a>

<a href="mailto:bhavikunaal@gmail.com">
  <img src="https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white" />
</a>

<a href="https://kunaal-portfolio.vercel.app/">
  <img src="https://img.shields.io/badge/Portfolio-000000?style=for-the-badge&logo=vercel&logoColor=white" />
</a>

<a href="https://dev.to/yuva_kunaal">
  <img src="https://img.shields.io/badge/dev.to-0A0A0A?style=for-the-badge&logo=devdotto&logoColor=white" />
</a>

</div>

---

## 💫 Who I Am

I'm **Boggavarapu Yuva Satya Kunaal** — a **B.E. AI & Data Science graduate from CBIT** with a **9.16 CGPA**.

I don't prototype and move on. I **design, build, ship, and own** end-to-end systems — from AI pipelines and data engineering to fully deployed SaaS products with real users. Over the last year, I have focused on turning ideas into practical, production-ready products.

> **From engineer → to founder. From builder → to shipper.**

---

## 🚀 What's New

### 🏛️ Founder — SQLumina *(Deployed · Pre-Launch)*

My most ambitious product yet. **SQLumina is a large-scale SQL learning SaaS platform** — designed from the ground up to be the definitive place where people go to master SQL. Not just a query tool, but a complete learning environment.

---

### 🎙️ AI Interview SDK *(Open Source · Published on npm)*

An **open-source TypeScript/React SDK** for embedding AI-scored interviews directly into your own product as a single component — your backend, your API keys, your database, end to end. The maintainers never see, store, or process a single candidate's answer.

**Key highlights:** One component, two modes — `client` for instant prototyping, `server` for production · Dynamic, depth-limited follow-up engine that scales difficulty to the candidate · HMAC-signed evaluation scores that can be verified, not just trusted · Interview Simulator & Bias/Consistency Harness for fairness testing before real candidates · Five provider adapters (OpenAI, Claude, Gemini, Deepgram, ElevenLabs) with automatic failover · Session persistence with `persistKey` and a typed event stream · Opt-in integrity signals (tab-switch/paste counts) — no webcam or emotion tracking

**Stack:** TypeScript · React · Node.js · OpenAI/Claude/Gemini/Deepgram/ElevenLabs adapters · Next.js examples · pnpm monorepo · CLI + local dashboard

[![Live App](https://img.shields.io/badge/Live_App-6366f1?style=flat-square)](https://ai-interview-sdk.vercel.app)
[![npm](https://img.shields.io/badge/npm-CB3837?style=flat-square&logo=npm&logoColor=white)](https://www.npmjs.com/org/interview-sdk)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=github)](https://github.com/Yuvakunaal/ai-interview-sdk)

---

### 📓 Habit Ink *(Recently Launched)*

A **minimal, intentional habit tracking SaaS** built for people who want clarity over clutter. No noise, no gamification gimmicks — just a clean daily rhythm that actually sticks. Live and growing.

[![Live App](https://img.shields.io/badge/Live_App-6366f1?style=flat-square)](https://habitink.vercel.app/)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=github)](https://github.com/Yuvakunaal/Habit-ink)

---

### 🔀 AI Flowchart Studio *(Launched)*

A **production-ready AI diagram generator** that turns plain English descriptions into structured flowcharts, workflow diagrams, and system design visuals — powered by Gemini AI and a **4-stage Multi-Agent pipeline**.

- **Orchestrator Agent** → validates if the prompt can be visualized as a flowchart
- **Logic Parser Agent** → decomposes text into a structured JSON graph of Nodes & Edges
- **Generator Agent** → converts the graph into optimized Mermaid.js syntax
- **Syntax Validator** → catches rendering anomalies before output reaches the browser

**Key highlights:** BYOK (Bring Your Own Key) privacy architecture · SSE real-time streaming pipeline status · 50-step undo/redo engine · Export to PNG (3x super-scaled), SVG, or Mermaid code · Dark/Light theming

**Stack:** FastAPI (Python) · Gemini AI SDK · Vanilla JS (ES6+) · Mermaid.js · html2canvas · Glassmorphic CSS3 · Vercel (frontend) · Render/Gunicorn+Uvicorn (backend)

[![Live App](https://img.shields.io/badge/Live_App-6366f1?style=flat-square)](https://ai-flowchart-studio.vercel.app)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=github)](https://github.com/Yuvakunaal/AI-Flowchart-Studio)

---

### ⚡ CommitAI *(dev.to Gemma 4 Challenge — Badge Earned ✅)*

A **local-first AI Git assistant** that eliminates the most repetitive part of every developer's workflow — writing commit messages. CommitAI reads your staged diff, sends a focused prompt to Ollama, and generates clean Conventional Commit messages.

**Key highlights:** AI-generated Conventional Commit messages · Automatic changelog generation · PR description generation (`--pr` flag) · `prepare-commit-msg` git hook integration · Multi-model support

**Stack:** Python 3.13+ · Ollama · Gemma 4 (`gemma4:e2b`) · Rich · Git hooks

**Architecture:**
```
Staged Git Diff → CommitAI → Ollama API → Gemma 4 → AI Commit Message → Git Commit
```

[![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=github)](https://github.com/Yuvakunaal/CommitAI)

---

### 🎨 Kunaal's Illustrations *(Open Source · Released)*

An **open source Agent Skill** that guides AI agents to generate clean, bizarre, hand-drawn in-text illustrations for English articles and knowledge content. Not a generic image prompt — a full visual instruction system.

**Key highlights:** Wide-composition hand-drawn illustrations · Pure white background, sparse red/orange/blue annotations · Reference Boy & Girl character IPs · Works with Antigravity + Gemini · Designed for readability and style consistency

[![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=github)](https://github.com/Yuvakunaal/kunaal-illustrations)

---

## 🧠 Core Technical Strengths

### 💻 Programming & Backend Engineering
- **Python** — Advanced backend development, automation-first architecture, production systems
- **SQL** — Expert in query optimization, window functions, CTEs, complex JOINs, analytics pipelines
- **FastAPI & Flask** — High-performance, production-ready API services
- **Git & GitHub** — Strong version control, hooks, collaborative and open-source workflows

### 🌐 Frontend & Full-Stack
- **HTML, CSS, JavaScript (ES6+)** — Responsive, production-ready, aesthetically intentional interfaces
- **Glassmorphic UI, Dark/Light Theming, SSE** — Real-time UX, modern design patterns
- **Vibe Coding** — Rapid, intuitive product iteration with a sharp sense of feel and function

### 🤖 AI, GenAI & LLM Engineering
- **Large Language Models** — Claude, GPT, Gemini, Mistral, DeepSeek, LLaMA, Qwen, Gemma 4
- **Multi-Agent Orchestration** — Designing intelligent pipelines with layered, specialized agent roles
- **Prompt Engineering** — Schema-aware, deterministic, structured-output prompting at production scale
- **RAG Systems** — Retrieval-augmented pipelines for grounded, accurate, hallucination-resistant AI outputs
- **Ollama** — Local LLM deployment, model selection, offline-first AI system design

### 📊 Data, Analytics & Automation
- **Data Analysis** — Pandas, NumPy, Matplotlib, business insight extraction, pattern detection
- **Data Engineering** — ETL pipelines, OCR-driven data extraction, end-to-end automated workflows
- **Automation Systems** — Certificate generation, attendance monitoring, HR workflows, Make.com

### 🏗️ SaaS & Product Building
- **End-to-end SaaS architecture** — From database schema to CI/CD and live deployment
- **BYOK (Bring Your Own Key)** — Privacy-first product design philosophy
- **Vercel + Render + Firebase + Supabase** — Production hosting, CORS, CDN, ASGI workers
- **LocalStorage-first, zero server retention** — Data ownership for users by default

---

## 🛠️ All Projects

| Project | What It Does | Stack Highlights | Status |
|---|---|---|---|
| **SQLumina** | Large-scale SQL learning SaaS platform — structured lessons, practice environments, progressive challenges | SaaS · Full-Stack | 🟡 Deployed · Pre-Launch |
| **AI Interview SDK** | Open-source SDK for embedding AI-scored, rubric-based interviews into any app — client & server modes, fairness testing built in | TypeScript · React · OpenAI/Claude/Gemini/Deepgram/ElevenLabs | 🟢 Published on npm |
| **Habit Ink** | Minimal habit tracking SaaS — clarity-first design, real daily consistency | SaaS · Full-Stack | 🟢 Live |
| **AI Flowchart Studio** | Text → diagrams via Gemini AI + 4-stage multi-agent pipeline. Export PNG/SVG/Mermaid | FastAPI · Gemini · Mermaid.js · SSE | 🟢 Live |
| **CommitAI** | Local AI Git assistant — staged diffs → Conventional Commits, changelogs, PR descriptions | Python · Ollama · Gemma 4 · Rich | 🏅 dev.to Badge |
| **Kunaal's Illustrations** | Open source Agent Skill — guides AI to generate hand-drawn in-text illustrations with consistent style and character IPs | Agent Skill · Gemini · Antigravity | 🟢 Released |
| **Query Forge AI** | Production NL→SQL engine with schema-aware prompting | FastAPI · MySQL · Mistral | ✅ Complete |
| **AnalyzeQuestion** | AI-driven coding pattern detection via RAG pipeline | RAG · LLM · Python | ✅ Complete |
| **ERP Academic Intelligence Engine** | Automated ETL + OCR system — saves 8+ hours weekly | ETL · OCR · Python | ✅ Complete |
| **ChatWithPDF** | PDF Q&A system with OCR grounding and LLM accuracy | RAG · OCR · LLM | ✅ Complete |
| **AI Voice Desktop Assistant** | Privacy-first voice agent with sub-second response time | Python · Local LLM · TTS/STT | ✅ Complete |
| **Automation Systems** | Certificate generation, attendance monitoring, HR workflow automation | Python · Make.com | ✅ Complete |

---

## 🏆 Competitive & Professional Credentials

- 🎓 **B.E. AI & Data Science — CBIT** · Final CGPA: **9.16 / 10**
- 💻 **200+ LeetCode problems solved** (Top 18%)
- ⭐ **HackerRank Master** — Python 5★ · Problem Solving 4★
- 🍴 **CodeChef 2★ Rated Coder**
- 🏅 **dev.to Gemma 4 Challenge — Completion Badge Earned** (CommitAI)
- 📜 Certified by **HackerRank, IBM, Infosys, Salesforce, NASSCOM, IIT Hyderabad**, CBIT GenAI Program

---

## 🎯 What I'm Ready For

**Target Roles**
- GenAI / AI Engineer
- Data Engineer · Data Analyst
- SaaS Founder / Indie Builder
- Automation Engineer (Make.com / n8n)
- Full-Stack AI Product Developer

**What I Bring**
- End-to-end product ownership — idea → architecture → deployment → users
- Multi-agent AI system design and orchestration
- Production data pipelines and intelligent automation
- A sharp eye for UX, performance, and reliability
- Proven track record of shipping real, usable products

---

## 🎯 Skills and Expertise

### ⚡ Core Languages

![Python](https://img.shields.io/badge/Python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)
![JavaScript](https://img.shields.io/badge/JavaScript-323330?style=for-the-badge&logo=javascript&logoColor=F7DF1E)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white)


### 🚀 Backend & APIs

![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white)
![Flask](https://img.shields.io/badge/Flask-000000?style=for-the-badge&logo=flask&logoColor=white)
![Socket.io](https://img.shields.io/badge/Socket.IO-010101?style=for-the-badge&logo=socket.io&logoColor=white)
![Gunicorn](https://img.shields.io/badge/Gunicorn-499848?style=for-the-badge&logo=gunicorn&logoColor=white)


### 🗄️ Databases & Storage

![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white)
![SQLite](https://img.shields.io/badge/SQLite-07405E?style=for-the-badge&logo=sqlite&logoColor=white)
![Neon](https://img.shields.io/badge/Neon-00E599?style=for-the-badge&logo=neon&logoColor=black)
![Supabase](https://img.shields.io/badge/Supabase-3ECF8E?style=for-the-badge&logo=supabase&logoColor=white)
![Firebase](https://img.shields.io/badge/Firebase-FFCA28?style=for-the-badge&logo=firebase&logoColor=black)


### 🤖 Data Analysis

![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white)


### 🛠️ Developer Tools

![Git](https://img.shields.io/badge/Git-F05033?style=for-the-badge&logo=git&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-121011?style=for-the-badge&logo=github&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![Postman](https://img.shields.io/badge/Postman-FF6C37?style=for-the-badge&logo=postman&logoColor=white)
![CLI](https://img.shields.io/badge/CLI-121011?style=for-the-badge&logo=gnubash&logoColor=white)


### 🎨 Design & Deployment

![Figma](https://img.shields.io/badge/Figma-F24E1E?style=for-the-badge&logo=figma&logoColor=white)
![Framer](https://img.shields.io/badge/Framer-000000?style=for-the-badge&logo=framer&logoColor=white)


### ☁️ Cloud & Infrastructure

![Vercel](https://img.shields.io/badge/Vercel-000000?style=for-the-badge&logo=vercel&logoColor=white)
![Netlify](https://img.shields.io/badge/Netlify-00C7B7?style=for-the-badge&logo=netlify&logoColor=white)
![Fly.io](https://img.shields.io/badge/Fly.io-8B5CF6?style=for-the-badge&logo=flydotio&logoColor=white)
![Render](https://img.shields.io/badge/Render-46E3B7?style=for-the-badge&logo=render&logoColor=black)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)


### 📨 Communication & Auth

![Clerk](https://img.shields.io/badge/Clerk-6C47FF?style=for-the-badge&logo=clerk&logoColor=white)
![Twilio](https://img.shields.io/badge/Twilio-F22F46?style=for-the-badge&logo=twilio&logoColor=white)
![Resend](https://img.shields.io/badge/Resend-000000?style=for-the-badge&logo=resend&logoColor=white)


### ⚙️ Modern AI Stack

![Claude](https://img.shields.io/badge/Claude-F97316?style=for-the-badge&logo=anthropic&logoColor=white)
![Codex](https://img.shields.io/badge/Codex-412991?style=for-the-badge&logo=openai&logoColor=white)
![Ollama](https://img.shields.io/badge/Ollama-000000?style=for-the-badge&logo=ollama&logoColor=white)
![Gemini](https://img.shields.io/badge/Gemini-4285F4?style=for-the-badge&logo=google&logoColor=white)
![DeepSeek](https://img.shields.io/badge/DeepSeek-4D6BFE?style=for-the-badge&logoColor=white)
![Qwen](https://img.shields.io/badge/Qwen-FF6A00?style=for-the-badge&logoColor=white)
![Groq](https://img.shields.io/badge/Groq-F55036?style=for-the-badge&logoColor=white)
![Kimi](https://img.shields.io/badge/Kimi-4F46E5?style=for-the-badge&logoColor=white)

---

## 📊 GitHub Stats

<div align="center">

![](https://github-readme-stats.vercel.app/api?username=Yuvakunaal&theme=tokyonight&hide_border=false&include_all_commits=true&count_private=true)<br/>
![](https://nirzak-streak-stats.vercel.app/?user=Yuvakunaal&theme=tokyonight&hide_border=false)<br/>
![](https://github-readme-stats.vercel.app/api/top-langs/?username=Yuvakunaal&theme=tokyonight&hide_border=false&include_all_commits=true&count_private=true&layout=compact)

</div>

---

## ✍️ Dev Quote

<div align="center">

![](https://quotes-github-readme.vercel.app/api?type=horizontal&theme=radical&quote=Perfection%20is%20achieved%20not%20when%20there%20is%20nothing%20more%20to%20add,%20but%20when%20there%20is%20nothing%20left%20to%20take%20away.)

</div>

---

<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=6366f1,8b5cf6,06b6d4&height=100&section=footer" />

**Boggavarapu Yuva Satya Kunaal** · Building real systems. Shipping real products. Making real impact.

</div>
