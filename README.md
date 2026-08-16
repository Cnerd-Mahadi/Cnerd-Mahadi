<h1 align="center">Hi, I'm Mahadi 👋</h1>

<p align="center">
  Full-Stack AI Engineer &nbsp;·&nbsp; Dhaka, Bangladesh
</p>

<p align="center">
  <a href="https://cnerdfolio.vercel.app"><img src="https://img.shields.io/badge/Portfolio-000000?style=for-the-badge&logo=vercel&logoColor=white" alt="Portfolio" /></a>
  <a href="https://linkedin.com/in/cnerd-mahadi"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>
  <a href="mailto:mahadidroid@gmail.com"><img src="https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" /></a>
</p>

---

I build AI-powered products end to end, from schema design through to the UI.

Most of my work sits in the backend: async job systems, payment and refund flows, financial correctness in ledger systems, and third-party integrations. I've owned SaaS products from the first migration to the last screen.

On the AI side I work with LLM APIs and build RAG pipelines on top of vector search.

---

## 💼 Things I've worked on

**Bevy Commerce** &nbsp;·&nbsp; *Full Stack Developer, 2024 – present*

- Owned an affiliate payout platform end to end. Took the balance ledger from full scans to a denormalized column with nightly reconciliation, and redesigned a recommendation pipeline from one long job into a per-shop fan-out that survives failure.
- Built a shared PDF pipeline for sales orders, invoices, POs, and quotes, then split the rendering into its own service running headless Chromium through Playwright.
- Own the UX direction for orders and purchase orders, deciding the interface design and guiding the team on implementation.

**AISEO.ai** &nbsp;·&nbsp; *Full Stack Developer Associate, 2023 – 2024*

- Worked on AI content generation tools, moving the product frontend from vanilla JavaScript to a modular Next.js architecture.

---

## 🛠 Tech I work with

**Languages**

<p>
  <img src="https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white" alt="TypeScript" />
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black" alt="JavaScript" />
  <img src="https://img.shields.io/badge/SQL-4479A1?style=flat-square&logo=postgresql&logoColor=white" alt="SQL" />
</p>

**Frontend**

<p>
  <img src="https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black" alt="React" />
  <img src="https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white" alt="Next.js" />
  <img src="https://img.shields.io/badge/Remix-000000?style=flat-square&logo=remix&logoColor=white" alt="Remix" />
  <img src="https://img.shields.io/badge/Tailwind-06B6D4?style=flat-square&logo=tailwindcss&logoColor=white" alt="Tailwind CSS" />
</p>

**Backend**

<p>
  <img src="https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white" alt="Node.js" />
  <img src="https://img.shields.io/badge/Express-000000?style=flat-square&logo=express&logoColor=white" alt="Express" />
  <img src="https://img.shields.io/badge/Prisma-2D3748?style=flat-square&logo=prisma&logoColor=white" alt="Prisma" />
  <img src="https://img.shields.io/badge/GraphQL-E10098?style=flat-square&logo=graphql&logoColor=white" alt="GraphQL" />
  <img src="https://img.shields.io/badge/BullMQ-DD2C00?style=flat-square&logo=redis&logoColor=white" alt="BullMQ" />
  <img src="https://img.shields.io/badge/QStash-00E9A3?style=flat-square&logo=upstash&logoColor=black" alt="Upstash QStash" />
</p>

**Databases**

<p>
  <img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white" alt="PostgreSQL" />
  <img src="https://img.shields.io/badge/MongoDB-47A248?style=flat-square&logo=mongodb&logoColor=white" alt="MongoDB" />
  <img src="https://img.shields.io/badge/Redis-FF4438?style=flat-square&logo=redis&logoColor=white" alt="Redis" />
  <img src="https://img.shields.io/badge/Firebase-DD2C00?style=flat-square&logo=firebase&logoColor=white" alt="Firebase" />
</p>

**Cloud & DevOps**

<p>
  <img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white" alt="Docker" />
  <img src="https://img.shields.io/badge/Heroku-430098?style=flat-square&logo=heroku&logoColor=white" alt="Heroku" />
  <img src="https://img.shields.io/badge/GitHub%20Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white" alt="GitHub Actions" />
</p>

**AI**

<p>
  <img src="https://img.shields.io/badge/Vercel%20AI%20SDK-000000?style=flat-square&logo=vercel&logoColor=white" alt="Vercel AI SDK" />
  <img src="https://img.shields.io/badge/Gemini-8E75B2?style=flat-square&logo=googlegemini&logoColor=white" alt="Google Gemini" />
  <img src="https://img.shields.io/badge/pgvector-4169E1?style=flat-square&logo=postgresql&logoColor=white" alt="pgvector" />
  <img src="https://img.shields.io/badge/Claude-D97757?style=flat-square&logo=claude&logoColor=white" alt="Claude" />
  <img src="https://img.shields.io/badge/Cursor-000000?style=flat-square&logo=cursor&logoColor=white" alt="Cursor" />
</p>

---

## 🚀 Things I've built

### [LITOL](https://github.com/Cnerd-Mahadi/litol_app) &nbsp;·&nbsp; [🌐](https://litol.vercel.app)

An AI study platform used by 60+ students. You write notes with recall cues and get quizzes generated from your own material. Cues are embedded into pgvector and pulled back by similarity search, so the model asks about what you actually wrote instead of what it happens to know.

`Next.js` `TypeScript` `Prisma` `PostgreSQL` `pgvector` `Vercel AI SDK` `Gemini` `Bun`

### [BeatRos](https://github.com/Cnerd-Mahadi/BeatRos) &nbsp;·&nbsp; [🌐](https://beatros.vercel.app)

A microservices e-commerce platform. Four services behind an API gateway, Stripe checkout with webhook verification, and guest carts that survive across sessions. Stock release and confirmation emails run as background jobs, so checkout stays fast.

`Next.js` `Express` `TypeScript` `Prisma` `PostgreSQL` `Redis` `Stripe` `Docker`

---

<p align="center">
  Open to remote roles. Happy to talk about anything above.
</p>
