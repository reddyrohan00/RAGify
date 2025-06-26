# RAGify
Built a context-aware Retrieval-Augmented Generation (RAG) chatbot using LangChain, HuggingFace, OpenAI, and ChromaDB. Integrated web-based document loading,
<div align="center">

<div align="center">

# 🧠 RAG Chatbot with Memory  
**LangChain | ChromaDB | HuggingFace | OpenAI GPT-4o**

</div>

---

<div align="center">

🔍 Retrieval-Augmented Generation | 🧩 Prompt Engineering | 💬 Chat History | 📚 Semantic Search

</div>

---

## 🚀 Overview

This project is an intelligent **RAG-based chatbot** capable of understanding **user context**, retrieving **relevant document chunks**, and generating **concise, accurate answers**. It combines multiple GenAI tools to deliver contextual memory-aware conversations.

---

## 🛠️ Tech Stack

| Tool / Library       | Purpose                              |
|----------------------|--------------------------------------|
| 🌐 `LangChain`        | LLM chaining, prompt templating       |
| 🗂️ `ChromaDB`         | Vector database for document retrieval|
| 🧠 `HuggingFace`       | Embeddings (`all-MiniLM-L6-v2`)       |
| 🤖 `OpenAI GPT-4o`     | Language generation engine            |
| 🕸️ `BeautifulSoup4`   | Web scraping and content parsing      |
| 🔐 `python-dotenv`    | Environment variable management       |

---

## ✨ Key Features

- ✅ **Web-based Document Ingestion** using `WebBaseLoader` & `BeautifulSoup`
- ✅ **Recursive Text Chunking** for fine-grained retrieval
- ✅ **Semantic Search** over vectorized documents
- ✅ **Memory-Aware Chat** with `MessagesPlaceholder`
- ✅ **Question Rewriting** using `create_history_aware_retriever`
- ✅ **Custom Prompt Templates** for both retrieval & response generation

---

## 🧪 Example Interaction

```text
User: What is self-reflection?
Bot: Self-reflection allows autonomous agents to improve by analyzing past actions...

User: Tell me more about it?
Bot: It helps identify inefficiencies and adjust future plans through reasoning traces...

