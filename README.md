# 🧠 RAG-Based Conversational Chatbot with Persona Extraction

## 📌 Overview

This project is a Retrieval-Augmented Generation (RAG) based chatbot system that processes conversational data, extracts user persona, performs topic segmentation, and generates intelligent context-aware responses.

---

## 🚀 Features

* Conversation preprocessing (User 1 / User 2 format)
* Persona extraction (interests, location, goals)
* Topic segmentation of dialogues
* Vector database creation using embeddings
* RAG-based chatbot for contextual responses
* JSON-based checkpoint storage

---

## 📂 Project Structure

```
project/
│
├── data/conversations.csv
├── preprocessing.py
├── topic_segmentation.py
├── build_rag.py
├── persona_extraction.py
├── chatbot.py
├── app.py
├── vectorstore/
├── outputs/
├── requirements.txt
└── README.md
```

---

## ⚙️ Workflow

### 1. Preprocessing

Raw conversation data is cleaned and structured.

### 2. Persona Extraction

Extracts user-specific details such as:

* Location
* Interests
* Goals

### 3. Topic Segmentation

Splits conversations into meaningful topics.

### 4. RAG Pipeline

* Converts text into embeddings
* Stores in vector database
* Retrieves relevant context for queries

### 5. Chatbot

Generates responses using retrieved context + user query.

---

## ▶️ Installation

```bash
pip install -r requirements.txt
```

---

## ▶️ How to Run

```bash
python preprocessing.py
python build_rag.py
python app.py
```

---

## 📊 Dataset Format

Each row contains a conversation:

```
User 1: Hi!
User 2: Hello!
User 1: How are you?
User 2: I am good.
```

---

## 🎥 Demo Video

Loom Video:
https://www.loom.com/share/63a596d3b1ce4dc3813791e431aac56c

---

## 👩‍💻 Author

Pothuraju Manjula

---


