**Simple RAG using URL**

This project demonstrates a **Retrieval-Augmented Generation (RAG)** pipeline that allows an AI model to answer questions using information dynamically extracted from a given URL.  
It’s a simple but powerful example of combining **information retrieval** and **large language models (LLMs)** for context-aware question answering.


**Project Overview**

Traditional LLMs rely on pre-trained data and often lack updated or specific knowledge.  
This RAG system solves that by:
1. Extracting and embedding text from a URL.
2. Storing those embeddings in a **FAISS vector database**.
3. Retrieving the most relevant information when a user asks a question.
4. Generating accurate, context-grounded answers using an LLM.

**Key Features**

- Fetch and process text directly from any URL.  
- Create and query a **vector store** using FAISS.  
- Combine **retrieval** + **generation** for intelligent responses.  
- Built with **LangChain** and **Hugging Face Transformers**.


**Technologies Used**

- Python  
- LangChain  
- Hugging Face Transformers  
- FAISS (Facebook AI Similarity Search)  
- Requests / BeautifulSoup (for text extraction)


# Run the notebook
Simple_RAG_Using_URL.ipynb
