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
[Open in Colab](https://colab.research.google.com/drive/1cWTH1kui2pI1QdWr-yzsGQLPM3Ga1k94?usp=sharing)

### Option 2: Local Setup

1. Clone the repository:
```bash
git clone https://github.com/YOUR_USERNAME/loan-desk-rag-ai.git
cd loan-desk-rag-ai

### 2. Install Dependencies

### 3. Get Your API Key
- Go to Groq Cloud  
- Sign up / login  
- Generate your API key  

### 4. Set API Key

#### In Google Colab:
import os
os.environ["GROQ_API_KEY"] = "your_api_key_here"
#### In Windows (PowerShell):
setx GROQ_API_KEY "your_api_key_here"

---

### 5. Run the Project

#### In Jupyter / Colab:
- Run all cells step-by-step  

#### Locally:
python your_script_name.py

---

### 6. Use the Application
- Upload a loan PDF document  
- Ask questions like:
  - What is the interest rate?
  - Are there penalties?
  - What are the repayment terms?
- Get instant AI-generated insights  

---

## ▶️ Run in Google Colab
[Open in Colab](PASTE_YOUR_COLAB_LINK_HERE)

---

## 🔐 API Key Setup
import os
os.environ["GROQ_API_KEY"] = "your_api_key_here"

---

## 📸 Demo
<img width="1889" height="813" alt="Screenshot 2026-05-02 164134" src="https://github.com/user-attachments/assets/05136447-aa2d-49e7-8998-c4141249847a" />

<img width="1896" height="977" alt="Screenshot 2026-05-02 163542" src="https://github.com/user-attachments/assets/1b37c501-f1c6-4688-a4d6-1b219353f613" />

---

## 📌 Future Improvements
- Multi-query retrieval for better accuracy  
- Chat memory for conversation context  
- Highlight relevant sections in PDF  
- Confidence scoring for responses  

---

## 🧠 Learning Outcome
This project demonstrates practical implementation of:
- Retrieval-Augmented Generation (RAG)
- Semantic search using embeddings
- LLM integration for real-world applications

---

## 👨‍💻 Author
Bhushan Walunj  
LinkedIn: https://www.linkedin.com/in/bhushan-walunj-3432b91ba/  
GitHub: https://github.com/YOUR_USERNAME
