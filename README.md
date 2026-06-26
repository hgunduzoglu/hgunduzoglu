<h1 align="center">Hi, I'm Hüsamettin Gündüzoğlu 👋</h1>

<p align="center">
  Backend-Oriented Full Stack Software Engineer · Product Builder · Industrial Engineering Background
</p>

<p align="center">
  <a href="https://hgunduzoglu.dev">
    <img src="https://img.shields.io/badge/Portfolio-hgunduzoglu.dev-1a2a6c?style=for-the-badge&logo=vercel&logoColor=white" alt="Portfolio — hgunduzoglu.dev" />
  </a>
</p>

<p align="center">
  <a href="mailto:gunduzoglu.husamettin@gmail.com">
    <img src="https://img.shields.io/badge/Email-gunduzoglu.husamettin%40gmail.com-red?style=flat-square&logo=gmail" alt="Email" />
  </a>
  <a href="https://www.linkedin.com/in/hgunduzoglu11/">
    <img src="https://img.shields.io/badge/LinkedIn-Hüsamettin%20Gündüzoğlu-blue?style=flat-square&logo=linkedin" alt="LinkedIn" />
  </a>
  <a href="https://x.com/hgunduzzoglu">
    <img src="https://img.shields.io/badge/X-@hgunduzzoglu-black?style=flat-square&logo=x" alt="X (Twitter)" />
  </a>
</p>

<p align="center">
  My projects and detailed case studies live at <a href="https://hgunduzoglu.dev"><b>hgunduzoglu.dev</b></a> &rarr;
</p>

---

## About

Full stack software engineer with an Industrial Engineering background. I build products end-to-end — backend architecture, data modeling, interfaces, deployment, and iteration based on real usage — with a focus on **backend systems, multi-tenant SaaS, distributed systems, and privacy-aware software design**.

**Focus areas:** API design · multi-tenant SaaS · PostgreSQL modeling · caching & queues · auth / RBAC / audit logging · forecasting & optimization · privacy-preserving verification

---

## Selected Work

### Kalis / Clinix

A SaaS platform for appointment-based businesses and psychology clinics, covering appointment management, customer records, staff roles, payments, audit logging, and AI-assisted operational workflows.

I designed the system as a **modular monolith** instead of starting directly with microservices. Since the product was in an early-stage customer validation phase, this architecture made it easier to move fast, keep deployment simple, preserve transactional consistency, and avoid unnecessary operational overhead.

At the same time, I structured the application around clear domain boundaries such as authentication, tenant management, appointments, customers, staff roles, payments, and audit logs. This keeps the system maintainable today while leaving the option open to extract selected modules into separate services later if scale, team structure, or operational needs require it.

Multi-tenancy and RBAC were central parts of the architecture. Because the platform serves multiple businesses within the same system, I focused on tenant isolation, role-based permissions, secure access control, and auditability from the beginning.

**Focus:** Modular monolith, multi-tenant SaaS, RBAC, PostgreSQL, secure workflows, scalable domain boundaries

---

### Consensus

A survey-based social platform focused on anonymous participation, demographic insights, voting integrity, regional heatmaps, and public discussion around daily questions.

I built Consensus with a **microservice-oriented architecture**. For the initial product scope, this was more complex than strictly necessary, but it was an intentional technical decision. The goal was to reduce future architectural debt while also gaining hands-on experience with service boundaries, independent deployments, inter-service communication, and production-oriented backend design.

The system was designed around separate responsibilities such as identity, voting, questions, comments, notifications, and analytics. This helped me think more clearly about ownership of data, scaling paths, and how different parts of a social product can evolve independently.

A key challenge was balancing anonymous participation with voting integrity. I worked on mechanisms such as device-level uniqueness, demographic segmentation, and privacy-aware participation flows so users could vote anonymously while the system could still protect against duplicate or manipulated votes.

**Focus:** Microservices, anonymous voting, backend architecture, voting integrity, privacy-aware product design

---

### Warehouse Decision Support System

A data-driven decision support system for e-commerce warehouse operations, including demand forecasting, ABC classification, replenishment planning, and operational optimization.

This project combined my Industrial Engineering background with software development. I worked on forecasting demand, classifying products by operational importance, and supporting inventory and replenishment decisions through data-driven models.

The system was designed to support operational decision-making rather than only produce predictions. This made the project especially valuable from a systems perspective: the goal was to connect forecasting outputs with warehouse processes, inventory priorities, and practical planning constraints.

**Focus:** Forecasting, operations research, inventory planning, decision support systems

---

### Magna

A zk-based verification layer for privacy-preserving digital trust.

Magna enables users to prove selected claims, ownership, or eligibility without exposing unnecessary private data. Instead of requiring applications to directly access sensitive information, Magna explores how zero-knowledge proofs can act as a verification layer between users and platforms.

I designed the project around a simple idea: verification should be possible without over-disclosure. The architecture focuses on separating the claim, proof generation, verification flow, and application integration layers so that the system can be extended to different use cases over time.

This project helped me work more deeply with zero-knowledge concepts from a product and infrastructure perspective, not only as a cryptographic primitive but as a developer-facing verification system.

**Focus:** Zero-knowledge proofs, privacy-preserving verification, trust infrastructure, developer-facing protocols

> Most of my recent work lives in private repositories. I can discuss architecture decisions, trade-offs, and implementation details in conversation.

---

## Tech Stack

### Languages

<p>
  <img src="https://skillicons.dev/icons?i=ts,js,go,python,rust,php,java,dart&theme=dark" alt="TypeScript, JavaScript, Go, Python, Rust, PHP, Java, Dart" />
</p>

### Backend

<p>
  <img src="https://skillicons.dev/icons?i=nodejs,nestjs,express,spring,flask,laravel,prisma&theme=dark" alt="Node.js, NestJS, Express, Spring, Flask, Laravel, Prisma" />
</p>

### Frontend & Mobile

<p>
  <img src="https://skillicons.dev/icons?i=react,nextjs,tailwind,flutter,html,css&theme=dark" alt="React, Next.js, Tailwind CSS, Flutter, HTML, CSS" />
</p>

### Databases

<p>
  <img src="https://skillicons.dev/icons?i=postgres,mysql,mongodb,redis&theme=dark" alt="PostgreSQL, MySQL, MongoDB, Redis" />
</p>

### Platform & Operations

<p>
  <img src="https://skillicons.dev/icons?i=docker,kubernetes,nginx,aws,vercel,cloudflare,githubactions,linux,bash,kafka,prometheus,grafana&theme=dark" alt="Docker, Kubernetes, Nginx, AWS, Vercel, Cloudflare, GitHub Actions, Linux, Bash, Kafka, Prometheus, Grafana" />
</p>

### Data, AI & Optimization

<p>
  <img src="https://skillicons.dev/icons?i=sklearn,pytorch,tensorflow&theme=dark" alt="scikit-learn, PyTorch, TensorFlow" />
</p>

### Blockchain & Privacy

<p>
  <img src="https://skillicons.dev/icons?i=solidity&theme=dark" alt="Solidity" />
</p>

### Tools

<p>
  <img src="https://skillicons.dev/icons?i=git,github,vscode,figma,postman&theme=dark" alt="Git, GitHub, VS Code, Figma, Postman" />
</p>

---

## Community & Open Work

**[metu-non.tech](https://metu-non.tech)** — A tool I built from scratch that lets METU students browse all Non-Technical Elective courses in one place instead of digging through scattered department pages. *Creator and maintainer.*

**[robotdegilim.xyz](https://robotdegilim.xyz)** — A schedule-building tool that helps METU students plan course selection before registration. *Maintainer and contributor.*

**METU Istanbul Alumni Association** — Adapted a JavaScript reference theme into a custom WordPress theme for the association's official site, restructuring content for events, announcements, and alumni info. *WordPress customization and content redesign.*

---

## 2026 GitHub Contribution Challenge

A **365/365 contribution challenge for 2026** — staying consistent by building, refactoring, documenting, and experimenting throughout the year. The goal is quality of work, not commit count.

---

## GitHub Overview

<p align="center">
  <img 
    src="https://github-readme-stats-sable-two-39.vercel.app/api?username=hgunduzoglu&show_icons=true&hide_border=true&theme=tokyonight&include_all_commits=true&count_private=true" 
    height="165"
    alt="Hüsamettin's GitHub statistics"
  />
  <img 
    src="https://github-readme-stats-sable-two-39.vercel.app/api/top-langs/?username=hgunduzoglu&layout=compact&langs_count=8&hide_border=true&theme=tokyonight&hide=html,css,scss" 
    height="165"
    alt="Most used languages"
  />
</p>

<p align="center">
  <img 
    src="https://github-readme-activity-graph.vercel.app/graph?username=hgunduzoglu&theme=tokyo-night&hide_border=true&area=true&custom_title=Contribution%20Activity"
    width="95%"
    alt="Contribution activity graph"
  />
</p>

---

<p align="center">
  Open to backend &amp; full-stack engineering opportunities · <a href="https://hgunduzoglu.dev">hgunduzoglu.dev</a>
</p>

<p align="center">
  <i>Building secure, scalable, and product-oriented software — with an engineer's mindset for systems and outcomes.</i>
</p>
