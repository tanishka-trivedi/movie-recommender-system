# 🎬 Movie Recommendation System

A modern **Content-Based Movie Recommendation System** built using **Python, Machine Learning, and Streamlit**.  
The app recommends movies similar to a selected movie using movie metadata and cosine similarity.

---

## 🚀 Features

- 🎥 Get movie recommendations instantly
- 🧠 Content-based recommendation system
- 🔍 Uses movie metadata for similarity matching
- ⚡ Fast recommendations using precomputed similarity matrix
- 🎨 Interactive Streamlit web interface
- 📊 Machine learning based similarity calculation

---

## 🛠️ Tech Stack

- Python
- Pandas
- NumPy
- Scikit-learn
- Streamlit
- Pickle

---

## 🧠 How It Works

This project uses **content-based filtering**.

The system analyzes movie information such as:

- Movie title
- Genres
- Keywords
- Overview
- Cast
- Crew

These features are combined and converted into numerical vectors.  
Cosine similarity is then used to find movies that are most similar to the selected movie.

---

## 📂 Project Structure

```bash
movies-recommender-system/
│
├── app.py                         # Streamlit application
├── main.py                        # Model/data processing script
├── Movie_recommender_system.ipynb # Main notebook
├── movies.pkl                     # Processed movie data
├── movies_dict.pkl                # Movie dictionary file
├── similarity.pkl                 # Similarity matrix
├── requirements.txt               # Project dependencies
└── README.md                      # Project documentation
