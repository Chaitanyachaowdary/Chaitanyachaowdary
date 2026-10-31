<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0f172a,50:1d4ed8,100:06b6d4&height=200&section=header&text=Chaitanya%20Yelamasetty&fontSize=56&fontColor=ffffff&animation=fadeIn&desc=AI-native%20full-stack%20engineer%20%E2%80%A2%20TypeScript%20%E2%80%A2%20Node.js%20%E2%80%A2%20React%20%E2%80%A2%20PostgreSQL&descSize=20&fontAlignY=38&descAlignY=58" alt="Chaitanya Yelamasetty, AI-native full-stack engineer" width="100%" />

<a href="https://git.io/typing-svg"><img src="https://readme-typing-svg.demolab.com/?font=Fira+Code&weight=500&size=19&pause=1200&color=38BDF8&center=true&vCenter=true&width=860&height=45&lines=Building+AI+agent+products%3A+DevOps%2C+security%2C+audits%2C+job+search;I+ship+production+software+with+AI+agents%2C+every+day;Offline-first%2C+accessible+apps+used+by+blind+field+officers;Open+to+full-stack+%2F+AI-engineering+roles%2C+Bengaluru+or+remote" alt="Typing banner" /></a>

<p>
  <a href="https://chaitanya.veltore.co.in"><img src="https://img.shields.io/badge/Portfolio-0f172a?style=for-the-badge&logo=googlechrome&logoColor=white" alt="Portfolio" /></a>
  <a href="https://www.linkedin.com/in/chaitanya-yelamasetty"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>
  <a href="mailto:chaitanyachowdary4e3@gmail.com"><img src="https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" /></a>
  <img src="https://img.shields.io/badge/Bengaluru%2C%20India-14b8a6?style=for-the-badge&logo=googlemaps&logoColor=white" alt="Bengaluru, India" />
  <img src="https://img.shields.io/badge/Open%20to%20work-22c55e?style=for-the-badge&logo=checkmarx&logoColor=white" alt="Open to work" />
</p>

</div>

## 👋 About me

**Full-stack engineer building AI agent products (DevOps, audits, job search) and shipping offline-first, accessible software in TypeScript, Node.js, React and PostgreSQL.** 2.8 years in production work, Bengaluru, India.

- 🔭 **Currently:** building **GarvSe 2.0**, a monitoring, evaluation and learning platform used by disability-inclusion field teams across India (CodeSage India, deployed to EnableIndia)
- 🛠️ **Also building AI agent products:** a DevOps and security-architect agent (Kanna DevOps Agent) that reviews infrastructure and runs read-only diagnostics, a job-application agent, a data-deletion audit agent, and an HRMS with a local AI assistant; all local-model first, all with human approval before any irreversible action
- 🤖 **How I work:** Claude Code for implementation, refactors, audits and tests, with the test suite and code review as the gate; local models through Ollama where data must stay on the machine
- 🌱 **Learning:** AI safety and control for coding agents; Rust through Tauri
- 💬 **Open to:** full-stack, backend, platform or AI-engineering roles in Bengaluru, Hyderabad or remote

## 🧊 A year of commits, in 3D

<div align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="./profile-3d-contrib/profile-night-rainbow.svg" />
    <source media="(prefers-color-scheme: light)" srcset="./profile-3d-contrib/profile-season-animate.svg" />
    <img src="./profile-3d-contrib/profile-night-rainbow.svg" alt="3D contribution calendar for the last twelve months" width="100%" />
  </picture>
</div>

<sub>Regenerated nightly by a GitHub Action; private contributions are counted without exposing repository names.</sub>

## 🤖 How I work in the AI era

| What | How I do it |
|---|---|
| **Agentic coding** | Claude Code is my primary implementation partner. I specify, it drafts, I review every diff, run the suites (2,100+ backend and 4,200+ frontend tests on my current project) and own what ships. |
| **Audits at scale** | Used an agent to audit our sync, upload and access-control paths: 20 verified defects with file and line references, all fixed, tested and ticketed across two repositories in one day. |
| **Local models** | Ollama (Qwen) for tooling that handles personal or client data, so nothing leaves the machine. |
| **AI features in product** | Shipped LLM-backed text simplification and a voice assistant in a production accessibility widget, and an AI-assisted KYC demo. |
| **Guard-rails** | Every agent I build stops for human review before any irreversible action, keeps an audit log and must trace each output back to a source. |

## 🚀 What I have built

### GarvSe 2.0 / MEL platform

Production system for 45 centres across 10 states and 2 union territories; many of its daily users are blind field officers.

- React 19 + TypeScript front end, Node.js (Hono) APIs on PostgreSQL 17 with Drizzle ORM, Redis and BullMQ jobs, S3 behind access-control middleware
- Offline-first desktop, Android and iOS builds with Tauri: a local SQLite mirror and a sync queue that survives poor connectivity, with idempotent replays, per-row failure handling and tombstones for server-side deletes
- WCAG 2.2 AA from the first sprint, verified with NVDA and TalkBack
- 369 merged pull requests across 6 repositories, 83 of 158 database migrations, and the production migration of 5,131 candidates from the legacy system with counts reconciled one by one
- CI/CD on GitHub Actions, Docker and Nginx on EC2, first Play Store and TestFlight releases, root-cause fixes for production incidents (a 21-minute outage, Postgres JIT slow pages, a 3-day email outage)

That code lives in a private company organisation, so it is not on this profile. The projects below are my own.

### AI agents and tools (private repositories, happy to walk through them)

| Project | What it does | Stack |
|---|---|---|
| **job-apply-agent** | Finds remote roles, tailors a resume with a local model, fills applications from a fixed profile and stops for human approval before any submit; outreach and a review dashboard | Python, Playwright, Ollama (qwen3) |
| **ghost-data-audit-agent** | Evidence-grounded agent that proves whether personal data was really deleted; orchestrated local agents, 99.2% step F1 on samples (HackerRank Orchestrate, Oct 2026) | Python, Ollama |
| **kanna-devops-agent** | Personal DevOps mentor and security-architect agent: reviews infrastructure, runs read-only diagnostics, secret scanning and posture reviews with a defence-in-depth model | Agents, read-only tooling |
| **humara-hrms** | Multi-tenant, India-first HRMS with a local Ollama assistant in development | Next.js, NestJS, Prisma |

### Open projects

| Project | What it does | Stack |
|---|---|---|
| [SahajLoan](https://github.com/Chaitanyachaowdary/SahajLoan) | Accessible loan-application and KYC demo (WCAG 2.2 AA) with privacy-safe AI helpers; the model only ever sees a mismatch category, never a name. Razorpay × Replit Buildathon, Sep 2026 | JavaScript, AI APIs |
| [Kanna](https://github.com/Chaitanyachaowdary/Kanna) | Native Android AI assistant: wake-word listening, Gemini-backed replies, encrypted Room history with the key in the Android keystore | Kotlin, Jetpack Compose |
| [TINYLINK](https://github.com/Chaitanyachaowdary/TINYLINK) | URL shortener with a link dashboard and per-link stats, [live on Vercel](https://tinylink-phi.vercel.app) | Next.js, TypeScript, PostgreSQL, Tailwind |
| [omnify-blog-fullstack](https://github.com/Chaitanyachaowdary/omnify-blog-fullstack) | Full-stack blog app with separate backend and frontend, [live on Vercel](https://omnify-blog-fullstack.vercel.app) | TypeScript, Node.js, React |
| [EnableU](https://github.com/Chaitanyachaowdary/EnableU) | Accessibility-first learning platform: dyslexia-friendly typography, AA contrast modes, full keyboard navigation, reduced motion | React, Node.js, Python (Flask) |
| [easyq-qa-service](https://github.com/Chaitanyachaowdary/easyq-qa-service) | AI-powered question and answer backend | Java, Spring Boot |

## 🛠️ Stack

<div align="center">

**Languages**<br/>
<a href="https://skillicons.dev"><img src="https://skillicons.dev/icons?i=ts,js,python,java,kotlin,postgres&theme=dark" alt="TypeScript, JavaScript, Python, Java, Kotlin, PostgreSQL" /></a>

**Backend and frontend**<br/>
<a href="https://skillicons.dev"><img src="https://skillicons.dev/icons?i=nodejs,nestjs,express,react,nextjs,vite,tailwind,redis,sqlite,tauri,rust,spring,fastapi&theme=dark" alt="Node.js, NestJS, Express, React, Next.js, Vite, Tailwind, Redis, SQLite, Tauri, Rust, Spring, FastAPI" /></a>

**Infra, AI and tools**<br/>
<a href="https://skillicons.dev"><img src="https://skillicons.dev/icons?i=docker,nginx,aws,githubactions,cloudflare,git,linux,androidstudio&theme=dark" alt="Docker, Nginx, AWS, GitHub Actions, Cloudflare, Git, Linux, Android Studio" /></a>

</div>

Also: Hono, Drizzle ORM, Zod, BullMQ, TanStack Router, shadcn/ui, Playwright, Vitest, Claude Code, Ollama, accessibility testing with NVDA and TalkBack.

<div align="center">
<img src="https://capsule-render.vercel.app/api?type=waving&color=0:06b6d4,50:1d4ed8,100:0f172a&height=120&section=footer" alt="" width="100%" />
</div>
