# PDF Question Answering using RAG (Retrieval-Augmented Generation)

This project demonstrates a **working RAG pipeline** that allows you to query PDF documents using semantic search and large language models (LLMs).  
It combines **Annoy** for efficient vector similarity search, **OpenAI embeddings** for semantic retrieval, and **OpenAI GPT** for response generation.

## 🚀 Features
- Extracts text from PDFs
- Converts text into embeddings using OpenAI
- Stores embeddings in **Annoy** (vector index)
- Performs **semantic retrieval** to find the most relevant passages
- Uses an **LLM (OpenAI GPT)** to generate answers from retrieved context
- Demonstrates **prompt engineering** for controlled LLM responses

## 📂 Project Structure
