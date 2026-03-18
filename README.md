# IMDB Sentiment Analysis NLP

## Overview
This project demonstrates a simple **Natural Language Processing (NLP)** task: **sentiment analysis** on movie reviews.  
We use the **IMDB dataset** containing 50,000 positive and negative reviews to train a model that predicts whether a review is positive or negative.

---

## Tools & Libraries
- Python
- Pandas & NumPy
- NLTK (stopwords, stemming)
- Scikit-learn (TF-IDF, Naive Bayes, train-test split)
- Jupyter Notebook / Google Colab

---

## Steps
1. **Load Dataset**: IMDB movie reviews CSV  
2. **Text Cleaning**: Lowercase, remove special characters, stopwords removal, stemming  
3. **Label Encoding**: Positive = 1, Negative = 0  
4. **Train-Test Split**: 80% training, 20% testing  
5. **Feature Extraction**: TF-IDF Vectorization  
6. **Model Training**: Multinomial Naive Bayes  
7. **Prediction & Evaluation**: Accuracy, Classification Report  
8. **Custom Input Prediction**: Predict sentiment for any review interactively  

---

## Usage
```python
# Load model & TF-IDF vectorizer
# Predict sentiment for any review
review = input("Enter your review: ")
print("Sentiment:", predict_sentiment(review))

Dataset

Source: IMDB Dataset of 50K Movie Reviews

 Results

Accuracy: ~85-90%

Successfully predicts positive and negative sentiments
