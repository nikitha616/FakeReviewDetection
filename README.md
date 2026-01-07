# Fake Review Detection

## Overview

This project focuses on detecting fake reviews on e-commerce platforms using machine learning and natural language processing techniques. A hybrid ensemble approach is used to improve classification accuracy and robustness.

## Technologies

- Python
- NLTK
- scikit-learn
- XGBoost

## Approach

- Text preprocessing using NLP techniques such as cleaning, tokenization, and lemmatization
- Feature extraction using Bag of Words (BoW)
- Model training using Random Forest and XGBoost
- Stacking ensemble with Logistic Regression as a meta-learner

## Results

- Achieved **86.45% accuracy** on the evaluation dataset
- Improved robustness compared to individual classifiers

## Files

- `FakeReview.ipynb` – Model implementation and experiments
- `Dataset.csv` – Review dataset

## How to Run

1. Install required dependencies
2. Open `FakeReview.ipynb` in Jupyter Notebook
3. Run all cells sequentially
