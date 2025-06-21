
# 🧠 RAG Chatbot

A **Retrieval-Augmented Generation (RAG)** based chatbot that combines the power of language models with relevant document data to give more accurate and contextual responses.

---

## 📌 Project Overview

This project implements a chatbot that uses **RAG (Retrieval-Augmented Generation)** architecture. The chatbot is capable of fetching relevant information from custom data sources and generating intelligent responses, making it suitable for tasks like FAQ answering, customer support, document querying, etc.

---

## 🚀 Features

- Custom document ingestion & vectorization
- Real-time semantic search using vector similarity
- GPT-powered natural language generation
- Easy-to-use notebook-based interface
- Fully customizable data sources

---

## 🛠️ Tech Stack

- **Python**
- **LangChain**
- **FAISS** for vector store
- **Hugging Face Transformers / OpenAI API** for LLM
- **Jupyter Notebook** for interactive workflow

---

## 📂 File Structure

```
📦RAG_Application.ipynb  - Main notebook with complete RAG implementation
```

---

## 📋 How It Works

1. Load and process custom documents.
2. Convert documents into vector embeddings.
3. Store embeddings in a FAISS vector store.
4. Use a retriever to fetch top-k relevant chunks.
5. Feed chunks + query to LLM for response generation.

---

## ✅ Requirements

Install dependencies using:

```bash
pip install -r requirements.txt
```

Or manually:

```bash
pip install langchain faiss-cpu openai python-dotenv
```

---

## 👨‍💻 Author

Created by **Anurag Tripathi**

---
