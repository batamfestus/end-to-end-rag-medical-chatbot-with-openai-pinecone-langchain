# 🩺 End-to-End Medical RAG Chatbot

An intelligent medical chatbot built using **LangChain**, **OpenAI**, and **Pinecone** that answers medical-related questions using Retrieval-Augmented Generation (RAG).

---

## 🚀 Features

- Medical document question answering
- Vector search using Pinecone
- LangChain retrieval pipeline
- Flask web interface
- PDF knowledge ingestion

---

## 🐍 Python Version

This project was developed and tested using:

Python 3.11

Using other Python versions may cause dependency issues.

## 🛠 Tech Stack

- Python
- LangChain
- OpenAI
- Pinecone
- Flask
- HTML/CSS

---

## 📂 Project Structure

```
end-to-end-medical-chatbot
│
├── app.py
├── src/
├── templates/
├── static/
├── data/
├── research/
└── README.md
```

---

## ⚙ Installation

### ⚠ Recommended Python Version

Make sure Python 3.11 is installed:

```
python --version
```

If not, install Python 3.11 before continuing.

### 1. Clone repository

```
git clone https://github.com/batamfestus/end-to-end-rag-medical-chatbot-with-openai-pinecone-langchain.git
cd end-to-end-medical-chatbot
```

### 2. Create virtual environment

```
python -m venv medicalbot
medicalbot\Scripts\activate
```

### 3. Install dependencies

```
pip install -r requirements.txt
```

---

## 🔑 Environment Setup

Create `.env` file:

```
OPENAI_API_KEY=your_key_here
PINECONE_API_KEY=your_key_here
```

---

## ▶ Run Application

```
python app.py
```

Open browser:

```
http://localhost:5000
```

---

## 🎯 Future Improvements

- Enhanced UI
- More medical datasets
- Deployment support
- Conversation memory

---

## 👨‍💻 Author

Batam Festus  
AI & ML Enthusiast

---

⭐ If you like this project, give it a star!
