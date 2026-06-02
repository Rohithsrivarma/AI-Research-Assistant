# AI Research Assistant

## Overview

AI Research Assistant is a Retrieval-Augmented Generation (RAG) application that allows users to ask questions across multiple PDF documents.

The system retrieves relevant information from uploaded documents and uses Google's Gemini model to generate accurate, context-aware responses.

---

## Features

* Multi-PDF Support
* Semantic Search
* ChromaDB Vector Database
* Sentence Transformer Embeddings
* Google Gemini Integration
* Source Citations with Page Numbers
* Retrieval-Augmented Generation (RAG)

---

## Architecture

PDF Documents
→ DirectoryLoader
→ Chunking
→ Embeddings
→ ChromaDB
→ Retriever
→ Gemini
→ Answer

---

## Technologies Used

* Python
* LangChain
* ChromaDB
* Sentence Transformers
* Google Gemini
* PyPDF
* Google Colab

---

## Project Workflow

1. Load multiple PDF documents
2. Split documents into chunks
3. Generate embeddings
4. Store embeddings in ChromaDB
5. Retrieve relevant chunks
6. Generate answers using Gemini
7. Display answer with source references

---

## Example Questions

* What is Machine Learning?
* What are the advantages of RAG?
* What is ChromaDB?
* Explain semantic search.

---

## Learning Outcomes

Through this project I learned:

* Retrieval-Augmented Generation (RAG)
* Document Chunking
* Embeddings
* Vector Databases
* Semantic Search
* Large Language Model Integration
* Multi-PDF Knowledge Base Systems

---

## Future Enhancements

* Streamlit Web Interface
* Conversational Memory
* Hybrid Search
* Reranking
* Web Search Integration
* Cloud Deployment

---

## Author

Rohith Sri Varma
