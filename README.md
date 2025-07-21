# 📄 Conversational RAG with PDF Upload and Chat History

This project implements a **Conversational Retrieval-Augmented Generation (RAG)** system that allows users to:
- Upload a PDF 📑
- Ask context-aware questions 🤖
- View history-aware responses using **LLMs** from **Groq API**
- Persist chat sessions using **Streamlit state management**

---

## 🚀 Features

- ✅ Upload single PDF and extract content
- ✅ Chunking and vectorization using HuggingFace Embeddings + ChromaDB
- ✅ Chat history tracking using LangChain's `RunnableWithMessageHistory`
- ✅ Question reformulation using contextual prompts
- ✅ Real-time responses powered by Groq LLMs (e.g. `Gemma2-9b-It`)
- ✅ Clean Streamlit UI

---

## 🧠 Tech Stack

- **LangChain**: Chains, prompts, chat history management
- **Groq LLMs**: Ultra-fast inference using `llama3` or `gemma`
- **HuggingFace Embeddings**: `all-MiniLM-L6-v2` for semantic search
- **ChromaDB**: Local vectorstore
- **Streamlit**: UI interface
- **PDF Parsing**: `PyPDFLoader`

---

## 🛠️ Setup

### 1. Clone the Repository

```bash
git clone https://github.com/your-username/conversational-rag-pdf.git
cd conversational-rag-pdf
