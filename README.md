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
- 🧠 Acts like a focused RAG (Retrieval-Augmented Generation) assistant

---

## 🎥 Demo Video

[Click to watch the demo on Google Drive](https://drive.google.com/file/d/1QMWz4-Kp5oVGJhXAW1jsbF-aPtrVOHFO/view?usp=drive_link)

## 📁 Project Structure
<pre>
├── app.py              # Streamlit frontend
├── summarizer.py       # Backend: parsing, summarization, QA logic
├── requirements.txt
├── .env                # API key (not pushed to GitHub)
└── README.md
<pre> 

## ⚙️ Installation

```bash
git clone https://github.com/muhammedehab35/WEB_SCRAPE_SUM.git
cd Projects_01

# Create a virtual environment
python -m venv venv
source venv/bin/activate  # or .\venv\Scripts\activate on Windows

pip install -r requirements.txt
---
## ▶️ Run the App
streamlit run app.py
---

## 👤 Author
by @muhammedehab
---

## 📜 License
MIT


