<div align="center">

# Om Salunke

### Software Engineer · Backend & Distributed Systems · AI Developer Tooling

**I don't fix bugs. I build the tools that stop them from showing up.**

Founder of the XtraFusion ecosystem — open-source tooling that makes AI coding agents faster, cheaper and safer.

<p>
  <a href="https://www.linkedin.com/in/om-salunke-81bb63292/"><img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>
  <a href="https://github.com/om0852"><img src="https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white" alt="GitHub" /></a>
  <a href="https://salunkeom.netlify.app/"><img src="https://img.shields.io/badge/Portfolio-6366F1?style=for-the-badge&logo=firefox&logoColor=white" alt="Portfolio" /></a>
  <a href="https://leetcode.com/omsalunke0852"><img src="https://img.shields.io/badge/LeetCode-FFA116?style=for-the-badge&logo=leetcode&logoColor=black" alt="LeetCode" /></a>
  <a href="mailto:salunkeom474@gmail.com"><img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" /></a>
</p>

<p>
  <img src="https://img.shields.io/badge/📍_Pune,_India-10b981?style=flat-square" alt="Location" />
  <img src="https://img.shields.io/badge/🏢_SDE_Intern_@_Creatosaurus-f59e0b?style=flat-square" alt="Creatosaurus" />
  <img src="https://img.shields.io/badge/ex--ADP_(Fortune_500)-ef4444?style=flat-square" alt="ADP" />
  <img src="https://img.shields.io/badge/🎓_B.E._CSE_·_CGPA_9.49-3b82f6?style=flat-square" alt="Academics" />
  <img src="https://img.shields.io/badge/⚔️_LeetCode_Knight_·_1857-8b5cf6?style=flat-square" alt="LeetCode" />
</p>

</div>

---

## 👋 About me

Backend by trade, tool-builder by instinct. If a workflow annoys me twice, it gets its own npm package.

- 🏢 **Now:** Software Developer Intern at **Creatosaurus** (round two) — backend pipelines, scrapers and real-time data at scale
- 🏦 **Before:** 3-month SDE internship at **ADP India (Fortune 500)** — Python/Pydantic backend services, AWS, Amazon Q, Agile CI/CD
- ⚙️ **And before that:** Full Stack Intern at **Creatosaurus** — scraping pipelines ingesting **10,000+ records/day** on AWS EC2, Redis & BullMQ
- 🚀 **Side quest:** Founder of **XtraFusion** — four shipped products around MCP servers, AI agent memory and secrets management
- ⚔️ **Competitive programming:** LeetCode Knight, rating **1,857** (top ~6% globally), **645+** problems solved
- 🎓 **Education:** B.E. Computer Engineering, D.Y. Patil College of Engineering, Pune (CGPA **9.49**)

---

## 📊 At a glance

<div align="center">

| 🧠 **99.98%** | ⚡ **~52 ms** | 📈 **10K+/day** | 🔐 **5K+/day** | 🏆 **Top 6%** |
|:---:|:---:|:---:|:---:|:---:|
| LLM prompt tokens saved by Codebase Trainer vs raw repo dumps | Hybrid BM25 + vector search latency, fully offline | Records ingested by pipelines I built at Creatosaurus | Secret-retrieval requests served by XtraSecurity | LeetCode contest standing worldwide |

</div>

---

## 🚀 What I've built

<table>
<tr>
<td width="50%" valign="top">

### 🧩 [Codebase Trainer](https://github.com/om0852/codebase-trainer)
<img src="https://img.shields.io/badge/npm-codebase--trainer-CB3837?style=flat-square&logo=npm" /> <img src="https://img.shields.io/badge/MCP-14_tools_·_5_resources-818cf8?style=flat-square" /> <img src="https://img.shields.io/badge/License-MIT-green?style=flat-square" />

**Local codebase intelligence engine for Cursor, Claude Code & VS Code.**

- Indexes a repo's AST, imports and call graph so agents get ~1.5k targeted tokens instead of multi-million-token dumps
- Hybrid retrieval: Okapi BM25 + local 128-d embeddings + PageRank, fused with Reciprocal Rank Fusion
- API contract drift detection, change-impact analysis, SARIF output for GitHub Actions
- 100% local — no API keys, no code leaves the machine

`npx codebase-trainer init` · [Live site](https://codebase-trainer.vercel.app)

</td>
<td width="50%" valign="top">

### 🔐 [XtraSecurity](https://xtrasecurity.in/)
<img src="https://img.shields.io/badge/Encryption-AES--256--GCM-blue?style=flat-square" /> <img src="https://img.shields.io/badge/Architecture-Zero--Knowledge-orange?style=flat-square" /> <img src="https://img.shields.io/badge/Stack-Next.js_·_Node_·_Redis-purple?style=flat-square" />

**Zero-knowledge environment variable & secrets manager.**

- Replaces `.env` files with client-side encrypted vaults, RBAC, JIT access and tamper-evident audit logs
- `xtra run` CLI injects secrets into process memory at startup — zero disk footprint
- REST backend serving 5,000+ retrievals/day with Redis caching; integrations for GitHub, AWS, Vercel, Slack

[Platform](https://xtrasecurity.in/) · [Docs](https://xtrasecurity.in/docs)

</td>
</tr>
<tr>
<td width="50%" valign="top">

### 🧠 [XtraContext](https://xtracontext.vercel.app/)
<img src="https://img.shields.io/badge/MCP-Memory_Layer-indigo?style=flat-square" /> <img src="https://img.shields.io/badge/Search-Vector_(RAG)-red?style=flat-square" /> <img src="https://img.shields.io/badge/Stack-Postgres_·_Spring_Boot-green?style=flat-square" />

**Persistent architectural memory for AI coding agents.**

- Fixes "AI amnesia": Cursor, Windsurf and Claude log decisions to a shared vault and recall them in later sessions
- Semantic search over architectural decisions, bug fixes and patterns; syncs across IDEs and CI
- Real-time telemetry dashboard with workspace-scoped API keys

[Live app](https://xtracontext.vercel.app/) · [Architecture](https://xtracontext.vercel.app/dashboard/docs)

</td>
<td width="50%" valign="top">

### 🌐 [XtraDevPilot](https://github.com/om0852/XtraDevPilot)
<img src="https://img.shields.io/badge/MCP-Browser_Bridge-818cf8?style=flat-square" /> <img src="https://img.shields.io/badge/Chrome-Manifest_V3-34d399?style=flat-square" /> <img src="https://img.shields.io/badge/Tools-33_verified-brightgreen?style=flat-square" />

**Local-first bridge between your real Chrome and your AI IDE.**

- Connects Claude Desktop, Cursor and Antigravity to the user's authenticated browser over local loopback via MCP
- 33 tools: live DOM extraction, one-click Playwright test synthesis, token-optimized DOM (up to 94% fewer tokens), runtime JS eval
- Code never leaves the machine

[Repo](https://github.com/om0852/XtraDevPilot) · [Portal](https://xtradevpilot.vercel.app/)

</td>
</tr>
</table>

<details>
<summary><b>More projects</b></summary>

- 🎨 **[Multi-UI](https://github.com/om0852/multi-ui)** — 30+ animated, type-safe React components (React 19, Next.js 15, Framer Motion) with live docs
- 👁️ **XtraTyping** — browser typing trainer using MediaPipe face mesh for real-time Eye Aspect Ratio blink detection

</details>

---

## 💼 Experience

| When | Where | What |
|---|---|---|
| **Oct 2026 – Present** | **Creatosaurus** · Software Developer Intern | Back for a second stint on the backend and data-pipeline side |
| **Jul 2026 – Sep 2026** | **ADP India (Fortune 500)** · Software Developer Intern | Production backend services in Python/Pydantic; Agile delivery with Amazon Q, AWS, Jira, Bitbucket |
| **Jul 2025 – Jul 2026** | **Creatosaurus** · Full Stack Developer Intern | Social Listening feature: multi-platform scrapers + Node.js pipelines, 10K+ records/day, AWS EC2 · PM2 · Redis · BullMQ · MongoDB |
| **Oct 2025 – Apr 2026** | **Eqvisor** · Frontend Developer | Investment analytics UI and type-safe component libraries |

```mermaid
timeline
    title Journey
    2021–2024 : Diploma, Sanjivani K.B.P. Polytechnic (93.14%)
    2024–2027 : B.E. Computer Engineering, D.Y. Patil COE (CGPA 9.49)
    2025 : Full Stack Intern, Creatosaurus
    2026 : Founded XtraFusion · SDE Intern, ADP India · back at Creatosaurus
```

---

## 🛠️ Tech stack

<div align="center">

**Languages**
<br>
<img src="https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white" />
<img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black" />
<img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" />
<img src="https://img.shields.io/badge/Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white" />
<img src="https://img.shields.io/badge/Solidity-363636?style=flat-square&logo=solidity&logoColor=white" />

**Backend & Data**
<br>
<img src="https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white" />
<img src="https://img.shields.io/badge/Express-000000?style=flat-square&logo=express&logoColor=white" />
<img src="https://img.shields.io/badge/NestJS-E0234E?style=flat-square&logo=nestjs&logoColor=white" />
<img src="https://img.shields.io/badge/Spring_Boot-6DB33F?style=flat-square&logo=springboot&logoColor=white" />
<img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white" />
<img src="https://img.shields.io/badge/MongoDB-47A248?style=flat-square&logo=mongodb&logoColor=white" />
<img src="https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white" />
<img src="https://img.shields.io/badge/BullMQ-E34234?style=flat-square" />
<img src="https://img.shields.io/badge/WebSockets-010101?style=flat-square&logo=socketdotio&logoColor=white" />

**Frontend**
<br>
<img src="https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black" />
<img src="https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white" />
<img src="https://img.shields.io/badge/Tailwind-06B6D4?style=flat-square&logo=tailwindcss&logoColor=white" />
<img src="https://img.shields.io/badge/Framer_Motion-0055FF?style=flat-square&logo=framer&logoColor=white" />
<img src="https://img.shields.io/badge/Redux-764ABC?style=flat-square&logo=redux&logoColor=white" />

**AI & Developer Tooling**
<br>
<img src="https://img.shields.io/badge/Model_Context_Protocol-8b5cf6?style=flat-square" />
<img src="https://img.shields.io/badge/Vector_Search_/_RAG-ef4444?style=flat-square" />
<img src="https://img.shields.io/badge/AST_Analysis-f59e0b?style=flat-square" />
<img src="https://img.shields.io/badge/Playwright-2EAD33?style=flat-square&logo=playwright&logoColor=white" />
<img src="https://img.shields.io/badge/MediaPipe-0097A7?style=flat-square" />

**Cloud & DevOps**
<br>
<img src="https://img.shields.io/badge/AWS-232F3E?style=flat-square&logo=amazonaws&logoColor=white" />
<img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white" />
<img src="https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white" />
<img src="https://img.shields.io/badge/Vercel-000000?style=flat-square&logo=vercel&logoColor=white" />
<img src="https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white" />

</div>

---

## 🏆 Highlights

- ⚔️ **LeetCode Knight** — rating 1,857, global rank 54,292 / 890,724; 645+ solved (443 E · 166 M · 36 H)
- 🥇 **1st place**, Code War · 🥉 **3rd place**, Techbliz Hackathon · **5th**, Avinay Hackathon (JSPM, Pune)
- ☁️ AWS Cloud Practitioner Essentials
- 📦 Published open-source npm package used with Cursor, Claude Code and VS Code

---

## 📈 GitHub

<div align="center">
  <img height="165" src="https://github-readme-stats.vercel.app/api?username=om0852&show_icons=true&theme=tokyonight&hide_border=true&count_private=true" alt="GitHub stats" />
  <img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=om0852&layout=compact&theme=tokyonight&hide_border=true" alt="Top languages" />
  <br>
  <img src="https://streak-stats.demolab.com?user=om0852&theme=tokyonight&hide_border=true" alt="Streak" />
</div>

---

<div align="center">

### 💬 Let's talk

Real-time pipelines · MCP servers · retrieval for code agents · zero-knowledge secrets

*Shipping > talking. But I do reply to emails.*

**📫 salunkeom474@gmail.com** · [LinkedIn](https://www.linkedin.com/in/om-salunke-81bb63292/) · [Portfolio](https://salunkeom.netlify.app/)

<img src="https://komarev.com/ghpvc/?username=om0852&label=Profile%20Views&color=8b5cf6&style=flat-square" alt="Profile views" />

</div>
