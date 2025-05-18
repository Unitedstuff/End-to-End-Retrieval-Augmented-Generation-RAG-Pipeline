# End-to-End-Retrieval-Augmented-Generation-RAG-Pipeline
 Medibot is an end-to-end Retrieval-Augmented Generation (RAG) system that enables intelligent question answering over PDF documents. Built with LangChain, Pinecone, HuggingFace embeddings, and Groq LLM, this project demonstrates how to ingest, chunk, embed, store, and retrieve information from documents, and generate concise.
 
Features
PDF Ingestion: Automatically loads and processes PDF files from a directory.
Text Chunking: Splits documents into manageable text chunks for efficient retrieval.
Embeddings: Utilizes HuggingFace sentence-transformer models for semantic search.
Vector Database: Stores and retrieves document embeddings using Pinecone.
Retrieval-Augmented Generation: Combines retrieval with Groq LLM for accurate, context-based answers.
Modular Pipeline: Easily adaptable for different document types, embedding models, and LLMs.
Use Cases
Medical document Q&A
Knowledge base assistants
Research paper summarization
Any scenario requiring context-aware question answering over large document sets
Getting Started
Clone the repository.
Add your PDF files to the Data directory.
Set your API keys in a .env file.
Run the notebook or scripts to build and query your own RAG-powered assistant.
Built with:

LangChain
Pinecone
HuggingFace Transformers
Groq LLM
Contributions and feedback are welcome!
