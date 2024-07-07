# Content Engine

This project is a Content Engine designed to analyze and compare multiple PDF documents, specifically identifying and highlighting their differences. The system uses Retrieval Augmented Generation (RAG) techniques to effectively retrieve, assess, and generate insights from the documents.

## Google Colab Link
You can access and run the project using Google Colab through the following link:

[Open in Google Colab](https://colab.research.google.com/drive/1fp7P7Cb9BuBo_csUUxPmKZnPdO9ef8jQ?usp=sharing)

## Project Overview
This Content Engine performs the following tasks:

1. Parse Documents: Extracts text and structure from PDFs.
2. Generate Vectors: Uses a local embedding model to create embeddings for document content.
3. Store in Vector Store: Utilizes local persisting methods in the chosen vector store.
4. Configure Query Engine: Sets up retrieval tasks based on document embeddings.
5. Integrate LLM: Runs a local instance of a Large Language Model for contextual insights.
6. Develop Chatbot Interface: Uses Streamlit to facilitate user interaction and display comparative insights.

## Steps to Run the Project
1. Open the Colab File: Click on the Colab link to open the project in Google Colab.
2. Enable GPU: Navigate to Runtime > Change runtime type.
   Select GPU as the hardware accelerator and ensure it is set to T4.

## Follow the Steps:

Follow the steps provided in the Colab notebook to install necessary libraries, load the documents, generate embeddings, and interact with the Content Engine.
Interact with the Engine: Use the provided interface to input queries and obtain insights from the analyzed documents.
