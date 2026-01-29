🤖 RAG & LLM Powered AI Tutor

Intelligent Document-Aware Chatbot

<p align="center"> <img src="https://img.shields.io/badge/Python-3.9%2B-blue?style=for-the-badge"/> <img src="https://img.shields.io/badge/RAG-Enabled-success?style=for-the-badge"/> <img src="https://img.shields.io/badge/LLM-Powered-purple?style=for-the-badge"/> <img src="https://img.shields.io/badge/Multi--Tool-Supported-orange?style=for-the-badge"/> </p> <p align="center"> <strong>An AI Tutor powered by Retrieval-Augmented Generation (RAG), Large Language Models (LLMs), and multi-tool reasoning to answer questions directly from uploaded PDFs.</strong> </p>
🌟 Project Overview

This project is a document-aware AI Tutor that allows users to upload PDFs and ask natural language questions.
The system retrieves relevant chunks from the document and uses an LLM to generate accurate, grounded, and context-aware answers.

Unlike traditional chatbots, this system:

Reads your documents

Understands context

Uses tools when needed

Avoids hallucinations

🖼️ Application Screenshot
<p align="center"> <img src="assets/app_screenshot.png" alt="AI Tutor RAG Chatbot Screenshot" width="900"/> </p>

📌 The screenshot shows real-time PDF-based question answering using RAG, thread-based chat history, and an interactive Streamlit UI.

✨ Key Features

📄 PDF-Based Question Answering
Ask questions directly from uploaded documents.

🔍 RAG Retrieval Pipeline
Retrieves the most relevant chunks before generating responses.

🧠 LLM-Powered AI Tutor
Explains concepts, definitions, and exercises clearly.

🛠️ Multi-Tool Support
Uses retrieval, reasoning, and extensible tools dynamically.

🧵 Thread-Based Conversations
Maintains chat sessions with unique thread IDs.

🎨 Clean Streamlit UI
Simple, modern, and user-friendly interface.

🧠 How It Works
User Uploads PDF
       ↓
Document Chunking & Embeddings
       ↓
Vector Retrieval (RAG)
       ↓
LLM + Tool Reasoning
       ↓
Accurate Answer from Document

🛠️ Tech Stack
Layer	Technology
Language	Python 🐍
UI	Streamlit
LLM	OpenAI / Gemini / Hugging Face
Retrieval	Embeddings + Vector Store
Tools	Search, PDF Retrieval
Backend	Modular Python Architecture
📂 Project Structure
├── backend/
│   ├── retriever.py
│   ├── llm_handler.py
│   ├── tools.py
│   └── ingest_pdf.py
├── frontend/
│   └── app.py
├── data/
├── assets/
│   └── app_screenshot.png
├── requirements.txt
└── README.md

🚀 Getting Started
git clone https://github.com/Subham837/Rag-and-LLM-powered-AI-chatbot.git
cd Rag-and-LLM-powered-AI-chatbot

python -m venv venv
source venv/bin/activate  # Windows: venv\Scripts\activate

pip install -r requirements.txt
streamlit run app.py

🎯 Use Cases

📚 AI Tutor for students

📄 PDF-based question answering

🏢 Enterprise document assistants

🔬 Research & academic RAG systems

🔮 Future Enhancements

Agentic workflows (LangGraph / LangChain)

Conversation memory

FastAPI backend

Cloud deployment (HF Spaces)

Authentication & roles

👨‍💻 Author

Subham Pradhan 🇮🇳
Machine Learning & AI Enthusiast
🔗 GitHub: Subham837

⭐ Support

If you like this project, star ⭐ the repository to support the work!

