# GYM AI Chatbot: Instagram CRM & Knowledge Assistant 🤖

![Workflow](https://img.shields.io/badge/Workflow-n8n-EF5B25) ![Database](https://img.shields.io/badge/Vector%20DB-Pinecone-000000) ![AI](https://img.shields.io/badge/AI-Google%20Gemini-4285F4) ![CRM](https://img.shields.io/badge/CRM-Google%20Sheets-34A853)

An enterprise-grade AI orchestration engine built for **Fitness GYM**. This system transforms Instagram into a high-conversion sales channel by combining **Retrieval-Augmented Generation (RAG)** with automated CRM workflows—built natively on **n8n** to eliminate the need for expensive third-party middlemen.

---

## 📸 System Architecture & Preview
![Chatbot Interaction](IG%20Message.png)
*Real-time interaction: AI retrieving gym facts from Pinecone while maintaining the sales funnel.*

---

## 🏆 The Competitive Edge: The Power of Open Integration
The standout feature of this project is its **Direct-to-API** architecture. Most Instagram bots are "closed systems" (like ManyChat or Chatfuel) that trap your data and limit your logic.

**Why this system is superior:**
*   **🔗 Universal Integration:** Unlike standard bots, this solution can be integrated with **any third-party tool** (Payment gateways, ERPs, specialized APIs) without restriction.
*   **🧠 Limitless Logic:** Standard builders cannot handle advanced math. This bot performs real-time **BMI calculations** and **Vector Database lookups**—logic impossible in closed-ecosystem bots.
*   **💰 Extreme Cost Efficiency:** By cutting out middlemen like ManyChat, this system runs at a flat rate, regardless of how many thousands of leads you capture.
*   **🛡️ Data Sovereignty:** You own the "Brain" and the data. Your leads move directly from Instagram to your private Google Sheets/Pinecone database.

---

## 💰 Cost Analysis & ROI (Monthly Estimation)
Using an **n8n-centric** stack provides a superior return on investment by removing "per-subscriber" taxes and third-party platform markups.

### **Option A: Our n8n AI Chatbot Solution (This Project)**
| Service | Plan | Est. Cost |
| :--- | :--- | :--- |
| **n8n Orchestration** | Self-hosted / Starter | $0 - $20 |
| **Google Gemini** | AI Studio (Free Tier) | $0 |
| **Pinecone DB** | Serverless Tier | $0 |
| **Google Sheets** | API (Free) | $0 |
| **Total** | | **~$20 / mo** |

### **Option B: Closed SaaS Platforms (ManyChat/Chatfuel)**
| Service | Plan | Est. Cost |
| :--- | :--- | :--- |
| **ManyChat Pro Fee** | Base Fee + 2.5k Subs | $40 |
| **AI Add-on Fee** | Extra Credits for GPT | $20 |
| **Integration Premium**| Fees for External API Sync| $40 |
| **Total** | | **~$100+ / mo** |

**💡 Financial Impact:** This custom solution saves the business **~$1200+ per year** while providing unlimited scalability and infinitely more complex logic.

---

## ✨ Key Features

*   **🧠 RAG-Powered Knowledge:** Utilizes a **Pinecone Vector Database** to answer complex questions about gym fees, location (**Rufi Lake**), and rules with 100% accuracy from an official manual.
*   **📋 Automated Lead Onboarding:** A multi-step conversational protocol that captures Full Name, WhatsApp, and Fitness Goals.
*   **⚖️ Live Health Logic:** Custom AI logic to calculate a user's **BMI** in real-time during the chat, providing immediate health value to the prospect.
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

### **Main Conversation Engine**
Incoming Webhooks are processed through an **AI Agent** equipped with a **Simple Memory** node. This allows the bot to handle "Distracted Conversations"—answering a question about parking in the middle of a signup process without forgetting the user's name.

![Main Workflow](IG%20chatbot.png)

### **Knowledge Base Indexing (RAG Pipeline)**
By utilizing **768-dimension semantic embeddings**, the bot performs a "Similarity Search" in Pinecone. A background workflow watches Google Drive and automatically re-indexes the data.

![Database Sync](IG%20Databse.png)

---

## ✍️ Author

**Muneeb Ali Khan**
- **GitHub:** [@Muneeb20019](https://github.com/Muneeb20019)
- **LinkedIn:** [Muneeb Ali Khan](https://www.linkedin.com/in/muneeb-ali-khan-2a1675365)
