# CTSE Lecture Notes Chatbot 📚🤖

This project involves developing a chatbot that can answer questions based on **CTSE lecture notes**. The chatbot uses **Large Language Models (LLMs)** integrated with the **LangChain** framework and **Groq API** to process and generate responses. The system uses **FAISS** for document retrieval and **HuggingFaceEmbeddings** for generating document embeddings, allowing the chatbot to provide accurate answers to user queries.

---

## 🚀 Features

- **✅Retrieval-Augmented Generation (RAG)** using FAISS for semantic search.
- **🧠 LLM-powered Q&A** via **Groq API** for natural and coherent responses.
- 📄Supports **PDF** and **PowerPoint** lecture note uploads.
- 🎛️ Simple and responsive **Streamlit based UI** for easy interaction with the chatbot.
- **Local and cloud deployment** options available.

---

## 🛠️ Tech Stack

- **Python**
- **LangChain**
- **Groq API**
- **FAISS (vector store for similarity search)**
- **Hugging Face Embeddings**
- **Streamlit (web interface)**

---

## 📦 Installation & Setup

### 1. Clone the Repository

```bash
git clone https://github.com/it21159480/chatbot.git
cd chatbot

```

### 2. Set Up Virtual Environment

```bash
python -m venv venv
# Activate it:
# On Windows:
venv\Scripts\activate
# On macOS/Linux:
source venv/bin/activate

```
### 3. Install Required Libraries

```bash
pip install -r requirements.txt
```
### 4. Create a .env file in the project root with the following content

```bash
GROQ_API_KEY=your_actual_groq_api_key_here
```
## ▶️ Run the App 

#### 1. locally 
```bash
python app.py
```
#### 2. Streamlit Web App
``` bash
streamlit run app.py
```
---

## 📚 Use Case

This chatbot was developed to support students in the CTSE course by providing instant, AI-powered access to lecture content. Upload lecture materials and ask anything — the bot will retrieve relevant segments and respond intelligently.

---

## 🌍 Contributing

Contributions are welcome! Please open an issue or submit a pull request.

---
