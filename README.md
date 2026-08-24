# AI Chatbot for Competitive Programming (RAG Pipeline)

## Overview
A Retrieval-Augmented Generation (RAG) chatbot system that scrapes, indexes, and retrieves contextual solution approaches for 2,500+ Codeforces problems.

## Key Highlights
* **Web Scraping Pipeline:** Automated dataset extraction across 2,500+ CP problems and editorial codes using BeautifulSoup and Selenium.
* **Vector Indexing & Embeddings:** Processed code snippets through CodeBERT to generate dense vector embeddings and indexed them in FAISS for fast similarity search.
* **RAG Retrieval:** Integrated semantic search retrieval with LLM generation to produce accurate algorithmic hints and code logic.

## Tech Stack & Tools
* **Language:** Python
* **Libraries:** FAISS, CodeBERT / Transformers, BeautifulSoup, Selenium, PyTorch
* **Concepts:** Retrieval-Augmented Generation (RAG), Vector Embeddings, Web Scraping
