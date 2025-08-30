📰 Fake News Detection using NLP & Machine Learning
📌 Overview

This project focuses on detecting Fake News articles using Natural Language Processing (NLP) and Machine Learning classification algorithms.
The model is trained to classify whether a news article is Real (0) or Fake (1) based on its textual content.

📂 Dataset

The dataset used is the Fake and Real News Dataset from Kaggle:
👉 Fake and Real News Dataset

Fake.csv → Fake news articles

True.csv → Real news articles

Columns: title, text, subject, date

We added a label column:

1 → Fake

0 → Real

🛠️ Tech Stack

Programming Language: Python

Libraries: Pandas, NumPy, Scikit-learn, NLTK

Feature Extraction: TF-IDF Vectorizer

Model: Logistic Regression (baseline)

🚀 Project Pipeline

Data Loading → Import real and fake news CSV files.

Data Preprocessing

Lowercasing, removing punctuation, numbers, stopwords

Cleaning text using regex

Feature Extraction

Convert text into numerical vectors using TF-IDF

Model Training

Logistic Regression classifier

Evaluation

Accuracy, Precision, Recall, F1-score

Confusion Matrix

📊 Results

Accuracy: ~92% (Logistic Regression + TF-IDF)

The model can successfully differentiate fake vs real news articles.
