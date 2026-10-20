## Hi, I'm Aahil 👋

I build AI systems on solid backends, and I measure them. Computer Engineering student at PCCOE Pune, open-source contributor to **CNCF Meshery**, and freelance **n8n AI automation** engineer on Upwork.

[LinkedIn](https://linkedin.com/in/aahil-sayed) · [Upwork](https://www.upwork.com/freelancers/~01c6df3ebf5b39913a) · [7.aahilsayed.7@gmail.com](mailto:7.aahilsayed.7@gmail.com) · Pune, India

---

### Featured projects

**[RepoPilot](https://github.com/aahil62/repopilot)**: private AI code review on local open-source LLMs · [live demo](https://repopilot-dev.vercel.app)  
Splits every change into what actually changes behavior and what is just formatting, scores file risk from git history, runs your tests in a throwaway worktree, and adds a local LLM second opinion. No API keys; code never leaves the machine.
- Formatting-only changes set aside at **100% precision** on held-out hand-labelled sets (Python and JS/TS)
- Planted-bug detection raised from **5% to 70%** with a skeptical second pass, at **0%** high-severity false alarms on real fixes
- Hybrid-search RAG finds the right file in the top 5 for **88–96%** of questions; indexes Django (529k lines) in 235 MB
- CLI, VS Code extension, web app and a GitHub Action · `Python` `FastAPI` `Ollama` `SQLite FTS5` `tree-sitter` `Next.js` `TypeScript`

**[FraudLens](https://github.com/aahil62/fraud_lens)**: real-time fraud operations platform for UPI, cards, net banking and ATMs · [live](https://fraud-lens-r3t0.onrender.com)  
Multi-analyst console with L1 → L2 → Supervisor approvals, a separate bank service that liens, freezes and closes accounts, and an AI agent that triages but never decides.
- Gradient-boosted classifier: **0.95 precision, 0.88 recall, 0.95 ROC-AUC** on 10.4k held-out synthetic transactions
- 6-signal ensemble: **85% recall at 74% precision** on a 376-payment evaluation; scoring cut from over 6 s to **16 ms**
- Exactly-once bank actions via a transactional outbox; **305 automated tests**; Docker on Render
- `Python` `FastAPI` `scikit-learn` `NetworkX` `Next.js` `SQLite` `Docker`

**[AI Lead Qualification → HubSpot](https://github.com/aahil62/n8n-lead-crm)**: n8n · 6 workflows  
The LLM extracts budget, timeline and authority; your rules set the score; unsure leads go to human review. Idempotent writes, HubSpot 429 retries and a dead-letter queue. **15/15 live test scenarios pass.**

**[AI Inbox Triage with Human-Approved Replies](https://github.com/aahil62/n8n-inbox)**: n8n · 6 workflows  
Gmail drafts that are never auto-sent, Asana tasks and a daily Slack brief. Caught **all 6 sensitive emails** in a 40-email labelled evaluation and blocks prompt injection. **14/15 live scenarios pass.**

---

### Open source

**[CNCF Meshery](https://github.com/meshery/meshery)** (12k ★) · **7 merged pull requests** ([all](https://github.com/meshery/meshery/pulls?q=is%3Apr+author%3Aaahil62+is%3Amerged)) adding AWS and Azure → Kubernetes relationships to Meshery's cloud-native model registry:

| PR | AWS / Azure services → Kubernetes Deployment and Pod |
|---|---|
| [#19490](https://github.com/meshery/meshery/pull/19490) | AWS DynamoDB Table, SQS Queue |
| [#19493](https://github.com/meshery/meshery/pull/19493) | Azure Service Bus Queue, Event Hub |
| [#19502](https://github.com/meshery/meshery/pull/19502) | AWS RDS DBInstance, Lambda Function |
| [#19506](https://github.com/meshery/meshery/pull/19506) | AWS ElastiCache ReplicationGroup |
| [#19507](https://github.com/meshery/meshery/pull/19507) | AWS SNS Topic |
| [#19508](https://github.com/meshery/meshery/pull/19508) | AWS Secrets Manager Secret |
| [#19528](https://github.com/meshery/meshery/pull/19528) | AWS EventBridge EventBus |

**[unslop](https://github.com/aahil62/unslop)** (author, 18 ★): Claude Code / Codex plugin that audits and re-themes React sites with a build check after every change. Took a stock landing page from 27 to 100/100.

---

### Freelance

**n8n AI automation on [Upwork](https://www.upwork.com/freelancers/~01c6df3ebf5b39913a)** (Verified · Rising Talent): lead qualification, CRM sync, inbox triage and AI agents, built so AI drafts but never sends and every failure is replayable. The two n8n systems above are my public case studies.

---

### Stack

**AI & ML** · LLM applications, RAG, embeddings, hybrid search, prompt engineering, structured outputs, LLM evaluation, scikit-learn, Ollama, Groq  
**Automation** · n8n, webhooks, API integration, HubSpot, Gmail, Asana, Slack, Airtable  
**Backend & full stack** · Python, TypeScript, FastAPI, Node.js, REST APIs, React, Next.js, PostgreSQL, SQLite  
**DevOps & cloud** · Docker, Kubernetes, GitHub Actions, CI/CD, AWS, Azure, Vercel, Render, Linux

---

### Also

- 🏆 Smart Horizon 2026 Finalist, Team Lead (FraudLens) · GDGC Alphabyte 3.0 Special Mention (RepoPilot)
- 💻 LeetCode 450+ · Codeforces 1540 (Specialist) · JEE Main top 3% of 1.5M
- 🎤 GDGC PCCOE Web Developer and DevOps: 4 workshops with 100+ participants each
- 📦 More: [FinAssure](https://finassure.vercel.app), a personal finance app with multi-model AI and an OCR receipt scanner
