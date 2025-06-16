# 📚 Best Selling Books ML Analysis

A data-driven exploration and machine learning analysis of best-selling books from 2009 to 2019. This project focuses on understanding trends in book sales, genre popularity, user ratings, and building a predictive model to estimate whether a book will be highly rated.

---

## 🔍 Project Overview

- **Dataset:** Amazon Best Selling Books (2009–2019)
- **Source:** [Kaggle](https://www.kaggle.com/datasets)
- **Objective:**
  - Explore top books, authors, genres, and trends
  - Visualize key patterns using seaborn & matplotlib
  - Predict if a book will have a high user rating (≥ 4.5)

---

## 📊 Exploratory Data Analysis

- Top authors and most recurring books
- Year-wise trends in genre and price
- Correlation between price, reviews, and ratings
- Split-view of top books before and after 2014
- Genre-wise comparison of user ratings and reviews

> 🖼️ Clean and minimalistic visualizations included using Seaborn

---

## 🤖 Machine Learning

We trained a **Random Forest Classifier** to predict whether a book is highly rated (user rating ≥ 4.5):

### ✅ Features used:
- `Price`
- `Reviews`
- `Year`
- `Genre` (encoded)

### 📈 Performance:
- Accuracy: ~82%
- Precision/Recall optimized using **SMOTE** for class balancing

---

## 🛠️ Tools & Libraries

- Python 🐍
- Pandas & NumPy
- Matplotlib & Seaborn
- Scikit-learn
- Imbalanced-learn (`SMOTE`)

---
## 📁 File Structure
📦 Best Selling Books ML Analysis/
├── 📘 Best Selling Books ML Analysis.ipynb
├── 📄 README.md
└── 📊 assets/ (optional: save plots or data exports here)

