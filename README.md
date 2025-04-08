# Personalized_Book_Recommender
A deep learning-based collaborative filtering system that recommends books based on user preferences and similar user behavior.

## 🧠 Approach

Have explored different recommendation methods:

- **Popularity-Based**: Recommends top-rated books across all users.
- **Content-Based**: Suggests books similar to a user’s reading history.
- **Collaborative Filtering**: Focused on user-user similarity to provide personalized recommendations.

> The final model uses **collaborative filtering** with neural embeddings for users and books.

## 📊 Dataset

- [Goodbooks-10K Dataset](https://www.kaggle.com/zygmunt/goodbooks-10k)
- Contains ratings for 10,000 books by 53,000 users.

## 🧪 Model Summary

- Embedding layers for users and books
- Dense layers for rating prediction
- Trained using Keras on user-book rating data

## 🚀 How to Run

1. Download dataset from the Kaggle link.
2. Run `book_recommender.ipynb` in Jupyter or Google Colab.

## 📌 To-Do

- Add evaluation metrics (RMSE, MAE)
- Expand to include hybrid recommendations
- Deploy using Streamlit or Flask (optional)

---

# Created by Azrocks
