# 🤖 GenAI Legal Assistant (RAG-Based Chatbot)

An advanced **Generative AI-based Legal Assistant System** that provides intelligent, context-aware legal responses using Retrieval-Augmented Generation (RAG) and multimodal input processing.

---

## 🚀 Overview

This project is designed to simplify legal information access by combining **Large Language Models (LLMs)** with **vector-based retrieval systems**.

Unlike traditional chatbots, this system:

* Understands documents
* Extracts text from images and audio
* Generates responses based on actual legal context

---

## 🧠 Key Features

* 💬 AI-powered legal query answering
* 📄 Document analysis (PDF, DOCX, TXT)
* 🖼️ OCR-based image text extraction
* 🎤 Voice input → speech-to-text processing
* 🔍 Context-aware responses using RAG
* 🧠 Semantic search using FAISS vector store
* 🔐 User authentication & chat history
* 🌐 Interactive frontend interface

---

## ⚙️ System Architecture

The system follows a **RAG (Retrieval-Augmented Generation) pipeline**:

1. User input (text / document / image / audio)
2. Convert input to text (OCR / speech-to-text)
3. Generate embeddings
4. Store & retrieve context using FAISS
5. Pass context + query to LLM
6. Generate accurate response

---

## 🧰 Tech Stack

### GenAI Components

* LLMs (Groq, Google Generative AI)
* LangChain
* FAISS (Vector Store)
* HuggingFace Embeddings

### Backend

* Python
* FastAPI
* SQLite

### Frontend

* React.js
* JavaScript

### Tools

* Tesseract OCR
* SpeechRecognition

---

## 📋 Prerequisites

* Python 3.8+
* pip
* Node.js
* npm

---

## ⚙️ Setup Instructions

### 1. Clone Repository

```bash
git clone https://github.com/mounikapindi357/Legal_chatbot
cd Legal_chatbot
```

---

### 2. Backend Setup

```bash
cd backend
pip install -r requirements.txt
```

Create `.env` file:

```env
GROQ_API_KEY=your_key_here
GOOGLE_API_KEY=your_key_here
```

---

### 3. Install Tesseract OCR

Download:
https://github.com/UB-Mannheim/tesseract/wiki

Update path in backend if needed.

---

### 4. Frontend Setup

```bash
cd ../frontend
npm install
```

---

## ▶️ Run the Application

### Backend

```bash
cd backend
uvicorn app:app --reload
```

---

### Frontend

```bash
cd frontend
npm start
```

---

## 🧠 How It Works

* Converts all input into structured text
* Uses embeddings for semantic understanding
* Retrieves relevant legal data using FAISS
* Generates responses using LLMs
* Maintains conversation context for better answers

---

## 📁 Project Structure

```
legal-chatbot/
│
├── backend/
├── frontend/
└── README.md
```

---

## ⚠️ Notes

- `.env` file is excluded to protect sensitive API keys  
- Large folders (e.g., node_modules, venv, vector stores) are ignored via `.gitignore`  
- This project is developed for educational and research purposes in the GenAI domain  

---

## 🔮 Future Enhancements

* Fine-tuned legal LLM
* Real-time legal API integration
* Multilingual improvements
* Cloud deployment

---

## 📌 Domain

**Generative AI (GenAI) – Legal Tech Application using RAG Architecture**
