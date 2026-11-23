# Hi, I'm Mani 👋

**Aspiring blue-team / defensive security engineer** — CS student focused on detection, triage and incident response, with a habit of measuring my own detections and writing down what doesn't work yet.

`#BlueTeam` `#DetectionEngineering` `#SOC` `#IncidentResponse` `#ContainerSecurity`

---

## 🛡️ Blue-team focus

| Area | What I've built or practised |
|---|---|
| **Detection engineering** | Custom Falco rules for container-escape behaviour; 13 evidence-backed MITRE ATT&CK mapping rules scored against ground-truth scenarios |
| **SOC triage & investigation** | Alert triage dashboard, case management, evidence timelines, multi-source correlation (Sysmon, Suricata EVE) |
| **Incident response** | Evidence provenance (SHA-256 chain of custody), role-tailored incident reports, human-in-the-loop review |
| **Runtime / container security** | Falco on Docker, automated container pause via webhook response |
| **Secure engineering** | RBAC, rate limiting, CSP/security headers, secrets out of source control, OWASP-mapped probe suite |
| **Evaluation** | Measuring detection recall honestly, ablations, "reality matrix" of what is verified vs. partial |

---

## Featured projects

### 🔐 [AISOP](https://github.com/mani17S/AISOP) — AI-Assisted Security Operations Platform
A local-first, privacy-preserving workbench for alert triage and incident investigation. Telemetry is hashed, deduplicated and normalized **before** any model sees it; AI output stays advisory behind human review, with no autonomous containment.

`Python` · `FastAPI` · `PostgreSQL + pgvector` · `Ollama` · `React + TypeScript` · `GitHub Actions`

- Sysmon and Suricata ingestion, ATT&CK mapping, SHA-256 provenance, scoped RBAC
- Evaluation framework with 20 ground-truth scenarios; weak recall is published, not hidden

### 🐳 [DockerScape](https://github.com/mani17S/DockerScape) — Container escape detection & response lab
Simulates a container breakout, detects it at runtime with **Falco** custom rules, and uses a webhook to pause the offending container.

`Docker` · `Falco` · `Python` · `Shell`

### ⏱️ [time-tracker](https://github.com/mani17S/time-tracker) — Full-stack app, hardened
A task/timer app (React, Express, PostgreSQL). I later audited it myself: removed a committed `.env` and a hardcoded JWT secret — a small real-world secrets-hygiene fix.

---

## Toolbox

| | |
|---|---|
| **Detection & telemetry** | Falco · Sysmon · Suricata (EVE) · MITRE ATT&CK · log normalization |
| **Languages** | Python · Shell · JavaScript · TypeScript |
| **Platforms** | Docker · PostgreSQL · Nginx · GitHub Actions |
| **Practices** | Threat modelling · OWASP · RBAC · secrets management · ADRs |

---

## Working style

- Write the requirement, the test and the limitation down — in the repo.
- Deterministic detection first; add a model only where it earns its place.
- Defensive only: tooling here is for detection, triage and response in labs I own.

📫 Open to SOC / detection-engineering internships and blue-team projects — reach me through an issue or discussion on any repo above.
