# Hybrid Search RAG with PineconeDB and LangChain

This project demonstrates the implementation of a hybrid search system combining both semantic and keyword search capabilities using Pinecone vector database and LangChain. The system leverages both dense vector embeddings and sparse matrix representations to provide comprehensive search functionality.

**Key Features**

• Implements hybrid search combining semantic and keyword-based search approaches.
• Uses Hugging Face sentence transformers for dense vector embeddings (384 dimensions).
• Employs BM25 encoder with TF-IDF for sparse matrix representations.
• Integrates Pinecone vector database for efficient storage and retrieval.
• Built with LangChain's PineconeHybridSearchRetriever.

**Technical Stack**

• Vector Database: Pinecone
• Frameworks: LangChain
• Embedding Models:- Dense: Hugging Face all-mini-lm-l6-v2 ;; Sparse: BM25 encoder with TF-IDF

**Use Case**

The system can effectively process and retrieve information using both semantic understanding and keyword matching, making it ideal for applications requiring precise and comprehensive search capabilities.
