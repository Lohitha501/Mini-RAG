# 🤖 Mini-RAG

A simple **Retrieval-Augmented Generation (RAG)** project that extracts information from PDF documents, creates embeddings, stores them in ChromaDB, and retrieves relevant content based on user questions.

## ✨ Features

- 📄 PDF document processing
- ✂️ Text chunking
- 🧠 Sentence Transformer embeddings
- 🗄️ ChromaDB vector storage
- 🔎 Semantic search
- 💬 Question-based information retrieval

## 🛠️ Tech Stack

**Language:** Python  
**Libraries:** LangChain, ChromaDB, PyPDF, Sentence Transformers  
**Model:** `all-MiniLM-L6-v2`

## 🔄 How It Works

```text
PDF Document
     ↓
Extract Text
     ↓
Split into Chunks
     ↓
Create Embeddings
     ↓
Store in ChromaDB
     ↓
Ask a Question
     ↓
Retrieve Top 3 Results
