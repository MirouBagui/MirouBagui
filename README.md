# 👋 Hi, I'm Amir SAOUDI

**Full-Stack Software Engineer **
---

## 🧩 The problems I've solved

**Problem 1 — "Too much data, too little time."**  
High-volume telemetry pipelines drowning users in noise, with dashboards lagging seconds behind reality.  
→ *My solution:* an event-driven ingestion architecture (queue + orchestrator + WebSocket fan-out) sustaining **50k+ concurrent data points at sub-50ms end-to-end latency**.

**Problem 2 — "Deploys take forever and break things."**  
Manual, error-prone release processes and unpredictable lead times.  
→ *My solution:* fully automated CI/CD pipelines (GitLab CI + Docker), parallelized jobs, prod-like staging environments. Result: **40% faster deployments**, regression-free releases.

**Problem 3 — "Legacy code is eating our velocity."**  
Heterogeneous, weakly-typed frontend codebases generating recurring bugs and slow delivery.  
→ *My solution:* incremental strangler-fig migration to TypeScript, strict linting, systematic code reviews, shared component library (Storybook), automated tests in CI. Result: **30% fewer frontend bugs**, &gt;95% sprint acceptance rate.

**Problem 4 — "Data silos, slow decisions."**  
Analysts piecing together insights from scattered tools and spreadsheets.  
→ *My solution:* a unified full-stack analytics platform (React + Node.js + MongoDB) with optimized queries and caching over large historical datasets. Result: **25% faster data-to-decision**, adopted as the daily working tool by its users.

---

## 🛠️ How I build


| Layer         | My tools                                                       |
| ------------- | -------------------------------------------------------------- |
| Frontend      | React, TypeScript, WebRTC, Storybook, Jest / RTL               |
| Backend       | Node.js, Express, REST, WebSockets, Mocha                      |
| Data          | PostgreSQL, MongoDB, query optimization &amp; caching          |
| Infra         | Docker, Kubernetes, Portainer, Jenkins, GitLab CI, AWS / Azure |
| Security      | Secure coding, JWT auth, Burp Suite, IAM/VPC                   |
| Observability | Datadog, monitoring &amp; logging                              |


---

## 📐 Architecture principles I live by

1. **Design for the failure case first** — a system is defined by how it behaves under load, not at rest.
2. **Decouple everything that changes at different speeds** — queues, events, and contracts over direct calls.
3. **Make the pipeline the quality gate** — tests, types, and linting run before any human review.
4. **Measure, then optimize** — no performance claim without a number behind it.
5. **Strangler over rewrite** — migrate legacy incrementally, ship value every step.

---

## 📫 Reach me

📧 [saoudi.amire@gmail.com](mailto:saoudi.amire@gmail.com) · 💼 [LinkedIn](https://linkedin.com/in/amir-saoudi05) · 📍 Paris, France

⭐ *Ask me about: event-driven architecture, real-time data pipelines, CI/CD design, legacy modernization.*
