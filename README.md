🎬 Movie Recommendation System

A content-based movie recommendation system that suggests movies similar to a selected title using machine learning techniques.

📌 Overview
This project recommends movies to users based on their preferences. It analyzes features such as genres, keywords, cast, and more to compute similarity scores between movies, helping users discover new films they’re likely to enjoy.

🚀 Features
Recommend top N similar movies for a selected title.

Uses TF-IDF and cosine similarity to measure relevance.

Interactive user interface (Streamlit/Flask, if applicable).

Based on publicly available datasets (e.g., TMDB or IMDb).

🧠 Technologies Used
Python 🐍

Pandas, NumPy

Scikit-learn (TF-IDF Vectorizer, Cosine Similarity)

Streamlit / Flask (for web app)

Jupyter Notebook (for development and visualization)

📂 Dataset
The dataset used is from The Movie Database (TMDB) and includes:

Movie titles

Overviews

Genres

Cast, crew

Keywords

⚙️ How It Works
The data is cleaned and preprocessed (removing nulls, combining relevant features).

A 'soup' of text is created for each movie combining genres, cast, keywords, etc.

TF-IDF Vectorizer is used to convert the text into numerical features.

Cosine Similarity is computed between movie vectors.

When a user selects a movie, the system returns the most similar ones.
