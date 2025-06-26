# Name Classification Model - FastText Approach

## Purpose

This notebook implements a machine learning model to classify names based on their likely origin or category (e.g., by nationality or linguistic background). The goal is to build an efficient text classification system that takes a name as input and predicts its class.

## Technologies Used

* FastText (by Facebook AI Research): Used for efficient text classification and word embeddings.
* Scikit-learn: Utilized for data preparation, traditional ML models (Random Forest, Naive Bayes, SVM, Logistic Regression), and evaluation metrics.
* Python libraries: pandas, numpy, re for data handling and preprocessing.
* Names-Dataset: A public dataset for name-based NLP tasks.

## Workflow Overview

1. Data Preparation: Splitting and cleaning name data.
2. Text File Formatting: Formatting training data for FastText.
3. Model Building: Training a FastText classifier.
4. Evaluation: Testing model performance using accuracy and classification reports.

