# 📚 Chat with Multiple PDFs

Interactively chat with the content of multiple PDF documents using OpenAI's language models, vector search (FAISS), and a Streamlit interface.

## 🔍 Overview

This app allows users to upload one or more PDF files, processes them using LangChain and OpenAI embeddings, and enables interactive querying through a conversational AI interface.

### Key Features

- 📄 Upload and process multiple PDF files
- 🤖 Ask questions and receive context-aware answers
- 🧠 Memory-enabled conversation using LangChain
- 🔎 Efficient vector similarity search with FAISS
- 🌐 Streamlit UI for easy interaction

## 🛠️ Technologies Usednk

- [Streamlit](https://streamlit.io/)
- [LangChain](https://python.langchain.com/)
- [OpenAI API](https://platform.openai.com/)
- [FAISS](https://github.com/facebookresearch/faiss)
- [PyPDF2](https://pypi.org/project/PyPDF2/)
- [python-dotenv](https://pypi.org/project/python-dotenv/)

## 🚀 Setup Instructions

### 1. Clone the Repository

```bash
git clone https://github.com/Simonpiro442-com/Multiple-pdf-reader-.git
cd Multiple-pdf-reader
```

### 2. Create and activate Virtual Environment

```bash
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
```
### 3. Install Dependencies
```bash
pip install -r requirements.txt
```

### 4. Set Up Environment Variables
Create a .env file in the root directory and add your OpenAI API key
```bash
OPENAI_API_KEY=your-openai-api-key
```
### 5. Run the App
```bash
streamlit run app.py
```




