# llm-book-recommender
This project is a personalized implementation of a book recommendation system built using large language models (LLMs). Inspired by a course from freeCodeCamp, it showcases how to combine semantic search, classification, sentiment analysis, and a web interface to deliver smart, AI-driven book suggestions.

The project is organized into five key parts:

1. Text Preprocessing and Cleaning
All initial text data cleaning and exploration are handled in the data-exploration.ipynb notebook. This step ensures that the raw book metadata is well-formatted and ready for downstream tasks.

2. Building a Vector Search Engine
The notebook vector-search.ipynb demonstrates how to convert book descriptions into semantic vectors and store them in a vector database. This enables natural language queries like “a novel about lost friendship” to return the most relevant book results.

3. Zero-Shot Text Classification
Using zero-shot learning capabilities of LLMs, the text-classification.ipynb notebook classifies each book as either fiction or non-fiction. This adds an extra layer of filtering to help refine recommendations.

4. Sentiment and Emotion Detection
In sentiment-analysis.ipynb, I used LLMs to assess the emotional tone of each book’s description. This makes it possible to sort and recommend books based on mood or style—whether they’re uplifting, tense, sorrowful, or adventurous.

5. Interactive Web Interface
A user-friendly interface built with Gradio can be found in gradio-dashboard.py. This allows users to interact with the recommender system, enter natural language queries, and explore recommended books with ease.

🛠️ Tech Stack & Dependencies
This project was built with Python 3.11 and relies on several key libraries, including:

kagglehub

pandas, matplotlib, seaborn (for data handling and visualization)

langchain-community, langchain-opencv, langchain-chroma

transformers (for working with pre-trained LLMs)

gradio (for the front-end interface)

notebook, ipywidgets (for working in Jupyter)

A full list of dependencies can be found in the included requirements.txt file.

🔑 API Keys & Environment Setup
To build and query the vector database, you’ll need access to the OpenAI API. Create a .env file in the root directory with your OpenAI key:

ini
Copy
Edit
OPENAI_API_KEY=your_openai_key_here
More detailed instructions are provided in the code notebooks.

📦 Dataset
The dataset for this project is sourced from Kaggle. Setup instructions for downloading and preparing the dataset are provided in the repository.

Feel free to explore, adapt, or expand on this project for your own learning or applications!

Let me know if you want a shorter version, or one formatted specifically for a portfolio or GitHub profile.








You said:
make it more simpler, it should be such a way that if a recruiter sees this he or she would want to hire me


ChatGPT said:
Absolutely! Here's a simplified, professional, and recruiter-friendly version of your README. It keeps things clear and impressive without sounding like a copy of the original source:

📚 AI-Powered Book Recommender System
This project is a smart book recommendation system built using Large Language Models (LLMs). It combines natural language understanding, emotion analysis, and an interactive web app to help users find books based on the mood, genre, or topic they describe.

🔍 Key Features
Text Cleaning & Preparation
Cleaned and explored book descriptions to make them ready for AI processing.

Semantic Search with Vector Database
Used LLMs to convert book summaries into embeddings and built a vector search system. This allows users to ask natural questions like “a story about revenge” and get relevant books.

Zero-Shot Text Classification
Classified books as fiction or non-fiction using a zero-shot approach—no extra training required.

Sentiment & Emotion Analysis
Detected emotions like joy, suspense, or sadness in book summaries so users can explore recommendations by tone.

Gradio Web App
Built an interactive interface using Gradio where users can type in a query and instantly get AI-generated book recommendations.

🛠️ Tech Stack
Python 3.11

LangChain, Transformers, Gradio

Pandas, Seaborn, Matplotlib

Kagglehub, dotenv

Jupyter Notebooks for development

All dependencies are listed in the requirements.txt file.

⚙️ Setup
Download the dataset from Kaggle (instructions in repo).

Add your OpenAI API key to a .env file in the root:

ini
Copy
Edit
OPENAI_API_KEY=your_key_here
Run the notebooks in order or launch the Gradio app to explore book recommendations.

✅ What I Learned
Built a full AI-powered product pipeline—from data cleaning to deployment.

Applied real-world LLM use cases like semantic search, zero-shot classification, and sentiment detection.

Strengthened skills in Python, NLP, and deploying user-friendly AI tools.

🚀 Try it Out
Launch the Gradio app and enter queries like:

“A book about a lonely journey”

“An uplifting true story”

“A dark and thrilling mystery”

The system will find the best matches using deep semantic understanding.

