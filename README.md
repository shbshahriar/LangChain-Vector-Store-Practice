#  LangChain Vector Store Practice with ChromaDB + Google Embeddings

This repository showcases a **hands-on practice project** using **LangChain**, **ChromaDB**, and **Google Generative AI embeddings**. It demonstrates how to build a local vector store, add documents with metadata, perform semantic search, and manage (update/delete) vectorized knowledge — all in a modular, extendable setup.

---

## 🚀 Key Features

- 📄 Create and manage text-based documents  
- 🧠 Generate vector embeddings using `text-embedding-004` (Google)  
- 🔍 Perform semantic similarity search  
- 🎯 Filter searches using document metadata  
- ✏️ Update or delete documents from the vector store  
- 💾 Persist locally using ChromaDB  

---

## 🛠️ Tech Stack

- **LangChain** – Framework for building with LLMs  
- **ChromaDB** – Lightweight local vector database  
- **Google Generative AI** – Embedding provider  
- **LangChain Loaders** – Document abstraction and metadata support  
- **Python 3.9+**  

---

## 📦 Installation

Install all required libraries:

```bash
pip install langchain chromadb openai tiktoken pypdf langchain_openai langchain-community google-generativeai
```

Or use the `requirements.txt`:

```bash
pip install -r requirements.txt
```

---

## 🔑 Environment Setup

Set your Google API key (required for generating embeddings):

```python
import os
os.environ["GOOGLE_API_KEY"] = "your-api-key-here"
```

> ⚠️ Always keep your API key secret. Avoid hardcoding it in production.

---

## 📁 Project Structure

```
.
├── my_chroma_db/        # Vector database storage  
├── main.py              # Main script  
├── requirements.txt     # All dependencies  
└── README.md            # This file  
```

---

## 🎯 Use Case Ideas

- Embedding practice for academic content or lecture notes  
- Local chatbot memory store  
- PDF or web scraping pipelines (with future integration)  
- Custom knowledge base for personal productivity tools  

