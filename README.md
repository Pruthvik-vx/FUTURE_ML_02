# FUTURE_ML_02 - Support Ticket Classification System

## Project Overview

This project uses Natural Language Processing (NLP) and Machine Learning to automatically classify IT support tickets and assign priority levels.

### Features

- Text cleaning and preprocessing
- Stopword removal
- TF-IDF feature extraction
- Multi-class ticket classification
- High / Medium / Low priority prediction
- Accuracy, Precision, Recall and F1 Score evaluation
- Confusion matrix visualization

## Dataset

Classification of IT Support Tickets dataset from Zenodo.

Dataset:
https://zenodo.org/records/7648117

The dataset contains 2,229 manually classified IT support tickets across 7 categories.

## Machine Learning

### Category Classification

TF-IDF converts ticket text into numerical features, followed by a Linear Support Vector Classifier (LinearSVC).

### Priority Classification

The original dataset does not contain priority labels. Therefore, High, Medium and Low priority labels are derived using transparent keyword-based rules.

## Technologies

- Python
- Pandas
- NumPy
- Scikit-learn
- NLTK
- Matplotlib
- Jupyter Notebook

## Project Structure

```text
FUTURE_ML_02/
├── data/
├── models/
├── notebooks/
├── outputs/
├── .gitignore
└── README.md




