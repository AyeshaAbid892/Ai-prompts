<div align="center">

# ⚡ Advanced Prompt Engineering
### ⚙️ Production-Grade AI Workflows · What / How / Why Framework

![Framework](https://img.shields.io/badge/Framework-What_%2F_How_%2F_Why-27500A?style=flat-square&labelColor=EAF3DE)
![Architecture](https://img.shields.io/badge/Architecture-Enterprise_MERN_%2B_AI-0C447C?style=flat-square&labelColor=E6F1FB)
![Quality](https://img.shields.io/badge/Prompt_Quality-Production_Ready-3C3489?style=flat-square&labelColor=EEEDFE)

</div>

---

> **`Ai-prompts`** is a curated collection of precision-engineered prompts built for real-world developer challenges, spanning distributed systems, database optimization, AI infrastructure, frontend performance, and backend security. Every prompt follows a strict 3-component framework designed to eliminate hallucinations and produce deterministic, production-ready outputs.

---

## 🧩 The Framework

| | Component | Role | Controls |
|:---:|:---:|:---|:---|
| 🟣 | **`WHAT`** | Exact technical deliverable | Core feature / algorithmic scope |
| 🟢 | **`HOW`** | Execution constraints & code standards | Style, structure, tooling, benchmarks |
| 🟡 | **`WHY`** | Architectural context | Business logic, system workload, project reality |

---

## 📁 Prompt Repository

<br>

### `PROMPT 01` 
&nbsp; Microservices Communication Bridge
> 🌐 **Domain:** Distributed Systems · Event-Driven Architecture

| | |
|:---:|:---|
| 🟣 **WHAT** | A working ExpressJS setup connecting two backend services via RabbitMQ or Redis Pub/Sub for inter-service messaging. |
| 🟢 **HOW** | One `Order Service` publishes a message; one `Inventory Service` consumes it. Plain JavaScript, clean folder structure (`/controllers`, `/services`), and basic reconnection/error handling. |
| 🟡 **WHY** | Splitting a monolithic app into isolated services — so if one service experiences a traffic spike, the rest of the system stays up and continues processing independently. |

---

### `PROMPT 02`
&nbsp; MongoDB Aggregation Pipeline Optimization
> 🗄️ **Domain:** Database Engineering · Performance Tuning

| | |
|:---:|:---|
| 🟣 **WHAT** | A MongoDB aggregation query that joins multiple collections and generates a structured sales report for an e-commerce analytics dashboard. |
| 🟢 **HOW** | Use `$lookup` to join `users`, `orders`, and `vendors`. Apply `$match` to filter, `$group` + `$project` to calculate monthly profit, and basic sorting. Include inline comments highlighting index usage. |
| 🟡 **WHY** | Heavy analytics queries cause dashboard lag under real data loads. Proper pipeline design prevents full collection scans and keeps the UI responsive. |

---

### `PROMPT 03`
&nbsp; Automated Code Review System Prompt
> 🤖 **Domain:** AI Infrastructure · System Prompt Engineering

| | |
|:---:|:---|
| 🟣 **WHAT** | A reusable LLM system prompt that instructs the model to behave as a senior developer performing structured code review. |
| 🟢 **HOW** | The AI must identify: security risks like SQL injection, performance bottlenecks, and clean code violations — then respond **only** in JSON with keys: `severity_level`, `file_path`, `issue_description`, `optimized_code_fix`. |
| 🟡 **WHY** | Replacing freeform AI feedback with deterministic structured output enables this to slot directly into an automated dev toolchain — no parsing ambiguity, no noise. |

---

### `PROMPT 04`
&nbsp; High-Performance React Data Stream Component
> 🎨 **Domain:** Frontend Engineering · UI Virtualization

| | |
|:---:|:---|
| 🟣 **WHAT** | A React component that renders a live-updating data table powered by Server-Sent Events from the backend. |
| 🟢 **HOW** | List virtualization library for rendering thousands of rows without jank. Column sorting, `useMemo` to prevent unnecessary re-renders, Tailwind CSS for layout. |
| 🟡 **WHY** | Real-time dashboards die under data load without virtualization. This setup keeps the interface completely fluid regardless of how fast the backend pushes updates. |

---

### `PROMPT 05` 
&nbsp; Enterprise API Gateway Middleware
> 🔒 **Domain:** Backend Security · Middleware Architecture

| | |
|:---:|:---|
| 🟣 **WHAT** | A modular Express.js middleware layer that secures all API routes with authentication and abuse prevention. |
| 🟢 **HOW** | ES6 standard. JWT for session verification, refresh tokens in `HttpOnly` secure cookies, `express-rate-limit` against spam, `Helmet` + `CORS` for security headers. |
| 🟡 **WHY** | Production APIs require layered defense. This middleware forms the security perimeter around all endpoints — protecting user data from the most common attack vectors. |

---

## 📈 Why This Framework Wins

| | Impact | Description |
|:---:|:---|:---|
| 🛑 | **Stops Hallucinations at the Source** | The `HOW` component locks the AI to specific tools and constraints — making irrelevant output structurally impossible. |
| 🎯 | **Generates Production-Ready Code** | The `WHY` component gives the model architectural awareness — resulting code handles real workloads and fits existing systems. |
| ♻️ | **Reusable Across Every Project** | Fully decomposed into `WHAT / HOW / WHY` — swap the domain details and regenerate any feature on demand. |

---

<div align="center">

**⚡ Production-grade prompt architecture for enterprise workflows.**

*Deterministic · Predictable · Production-Ready*

</div>
