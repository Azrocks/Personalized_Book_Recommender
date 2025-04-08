# 📚 Personalized_Book_Recommender
A deep learning-based collaborative filtering system that recommends books based on user preferences and similar user behavior.
---
## 🔧 What It Does

- Uses a neural network to learn user and book preferences.
- Gives personalized book recommendations.
- Built using the Book-Crossing dataset.
---
## 🗂️ Dataset

Download the dataset from Kaggle:  
[Book-Crossing Dataset](https://www.kaggle.com/datasets/arashnic/book-recommendation-dataset)

You'll need these 3 CSV files:
- `Books.csv`
- `Users.csv`
- `Ratings.csv`

Place them inside a `data` folder in your project.
---
## ▶️ How to Run

1. Clone this repo:
```bash
git clone https://github.com/Azrocks/Personalized_Book_Recommender.git
```

2. Open the notebook (`Book_Recommendation_DL.ipynb`) in **Google Colab** or **Jupyter Notebook**.

3. Set the user ID to recommend books for:
```python
this_user = 4562  # change to any user ID from the dataset
```

4. Run all cells and check the output!
---
## 🛠️ Requirements

- Python 3
- TensorFlow
- Pandas
- NumPy
- Scikit-learn

Install them using:
```bash
pip install tensorflow pandas numpy scikit-learn
```
---
## ✅ To Do

- Add model evaluation (e.g., RMSE)
- Build a simple UI (like Streamlit or Gradio)
- Save and load trained models
---
## ✨ Author

Made by [Azrocks](https://github.com/Azrocks)  
