## HeiFinance AI Email Assistant ⚡

**Overview**

This project was built as a capstone case study at Heicoders Academy.

The case highlighted core challenges faced by HeiFinance Bank:

1. Overwhelmed customer support staff handling repetitive product enquiries.

2. Inconsistent responses leading to customer confusion.

3. Slow turnaround time, especially for simple fact-based questions (e.g., deposit requirements, interest rates).

The solution: an AI-driven email assistant implemented in n8n, integrated with OpenAI and Pinecone, to automate accurate and natural replies to customer emails.

**Solution**

This workflow (heifinance_final_workflow.json) turns Gmail + n8n + OpenAI + Pinecone into a 24/7 AI email assistant:

1. Catch & Learn – Grabs new emails and updates factsheets from Google Drive.

2. Understand & Retrieve – Splits text, builds embeddings, and pulls exact product facts.

3. Respond Smartly – Drafts natural, accurate replies with strict guardrails (no hallucinations, numbers copied verbatim).

4. Close the Loop – Creates Gmail drafts and marks emails as processed.

Why It Wins
<br> ✅ Instant, consistent responses
<br> ✅ Facts always up-to-date
<br> ✅ Saves support teams hours
<br> ✅ Scales as queries grow

Quick Start

1. Import the JSON into n8n.

2. Add Gmail, Drive, OpenAI, and Pinecone credentials.

3. Activate. Watch your inbox calm down. 🧘
