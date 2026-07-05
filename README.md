# AI-Powered Research Paper Semantic Search

![Python](https://img.shields.io/badge/Python-3.10+-blue)
![FAISS](https://img.shields.io/badge/FAISS-Vector_Search-green)
![SentenceTransformers](https://img.shields.io/badge/SentenceTransformers-NLP-orange)

## About

This project is an intelligent research paper search system that retrieves relevant Machine Learning papers using semantic similarity instead of keyword matching. It combines transformer-based embeddings with FAISS for efficient and accurate search.

## Why This Project?

Keyword-based search often overlooks papers that are conceptually related. This project addresses that issue by converting documents and queries into vector embeddings and ranking papers based on semantic closeness.

## Features

- Data cleaning and preprocessing
- Exploratory Data Analysis (EDA)
- Sentence embeddings using all-MiniLM-L6-v2
- FAISS-powered vector search
- Natural language query support
- Fast Top-K document retrieval

## Technologies Used

- Python
- Pandas
- NumPy
- Hugging Face Datasets
- Sentence Transformers
- FAISS
- Jupyter Notebook

## Repository Structure

```text
EDA.ipynb
Search_Engine.ipynb
README.md
requirements.txt
dataset.md
```

## Installation

```bash
pip install -r requirements.txt
```

## Running the Project

1. Open `EDA.ipynb`
2. Execute `Search_Engine.ipynb`
3. Run:

```python
search_paper("your search query")
```

## Future Scope

- Web interface using Streamlit
- Search filters (author, year, topic)
- Research paper summarization
- PDF upload support

## Maintainer

**Tanishk**
