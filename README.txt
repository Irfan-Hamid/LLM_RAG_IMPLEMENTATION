This project implements a RAG pipeline. The system is capable of extracting and preprocessing text from PDF files, embedding text chunks for efficient retrieval, and generating context-aware responses using a large language model (LLM) based on user queries.

Project Overview

This repository contains a Colab notebook and a PDF biography of a hypothetical Manchester United footballer. The primary objective of this project is to allow users to input queries and receive relevant, context-driven answers from the PDF's content. The system is built using vector-based text retrieval and a large language model (LLM) for response generation.

Key Components:

1. Text Extraction and Preprocessing:
   Text is extracted from the PDF file and preprocessed into manageable chunks. These chunks are then transformed into numerical representations suitable for efficient storage and retrieval.

2. Vector-Based Retrieval System:
   A retrieval system built on vector embeddings is used to match user queries with the most relevant text chunks from the PDF content.

3. Context-Aware Prompt Generation and Response:
   Retrieved text chunks are combined to form context-aware prompts, which are passed to the Google/GEMMA-7B-it language model. The model generates context-driven responses that are accurate and based on the relevant content of the PDF file.

Repository Contents:

- RAG_model.pdf: The hypothetical biography of a Manchester United footballer used for this project.
- LLM_RAG_IMPLEMENT.ipynb: The Colab notebook containing all code for the text extraction, retrieval system, and LLM-based question answering.

Instructions for Use:

1. Create a folder named `RAG_MODEL` in your Google Drive and upload the PDF file into that folder.
   
2. Run the Colab Notebook:
   Open the LLM_RAG_IMPLEMENT.ipynb in Google Colab. Follow the step-by-step instructions within the notebook to:
   - Extract and preprocess the PDF content.
   - Build the vector-based retrieval system.
   - Generate responses to user queries using the Google/GEMMA-7B-it language model.

3. Submit Queries:
   Input any query related to the footballer's biography, and the system will return contextually accurate responses by retrieving relevant text chunks from the PDF and passing them to the LLM.

Contact:

For any questions or feedback, feel free to reach out via GitHub issues or pull requests.
