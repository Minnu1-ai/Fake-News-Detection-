# Fake News Detection

A Natural Language Processing (NLP) and Machine Learning project for automatically classifying news articles as **Real** or **Fake**.

This project implements an end-to-end text classification pipeline covering data preparation, text preprocessing, TF-IDF feature extraction, model training, evaluation, model comparison, error analysis, prediction confidence analysis, and final news classification.


## Overview

The spread of misleading and fabricated news highlights the importance of automated approaches for analyzing and classifying news content.

This project develops a machine learning pipeline that analyzes the textual content of news articles and predicts whether an article is **Real** or **Fake**.

Two classification models are trained and compared:

- **Multinomial Naive Bayes**
- **Logistic Regression**

The best-performing model is selected based on **F1-Score** and used as the final prediction model.


## Project Workflow

```text
Raw News Data
      ↓
Data Loading & Inspection
      ↓
Data Cleaning
      ↓
Text Preprocessing
      ↓
Train/Test Split
      ↓
TF-IDF Feature Extraction
      ↓
Model Training
      ↓
Model Evaluation
      ↓
Model Comparison
      ↓
Best Model Selection
      ↓
Error Analysis
      ↓
Prediction Confidence Analysis
      ↓
Final News Prediction
