# n8n-practice
 
Personal learning repository for studying n8n workflow automation, self-hosted infrastructure, and AI-powered backend integrations.
 
---
 
## 🤖 What is n8n?
 
**n8n** (pronounced *"n-eight-n"*) is an open-source workflow automation tool that lets you connect apps, APIs, and services through a visual node-based editor — without writing boilerplate integration code.
 
Think of it as a self-hostable alternative to Zapier or Make (formerly Integromat), but with full code access when you need it.
 
Key characteristics:
- **Visual workflow editor** — drag-and-drop nodes to build automation pipelines
- **Self-hostable** — run it entirely on your own infrastructure via Docker
- **Code-friendly** — drop into JavaScript/Python inside any node when logic gets complex
- **AI-ready** — native LangChain integration for building AI agent workflows
---
 
## 📌 What I'm Learning
 
- Self-hosted n8n setup via Docker
- Workflow orchestration & automation pipelines
- Webhook & API integrations
- AI automation with n8n nodes
- Queue-based execution concepts
- Backend automation architecture
---
 
## 🐳 Local Setup
 
This project runs on the [n8n self-hosted AI starter kit](https://github.com/n8n-io/self-hosted-ai-starter-kit), which bundles n8n with Ollama, Qdrant, and PostgreSQL via Docker Compose.
 
### Prerequisites
 
- [Docker](https://docs.docker.com/get-docker/) installed and running
### Steps
 
```bash
# 1. Clone the starter kit
git clone https://github.com/n8n-io/self-hosted-ai-starter-kit.git
cd self-hosted-ai-starter-kit
 
# 2. Start the environment
docker compose up -d
```
 
Access n8n at: **http://localhost:5678**
 
To stop:
 
```bash
docker compose down
```
 
> ⚠️ The `.env` file contains API keys and credentials — make sure it's listed in `.gitignore` before pushing anywhere.
 
---
 
## 📚 Study Notes
 
Detailed conceptual summaries and learning notes are organized in Notion:
 
🔗 [Open Study Notes in Notion](https://www.notion.so/Book-35de765f6fbd80aa988ef9746a6940dd?source=copy_link)
 
---
 
## 🛠️ Topics
 
`n8n` `Docker` `Workflow Automation` `API Integration` `AI Automation` `Webhooks` `Self-Hosting` `Backend Infrastructure`
