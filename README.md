# 🎯 LinkedIn Algerian Entrepreneurs AI Finder (n8n + Ollama)

An autonomous AI Agent that automates B2B lead generation within the Algerian market (Algiers, Blida, Tipaza and surroundings). It triggers from a Telegram Bot, performs OSINT search on LinkedIn using DuckDuckGo, processes profiles locally using an LLM, and archives everything into Google Sheets.

## ✨ Features
- **100% Free & Open-Source:** Uses local AI via Ollama (Llama 3 / Qwen) and free scraping tools.
- **Telegram Native:** Command your agent with a simple text (e.g., "Blida").
- **Smart Enrichment:** Extracts Name, Job Title, Company, and generates a personalized **Icebreaker** message in French/Arabic.
- **Automated CRM:** Syncs data dynamically into Google Sheets.

## 🛠️ Tech Stack
- **n8n** (Workflow Automation)
- **Ollama** (Local LLM Deployment)
- **JavaScript** (Data Parsing Node)
- **Telegram Bot API** & **Google Sheets API**

## 🚀 How to Use
1. Download the `linkedin-algerian-leads-agent.json` file.
2. Import it into your n8n instance.
3. Configure your Telegram Bot Token and Google Sheets credentials.
4. Ensure Ollama is running locally with your preferred model.
5. Activate the workflow and text your bot!
