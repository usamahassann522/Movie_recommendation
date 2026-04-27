# 🎬 Movie Recommendation System Using Machine Learning Techniques

## 📌 Project Overview
This project implements a movie recommendation system using the MovieLens dataset. The main objective is to compare multiple machine learning techniques and identify the most accurate model for predicting user preferences.

## 📊 Dataset
- MovieLens (ml-latest-small)
- 100,836 ratings from 610 users
- 9,742 movies
- Rating scale: 0.5 – 5  
Source: https://grouplens.org/datasets/movielens/

## ⚙️ Models Implemented
- Content-Based Filtering (TF-IDF + Cosine Similarity)
- User-Based Collaborative Filtering (KNN)
- Item-Based Collaborative Filtering (KNN)
- SVD (Matrix Factorization)

## 📈 Evaluation Metrics
- RMSE (Root Mean Square Error)
- MAE (Mean Absolute Error)
- Precision@K
- Recall@K

## 🏆 Results
- SVD achieved the best performance
- Lowest RMSE indicates highest prediction accuracy
- Effectively handles sparse user-item data

## 🔧 Technologies Used
- Python
- Pandas, NumPy
- Scikit-learn
- Surprise Library
- Matplotlib / Seaborn

## ▶️ How to Run
1. Open the notebook in Google Colab
2. Upload MovieLens files or mount Google Drive before running
3. Install required libraries:
4. 3. Run all cells

## 👤 Author
Usama Hassan  
MSc Data Science – University of Hertfordshire
