# Hi, I'm Chaitanya Yelamasetty

**Full-stack engineer building offline-first, accessible web and mobile products in TypeScript, Node.js, React and PostgreSQL.** Bengaluru, India. 2.8 years in production work.

- 🔭 **Currently:** building [GarvSe 2.0](#garvse-20--mel-platform), a monitoring, evaluation and learning platform used by disability-inclusion field teams across India (CodeSage India, deployed to EnableIndia)
- 🤖 **Working style:** AI-assisted development every day (Claude Code, local models with Ollama), with the test suite and code review as the gate
- 🌱 **Learning:** AI safety and control for coding agents; Rust through Tauri
- 💬 **Open to:** full-stack, backend or platform roles in Bengaluru, Hyderabad or remote

## What I have built

### GarvSe 2.0 / MEL platform

Production system for 45 centres across 10 states and 2 union territories; many of its daily users are blind field officers.

- React 19 + TypeScript front end, Node.js (Hono) APIs on PostgreSQL 17 with Drizzle ORM, Redis and BullMQ jobs, S3 behind access-control middleware
- Offline-first desktop, Android and iOS builds with Tauri: a local SQLite mirror and a sync queue that survives poor connectivity, with idempotent replays, per-row failure handling and tombstones for server-side deletes
- WCAG 2.2 AA from the first sprint, verified with NVDA and TalkBack
- 369 merged pull requests across 6 repositories, 83 of 158 database migrations, and the production migration of 5,131 candidates from the legacy system with counts reconciled one by one
- CI/CD on GitHub Actions, Docker and Nginx on EC2, first Play Store and TestFlight releases, root-cause fixes for production incidents (a 21-minute outage, Postgres JIT slow pages, a 3-day email outage)

That code lives in a private company organisation, so it is not on this profile. The projects below are my own.

### Own projects

| Project | What it does | Stack |
|---|---|---|
| [SahajLoan](https://github.com/Chaitanyachaowdary/SahajLoan) | Accessible loan-application and KYC demo (WCAG 2.2 AA) with privacy-safe AI helpers, built for the Razorpay × Replit Buildathon, Sep 2026 | JavaScript, AI APIs |
| [TINYLINK](https://github.com/Chaitanyachaowdary/TINYLINK) | URL shortener with a link dashboard, [live on Vercel](https://tinylink-phi.vercel.app) | Next.js, TypeScript, PostgreSQL, Tailwind |
| [omnify-blog-fullstack](https://github.com/Chaitanyachaowdary/omnify-blog-fullstack) | Full-stack blog app with separate backend and frontend, [live on Vercel](https://omnify-blog-fullstack.vercel.app) | TypeScript, Node.js, React |
| [Kanna](https://github.com/Chaitanyachaowdary/Kanna) | AI assistant Android app | Kotlin |
| [easyq-qa-service](https://github.com/Chaitanyachaowdary/easyq-qa-service) | AI-powered question and answer backend | Java, Spring Boot |
| job-apply-agent (private) | Local-model agent that fills job applications from a fixed profile and stops for human review before any submit | Python, Playwright, Ollama |

## Stack

- **Languages:** TypeScript, JavaScript, Python, Java, SQL
- **Backend:** Node.js (Hono, NestJS, Express), PostgreSQL, Drizzle ORM, Redis, BullMQ, REST APIs, Spring Boot
- **Frontend and apps:** React 19, TanStack Router, Vite, Next.js, Tauri (desktop, Android, iOS), SQLite, accessibility (WCAG 2.2)
- **Infra:** Docker, Nginx, AWS (EC2, S3, IAM), GitHub Actions, Cloudflare

## Contact

[Portfolio](https://chaitanya.veltore.co.in) · [LinkedIn](https://www.linkedin.com/in/chaitanya-yelamasetty) · chaitanyachowdary4e3@gmail.com

![Chaitanya's GitHub stats](https://github-readme-stats.vercel.app/api?username=Chaitanyachaowdary&show_icons=true&theme=github_dark&hide_border=true&count_private=true&include_all_commits=true&cache_seconds=86400)
