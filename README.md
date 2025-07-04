# 🧠 Webpage Analyzer and Q&A Assistant

This is an intelligent assistant that analyzes any public webpage and allows you to:
- ✅ Generate a concise and structured summary of the page
- ❓ Ask detailed questions about the page content
- 💬 Get accurate answers based strictly on the website data (RAG-like behavior)
---

## 🚀 Features

- 🔗 Input any public website URL
- 🧹 Clean and extract meaningful content (ignoring scripts, navbars, etc.)
- 📝 Generate a smart summary of the main text
- 💡 Ask follow-up questions about the site
- ⚡ Uses GPT-4o-mini for lightweight fast performance
- 🧠 Acts like a focused RAG (Retrieval-Augmented Generation) assistant

---

## 🖼 Demo Screenshot

![screenshot](./screenshot.png) <!-- Optional, if you add a screenshot -->

---

## 🧑‍💻 Tech Stack

- `Python 3.10+`
- `Streamlit`
- `OpenAI API (GPT-4o-mini)`
- `BeautifulSoup4` (for HTML parsing)
- `.env` (for API key management)

---

## ⚙️ Installation

```bash
git clone https://github.com/your-username/webpage-analyzer-chat
cd webpage-analyzer-chat

# (Optional) Create a virtual environment
python -m venv venv
source venv/bin/activate  # or .\venv\Scripts\activate on Windows

pip install -r requirements.txt
