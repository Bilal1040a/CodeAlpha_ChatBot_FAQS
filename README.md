# CodeAlpha_ChatBot_FAQS
# FAQ Chatbot 🤖

An intelligent FAQ chatbot built as Task 2 of the CodeAlpha Artificial Intelligence 
Internship. Combines NLP-based question matching with a full-stack web application 
featuring user authentication and persistent, per-user chat history.

## Features

- 🧠 **Smart NLP Matching** — Combines TF-IDF cosine similarity, fuzzy string matching 
  (difflib), and small-talk pattern detection (greetings, thanks, help queries) to 
  understand user questions even with typos or rephrasing
- 🔐 **User Authentication** — Secure signup/login with hashed passwords via Flask-Login
- 💬 **Persistent Chat History** — ChatGPT-style collapsible sidebar showing past 
  conversations, stored per user in SQLite
- 🎨 **Modern UI** — Full-window, responsive split layout with a glassmorphic purple 
  design
- 🛡️ **Protected Routes** — Unauthenticated users can't access chat functionality

## Tech Stack

- **Backend:** Flask, Flask-Login, Flask-SQLAlchemy
- **Database:** SQLite
- **NLP:** scikit-learn (TF-IDF vectorization + cosine similarity), difflib (fuzzy matching)
- **Frontend:** HTML/CSS/JS

## Getting Started

```bash
pip install -r requirements.txt
python app.py
```

Then visit `http://localhost:5001` (or the configured port).

## About

Part of the CodeAlpha AI Internship program, demonstrating both applied NLP techniques 
and full-stack web development skills.
