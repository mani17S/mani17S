# Hi, I'm Mani 👋

**Computer science student building security tooling and applied AI** — with a habit of measuring my own work and writing down what doesn't work yet.

---

## What I'm focused on

- 🛡️ **Defensive security engineering** — SOC workflows, runtime container security, detection rules mapped to MITRE ATT&CK
- 🤖 **Applied AI done carefully** — local-first LLMs, retrieval (RAG), and guardrails that keep model output separate from verified facts
- 🧪 **Evaluation over vibes** — ground-truth scenarios, ablations, and honest reporting of weak results

---

## Featured projects

### 🔐 [AISOP](https://github.com/mani17S/AISOP) — AI-Assisted Security Operations Platform
A local-first, privacy-preserving workbench for alert triage and incident investigation. Telemetry is hashed, deduplicated and normalized **before** any model sees it, and every AI conclusion stays advisory behind human review.

`Python` · `FastAPI` · `PostgreSQL 17 + pgvector` · `Ollama` · `React + TypeScript` · `GitHub Actions` · `Docker`

- SHA-256 evidence provenance, scoped RBAC, rate limiting, hardened security headers
- Evaluation framework with 20 ground-truth scenarios; weak recall is published rather than hidden
- README carries a "reality matrix" separating verified, partial and deferred features

### 🐳 [DockerScape](https://github.com/mani17S/DockerScape) — Container escape detection lab
A Docker lab that simulates a container breakout, detects it at runtime with **Falco** custom rules, and uses a webhook to pause the offending container automatically.

`Docker` · `Falco` · `Python` · `Shell`

### ⏱️ [time-tracker](https://github.com/mani17S/time-tracker) — Task & timer app
Full-stack app for managing tasks and timers with authentication and session handling.

`React` · `Node.js / Express` · `PostgreSQL` · `Knex` · `Docker`

---

## Toolbox

| | |
|---|---|
| **Languages** | Python · JavaScript · TypeScript · Shell |
| **Backend & data** | FastAPI · Express · PostgreSQL · pgvector · Knex · Alembic |
| **Security** | Falco · Sysmon · Suricata EVE · MITRE ATT&CK · RBAC · OWASP |
| **Infra & tooling** | Docker · Docker Compose · GitHub Actions · Nginx · Git |
| **AI** | Ollama · embeddings · RAG · guardrails & evaluation |

---

## Working style

- Write the requirement, the test and the limitation down — in the repo, not in my head.
- Prefer deterministic code first; add a model only where it earns its place.
- Document trade-offs with short ADRs so decisions can be revisited.

---

📫 Open to internships, research collaboration and security/AI projects — the best way to reach me is a GitHub issue or discussion on any repo above.
