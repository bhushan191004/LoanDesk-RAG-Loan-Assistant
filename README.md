# 🏦 Loan Desk – Smart Loan Assistant (RAG-based AI System)

## 🚀 Overview
Loan Desk is an AI-powered assistant that helps users analyze and understand complex loan agreements and financial documents. Instead of manually reading long PDFs, users can upload documents and ask questions to get instant, context-aware answers.

The system uses a Retrieval-Augmented Generation (RAG) pipeline to combine semantic search with Large Language Models (LLMs) for accurate and efficient document analysis.

---

## 🧠 How It Works
1. User uploads a loan document (PDF)
2. Document is split into meaningful chunks
3. Text is converted into embeddings
4. Stored in a vector database
5. User query retrieves relevant context
6. LLM generates a structured answer

---

## ⚙️ Tech Stack
- Python
- LangChain
- ChromaDB (Vector Database)
- Gradio (UI)
- Groq (Llama 3.3 70B)
- Sentence Transformers (`all-MiniLM-L6-v2`)

---

## 🔥 Features
- 📄 PDF document analysis  
- 🔍 Semantic search using embeddings  
- ⚡ Fast LLM-based responses  
- 💬 Interactive UI for real-time querying  
- 📊 Context-aware financial insights  

---

## ▶️ Run the Project

### Option 1: Google Colab
[Open in Colab](PASTE_YOUR_COLAB_LINK_HERE)

### Option 2: Local Setup

1. Clone the repository:
```bash
git clone https://github.com/YOUR_USERNAME/loan-desk-rag-ai.git
cd loan-desk-rag-ai
