# Spam Ham Classifier (Data 100 @ UC Berkeley) 📩

## Overview

This project builds a simple machine learning model to classify messages as spam or not spam. The goal is to understand how text data can be transformed into features and used in a supervised learning setting.

---

## Task

Given a message, predict whether it is:
- **Spam**
- **Not Spam (Ham)**

---

## Approach

- Preprocessed text data (cleaning, tokenization)
- Converted text into numerical features using **TF-IDF**
- Trained a classification model (Logistic Regression / Naive Bayes)
- Evaluated performance on a held-out test set

---

## Model + Features

- **Features**: TF-IDF (bag-of-words representation)
- **Model**: Logistic Regression 

---

## What I learned

- How to turn raw text into usable features  
- Tradeoffs between different models for text classification  
- The importance of preprocessing in NLP tasks  

---

## Files

- `eda.ipynb` — data exploration and preprocessing  
- `model.ipynb` — feature engineering and model training  
