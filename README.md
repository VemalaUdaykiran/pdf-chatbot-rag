# 🤖 AI-Powered PDF Chatbot (RAG)

An intelligent chatbot that allows users to upload PDF documents and ask questions based on their content. This project uses **Retrieval-Augmented Generation (RAG)** to provide accurate and context-aware answers.

---

## 🚀 Features
- 📄 Upload PDF documents  
- 💬 Ask questions in natural language  
- ⚡ Real-time responses  
- 🧠 Context-aware answers using RAG pipeline  
- 🔍 Semantic search using vector embeddings  

---

## 🛠️ Tech Stack
- **Python**
- **Streamlit** (UI)
- **LangChain** (RAG pipeline)
- **FAISS** (Vector database)
- **OpenAI** (LLM & embeddings)
- **pdfplumber** (PDF text extraction)

---

## 🧠 How It Works
1. Extract text from uploaded PDF  
2. Split text into smaller chunks  
3. Convert chunks into embeddings  
4. Store embeddings in FAISS vector database  
5. Retrieve relevant chunks based on user query  
6. Generate answer using LLM with retrieved context  

---

