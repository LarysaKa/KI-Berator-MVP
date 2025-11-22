# KI-Karriere-Berater (Open Career Navigator)

**An AI-powered navigation tool for migrants and career changers in Germany.**

## ℹ️ About the Project
The "KI-Karriere-Berater" addresses the issue of "Brain Waste" in the German labor market. Unlike traditional tools that only optimize CVs, this project acts as a **navigator**. It conducts deep, narrative interviews in the user's native language (DE, RU, UA, TR) to identify hidden skills and match them with the German labor market reality.

## 🛠 Tech Stack
- **Orchestration:** [n8n](https://n8n.io/) (Self-hosted)
- **AI Models:** OpenAI (GPT-4o), local LLMs via API
- **Database:** Supabase / PostgreSQL
- **Hosting:** Hetzner / Elestio (Data stored in Germany 🇩🇪)

## 📂 Repository Structure
- `career_agent_workflow.json` - The core n8n workflow managing the 5-agent pipeline (Intake, Research, Scoring, Matching, Writing).

## 🛡 Privacy & Ethics
- No biometric analysis (voice/face).
- Semantic analysis only.
- GDPR-compliant architecture.

---
*This project is a prototype candidate for the Prototype Fund (Round 02).*
