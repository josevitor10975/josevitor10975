> ⚠️ **Notice to new followers:** this is now my **primary** GitHub account. I lost access to my previous account ([@josevitor555](https://github.com/josevitor555)) due to an MFA issue. This account ([@josevitor10975](https://github.com/josevitor10975)) carries forward the work I was doing there — **the goal is not to migrate or recreate the old repositories here**, except when it makes sense in the context of shipping a new feature update to one of those projects.

# Hi, I'm José Vitor

### Full-Stack Developer | TypeScript, NestJS, Next.js and AI Engineering

I build modern web applications by combining modular backend architecture, responsive interfaces and AI-powered features — with a particular focus on provider-agnostic AI integration: designing systems where models and providers can be evaluated or swapped without rewriting the application around them.

🎓 Undergraduate thesis graded **10/9.75** · 🏆 IAArena selected in the **top 200 of Centelha PI**

<p align="left">
  <a href="https://linkedin.com/in/josé-vitor-sousa2003" target="_blank">
    <img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" />
  </a>
  <a href="mailto:josevitordesousa123@gmail.com">
    <img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" />
  </a>
  <a href="https://github.com/josevitor555" target="_blank">
    <img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white" alt="GitHub" />
  </a>
</p>

---

## Contents

- [About Me](#about-me)
- [Featured Projects](#featured-projects)
- [Technical Stack](#technical-stack)
- [AI & LLM Experience](#ai--llm-experience)
- [Current Learning Focus](#current-learning-focus)
- [GitHub Activity](#github-activity)
- [YouTube — IAArena Development](#youtube--iaarena-development)
- [Contact](#contact)

---

## About Me

My journey in web development began in 2019. Since then, I've worked on projects involving authentication, payment processing, relational and vector databases, REST APIs, semantic retrieval and generative AI — both in solo commercial work and in academic research.

I'm currently pursuing a degree in **Systems Analysis and Development at IFPI**, where my undergraduate thesis — a gamified AI tutoring platform using a dual-layer RAG architecture — was graded **10/10**.

My current technical focus sits across four areas:

* **Backend Engineering** — modular APIs with NestJS, Django, Prisma and PostgreSQL
* **Frontend Development** — responsive applications with React, Next.js and TypeScript
* **AI Engineering** — RAG pipelines, embeddings, vector search and LLM integrations
* **Software Quality** — testing, maintainability, documentation and deployment workflows

---

## Featured Projects

### NovaVisionHub

**Commercial SaaS platform for video editors, motion designers and digital creators — live in production.**

Built and operated end-to-end as **Solo Full-Stack Developer**, from feature implementation through production infrastructure.

**Engineering highlights:**

* Migrated binary image assets from MongoDB to AWS S3 — a **~99.95% reduction** in database storage for the Assets collection
* Diagnosed and fixed a MongoDB race condition on `CreditCycle` documents, resolved with a unique index
* Implemented a three-tier credit billing system (FREE, START, CREATOR) with Stripe, including webhook routing across environments
* Configured cross-origin session cookies, Hostinger DNS, and Google OAuth via Passport.js for production deployment
* Built a `SmartUpgradeModal` with onboarding-based personalization to drive tier upgrades
* Resolved a Zustand store sync issue following Stripe checkout and a `manageableStatuses` reference error

**Stack:** React, TypeScript, Tailwind CSS, Node.js, MongoDB, Stripe, AWS S3

**Status:** Live (Production) · [novavisionhub.com](https://www.novavisionhub.com/home)

---

### IAArena

**AI-mediated debate, learning and critical-thinking platform — selected in the top 200 of Centelha PI.**

IAArena goes beyond a conventional chatbot experience, creating an environment where users engage with AI through structured debates, argumentation and reasoning-oriented activities.

**Main features:**

* AI-mediated conversations and debates
* Persistent user sessions with authentication and data management
* Responsive interface, deployed to production

**Stack:** Next.js, TypeScript, Tailwind CSS, Supabase

[Landing Page](https://portolio-iaarena.onrender.com/) · [YouTube dev log](https://www.youtube.com/@IAArena-b8b)

---

### SQLAIGen

**Natural-language-to-SQL generation using RAG and vector similarity search.**

Converts natural-language requests into SQL by retrieving relevant database-schema context before generating the final query, using vector embeddings and semantic similarity to identify the most relevant schema elements per request.

**Main features:**

* Schema-aware semantic retrieval (Retrieval-Augmented Generation)
* Vector similarity search with PGVector, 1024-dimensional embeddings
* Contextual prompt enrichment before generation

**Stack:** React, TypeScript, AdonisJS, Supabase, PostgreSQL, PGVector, Mistral AI

[View Repository](https://github.com/josevitor555/SQLAIGen.git)

---

### Solar E-commerce

**Full-stack e-commerce application with Stripe payment integration.**

An e-commerce platform for solar-energy products, combining a React interface with a Django backend, user authentication, relational data persistence and online payment processing.

**Main features:**

* User registration, authentication and product catalog
* Full checkout workflow with Stripe payment integration
* PostgreSQL persistence with clean frontend/backend separation

**Stack:** Django, Python, React, TypeScript, PostgreSQL, Stripe

[View Repository](https://github.com/josevitor555/SolarProject_Stripe.git)

---

### Black Thunder

**Frontend application focused on visual identity, branding and interface engineering.**

Explores the relationship between software development and digital brand identity through a responsive, visually distinctive interface.

**Main features:**

* Component-based frontend architecture with custom visual identity
* SCSS styling and interface/branding experimentation

**Stack:** React, Vite, SCSS, UX/UI Design

[View Repository](https://github.com/josevitor555/black_thunder.git)

---

## Technical Stack

### Backend and APIs

<p align="left">
  <img src="https://img.shields.io/badge/NestJS-E0234E?style=flat-square&logo=nestjs&logoColor=white" alt="NestJS" />
  <img src="https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white" alt="Node.js" />
  <img src="https://img.shields.io/badge/Django-092E20?style=flat-square&logo=django&logoColor=white" alt="Django" />
  <img src="https://img.shields.io/badge/REST_APIs-005571?style=flat-square" alt="REST APIs" />
</p>

NestJS and Node.js · Django and Python · REST API development · dependency injection and modular architecture · authentication/authorization with JWT and password hashing · integration with external services and LLM APIs

### Frontend

<p align="left">
  <img src="https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB" alt="React" />
  <img src="https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white" alt="Next.js" />
  <img src="https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white" alt="TypeScript" />
  <img src="https://img.shields.io/badge/Tailwind_CSS-06B6D4?style=flat-square&logo=tailwindcss&logoColor=white" alt="Tailwind CSS" />
</p>

React and Next.js · TypeScript · component-based, responsive/mobile-first interfaces · server-side rendering and static generation · Tailwind CSS and SCSS

### Databases and Data Access

<p align="left">
  <img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white" alt="PostgreSQL" />
  <img src="https://img.shields.io/badge/MongoDB-47A248?style=flat-square&logo=mongodb&logoColor=white" alt="MongoDB" />
  <img src="https://img.shields.io/badge/Supabase-3FCF8E?style=flat-square&logo=supabase&logoColor=white" alt="Supabase" />
  <img src="https://img.shields.io/badge/Prisma-2D3748?style=flat-square&logo=prisma&logoColor=white" alt="Prisma" />
</p>

PostgreSQL, MySQL and MongoDB · Supabase · Prisma ORM · relational and NoSQL document modeling · database migrations · vector databases, PGVector and similarity search

### AI Engineering

<p align="left">
  <img src="https://img.shields.io/badge/RAG-Retrieval_Augmented_Generation-blueviolet?style=flat-square" alt="RAG" />
  <img src="https://img.shields.io/badge/LangChain-1C3C3C?style=flat-square&logo=langchain&logoColor=white" alt="LangChain" />
  <img src="https://img.shields.io/badge/LLM_APIs-412991?style=flat-square" alt="LLM APIs" />
</p>

Retrieval-Augmented Generation · embeddings and semantic search · vector similarity retrieval · LangChain · multi-provider LLM API integration · Model Context Protocol fundamentals · agentic workflow experimentation

### Tools and Infrastructure

<p align="left">
  <img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white" alt="Docker" />
  <img src="https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white" alt="Git" />
  <img src="https://img.shields.io/badge/Jest-C21325?style=flat-square&logo=jest&logoColor=white" alt="Jest" />
</p>

Git and GitHub · Docker and containerized environments · Jest and unit testing · Postman and API testing · Render and Vercel deployments · agile workflows (Scrum/Kanban)

---

## AI & LLM Experience

I use language models as components inside software systems rather than only as conversational tools — my projects explore how models interact with application data, retrieve context, generate structured outputs, and support users through specialized interfaces.

I've integrated APIs and tools from OpenAI, Google, Anthropic, Mistral AI, Meta, DeepSeek, Alibaba Cloud, and Moonshot AI. My interest isn't tied to any specific model version — I focus on architectures where providers and models can be evaluated or replaced without rewriting the application.

| Area | Current Focus | Goal |
|---|---|---|
| **AI Engineering** | RAG, MCP, agentic workflows, structured outputs | Context-aware systems with reliable tool/data integration |
| **Backend Architecture** | NestJS, modular design, queues, distributed systems | Scalability, maintainability, fault isolation |
| **Frontend Architecture** | Next.js, advanced TypeScript, rendering strategies | Faster, more maintainable UIs |
| **DevOps** | Docker, CI/CD, deployment automation | Reliable delivery and infra management |
| **Software Quality** | Unit/integration tests, observability | Fewer regressions, higher reliability |
| **Web Quality** | Accessibility, SEO, performance | Applications optimized for users and production |

---

## GitHub Activity

<p align="left">
  <a href="https://github.com/josevitor10975">
    <img src="https://github-readme-streak-stats.herokuapp.com?user=josevitor10975&theme=dracula&hide_border=true" alt="GitHub Streak" />
  </a>
</p>

---

## YouTube — IAArena Development

I share development progress, technical experiments and project updates related to IAArena. Content is primarily in Brazilian Portuguese.

[Visit the IAArena YouTube Channel](https://www.youtube.com/@IAArena-b8b)

---

## Contact

I'm currently interested in opportunities where I can contribute to full-stack applications while expanding my experience with **TypeScript, NestJS, Next.js, AI Engineering and DevOps**.

* [LinkedIn](https://linkedin.com/in/josé-vitor-sousa2003)
* [GitHub](https://github.com/josevitor555)
* [Email](mailto:josevitordesousa123@gmail.com)
* [Dribbble](https://dribbble.com/kral123)

---

![GitHub contribution snake animation](https://raw.githubusercontent.com/josevitor10975/josevitor10975/output/github-contribution-grid-snake-dark.svg?v=1)
