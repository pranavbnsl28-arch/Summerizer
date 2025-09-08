# 📚 Zummary - Summarize Content On the Go!

Zummary is a Streamlit-powered tool that helps users quickly create meaningful summaries along with audio downloads, from:

1. 🎥 YouTube videos
2. 🌐 Web URLs
3. 📄 PDF documents

Powered by **LangChain**, **Groq LLM (Gemma2-9b-it)**, and **gTTS**, Zummary makes digesting lengthy content easier, faster, and accessible.

---

## ✨ Features

**🔍 Structured Summaries:** Includes an intro, highlights of the content, and a closing section with a title.

**🎧 Audio Support:** Generates an MP3 version of the summary using gTTS for easier listening.

**📥 Export Options:** Download summaries in both text and audio formats.

**🤖 LLM-Driven:** Uses LangChain and Groq's Gemma model for high-quality summarization.

**🧠 Smart Mode Switching:** Chooses between summarization methods (stuff / map_reduce) depending on the content size.

**✅ Supports:**

1. YouTube video transcripts
2. Unstructured website content
3. PDF documents

---

## 🧩 Tech Stack

**Streamlit** — UI & interaction

**LangChain** — LLM integration and summarization chains

**ChatGroq** — Gemma2-9b-it model

**gTTS** — Text-to-speech for summary audio

**YouTubeTranscriptAPI** — Fetching video transcripts

**UnstructuredURLLoader, PyPDFLoader** — Web & PDF parsing

**PIL, Base64, Regex** — Utility handling for media and content

---

## 🚀 Getting Started

1. Clone the Repo

> git clone https://github.com/pranavbnsl28-arch/Summerizer.git

> cd Zummary-Content-Summarizer-App

2. Install Dependencies

It’s recommended to use a virtual environment.

> pip install -r requirements.txt

3. Environment Setup

Create a .env file in the root directory:

> LANGCHAIN_API_KEY=your_langchain_key

> GROQ_API_KEY=your_groq_key

(Only needed if you're using proxies)

> proxy_username=your_proxy_username   

> proxy_password=your_proxy_password

Add these secrets to .streamlit/secrets.toml as well (used in app):

> LANGCHAIN_API_KEY = "your_langchain_key"

> GROQ_API_KEY = "your_groq_key"

4. Run the App

> streamlit run summarize.py

---

## 📸 Screenshots

https://github.com/user-attachments/assets/bd4deeba-f959-4587-a515-2f9077b47f8a

---

## 👨‍💻 Author

Pranav Bansal

Feel free to connect with me for suggestions or feedback! 

Connect with me on 📧 LinkedIn: https://www.linkedin.com/in/pranavbnsl


