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

## 📂 Folder Structure


---

## 🛠️ Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/your-username/medibot-rag-chatbot.git
   cd medibot-rag-chatbot
Install dependencies

bash
Copy
Edit
pip install -r requirements.txt
Set up .env file
Create a .env file in the root directory:

env
Copy
Edit
HF_TOKEN=your_huggingface_api_token
🧪 Run the App
bash
Copy
Edit
streamlit run app.py
📌 Requirements
text
Copy
Edit
streamlit
langchain
huggingface_hub
python-dotenv
faiss-cpu
sentence-transformers
