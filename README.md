# HeiFinance AI Email Assistant ⚡  

[![Built with n8n](https://img.shields.io/badge/Built%20with-n8n-4A90E2?logo=n8n&logoColor=white)](https://n8n.io)  
[![Powered by OpenAI](https://img.shields.io/badge/Powered%20by-OpenAI-412991?logo=openai&logoColor=white)](https://openai.com)  
[![Vector DB: Pinecone](https://img.shields.io/badge/Vector%20DB-Pinecone-3DDC84?logo=pinecone&logoColor=white)](https://www.pinecone.io/)  
[![Email via Gmail](https://img.shields.io/badge/Email-Gmail-EA4335?logo=gmail&logoColor=white)](https://mail.google.com)  

---

### 📌 Overview  
This project was developed as a capstone case study at **Heicoders Academy**.  

HeiFinance Bank faced three key challenges in its customer support operations:  
1. High volumes of repetitive product-related enquiries  
2. Inconsistent responses leading to customer uncertainty  
3. Delays in turnaround, even for straightforward queries  

**The solution:** an AI-driven email assistant built in **n8n**, leveraging **OpenAI** and **Pinecone**, to deliver accurate, timely, and professional replies.  

---

### 🔧 Solution  
The workflow (`heifinance_final_workflow.json`) integrates seamlessly with Gmail, Google Drive, OpenAI, and Pinecone to function as a **24/7 AI support assistant**:  

1. **Catch & Learn** – Captures incoming emails and updates product factsheets automatically  
2. **Understand & Retrieve** – Splits documents, builds embeddings, and retrieves precise information  
3. **Respond with Accuracy** – Generates clear, professional replies with strict fact-checking guardrails  
4. **Close the Loop** – Creates Gmail drafts and marks emails as processed for smooth workflow management  

---

### ✅ Benefits  
- Consistent and reliable responses  
- Always aligned with the latest product information  
- Significant time savings for support teams  
- Scalable to meet growing customer demand  

---

### 🚀 Quick Start  
1. Import the JSON into **n8n**  
2. Add your **Gmail, Drive, OpenAI, and Pinecone credentials**  
3. Activate → watch your inbox handle itself 🧘  

---
