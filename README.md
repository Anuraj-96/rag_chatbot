# RAG with Google's Gemini 1.5 Flash 🚀
This project implements a **Retrieval Augmented Generation (RAG)** system using **Google's Gemini 1.5 Flash model** with LangChain.  
It allows multiple users to query a knowledge base (backed by vector search) and get concise, context-aware answers.

---

## ✨ Features
- Uses **Gemini 1.5 Flash** for fast, cost-efficient responses.
- **Web document ingestion** via `WebBaseLoader`.
- **Text chunking** with `RecursiveCharacterTextSplitter`.
- **Chroma vectorstore** for semantic search and retrieval.
- **Custom system prompts** for concise answers (max 3 sentences).
- Integrated with **LangSmith** for observability and tracing.

---

## 🛠️ Tech Stack
- [LangChain](https://www.langchain.com/)
- [Google Gemini API](https://ai.google.dev/)
- [ChromaDB](https://www.trychroma.com/)
- Python

---

