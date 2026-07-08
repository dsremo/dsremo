# Hi, I'm Ashutosh Tiwari 👋

**Software Engineer · Backend + AI/ML · Bangalore, India**

> `dsremo` is my personal handle — this org holds my side projects.
> Portfolio → **[ashutosh.dsremo.com](https://ashutosh.dsremo.com)** · [Résumé (PDF)](https://ashutosh.dsremo.com/Ashutosh_Tiwari_Resume.pdf) · [LinkedIn](https://www.linkedin.com/in/ashutosh-tiwari-495567203/) · ashutosh108t@gmail.com

I'm a software engineer at **Simplotel** building production systems for a hotel-commerce platform — a Google Ads integration that lifted booking conversions **30%**, AI customer-engagement products (chatbot, voicebot, call analyzer) that raised international-client engagement **20%**, and AWS serverless automation that removed **~260** recurring support tickets a year. On my own time I design, deploy, and *operate* the live services below. M.Sc. in Mathematics & Computing (BIT Mesra).

- 🤖 LLMs/RAG, NLP, PyTorch — and getting them into production
- ☁️ End-to-end: FastAPI backends, AWS serverless (Lambda, Step Functions, ECS), Cloudflare Workers, Docker
- 🔒 Application & cloud security — VAPT remediation, secure code review (OWASP Top 10), cloud-posture hardening
- 🛰️ **ARIA** — a design study for a safety-first AI control architecture (a policy layer evaluated independently of the model, a runtime monitor, fail-closed defaults), explorable as an interactive lab

### 🌐 Live & operating

Services I run on my own domain (AWS S3/CloudFront · Cloudflare Workers · SES):

- [**pay.dsremo.com**](https://pay.dsremo.com) — payment-orchestration service: idempotency, an enforced state machine, HMAC signature verification, webhooks, refunds
- [**telemetry.dsremo.com**](https://telemetry.dsremo.com) — satellite-telemetry anomaly detection: an LSTM/TCN ensemble, evaluated on public ISS/ESA/SKAB benchmarks
- [**sanitize.dsremo.com**](https://sanitize.dsremo.com) — SanitizeMe: find your exposed data and auto-generate DPDP/GDPR/CCPA opt-out letters for 225 brokers
- [**aria.dsremo.com**](https://aria.dsremo.com) — ARIA: the safety-architecture design study, as an interactive browser lab
- [**auth.dsremo.com**](https://auth.dsremo.com) — a custom OAuth/SSO service (Cloudflare Worker) powering single sign-on across the dsremo apps
- [**apps.dsremo.com**](https://apps.dsremo.com) · [**markdown.dsremo.com**](https://markdown.dsremo.com) · [**learn.dsremo.com**](https://learn.dsremo.com)

### 🛠️ Selected repos

| Project | What it is |
|---|---|
| [**pay-service**](https://github.com/dsremo/pay-service) | Payment orchestrator — gateway-adapter layer (Razorpay), idempotency, state machine, HMAC, refunds; FastAPI + a Cloudflare Workers edge twin |
| [**telemetry-anomaly-detection**](https://github.com/dsremo/telemetry-anomaly-detection) | Satellite-telemetry anomaly detection — LSTM/TCN ensemble, ops dashboard, SSO; benchmarked on ISS/ESA/SKAB |
| [**sanitizeme**](https://github.com/dsremo/sanitizeme) | SanitizeMe — find exposed email/phone/usernames + auto-generate GDPR/DPDP/CCPA opt-out letters (225 brokers) |
| [**aria**](https://github.com/dsremo/aria) | ARIA — a safety-first AI control architecture design study (source-available) |
| [**mediscan**](https://github.com/dsremo/mediscan) | MediScan — offline, on-device symptom-information prototype for low-connectivity areas (educational, not diagnostic) |
| [**are-you-safe**](https://github.com/dsremo/are-you-safe) | Daily safety check-in — miss a day and your emergency contacts get alerted (React Native + AWS Lambda) |

### Stack

`Python` `Java` `C/C++` `SQL` `TypeScript` · `PyTorch` `Hugging Face` `LLMs / RAG` `NLP` `scikit-learn` · `FastAPI` `Django` `AWS` `Cloudflare Workers` `Docker` · `PostgreSQL` `MongoDB` `BigQuery`
