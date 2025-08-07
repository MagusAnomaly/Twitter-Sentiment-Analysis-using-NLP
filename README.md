# Twitter Sentiment Analysis using NLP

A Natural Language Processing (NLP) project that focuses on classifying tweet sentiments using pre-cleaned data. This project demonstrates end-to-end sentiment analysis using machine learning on real-world text data.

---

## Project Overview

- Dataset: Pre-cleaned tweets with sentiment labels  
- Goal: Predict whether a tweet expresses a positive, neutral, or negative sentiment  
- Tech Stack: Python, Scikit-learn, Pandas, Seaborn, NLP libraries (TextBlob, CountVectorizer)

---

## Highlights & Methodology

- Text Preprocessing:
  - Lowercasing, punctuation removal, stopword filtering, stemming
  - Used `CountVectorizer` for tokenization and vector representation

- ML Models Trained:
  - Multinomial Naive Bayes  
    - Accuracy: 82.12%
  - Logistic Regression
    - Accuracy: 84.00%
  - Support Vector Machine (SVM)
    - Accuracy: 84.89% (Best)

- Evaluation Metrics:
  - Confusion matrix, classification report
  - Accuracy, precision, recall, and F1-score

---

## Sample Results

| Model                 | Accuracy |
|----------------------|----------|
| Multinomial NB       | 82.12%   |
| Logistic Regression  | 84.00%   |
| SVM (Linear Kernel)  | 84.89%   |

- Sentiment distribution:
  - Positive: ~43%
  - Neutral: ~30%
  - Negative: ~27%

---

## Features

- End-to-end sentiment classification pipeline  
- Lightweight and interpretable models  
- Focused on real-world text processing challenges

---

## Future Enhancements

- Incorporate LSTM or BERT for deep learning-based sentiment classification  
- Add live sentiment scraping using Tweepy and Twitter API  
- Add visualizations like word clouds or polarity histograms

---

## Learning Outcomes

- Built practical NLP skills with real sentiment data  
- Gained experience with different ML models and evaluation techniques  
- Understood preprocessing impact on model performance
