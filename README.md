# Doc-Chat-AI

**AI-powered document Q&A system for intelligent information retrieval**

## 🎯 Project Overview

Doc-Chat-AI is a full-stack web application that allows users to upload documents, search through them, and ask natural language questions to receive AI-generated answers with citations. Built as a portfolio project to demonstrate modern web development and AI integration skills.

## ✨ Key Features (Planned)

- 📤 **Document Upload** - Support for TXT, MD, and PDF files
- 🔍 **Semantic Search** - Find relevant content using AI embeddings
- 💬 **AI-Powered Q&A** - Ask questions and get contextual answers with citations
- 🎨 **Clean Interface** - Simple, responsive vanilla JavaScript frontend
- 🚀 **RESTful API** - Well-documented FastAPI backend

## 🛠️ Tech Stack

**Backend:**
- Python 3.10+
- FastAPI (async web framework)
- SQLite (document & chunk storage)
- OpenAI API (embeddings & chat)

**Frontend:**
- HTML5 + CSS3
- Vanilla JavaScript (ES6+)
- Fetch API for backend communication

**Tools & Deployment:**
- Docker (containerization)
- pytest (testing)
- GitHub Actions (CI/CD)

## 📅 Project Timeline

**Duration:** October 1 - December 15, 2025 (10 weeks)

- **Weeks 1-2:** Python fundamentals + FastAPI setup
- **Weeks 3-4:** File upload & database design
- **Weeks 5-6:** Search functionality & text chunking
- **Weeks 7-8:** AI integration (embeddings + chat)
- **Weeks 9-10:** Frontend interface
- **Week 11:** Polish, documentation, deployment

Current Status: **🚧 Planning Phase** (Week 0)

## 🎓 Learning Goals

This project is designed to develop skills in:
- RESTful API development with Python
- Database design and SQL integration
- AI/ML integration (RAG - Retrieval Augmented Generation)
- Frontend-backend communication
- Full-stack application architecture
- Clean code practices and documentation

## 🎯 Target Job Alignment

Built to demonstrate skills for co-op positions requiring:
- Python development (FastAPI)
- Full-stack web development
- OpenAI API integration
- Linux deployment
- Modern JavaScript

## 📝 Architecture (High-Level)

```
┌─────────────┐
│   Browser   │
│  (HTML/JS)  │
└──────┬──────┘
       │ HTTP/REST
       │
┌──────▼──────────┐
│  FastAPI Backend│
│  - /upload      │
│  - /search      │
│  - /chat        │
└──────┬──────────┘
       │
┌──────▼──────────┐
│  SQLite DB      │
│  - documents    │
│  - chunks       │
│  - embeddings   │
└─────────────────┘
```

## 🚀 Getting Started

*Setup instructions will be added as development progresses.*

### Prerequisites
- Python 3.10 or higher
- pip (Python package manager)
- OpenAI API key

### Installation
```bash
# Coming soon
```

## 📖 API Documentation

*API endpoints will be documented here as they're implemented.*

## 🧪 Testing

*Test suite information will be added during development.*

## 📦 Project Structure

```
doc-chat-ai/
├── backend/
│   ├── main.py           # FastAPI app
│   ├── rag.py           # AI/RAG logic
│   ├── chunking.py      # Text processing
│   ├── db.py            # Database helpers
│   └── requirements.txt
├── frontend/
│   ├── index.html
│   ├── styles.css
│   └── app.js
├── docs/
│   ├── PROJECT_OVERVIEW.md
│   └── ARCHITECTURE.md
├── tests/
├── .gitignore
├── README.md
└── LICENSE
```

## 🤝 Contributing

This is a personal learning project, but feedback and suggestions are welcome!


## 🙏 Acknowledgments

- FastAPI documentation and community
- OpenAI API documentation
- Inspiration from modern RAG implementations

---

**Note:** This project is under active development as part of a 10-week learning journey (Oct-Dec 2025). Check back for updates!

