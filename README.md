# 📚 Book Recommendation System  
### Collaborative Filtering using KNN

## 📌 Project Overview

This project implements a Book Recommendation System using collaborative filtering techniques.

Read data from three different files named books.csv, users.csv and ratings.csv. Create a book recommendation system based on user inputs.

```text
  1.Find similar users if a user ID is given as input. (Collaborative filtering)
  2.Find similar books if a book ID (ISBN) is given as input. (Content based filtering)
  3.Find book recommendations for a given user ID.
```

Different distance matrices are implemented and user can select which distance funcion to be used.

Implemented accuracy check and comparison of different distance metrices used.

The objective is to:

- Analyze user rating behavior
- Identify popular and highly rated books
- Build a recommendation model using user-item similarity
- Generate personalized book recommendations

The system is based on a memory-based collaborative filtering approach using K-Nearest Neighbors (KNN).

---

## 📁 Project Structure

```text
Book-Recommendation/
├── Book Recommendation.ipynb
├── Books.csv
├── Ratings.csv
├── Users.csv
├── README.md
├── requirements.txt
└── LICENSE
```
---

## 📊 Dataset

The project uses a book ratings dataset containing:

- ISBN
- Book Title
- Book Author
- Year of Publication
- Publisher
- User-ID
- Book-Rating

This Books dataset, which is commonly available via Kaggle in 3 different files Books.csv, Ratings.csv and Users.csv.

If redistributing the dataset, verify original source attribution.

---

## 🛠 Technologies Used

- Python 3.x
- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn
- scipy

---

## 📈 Exploratory Data Analysis

The notebook includes:

- Ratings distribution visualization
- Most rated books analysis
- Active users analysis
- Data filtering and cleaning
- Popularity-based recommendation logic

---

## 🤖 Recommendation Model

### Approach: Memory-Based Collaborative Filtering

Steps performed:

1. Filter users and books based on rating activity
2. Create User-Item matrix
3. Convert matrix to sparse format
4. Apply K-Nearest Neighbors (cosine similarity)
5. Generate similar book recommendations

Model Type:
- KNN with cosine similarity
- Unsupervised similarity-based recommendation

Note:
This is not a deep learning or matrix factorization model. It is a classical neighborhood-based recommender system.

---

## 🚀 How to Run the Project

Clone the repository:

```bash
git clone https://github.com/rahulsreemvk/Book-Recommendation.git
cd Book-Recommendation
Open:
  Book Recommendation.ipynb
Install dependencies:
  pip install -r requirements.txt

