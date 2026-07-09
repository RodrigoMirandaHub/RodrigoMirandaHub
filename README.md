# Rodrigo Miranda

**N8N Automation Engineer · AI/LLM Integrations · REST APIs**

I build end-to-end workflow automations that connect APIs, process data with LLMs, and trigger real-time actions across business systems. Based in Brasília, Brazil.

---

## 📂 Projects

### 🔗 [Make Financial Monitor](https://github.com/RodrigoMirandaHub/Make-Financial-Monitor)
An automation built in Make (formerly Integromat) that monitors the USD/BRL exchange rate on a schedule, branches on real business logic, and takes different actions depending on the result including generating an AI-written recommendation with an LLM.

### 🔗 [LangChain Studies](https://github.com/RodrigoMirandaHub/langchain-studies)
Building hands-on projects with LangChain, LCEL, and Groq.
Covers chains, prompt templates, memory, RAG, and agents.

![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=flat&logo=langchain&logoColor=white)
![Groq](https://img.shields.io/badge/Groq-F55036?style=flat&logo=groq&logoColor=white)

→ [langchain-studies](https://github.com/RodrigoMirandaHub/langchain-studies)


### 🔥 [Lead Enrichment Pipeline — N8N + Groq + Supabase + HubSpot]([https://github.com/RodrigoMirandaHub/lead-enrichment-pipeline-n8n](https://github.com/RodrigoMirandaHub/Lead-Enrichment-Pipeline))
AI pipeline that receives leads via webhook, scores them with LLaMA 3.3-70b, stores results in Supabase (PostgreSQL) with duplicate protection, creates contacts in HubSpot CRM, and fires Gmail alerts for hot leads (score ≥ 7).  
`n8n` `Groq API` `LLaMA 3.3` `Supabase` `HubSpot` `PostgreSQL` `Gmail`

### 🎫 [Ticket Classification Pipeline — N8N + Groq + LLaMA](https://github.com/RodrigoMirandaHub/pipeline-classificador-tickets-n8n)
AI pipeline for automatic fintech support ticket triage. Receives tickets via webhook, classifies them by category and severity using LLaMA 3.3-70b, fires critical alerts via Gmail, and logs all results to Google Sheets.  
`n8n` `Groq API` `LLaMA 3.3` `Webhooks` `Google Sheets` `Gmail`

### 🤖 [Telegram AI Chatbot with Memory](https://github.com/RodrigoMirandaHub/telegram-ai-chatbot1)
Fully functional Telegram chatbot powered by Groq (LLaMA 3.3), with persistent conversation history stored in Google Sheets. Deployed on Railway with zero cost infrastructure.  
`n8n` `Groq API` `Telegram Bot API` `Google Sheets` `Railway`

### 📊 [Lead Analysis Agent — N8N + AI](https://github.com/RodrigoMirandaHub/-Agente-de-An-lise-de-Leads-com-IA-N8N)
Webhook-triggered workflow that receives lead data, processes it through an LLM for qualification and classification, and saves structured results to Google Sheets.  
`n8n` `Groq API` `Webhooks` `Google Sheets` `JSON parsing`

### 📈 [Financial Rate Monitor with Alerts](https://github.com/RodrigoMirandaHub/monitor-cotacoes-n8n)
Scheduled automation polling USD and BTC rates every 30 minutes via AwesomeAPI. Stores history in Google Sheets and sends conditional Gmail alerts when thresholds are crossed.  
`n8n` `AwesomeAPI` `Google Sheets` `Gmail` `Schedule Trigger`

### 🔌 [Claude MCP Projects — Filesystem, SQLite & Google Sheets](https://github.com/RodrigoMirandaHub/claude-mcp-projects)
Documented setup and integration of Model Context Protocol (MCP) servers with Claude Desktop on Windows covering filesystem access, SQLite queries, and Google Sheets operations.  
`MCP` `Claude Desktop` `SQLite` `Google Sheets` `Windows`

### 05 — Agent with Tools
LangChain agent with two tools: a calculator and a web search tool.
Uses `bind_tools` for manual tool call loop control instead of `create_agent`.

**Known issue:** Groq API (`llama-3.3-70b-versatile`) generates malformed XML
instead of JSON when calling external search tools — confirmed bug on Groq's side.
Calculator tool works correctly. Web search fails consistently due to provider bug.

**Lesson:** For reliable tool calling in production, prefer OpenAI or Anthropic API,
or implement provider fallback logic.


---

## 🛠 Tech Stack

| Area | Tools |
|---|---|
| Automation | N8N, Webhooks, Schedule Triggers |
| AI / LLM | Groq API, LLaMA 3.3, Prompt Engineering |
| APIs | REST, OAuth 2.0, HubSpot, Telegram Bot API, AwesomeAPI |
| Database | Supabase, PostgreSQL, SQLite, Google Sheets |
| Infrastructure | Railway, Render, Docker |
| Security | Cisco CCNA, CyberOps Associate (certified) |

---

## 📌 Background

Communication degree (UnB) + self-directed path into automation and AI engineering. Every project here was built from scratch to solve a real use case end-to-end — webhook intake, LLM processing, conditional logic, database persistence, CRM integration, and alerting.

Currently focused on: LLM-powered business workflows, CRM integrations, and fintech automations.

---

## 📫 Contact

[LinkedIn](https://www.linkedin.com/in/rodrigo-h-miranda) · [Email](mailto:negociosonlinerh2@gmail.com)
