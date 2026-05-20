
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


⚙️ Installation
1️⃣ Clone the Repository
Bash
git clone https://github.com/Abhishek-9090/ai-pdf-chatbot.git
cd ai-pdf-chatbot
2️⃣ Install Dependencies
Bash
pip install -r requirements.txt
3️⃣ Add API Key
Create a .env file and add:
Environment
OPENAI_API_KEY=your_api_key_here
4️⃣ Run the Application
Bash
streamlit run app.py

💡 Future Improvements
Support for DOCX and TXT files
Voice-enabled chatbot
Advanced vector databases
Authentication system
Cloud deployment

📌 Key Concepts Learned
Retrieval-Augmented Generation (RAG)
Vector Embeddings
Semantic Search
Conversational AI
LangChain Workflows
LLM Integration
Vector Databases

Author
Abhishek Mishra
GitHub: https://github.com/Abhishek-9090⁠�
LinkedIn: https://www.linkedin.com/in/abhishek-mishra-0076952a7⁠�
Portfolio: https://abhishek-mishra-ai-nm6sctr.gamma.site/⁠�