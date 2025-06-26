# RAGify
Built a context-aware Retrieval-Augmented Generation (RAG) chatbot using LangChain, HuggingFace, OpenAI, and ChromaDB. Integrated web-based document loading,
RAG Chatbot with Memory using LangChain, ChromaDB & OpenAI
A context-aware Retrieval-Augmented Generation (RAG) chatbot that understands and remembers previous interactions. Built using:

LangChain to orchestrate LLM chains and memory-aware retrieval.

ChromaDB as a vector store for semantic search over documents.

HuggingFace Embeddings (all-MiniLM-L6-v2) to convert text into vectors.

OpenAI GPT-4o to generate smart, concise responses.

BeautifulSoup4 and WebBaseLoader to extract structured content from web pages.

Features:

Context-preserving chat history using MessagesPlaceholder.

Dynamic question rewriting via create_history_aware_retriever.

Custom prompt templates for both retrieval and generation.

End-to-end NLP pipeline showcasing GenAI + prompt engineering
