# 🧠 MediBot – RAG-based Medical PDF Chatbot

MediBot is an AI-powered chatbot designed to provide context-aware answers from medical PDF documents. It uses **LangChain**, **Hugging Face Inference API**, **FAISS**, and **Streamlit** to enable Retrieval-Augmented Generation (RAG). Simply upload a medical PDF, and MediBot can answer your queries intelligently using the document content.

---

## 🚀 Features

- 💬 Conversational chatbot interface using **Streamlit**
- 🧠 RAG (Retrieval-Augmented Generation) powered by **LangChain**
- 🩺 PDF-based document ingestion (example: `the_gayle-enclopedia_of_medicne.pdf`)
- 🤖 LLM from **Hugging Face Inference Endpoints**
- 🗃️ Vector storage using **FAISS**
- 🎨 Clean and user-friendly chat interface (no sidebar distractions)

---
medibot-rag-chatbot/
├── app.py # Main Streamlit chatbot app
├── vectorstore/ # FAISS vector database folder
│ └── db_faiss/ # FAISS index files created from the PDF
├── data/ # Folder to store your medical PDFs
│ └── the_gayle-enclopedia_of_medicne.pdf
├── .env # Your Hugging Face API key
├── requirements.txt # Required Python packages
└── README.md

python -m venv venv
source venv/bin/activate     # On Linux/macOS
venv\Scripts\activate        # On Windows

HF_TOKEN=your_huggingface_api_token

streamlit run app.py

