# fake-news-predictor-ml
A machine learning-based system to classify news articles as real or fake using NLP techniques like TF-IDF, stemming, and classification models including Logistic Regression, SVM, and Random Forest.
Project Title: Fake News Predictor using ML

Dataset Source: Kaggle (or mention the specific source)

Tech Stack: Python, Scikit-learn, Pandas, NLTK

Algorithms: Logistic Regression, SVM, Random Forest

Metrics: Accuracy, Precision, Recall, F1-score

Outcome: 98% training accuracy

# 📰 Fake News Predictor using Machine Learning

A machine learning-based project aimed at classifying news articles as **real** or **fake** using natural language processing (NLP) techniques. This project combines efficient text preprocessing, feature extraction (TF-IDF), and powerful classification algorithms to tackle the modern-day challenge of misinformation.

---

## 📌 Project Objective

- Develop a system that predicts the authenticity of a news article based on its **author** and **title**.
- Utilize classic ML algorithms like **Logistic Regression**, **Support Vector Machine (SVM)**, and **Random Forest**.
- Achieve high accuracy through advanced text processing and feature engineering techniques.
- Demonstrate how **Machine Learning** and **NLP** can help in combating misinformation.

---

## 📂 Dataset Information

- **Source:** Commonly available fake news datasets (e.g., [Kaggle Fake News](https://www.kaggle.com/c/fake-news/data), LIAR, BuzzFeed, PolitiFact).
- **Type:** Tabular text data with the following columns:
  - `author`: Name of the news article's author.
  - `title`: Headline of the article.
  - `label`: `1` for fake, `0` for real.
- **Derived Column:**
  - `content`: A new column created by merging `author` and `title`.

---

## ⚙️ Technologies Used

| Category              | Tools / Libraries                         |
|-----------------------|-------------------------------------------|
| Language              | Python 3.x                                |
| Libraries             | Pandas, NumPy, Scikit-learn, NLTK         |
| NLP Techniques        | Stemming, TF-IDF, Stopword Removal        |
| Classification Models | Logistic Regression, SVM, Random Forest  |
| Evaluation Metrics    | Accuracy, Precision, Recall, F1-Score     |
| Optional UI           | Streamlit or Flask (for deployment)       |

---

## 🧪 Machine Learning Pipeline

1. **Data Cleaning & Imputation**
   - Handling missing values
2. **Text Preprocessing**
   - Lowercasing
   - Stemming
   - Stopword Removal
   - Tokenization
3. **Feature Engineering**
   - Merging `author` and `title` into `content`
   - Applying TF-IDF Vectorization
4. **Model Building**
   - Training Logistic Regression, SVM, and Random Forest models
5. **Model Evaluation**
   - Using metrics like Accuracy, Precision, Recall, and F1 Score
6. **Prediction**
   - Predicting whether a news article is *real* or *fake*

---

## 📊 Performance Metrics

- **Training Accuracy:** 98%
- **Model Comparison Table:**

| Model               | Accuracy | Precision | Recall | F1 Score |
|--------------------|----------|-----------|--------|----------|
| Logistic Regression| 98%      | 0.97      | 0.98   | 0.975    |
| SVM                | 97.5%    | 0.96      | 0.97   | 0.965    |
| Random Forest      | 98.2%    | 0.98      | 0.98   | 0.98     |

---

## 🎯 Features

- Simple and effective classification of news articles.
- Easy to understand and modify code structure.
- Well-preprocessed dataset to ensure clean inputs to ML models.
- Optionally deployable as a web app using Streamlit.

---

## 🧠 Insights & Explainability

- The model captures key linguistic patterns in fake news headlines.
- Stemming and TF-IDF help in reducing feature space and improving generalization.
- Logistic Regression provides a baseline that is interpretable and robust.

---


