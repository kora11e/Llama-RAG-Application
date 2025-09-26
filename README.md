# Llama RAG Application

A Retrieval Augmented Generation Project to communicate offline with Llama 3.1 model.
A streamlit App designed to run Llama 3.1 model and chat about a website. 

## How To use it?

1. Download or clone repository
2. Install requireed files with pip install -r requirements.txt
3. Run the applicatinn with streamlit run llama_rag.py

## How it works?

The app loads the webpage data using WebBaseLoader and splits it into chunks using RecursiveCharacterTextSplitter.
It creates Ollama embeddings and a vector store using Chroma.
The app sets up a RAG (Retrieval-Augmented Generation) chain, which retrieves relevant documents based on the user's question.
The Llama-3.1 model is called to generate an answer using the retrieved context.
The app displays the answer to the user's question.
