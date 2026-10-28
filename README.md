<div align="center">

# Hi, I'm Valentino Berdini 👋

### Junior Full Stack Developer (backend-focused) | Node.js · TypeScript · Java · Spring Boot · PostgreSQL · Docker

Henry Fullstack Developer graduate based in Bahía Blanca, Argentina. I design REST APIs, model relational data and test what I build.
I ship complete applications end to end, from the database to deployment, and I'm looking for my first position as a backend or full stack junior developer (remote).

[![LinkedIn](https://img.shields.io/badge/-LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/valenberdini/)
[![Email](https://img.shields.io/badge/-Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:vaberdini@gmail.com)

</div>

---

## 🛠️ Stack

**Backend** &nbsp;
![Node.js](https://img.shields.io/badge/-Node.js-339933?style=flat&logo=node.js&logoColor=white)
![Express](https://img.shields.io/badge/-Express-000000?style=flat&logo=express&logoColor=white)
![TypeScript](https://img.shields.io/badge/-TypeScript-3178C6?style=flat&logo=typescript&logoColor=white)
![Java](https://img.shields.io/badge/-Java%2021-ED8B00?style=flat&logo=openjdk&logoColor=white)
![Spring Boot](https://img.shields.io/badge/-Spring%20Boot-6DB33F?style=flat&logo=springboot&logoColor=white)

**Data & Cloud** &nbsp;
![PostgreSQL](https://img.shields.io/badge/-PostgreSQL-4169E1?style=flat&logo=postgresql&logoColor=white)
![Firebase](https://img.shields.io/badge/-Firebase-FFCA28?style=flat&logo=firebase&logoColor=black)
![AWS SES](https://img.shields.io/badge/-AWS%20SES-232F3E?style=flat&logo=amazonaws&logoColor=white)

**Testing & DevOps** &nbsp;
![Vitest](https://img.shields.io/badge/-Vitest-6E9F18?style=flat&logo=vitest&logoColor=white)
![JUnit](https://img.shields.io/badge/-JUnit%205-25A162?style=flat&logo=junit5&logoColor=white)
![Docker](https://img.shields.io/badge/-Docker-2496ED?style=flat&logo=docker&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/-GitHub%20Actions-2088FF?style=flat&logo=githubactions&logoColor=white)

**Frontend & Mobile** &nbsp;
![React](https://img.shields.io/badge/-React-61DAFB?style=flat&logo=react&logoColor=black)
![Vite](https://img.shields.io/badge/-Vite-646CFF?style=flat&logo=vite&logoColor=white)
![Capacitor](https://img.shields.io/badge/-Capacitor-119EFF?style=flat&logo=capacitor&logoColor=white)

**Also** &nbsp; REST APIs · JWT authentication · SQL (explicit queries with `pg` in Node, JPA/Hibernate + Flyway in Java) · Integration testing with Testcontainers · Git & Pull Requests · AI-assisted development (I always review and validate what it generates) · English C2 (EF SET)

---

## 🚀 Featured Projects

### 📅 [Reservas API: Booking Service with Java + Spring Boot](https://github.com/valenberdev/reservas-spring-boot)
REST API to book resources (courts, rooms, time slots) that **never double-books**, even under concurrent requests. A PostgreSQL **exclusion constraint** is the real guarantee; a **pessimistic lock** per resource serializes competing requests and was added after a concurrency test exposed a PostgreSQL deadlock. Personal project I built to learn the Java/Spring ecosystem from scratch.
- **27 automated tests** (JUnit 5, Mockito, MockMvc, **Testcontainers** with a real PostgreSQL), including 30 simultaneous booking requests for the same slot → exactly 1 succeeds.
- Stateless **JWT** security with roles, errors as RFC 9457 `ProblemDetail`, Flyway migrations, OpenAPI/Swagger UI.
- Multi-stage **Docker** image, **GitHub Actions** CI, deployed on Render (free tier: the first request can take ~1 minute to wake up).

`Java 21` `Spring Boot 4` `PostgreSQL` `Docker` `Testcontainers` · [API docs (Swagger UI)](https://reservas-api-tf38.onrender.com/swagger-ui/index.html)

### 💸 [Control de Gastos: Expense Tracker](https://github.com/valenberdev/control-gastos)
Multi-user expense tracker built for speed: log an expense in seconds by sending a message to a **Telegram bot**, then see where your money goes in a **spending-by-category pie chart**. Installable as a **PWA on iPhone**, with no App Store or developer account needed.
- **Integration tests against a real PostgreSQL** (Vitest + supertest) that caught real bugs, such as an amount typed as `1.500` stored as `1.5`.
- **Custom authentication** (bcrypt, JWT with revocable sessions), Dockerized, with a **CI/CD pipeline on GitHub Actions** that deploys only if the tests pass.
- Cut the initial JavaScript from **666 KB to 315 KB** after AI-assisted audits.

`React` `TypeScript` `Node.js` `Express` `PostgreSQL` `Docker` · [Live demo](https://control-gastos-roan-eight.vercel.app/login)

### 🧀 [Cheese Cash: Multi-Currency Digital Wallet](https://github.com/valenberdev/cheesecash-backend)
Henry final project, built in a team of 4 over 3 weeks (2 sprints). I owned the **backend**: data model, REST endpoints and transactional logic for a travel wallet (ARS/USD/EUR + BTC) with buying/selling at real-time rates, transactional email notifications, and confirmation for high-value transactions.

`Express` `TypeScript` `PostgreSQL` · Deployed on Railway

### 🤖 [MCP GitHub Agent](https://github.com/valenberdev/mcp-github-agent)
MCP server that automates GitHub via natural language (create repos, issues, commits) using Octokit, with contract validation in Zod, typed error handling, and exponential-backoff retries on rate limits. Verified end to end with MCP Inspector and Claude Desktop.

`Node.js` `TypeScript` `Octokit` `Zod` `Vitest` · 13 tests

### ✅ [Task Manager](https://github.com/valenberdev/gestor-tareas)
Full stack SPA with authentication (email/password and Google Sign-In), Firestore security rules per user, task priorities, due dates, filters and drag & drop. A serverless function sends a task summary by email through AWS SES.

`React` `TypeScript` `Firebase` `Vercel` · 32 tests · [Live demo](https://proyecto-m4-valentino-berdini.vercel.app)

---

## 🔭 Currently

- Building the frontend of a **patient-facing mobile app for a healthcare client** (React + Capacitor), working with a backend developer and the client through feature branches and Pull Requests.
- Developing, in a team, the backend of a management system for a restaurant business (in progress).

---

## 📬 Let's talk

Open to remote junior backend / full stack opportunities. Reach me on [LinkedIn](https://www.linkedin.com/in/valenberdini/) or at [vaberdini@gmail.com](mailto:vaberdini@gmail.com).

📍 Bahía Blanca, Argentina
