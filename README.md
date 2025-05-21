## 🎵 Lyrics-Based Music Recommender

A content-based music recommendation system that suggests top 5 similar songs using lyrical similarity via TF-IDF and cosine similarity. Built using the Spotify Million Song Lyrics dataset.

---

## 🔍 Overview

Modern music apps are overloaded with options—this recommender helps users discover lyrically aligned tracks based on a song of their choice.

**Key Features:**
- Content-based filtering using lyrics only
- TF-IDF vectorization + cosine similarity
- Precision@5 = 1.0000, Recall@5 = 0.7143, Accuracy = 1.0000
- Clean UI built using Streamlit

---

## 📂 Dataset

- **Source:** Kaggle - [Spotify Million Song Lyrics](https://www.kaggle.com/datasets/gyani95/spotify-million-song-dataset)
- ~237,000 songs with lyrics, artist, and track names

---

## 🧠 How It Works

1. Clean & preprocess lyrics (stopwords, stemming, etc.)
2. Convert lyrics to TF-IDF vectors (top 10k terms)
3. Compute cosine similarity between songs
4. Recommend top 5 songs most similar to the query
5. (Optional) Retrieve album art via Spotify API

---

## 🧪 Evaluation

| Metric        | Score   |
|---------------|---------|
| Precision@5   | 1.0000  |
| Recall@5      | 0.7143  |
| Accuracy      | 1.0000  |

---

## 💻 Tech Stack

- **Python 3.x**
- **Libraries:** `pandas`, `numpy`, `nltk`, `scikit-learn`, `Streamlit`, `Spotipy`
- **Modeling:** TF-IDF, cosine similarity
- **Frontend:** Streamlit UI

---

## 🚀 How to Run

```bash
git clone https://github.com/<your-username>/lyrics-based-music-recommender.git
cd lyrics-based-music-recommender
pip install -r requirements.txt
streamlit run app.py

```
---

## 🔮 Future Work
- Add genre and audio features (tempo, energy, etc.)
- Build a REST API using FastAPI
- Containerize with Docker for deployment
- Explore hybrid models with collaborative filtering

---

## ⭐️ Show Your Support
If you like this project, consider giving it a ⭐️ on GitHub!









