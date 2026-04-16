# Amazon Review Sentiment Analysis
This project implements a machine learning pipeline to classify Amazon reviews as Positive or Negative. Using a dataset of 50,000 reviews, the model achieves high accuracy by combining text preprocessing with a Logistic Regression classifier.

---
# 🚀 Performance
Accuracy: 87.78%

Precision/Recall: Balanced across both classes (~0.88 F1-Score)

Features: TF-IDF Vectorization (10,000 max features)

---
# 🛠️ Features
Text Cleaning: Automated removal of special characters and stop words.

Lemmatization: Uses NLTK's WordNetLemmatizer to reduce words to their base forms (e.g., "stuning" -> "stun").

Efficient Storage: The trained model and vectorizer are exported as lightweight .pkl files for instant deployment.

Inference Function: Includes a predict_sentiment() function that provides a sentiment label and a confidence score.

---
# 📁 Project Structure
Untitled.ipynb: The full training pipeline, from data loading to evaluation.

sentiment_model.pkl: The trained Logistic Regression model.

tfidf.pkl: The fitted TF-IDF Vectorizer.

requirements.txt: List of Python dependencies (Pandas, Scikit-Learn, NLTK).

---

