# Applied NLP Projects

**Exploring Natural Language Processing with Python, Transformer Models, and Semantic Search.**

This repository contains practical Natural Language Processing (NLP) implementations using pre-trained machine learning models. It demonstrates text sentiment classification, sentence embeddings, and semantic similarity search.

## Projects Overview

### 1. Sentiment Analysis
An interactive text classification application using Hugging Face Transformers.

- Classifies text into Positive, Negative, and Neutral sentiments.
- Uses zero-shot classification.
- Generates confidence scores for each sentiment.
- Supports interactive command-line input.

**Model:** `typeform/distilbert-base-uncased-mnli`

**File:** `sentiment-analysis.py`

### 2. Text Embeddings & Semantic Search
A semantic similarity application using Sentence Transformers.

- Converts sentences into numerical embeddings.
- Measures similarity using cosine similarity.
- Retrieves the most relevant sentences.
- Implements Top-K semantic search.
- Identifies the closest matching sentence.

**Model:** `sentence-transformers/all-MiniLM-L6-v2`

**File:** `text-embeddings.py`

## Technology Stack

- Python
- Hugging Face Transformers
- Sentence Transformers
- PyTorch
- UV Package Manager
- Python-dotenv

### Run Sentiment Analysis
uv run python sentiment-analysis.py

### Run Text Embeddings
uv run python text-embeddings.py



---

*Building practical NLP applications through machine learning and modern language models.*
