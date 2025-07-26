# 🤖 Gemini PDF Chatbot with LangChain and FAISS
This project is a simple chatbot powered by Google Gemini (Generative AI) and LangChain that lets you ask questions from any uploaded PDF document. It uses Retrieval-Augmented Generation (RAG) to answer user queries based on the contents of the PDF.
🔧 Features
💬 Chat interface for PDF-based Q&A

🔍 Semantic search using FAISS

🧠 Embeddings via HuggingFace (all-MiniLM-L6-v2)

⚡ Powered by Google Gemini-Pro via LangChain

✅ Runs entirely on Google Colab (no local setup required)

📁 How It Works
Upload a PDF document.

The PDF is split into smaller text chunks.

Embeddings are generated and stored in a FAISS vector store.

User queries are compared to relevant chunks via semantic similarity.

Gemini LLM generates a contextual answer from the retrieved chunks.

