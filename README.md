# 📄 Intelligent Contract Review Assistant (RAG)

An LLM-powered system that analyzes legal contracts using
Retrieval-Augmented Generation (RAG).

## Features
- Contract clause retrieval (CUAD dataset)
- Semantic search using FAISS
- Risk detection (indemnity, liability, termination)
- Flask-based UI

## Tech Stack
- Python
- HuggingFace Datasets
- Sentence Transformers
- FAISS
- Flask
- Ngrok (Colab)

## Notebooks
- `notebook1_data_processing.ipynb`: Dataset loading, chunking, embeddings, FAISS index
- `notebook2_rag_flask_app.ipynb`: RAG pipeline + Flask UI
