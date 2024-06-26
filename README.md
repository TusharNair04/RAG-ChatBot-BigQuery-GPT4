# rag-chatbot-bigquery-gpt4

This project demonstrates a chatbot built using Retrieval-Augmented Generation (RAG) with Google BigQuery as the vector store and GPT-4 as the language model. It provides efficient and scalable vector search for robust similarity search and retrieval.

## Installation

1. Clone the repository:
```bash
git clone https://github.com/TusharNair04/RAG-ChatBot-BigQuery-GPT4.git
```
```bash
cd RAG-ChatBot-BigQuery-GPT4
```

2. Install the required dependencies:
```
pip install -r requirements.txt
```

## Usage
To use this project, follow these steps:

1. Update the configuration variables in the `bigquery_vector_search.py` and `llm.py` files with your own values.
2. Run the script to ingest vectors if needed:
```bash
python bigquery_vector_search.py
```
3. Search using the provided methods.
