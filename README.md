# 🎵 Spotify Music Recommendation System

A **Content-Based Music Recommendation System** built using **Python** and **Machine Learning**. This project recommends songs that are similar to a selected track by analyzing Spotify audio features such as danceability, energy, tempo, loudness, valence, and acousticness.

---

## 📌 Project Overview

The objective of this project is to build a recommendation engine that suggests songs with similar musical characteristics. The system uses Spotify audio features, standardizes them, and applies the **K-Nearest Neighbors (KNN)** algorithm with the **cosine distance** metric to find similar tracks.

---

## 🚀 Features

- Load and preprocess Spotify dataset
- Handle missing values and duplicate records
- Perform Exploratory Data Analysis (EDA)
- Select relevant audio features
- Standardize numerical features using StandardScaler
- Train a K-Nearest Neighbors (KNN) recommendation model
- Recommend the Top 10 similar songs
- Memory-efficient implementation for large datasets

---

## 📊 Dataset

**Dataset:** Spotify Tracks Dataset

The dataset contains:

- Track Name
- Artist
- Album Name
- Popularity
- Genre
- Danceability
- Energy
- Loudness
- Speechiness
- Acousticness
- Instrumentalness
- Liveness
- Valence
- Tempo

---

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Scikit-learn
- Jupyter Notebook

---

## 🤖 Machine Learning

**Algorithm Used:**

- K-Nearest Neighbors (KNN)

**Distance Metric:**

- Cosine Distance

**Feature Scaling:**

- StandardScaler

---

## 📂 Project Structure

```
Spotify-Music-Recommendation-System/
│
├── Spotify_Music_Recommendation_System.ipynb
├── spotify.csv.xlsx
├── README.md
├── requirements.txt
├── app.py
└── images/
```

---

## 📈 Project Workflow

1. Import Libraries
2. Load Dataset
3. Data Exploration
4. Data Cleaning
5. Exploratory Data Analysis (EDA)
6. Feature Selection
7. Feature Scaling
8. Train KNN Model
9. Generate Recommendations
10. Model Testing

-

---

## 👩‍💻 Author

**Lakshmi Rushitha Dabbiru**

- GitHub: https://github.com/rushithadabbiru4-ai
- 

---

## ⭐ If you found this project useful, please consider giving it a star on GitHub!
