# 🧠 MediBot – RAG-based Medical PDF Chatbot

MediBot is an AI-powered chatbot designed to provide context-aware answers from medical PDF documents.  
It uses **LangChain**, **Hugging Face Inference API**, **FAISS**, and **Streamlit** to enable Retrieval-Augmented Generation (RAG).  
Simply upload a medical PDF, and MediBot can answer your queries intelligently using the document content.

---

## 🚀 Features

- 💬 Conversational chatbot interface using **Streamlit**  
- 🧠 RAG (Retrieval-Augmented Generation) powered by **LangChain**  
- 🩺 PDF-based document ingestion (example: `the_gayle-enclopedia_of_medicne.pdf`)  
- 🤖 LLM from **Hugging Face Inference Endpoints**  
- 🗃️ Vector storage using **FAISS**  
- 🎨 Clean and user-friendly chat interface (no sidebar distractions)

---

---

## ⚙️ Installation & Setup

### 1. Clone the repository

```bash
git clone https://github.com/your-username/medibot-rag-chatbot.git  
cd medibot-rag-chatbot  
2. Create and activate a virtual environment
bash
Copy
Edit
python -m venv venv  
source venv/bin/activate           # On Linux/macOS  
venv\Scripts\activate              # On Windows  
3. Install dependencies
bash
Copy
Edit
pip install -r requirements.txt  
4. Add your Hugging Face API token
Create a .env file in the root directory and add your Hugging Face token:

env
Copy
Edit
HF_TOKEN=your_huggingface_api_token  
Make sure your token has Inference Endpoint permissions.

5. Add your PDF
Place your medical PDF file in the data/ folder.
Example: data/the_gayle-enclopedia_of_medicne.pdf

▶️ Run the Chatbot
bash
Copy
Edit
streamlit run app.py  
Then open your browser at:
http://localhost:8501

🧪 Example Query
User: What is hypertension and how is it treated?
MediBot: (Retrieves the answer from the uploaded PDF content)

📦 requirements.txt
text
Copy
Edit
streamlit  
langchain  
huggingface_hub  
python-dotenv  
faiss-cpu  
sentence-transformers  
🙌 Acknowledgments
🤗 Hugging Face

🔗 LangChain

💡 Streamlit

🔍 Sentence Transformers

