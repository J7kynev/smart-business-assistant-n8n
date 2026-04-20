*# 🤖 n8n AI Automation Portfolio*



*Professional automation workflows built with n8n, OpenAI and third-party integrations.*



*---*



*## 📁 Project 1: Smart Business Assistant (RAG Agent)*



*AI agent that answers business questions via Telegram using RAG with OpenAI and Pinecone.*



*\*\*Stack:\*\* n8n · OpenAI GPT-4o-mini · Pinecone · Telegram · Simple Memory*



*\*\*Workflows:\*\**

*- `01\_knowledge\_ingestion` — Loads documents into Pinecone vector database*

*- `02\_agent\_core` — AI agent that receives and responds to Telegram messages*

*- `03\_weekly\_report` — Sends automatic weekly status report every Monday*



*---*



*## 📁 Project 2: AI Sales Pipeline*



*Automated lead qualification system that captures leads via webhook, enriches them with Hunter.io, scores them with OpenAI and routes them into Airtable CRM.*



*\*\*Stack:\*\* n8n · OpenAI GPT-4o-mini · Hunter.io · Airtable · Telegram*



*\*\*Workflow:\*\* `02\_ai\_sales\_pipeline`*



*\*\*How it works:\*\**

*1. Lead arrives via webhook*

*2. Hunter.io enriches the lead data*

*3. OpenAI scores the lead from 1 to 10*

*4. Hot leads (score ≥ 7) trigger an immediate Telegram alert*

*5. Cold leads enter an automated nurturing sequence*

*6. All leads are saved to Airtable CRM automatically*



*---*



*## ⚙️ Setup*



*1. Clone this repository*

*2. Install n8n: `npm install -g n8n`*

*3. Copy `.env.example` to `.env` and fill in your credentials*

*4. Import the workflows into n8n*

*5. Activate the workflows*



*## 🔑 Required Credentials*



*- OpenAI API Key*

*- Pinecone API Key*

*- Telegram Bot Token*

*- Airtable Token*

*- Hunter.io API Key*



*## 📄 License*



*MIT*

