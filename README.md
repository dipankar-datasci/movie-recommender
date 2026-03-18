# 🎬 Movie Recommender System

A content-based movie recommender system built using Machine Learning.

## 🔗 Live Demo
[Click here to see the app](https://movie-recommender-jdmlvsurxxkhjnaecrb3ks.streamlit.app/)

## 📌 About the Project
This project recommends 5 similar movies based on the selected movie using:
- Content-based filtering
- Cosine similarity
- TMDB API for movie posters

## 🛠️ Tech Stack
- Python
- Pandas, NumPy
- Scikit-learn
- NLTK
- Streamlit
- TMDB API

## 📊 Dataset
- TMDB 5000 Movies Dataset
- 4806 movies

## ⚙️ How it works
1. Movie tags are created from genres, keywords, cast, crew and overview
2. Tags are vectorized using CountVectorizer (5000 features)
3. Cosine similarity is calculated between all movies
4. Top 5 most similar movies are recommended

## 🚀 How to run locally
1. Clone the repository
git clone https://github.com/yourusername/movie-recommender

2. Install dependencies
pip install -r requirements.txt

3. Run the app
streamlit run app.py

## 📸 Screenshots

![Home](Screenshot%20(80).png)
![Recommendations](Screenshot%20(81).png)
