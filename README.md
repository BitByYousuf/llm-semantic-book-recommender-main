# LLM Semantic Book Recommender

A sophisticated book recommendation engine that uses Large Language Models (LLMs) to provide semantic search capabilities, emotional tone filtering, and zero-shot genre classification.



## 🚀 Overview

Traditional book recommenders often rely on simple keyword matching or collaborative filtering. This project elevates the experience by understanding the **semantic context** of a user's request. Whether you're looking for "a story about heartbreak and healing in a rural setting" or "a fast-paced sci-fi with a surprising twist," the system uses vector embeddings to find the best matches.

### Key Features
* **Semantic Search:** Uses OpenAI's `text-embedding-3-small` and ChromaDB to find books based on the meaning of descriptions.
* **Emotion Analysis:** Classifies books into emotional categories (Happy, Sad, Angry, Suspenseful, Surprising) using a DistilRoBERTa model.
* **Zero-Shot Classification:** Leverages the BART model to automatically categorize books into broad "Fiction" and "Non-fiction" labels without specific training.
* **Interactive Dashboard:** A sleek, user-friendly web interface built with Gradio.

## 🛠️ Tech Stack

- **Language:** Python
- **LLM Integration:** LangChain
- **Embeddings:** OpenAI
- **Vector Database:** ChromaDB
- **Models:** HuggingFace Transformers (DistilRoBERTa & BART)
- **UI:** Gradio
- **Data:** Pandas & NumPy

## 📁 Project Structure

* `data-exploration.ipynb`: Initial cleaning and analysis of the 7k books dataset.
* `text-classification.ipynb`: Implementation of the zero-shot classification pipeline.
* `sentiment-analysis.ipynb`: Scoring book descriptions for emotional tones.
* `vector-search.ipynb`: Building the vector database and testing similarity search logic.
* `gradio-dashboard.py`: The main application script that runs the web UI.
* `requirements.txt`: List of all necessary Python dependencies.

## ⚙️ Installation & Setup

1. **Clone the Repository:**
   ```bash
   git clone [https://github.com/your-username/llm-semantic-book-recommender.git](https://github.com/your-username/llm-semantic-book-recommender.git)
   cd llm-semantic-book-recommender
