# 📧 Customer Support Workflow (n8n)

![n8n](https://img.shields.io/badge/automation-n8n-blue?style=flat-square)  
![OpenAI](https://img.shields.io/badge/AI-OpenAI-success?style=flat-square)  
![License](https://img.shields.io/badge/license-MIT-orange?style=flat-square)

An **AI-powered customer support workflow** built with [n8n](https://n8n.io/) that **automatically receives, classifies, and responds to customer inquiries** with friendly, accurate, and personalized messages — ensuring faster resolutions and a better customer experience.

---

## ✨ Features
- 🔄 **Automated Inquiry Handling** – Processes incoming emails instantly.
- 🧠 **AI-Powered Classification** – Categorizes messages into *Customer Support* or *Other* using OpenAI.
- 📚 **Knowledge Base Integration** – Fetches relevant answers from your support knowledge base.
- 💬 **Friendly & Accurate Replies** – Ensures brand-consistent tone in responses.
- 🏷 **Gmail Labeling** – Tags processed messages for easy tracking.
- 🚫 **Smart Filtering** – Ignores irrelevant or non-support inquiries.

---

## 🗺 Workflow Overview
![Workflow](workflow.png)

*Figure: The n8n workflow that powers automated customer support, integrating AI for classification and response generation.*

### Step-by-Step Process
1. **📥 Gmail Trigger**  
   Detects incoming customer emails.
2. **🏷 Text Classifier (AI)**  
   Categorizes the inquiry via OpenAI Chat Model.
3. **🔀 Routing Decision**  
   - *Customer Support* → Sends to AI Agent.  
   - *Other* → Stops workflow.
4. **🤖 AI Agent + Knowledge Base**  
   Generates accurate, friendly, and context-aware responses.
5. **📌 Gmail Labeling & Reply**  
   Adds a label (e.g., `Customer Support – Replied`) and sends the AI-generated response.

---

## 🛠 Tech Stack
- **[n8n](https://n8n.io/)** – Automation platform for building workflows.
- **OpenAI API** – For classification, embeddings, and response generation.
- **Gmail API** – For email retrieval, labeling, and sending.
- **Vector Embeddings** – For relevant knowledge retrieval.

---

## 🚀 Benefits
- Saves time by automating repetitive customer service tasks.
- Reduces human error in classification and replies.
- Ensures consistent tone and brand voice.
- Scales easily as your customer base grows.


