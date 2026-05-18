# 🎯 Autonomous Lead Generation & Prospect Intelligence Pipeline

An end-to-end, production-grade web scraping, enrichment, and automated lead-scoring pipeline that eliminates manual cold prospecting and synchronizes qualified intelligence directly to a cloud database.

---

## 📊 Workflow Architecture
![n8n Lead Generation Canvas]<img width="1855" height="602" alt="Screenshot 2026-05-19 011524" src="https://github.com/user-attachments/assets/5c8ffcf7-d036-4b46-8c25-e306a6e0cc28" />


---

## 🛠️ Core Tech Stack
* **Workflow Orchestration:** n8n (Webhook Triggers, Advanced Conditional Logic)
* **Data Extraction:** Apify API (Web Scraping Engines)
* **AI & Intelligence Filtering:** OpenAI API (GPT-4o), Structured Data Parsing
* **Backend Cloud Database:** Supabase (PostgreSQL)
* **Integrations:** Google Sheets API

---

## 💡 Key Core Functionalities
* **Scalable Data Sourcing:** Leverages Apify APIs to automatically extract target business profile and contact metrics across multiple web platforms seamlessly.
* **LLM-Driven Lead Qualification:** Processes raw scraped datasets through an OpenAI LLM scoring module to automatically evaluate, segment, and isolate premium target accounts based on custom business criteria.
* **Automated Database Syncing:** Completely eliminates manual CRM entry by utilizing Supabase (PostgreSQL) webhooks to automatically pipe fully enriched, qualified prospects into production tables in real time.

---

## 🚀 Deployment Instructions

### 1. Import the Workflow to n8n
1. Download the `Autonomous-Lead-Gen-Pipeline.json` file from this repository.
2. In your n8n dashboard, create a new workflow, click the three dots in the top-right corner, and select **Import from File**.
3. Upload the `.json` file to instantly map the entire multi-node architecture.

### 2. Required Connection Credentials
To make this automation fully operational, ensure you configure the following active credential integrations in your n8n workspace:
* **Apify API Key** (For handling structured web scraping tasks)
* **OpenAI API Key** (For driving the intelligent lead qualification and scoring logic)
* **Supabase Service Role Key & URL** (For writing target leads directly to your cloud tables)
* **Google Sheets OAuth2** (For standard tracking logs)

---

## 📂 Repository Contents
* `Autonomous-Lead-Gen-Pipeline.json` — Full n8n workflow export JSON schema.
* `README.md` — In-depth architectural setup and operational manual.
