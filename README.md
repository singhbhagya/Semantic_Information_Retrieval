# Semantic Information Retrieval Engine  

This project implements a **scalable semantic search engine** that combines **classical Information Retrieval (IR)** techniques with **modern neural retrieval methods**. The system is capable of efficiently searching over large document collections by integrating **sparse retrieval (TF-IDF, BM25)** with **dense retrieval (Sentence-BERT + FAISS)**, and finally merging results through a **hybrid pipeline** for improved ranking quality.  

The implementation is based on standard IR principles and neural embedding models, making it suitable both as a **research prototype** and as a **demonstration project** for real-world document retrieval tasks.  

---

## ✨ Features

- **Preprocessing & Indexing**  
  - Text normalization, tokenization, stopword removal, and passage segmentation.  
  - Inverted index construction for scalable sparse retrieval.  

- **Sparse Retrieval**  
  - Implements **TF-IDF** and **BM25** models.  
  - Efficient query-time search over large text collections.  

- **Dense Retrieval**  
  - Uses **Sentence-BERT** embeddings to capture semantic meaning.  
  - **FAISS** (Facebook AI Similarity Search) enables fast nearest-neighbor search in high-dimensional vector space.  

- **Hybrid Pipeline**  
  - Combines BM25 and dense embeddings with configurable fusion.  
  - Produces significantly improved ranked results compared to standalone methods.  

- **Evaluation Framework**  
  - Metrics: **NDCG@10, Recall@K, Mean Reciprocal Rank (MRR)**.  
  - Easily reproducible experiments on standard datasets.  

---
