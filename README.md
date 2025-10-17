[README.md](https://github.com/user-attachments/files/22965454/README.md)
# 🧩 RAG Pipeline (n8n Cloud + Pinecone + AI Agent)

This project is a **Retrieval-Augmented Generation (RAG)** pipeline built entirely on **n8n Cloud** — no coding required.

It connects:
- **AI Agent node** for question answering  
- **Pinecone vector store** for semantic document retrieval  
- **Chat Trigger** for interactive querying  

---

## 🚀 How It Works
1. User asks a question (e.g., “What is our refund policy?”)  
2. The **AI Agent** sends the query to **Pinecone**  
3. Pinecone retrieves the most relevant document chunk  
4. The AI Agent uses that context to generate an accurate response  

---

## 💡 Example Queries
> **Q:** What is our refund policy?  
> **A:** If you’re not completely satisfied with your purchase, you may request a return within 7 days of receiving your order...

> **Q:** Where is your return address?  
> **A:** 25 Allen Avenue, Ikeja, Lagos, Nigeria.

---

## 🛠 How to Use
1. Open [n8n.io](https://n8n.io) and log into your workspace.  
2. Click **Import Workflow** and upload `rag-pipeline-n8n.json`.  
3. Add your **Pinecone API key** and **OpenAI key** in Credentials.  
4. Execute or trigger the workflow — it’s ready to use!  

---

## 👩‍💻 Author
**Jane Ifeoma Ugwu**  
📧 bestjaneugwu@gmail.com  
🇳🇬 Nigerian Air Force | AI & Automation Enthusiast  

---

## 🪪 License
MIT License

