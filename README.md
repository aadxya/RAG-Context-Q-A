# Retrieval-Augmented-Generation-RAG-for-Context-Aware-Q-A

This project implements a Retrieval-Augmented Generation (RAG) pipeline that lets users ask natural language questions over a document collection. The system retrieves the most relevant chunks based on semantic similarity and generates an informed answer grounded in the retrieved context. Here, I've used a Nutrition based pdf document.


Features
1. Semantic Retrieval: Embeds and indexes document chunks using a sentence embedding model.
2. Context-Aware Answers: Combines retrieved chunks with a language model to generate contextual responses.
3. Chunk-Level Transparency: Displays the top matching chunks with their relevance scores and page numbers.
4. Modular & Extensible: Can be adapted to different embedding models, LLMs, or datasets.
