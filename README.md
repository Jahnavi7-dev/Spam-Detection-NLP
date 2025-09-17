# Spam Detection using NLP

This project builds a **Spam Detection system** using Natural Language Processing (NLP) and Machine Learning.  
The model classifies SMS/text messages as **Spam** or **Ham (Not Spam)** based on their content.  

The work includes text preprocessing, feature extraction with TF-IDF, model training with Logistic Regression, and hyperparameter optimization using Bayesian search.

## Problem Statement
Spam messages (unwanted SMS, promotional texts, phishing attempts) are a common nuisance and security risk.  
The goal of this project is to automatically classify text messages as spam or not spam using NLP and machine learning.

## Features
- **Data Preprocessing**
  - Removed HTML tags (BeautifulSoup)  
  - Normalized text (Unidecode)  
  - Tokenization (NLTK)  
  - Stopword removal (NLTK)  
  - Lemmatization (spaCy)  

- **Feature Engineering**
  - Converted text into numerical features using **TF-IDF Vectorization**

- **Model Training**
  - Logistic Regression model  
  - Hyperparameter tuning using **BayesSearchCV** from scikit-optimize  

- **Evaluation**
  - Accuracy Score  
  - F1-score  
  - Confusion Matrix visualization  

## Results
- Accuracy: 98.4%
- F1-score: 0.991
  
## Tech Stack
- Python  
- pandas, numpy  
- NLTK, spaCy, BeautifulSoup, unidecode  
- scikit-learn  
- scikit-optimize  
- matplotlib, seaborn  
