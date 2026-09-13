# Airlines Q&A Bot

## Overview
This project is a Retrieval-Augmented Generation (RAG) chatbot that answers airline-related questions using information extracted from airline documents.

## Features
- PDF document loading
- Text chunking
- Embedding generation
- Vector database search
- Retrieval-Augmented Generation (RAG)
- LLM-based answer generation

## Technologies
- Python
- LangChain
- FAISS
- Hugging Face Embeddings
- Groq API / LLM
- Google Colab

## Workflow
1. Load airline documents
2. Split into chunks
3. Generate embeddings
4. Store in FAISS
5. Retrieve relevant context
6. Generate answers using the LLM

## Example Questions
- What is the baggage allowance?
- Can I cancel my ticket?
- How can I request a refund?
- What documents are required for international travel?

## Future Improvements
- Streamlit interface
- Multi-document support
- Chat history
- Source citations
