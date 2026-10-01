# Crop Disease RAG Chatbot 

## Project Description

The **Crop Disease RAG Chatbot** is an AI-powered question-answering system that provides information about crop diseases using Retrieval-Augmented Generation (RAG). The system uses a crop disease knowledge-base PDF as its source of information, splits the text into smaller chunks, converts the chunks into numerical embeddings using the Sentence Transformers model (`all-MiniLM-L6-v2`), and stores them in a ChromaDB vector database. When a user asks a question, the system retrieves the most relevant information using semantic search and passes it to a Large Language Model (LLM) through the Groq API to generate a clear, context-based answer.

## Technologies Used

* Python
* Google Colab
* Sentence Transformers
* ChromaDB
* Groq API
* GPT-OSS-120B
* Retrieval-Augmented Generation (RAG)

## Key Features

* PDF text extraction
* Text chunking with overlap
* Text embeddings generation
* Semantic search using ChromaDB
* Context-based answer generation using an LLM
* Interactive question-answering through a command-line interface

## How It Works

1. Extract text from the crop disease knowledge-base PDF.
2. Split the text into smaller chunks.
3. Generate embeddings for each chunk.
4. Store the chunks and embeddings in ChromaDB.
5. Retrieve relevant information based on the user's question.
6. Generate an answer using the Groq API and the retrieved context.

## Learning Outcomes

This project helped me understand the practical implementation of RAG systems, embeddings, vector databases, semantic retrieval, API integration, and LLM-based question answering.

## Future Enhancements

* Develop a web-based chatbot interface.
* Support crop leaf image uploads for disease identification.
* Expand the knowledge base with more crop diseases and agricultural information.
* Add persistent vector database storage.
* Improve retrieval accuracy and answer evaluation.

## Note

This project is an educational prototype. The accuracy of answers depends on the knowledge base and retrieved information. The chatbot should not replace professional agricultural diagnosis or advice.
