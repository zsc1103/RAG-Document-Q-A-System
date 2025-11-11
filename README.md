#  RAG Document Q&A System

**Tech Stack:** Python, FastAPI, Milvus, OpenAI API, Elasticsearch, Docker

## Overview
A Retrieval-Augmented Generation (RAG) system that combines dense vector search and traditional keyword-based retrieval to answer user questions over custom documents.  
The project focuses on hybrid information retrieval, semantic embeddings, and efficient context retrieval for LLM-based Q&A.

## Architecture
- **Retrieval Layer:** BM25 (Elasticsearch) + Dense Vector (Milvus)  
- **API Layer:** FastAPI providing endpoints for query, upload, and retrieval  
- **LLM Integration:** OpenAI GPT API for natural language responses  
- **Containerization:** Fully dockerized setup for reproducibility  

## Key Features
- Implemented hybrid ranking algorithm (BM25 + vector similarity)  
- Designed modular pipeline for document ingestion and indexing  
- Developed RESTful endpoints for question-answering  
- Tuned embedding similarity thresholds for precision and recall  

## Outcome
Delivered a low-latency, accurate Q&A system that integrates structured and unstructured retrieval, powering real-world knowledge search scenarios.

> *Full source code available upon request.*
