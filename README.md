# 🔍 RAG Chatbot using LangChain + Gemini + Chroma

This project is a **Retrieval-Augmented Generation (RAG) chatbot** built using **LangChain**, **Gemini Pro (Google's LLM)**, and **ChromaDB**. The chatbot takes any website URL, scrapes and preprocesses the content, converts it into vector embeddings, and then answers questions with rich, context-aware responses.

## 🚀 Features

- 🌐 **Dynamic Website Scraping**: Enter any article or blog URL — the chatbot fetches and processes the content in real time.
- 🧠 **Contextual Q&A with Gemini**: Uses Google's Gemini model to generate intelligent answers based on retrieved context chunks.
- ⚡ **Fast Semantic Search**: ChromaDB is used to store and retrieve vectorized document chunks using Sentence Transformers.
- 💬 **Interactive Chat Interface**: Engage with the chatbot directly via a command-line chat loop or a Colab widget interface.

---

## 🛠️ Tech Stack

- **🧠 LLM**: Google Gemini Pro (`gemini-1.5-flash`)
- **🔗 Framework**: LangChain
- **📦 Vector Store**: ChromaDB
- **🧬 Embeddings**: `sentence-transformers/all-MiniLM-L6-v2`
- **🔍 Web Scraping**: BeautifulSoup
- **💡 Environment**: Google Colab / Jupyter Notebook / Local Python

---

## 📦 Installation

```bash
pip install langchain langchain-community sentence-transformers chromadb google-generativeai bs4
