# Marbet RAG Chatbot – Team Nika & Ali

This project is our submission for the Marbet Week 9/10 Challenge. It is a Retrieval-Augmented Generation (RAG)-based chatbot designed to support guests during Marbet’s incentive trips. The chatbot can answer user questions related to schedules, activities, packing requirements, ship services, and travel policies using the provided event documents.

The system combines LangChain, FAISS, and Ollama (llama3.2 model) to retrieve relevant information and generate document-grounded responses.

## What It Does

- Answers natural language questions like:
  - "What are the activities on Day 3?"
  - "Do I need a visa?"
  - "What are the spa rules?"
- Retrieves information from the following documents:
  - Activities Overview
  - Packing List
  - Scenic Eclipse A-Z Guide
  - Tutorials and Travel Info
- Uses a FAISS vector store for semantic search
- Generates context-aware responses using Ollama's llama3.2 model

## Tech Stack

- Python
- LangChain
- FAISS
- Ollama (llama3.2)
- Jupyter Notebook (for development and testing)

## How to Run

1. Connect to the BUas VPN if off-campus.  
   Ollama is hosted on the BUas server and requires VPN access.  
   VPN setup instructions: [BUas VPN Guide](https://adsai.buas.nl/Study%20Content/Data%20Engineering/assets%2FADSAI%20Remote%20VPN.pdf)

2. Install dependencies:

