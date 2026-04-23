

## Company: Highwatch AI - Trial Assignment

## 🔗 Live Notebook
Run directly in Google Colab:
https://colab.research.google.com/drive/1PzHYnocfa1lA-vdZVDYrRXJt6org2Jgt?usp=sharing

## 🚀 What This Does
Your personal ChatGPT over Google Drive.
Upload store documents to Google Drive — ask any question — get instant AI answers.

## ✅ Features Completed
- Google Drive Integration (OAuth)
- Document Processing and Chunking
- SentenceTransformers Embeddings (all-MiniLM-L6-v2)
- FAISS Vector Store
- Q&A with Groq LLM (llama-3.3-70b-versatile)
- Caching (same question = instant reply)
- Metadata Filtering (filter by specific file)
- Async Pipeline (multiple questions simultaneously)
- Incremental Sync (only changed files re-processed)
- Gradio UI

## 🏗️ Architecture
- connectors/ - Google Drive Integration
- processing/ - Text extraction and chunking
- embedding/ - SentenceTransformers
- search/ - FAISS vector store
- api/ - FastAPI endpoints

## 📦 Tech Stack
- Python
- SentenceTransformers
- FAISS
- Groq LLM
- Google Drive API
- Gradio

## ⚙️ Setup
1. Open Colab notebook above
2. Mount Google Drive
3. Add GROQ_API_KEY
4. Run all cells

## 💬 Sample Q&A


Q: What is the return policy?
A: Returns accepted within 7 days. Damaged or wrong items eligible for return.

Q: What is the price of Linen Saree?
A: The price of Linen Saree is 1100 rupees.

Q: What are delivery charges?
A: Zone 1 Local 40 rupees, Zone 2 60 rupees, Zone 3 Tamil Nadu 80 rupees.

Q: What is the exchange policy?
A: Exchange allowed within 15 days with original bill.
<img width="1919" height="867" alt="Screenshot 2026-04-23 212137" src="https://github.com/user-attachments/assets/1560372a-9c63-46b7-8d8d-58fd8b915b47" />
<img width="1903" height="848" alt="Screenshot 2026-04-23 212247" src="https://github.com/user-attachments/assets/887c9478-f5ac-40dc-8c02-41b88ae81ccc" />
<img width="1913" height="852" alt="Screenshot 2026-04-23 212319" src="https://github.com/user-attachments/assets/3545609b-a325-4eb3-96e4-68b4da98c2cd" />
<img width="1919" height="869" alt="Screenshot 2026-04-23 212412" src="https://github.com/user-attachments/assets/4ea5c3bd-6213-4727-8910-9b558e3a75a5" />
<img width="1919" height="864" alt="Screenshot 2026-04-23 212616" src="https://github.com/user-attachments/assets/759865cc-89ad-46f2-b6a8-f5b8de6d3504" />






## 📂 Documents Used
- dress_catalog.docx - 100 products
- company_policy.docx - Return, exchange, refund rules
- order_status.docx - 50 customer orders
- delivery_policy.docx - Zone wise charges
- complaint_policy.docx - Complaint escalation
- shop_timing_contact.docx - Store info and timings

## 👩‍💻 Author
Sinega M
