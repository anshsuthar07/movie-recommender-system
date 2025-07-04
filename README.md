# 🎬 Movie Recommender System

A simple content-based movie recommender built using **Python**, **pandas**, **scikit-learn**, and **Streamlit**.  
It suggests similar movies based on metadata like genres, cast, and keywords.

---

## 🔧 Features

- Recommend movies based on a selected title
- Uses cosine similarity on combined metadata
- Clean and interactive Streamlit UI

---

## 🖼️ Screenshot

![App Screenshot](screenshot.png)

---

## 🛠️ Tech Stack

- Python, pandas, numpy
- scikit-learn (CountVectorizer, Cosine Similarity)
- Streamlit (for the web app)
- TMDB 5000 Movies Dataset

---

## ▶️ Run the App

```bash
git clone https://github.com/anshsuthar07/movie-recommender-system.git
cd movie-recommender-system
pip install -r requirements.txt
streamlit run main.py
