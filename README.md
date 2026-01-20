# GYM AI Chatbot: Instagram CRM & Knowledge Assistant 🤖

![Workflow](https://img.shields.io/badge/Workflow-n8n-EF5B25) ![Database](https://img.shields.io/badge/Vector%20DB-Pinecone-000000) ![AI](https://img.shields.io/badge/AI-Google%20Gemini-4285F4) ![CRM](https://img.shields.io/badge/CRM-Google%20Sheets-34A853)

An enterprise-grade AI orchestration engine built for **Fitness GYM**. This system transforms Instagram into a high-conversion sales channel by combining **Retrieval-Augmented Generation (RAG)** with automated CRM workflows—built entirely without expensive third-party chat platforms.

---

## 📸 System Architecture & Preview
![Chatbot Interaction](https://github.com/Muneeb20019/mak-gym-rag-crm-automation/blob/main/chat.png?raw=true)
*Real-time interaction: AI retrieving gym facts from Pinecone while maintaining the sales funnel.*

---

## 🏆 The Competitive Edge: Beyond "No-Code" Builders
The standout feature of this project is that it was built **without ManyChat, Chatfuel, or other third-party marketing platforms.** 

**Why this is a Game-Changer:**
*   **💰 Zero Subscription Bloat:** Standard bots charge monthly fees that scale with your lead count. This system runs via direct API calls, making it significantly more **cost-effective** for growing businesses.
*   **🧠 Limitless Logic:** "No-code" builders often fail at complex tasks. This bot performs real-time **BMI calculations** and **Vector Database lookups**—features that are nearly impossible to implement in closed systems.
*   **🔓 Zero Vendor Lock-in:** Unlike standard tools that "own" your flow, this architecture is **3rd-party agnostic**. You have the freedom to swap Gemini for GPT-4 or Pinecone for Milvus with zero downtime.
*   **🛡️ Data Sovereignty:** Your leads' data never sits on a third-party chat server. It moves directly from the Instagram API to your private database, ensuring maximum privacy and security.

---

## ✨ Key Features

*   **🧠 RAG-Powered Knowledge:** Utilizes a **Pinecone Vector Database** to answer complex questions about gym fees, location, and rules with 100% accuracy.
*   **📋 Automated Lead Onboarding:** A multi-step conversational protocol that captures Full Name, WhatsApp, and Fitness Goals.
*   **⚖️ Live Health Logic:** Custom AI logic to calculate a user's **BMI** in real-time during the chat, providing immediate value to the prospect.
*   **📊 Persistent CRM Sync:** Real-time data streaming to **Google Sheets API**, ensuring the MAK GYM staff has a live dashboard of new leads.
*   **🔄 Automated Knowledge Sync:** A background workflow monitors **Google Drive**. Any update to the gym's PDF manual is automatically re-indexed into Pinecone.

---

## 🚀 Technical Stack

| Layer | Technology |
| :--- | :--- |
| **Automation Hub** | n8n Orchestration 🔗 |
| **AI / LLM** | Google Gemini (via OpenRouter) ♊ |
| **Vector Database** | Pinecone (768-Dimension Index) 🌲 |
| **Knowledge Retrieval** | text-embedding-004 (Google) 🔍 |
| **CRM / Storage** | Google Sheets API 📊 |
| **Interface** | Instagram Graph API 📸 |

---

## ⚙️ Workflow Logic

### **1. The Response Pipeline**
Incoming Webhooks are processed through an **AI Agent** equipped with a **Simple Memory** node. This allows the bot to handle "Distracted Conversations"—for example, answering a question about parking in the middle of a signup process without forgetting the user's name.

### **2. Semantic Vector Search**
By utilizing **768-dimension semantic embeddings**, the bot performs a "Similarity Search" in Pinecone. It understands the *intent* behind questions like "Can I come on Friday?" and provides specific Jumu'ah prayer timing details from the gym manual.

### **3. Safe CRM Writing**
To handle the "Plus Sign" formatting issue in Google Sheets, the system implements **single-quote prefix logic** via n8n expressions, ensuring all WhatsApp data is stored as clean, searchable text rather than broken formulas.

---

## 🏗️ Visualizing the Workflows

### **Main Conversation Engine**
![Main Workflow](https://github.com/Muneeb20019/mak-gym-rag-crm-automation/blob/main/workflow.png?raw=true)

### **Knowledge Base Indexing**
![Database Sync](https://github.com/Muneeb20019/mak-gym-rag-crm-automation/blob/main/database.png?raw=true)

---

## ✍️ Author

**Muneeb Ali Khan**
- **GitHub:** [@Muneeb20019](https://github.com/Muneeb20019)
- **LinkedIn:** [Muneeb Ali Khan](https://www.linkedin.com/in/muneeb-ali-khan-2a1675365)
