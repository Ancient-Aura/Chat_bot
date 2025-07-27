# 🤖 Aura Bot — Retrieval-Augmented Generation (RAG) System

Aura Bot is a Retrieval-Augmented Generation (RAG) system designed to provide context-aware answers by combining large language models with external knowledge sources. This notebook demonstrates a simplified RAG pipeline using modern NLP tools.

---

## 📁 Project Structure

- `Aura_bot_(RAG_System).ipynb`: Main notebook containing code and step-by-step implementation of the RAG system.
- `index/`: Index files (e.g. FAISS index).
- `models/`: Pre-trained model files (e.g. all-MiniLM-L6-v2).
- `app.py`: Main Python app for running the RAG bot.
- `Dockerfile`: Docker configuration for containerizing the app.
- `requirements.txt`: Python dependencies.

---

## 🚀 Features

- 🔍 **Document Retrieval** using embeddings
- 💬 **Context-aware Response Generation**
- 🧠 **Integration with pre-trained Language Models**
- 📦 Modular and easy to expand

---

## 🛠️ Tools & Libraries Used

- `LangChain`
- `FAISS`
- `SentenceTransformers`
- `PyPDFLoader` 

---

## 📌 How It Works

1. **Load Documents** from local PDFs or other formats
2. **Chunk & Embed** the documents
3. **Build Vector Store** using FAISS
4. **Retrieve** relevant chunks based on user query
5. **Generate Answer** using the retrieved context + LLM

---

## 📚 Use Cases

- Chatbots for documents or internal knowledge bases  
- Educational Q&A systems  
- Legal or technical document assistants

---

