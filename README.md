Turkish News Classification
Classification of Turkish News Headlines

This project automatically classifies Turkish news headlines into categories using Multinomial Naive Bayes. It includes text preprocessing, TF‑IDF vectorization, model training, and performance evaluation.

🔹 Objective
Accurately categorize news headlines.
Understand the most frequent words per category.
Evaluate model performance using accuracy, precision, recall, and F1-score.

🔹 Methods
Text Preprocessing: Lowercasing, removing punctuation and numbers, filtering stopwords.
TF‑IDF Vectorization: Converting text into numerical features.
Multinomial Naive Bayes: Probabilistic model for categorical classification.
Performance Evaluation: Confusion matrix and category-wise metrics.

🔹 Project Files
TURKISH-NEWS-CLASSIFICATION.ipynb – Jupyter Notebook with all steps.
news.csv – Dataset containing news headlines and categories.
news_model.pkl – Trained Naive Bayes model.
vectorizer.pkl – TF‑IDF vectorizer used for feature extraction.

📊 Outputs
WordClouds: Visual representation of most common words per category.
Performance Bar Chart: Displays precision, recall, and F1-score.
Confusion Matrix: Shows misclassified categories.


📦 Saving the Model
import pickle

pickle.dump(model, open("news_model.pkl", "wb"))
pickle.dump(vectorizer, open("vectorizer.pkl", "wb"))


