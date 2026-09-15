# AI PDF Chatbot (RAG)

An AI-powered PDF Question Answering application built with Python, LangChain, Google Gemini, FAISS, and Streamlit. The application uses Retrieval-Augmented Generation (RAG) to provide accurate, context-aware answers from uploaded PDF documents instead of relying on general LLM knowledge.

# Features

- Upload any PDF document
- Ask questions in natural language
- Context-aware responses using RAG
- Semantic document retrieval with FAISS
- Interactive Streamlit interface
- Fast and scalable document search


# Architecture

The application follows a Retrieval-Augmented Generation (RAG) pipeline.

1. Upload PDF
2. Extract text using PyPDF2
3. Split text into chunks with LangChain
4. Generate embeddings
5. Store vectors in FAISS
6. Retrieve relevant chunks
7. Generate responses using Google Gemini
8. Display answers through Streamlit


# Tech Stack 

Python | LangChain | Google Gemini | FAISS | Streamlit | PyPDF2 
