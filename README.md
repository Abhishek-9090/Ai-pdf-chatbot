
# 📚 AI PDF Chatbot (RAG-based Conversational QA System)

An end-to-end Retrieval-Augmented Generation (RAG) based AI chatbot that enables users to upload PDF documents and interact with them using natural language queries. The system performs intelligent document retrieval using semantic search and generates context-aware responses with Large Language Models (LLMs).

---

## 🚀 Features

- 📄 Upload and process multiple PDF documents
- ✂️ Intelligent text chunking for efficient retrieval
- 🧠 Semantic search using vector embeddings
- 🤖 Context-aware answers using LLMs
- 💬 Conversational memory for multi-turn chat
- ⚡ Interactive Streamlit user interface
- 🔄 Support for OpenAI and HuggingFace embeddings

---

## 🧠 RAG Pipeline

1. **PDF Ingestion** → Extract text using PyPDF2  
2. **Chunking** → Split text into smaller overlapping chunks  
3. **Embeddings** → Convert chunks into vector embeddings  
4. **Vector Store** → Store embeddings using FAISS  
5. **Retrieval** → Fetch relevant chunks for user query  
6. **LLM Generation** → Generate context-aware response  
7. **Memory** → Maintain chat history for conversations  

---

## 🛠️ Tech Stack

- **Language:** Python  
- **Frameworks/Libraries:** LangChain, Streamlit  
- **LLM:** OpenAI  
- **Vector Database:** FAISS  
- **Embeddings:** HuggingFace / OpenAI  
- **PDF Processing:** PyPDF2  
- **Environment Management:** python-dotenv  

---

## 📂 Project Structure

```bash
AI-PDF-Chatbot/
│── app.py
│── htmlTemplates.py
│── requirements.txt
│── .env
│── README.md