# 🧠 RAG App with Hugging Face + Groq (`llama3-70b-8192`)

This is a Retrieval-Augmented Generation (RAG) application built using **Streamlit**, **LangChain**, **FAISS**, **HuggingFace sentence transformers**, and **Groq’s LLaMA3 model** via LangChain's `ChatGroq` wrapper.

The app lets you upload a PDF, ask questions about its content, and receive intelligent answers powered by LLMs and semantic search.

---

## 🚀 Features

- 🧾 **PDF Document Loader** using `PyPDFLoader`
- 🧠 **Semantic Search** with Hugging Face MiniLM embeddings
- 🔍 **Vector Search** using FAISS
- 💬 **LLM Response Generation** via Groq (`llama3-70b-8192`)
- 🧪 **Prompt Template with Context Injection**
- 📄 **Document Viewer** for source context
- ⏱️ **Response Time Display**

---

## 🛠️ Setup Instructions

### 1. Clone the Repository

```bash
git clone https://github.com/your-username/rag-app-groq.git
cd rag-app-groq
```

### 2. Create and Activate Virtual Environment
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate

### 3. Install Dependencies
pip install -r requirements.txt

### 4. Set Up Environment Variables
Create a .env file in the root directory and add your Groq API key:

GROQ_API_KEY=your_groq_api_key_here

### Technologies Used
Streamlit

LangChain

Hugging Face Sentence Transformers

Groq API

FAISS Vector Store
---

### Future Scope
This project has great potential for expansion and can evolve into a robust document intelligence or enterprise search platform. Here are some planned or possible enhancements:

 Dynamic PDF Upload

Replace the hardcoded PDF path with a Streamlit file uploader so users can upload their own documents directly through the UI.

 Multi-Document Support

Allow users to query across multiple uploaded PDFs or an entire folder of documents.

 RAG with Local Models

Add support for running inference on local models (e.g., via Ollama or Transformers) to reduce latency and API costs.


