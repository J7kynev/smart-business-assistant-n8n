# 🤖 Smart Business Assistant - n8n AI Agent

Automated AI agent built with n8n that answers business questions via Telegram using RAG (Retrieval-Augmented Generation) with OpenAI and Pinecone vector database.

## 🏗️ Architecture

- **n8n** - Workflow orchestration
- **OpenAI GPT-4o-mini** - AI responses
- **OpenAI Embeddings** - text-embedding-3-small
- **Pinecone** - Vector database for knowledge base
- **Telegram** - User interface
- **Simple Memory** - Conversation history

## 📁 Workflows

- `01_knowledge_ingestion` - Loads documents into Pinecone
- `02_agent_core` - Main AI agent that receives and responds to Telegram messages
- `03_weekly_report` - Sends automatic weekly status report every Monday

## ⚙️ Setup

1. Clone this repository
2. Install n8n: `npm install -g n8n`
3. Copy `.env.example` to `.env` and fill in your credentials
4. Import the workflows from the `/workflows` folder into n8n
5. Activate the workflows

## 🔑 Required Credentials

- OpenAI API Key
- Pinecone API Key
- Telegram Bot Token

## 📄 License

MIT



