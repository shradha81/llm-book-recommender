# llm-book-recommender
This project is a complete pipeline for building an AI-powered book recommendation system using Large Language Models (LLMs). It includes:

Data Cleaning: Preprocessing and exploring book data for analysis (data-exploration.ipynb).
Vector Search: Generating embeddings and creating a vector database to retrieve similar books using natural language queries (vector-search.ipynb).
Zero-Shot Classification: Categorizing books as fiction or non-fiction using LLMs (text-classification.ipynb).
Sentiment & Emotion Analysis: Extracting the emotional tone of book descriptions to sort by mood (sentiment-analysis.ipynb).
Gradio Web App: Interactive UI where users can enter a prompt and get smart book recommendations (gradio-dashboard.py).

Requirements
Python 3.11

OpenAI API key in a .env file

Packages:

kagglehub

pandas

matplotlib

seaborn

python-dotenv

langchain-community

langchain-opencv

langchain-chroma

transformers

gradio

notebook

ipywidgets

##Data
The dataset is sourced from Kaggle.
