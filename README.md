# 📚 Book Recommendation System

A Collaborative Filtering based Book Recommendation System built using Python, Pandas, NumPy and Flask.  
The system recommends books based on user similarity using cosine similarity on a user-item interaction matrix.

---

## 🚀 Features

- 🔥 Top 50 Most Popular Books (based on ratings & votes)
- 🤝 Collaborative Filtering based recommendations
- 📊 Cosine Similarity on User-Book Matrix
- 🌐 Flask Web Interface
- 📖 Clean Bootstrap UI
- ⚡ Fast recommendations using precomputed similarity matrix

---

## 🧠 How It Works

### 1️⃣ Popularity Based Recommendation
- Books with more than 250 ratings
- Sorted by average rating
- Top 50 books displayed on homepage

### 2️⃣ Collaborative Filtering
- Users who rated more than 200 books are considered
- Books with at least 50 ratings are selected
- User-Item Pivot Table created
- Cosine Similarity computed between books
- Top similar books recommended

---

## 🛠️ Tech Stack

- Python
- Pandas
- NumPy
- Scikit-learn
- Flask
- Bootstrap (Frontend)

---

## 📂 Project Structure

