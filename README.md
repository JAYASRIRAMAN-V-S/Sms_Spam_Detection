# Spam Detection Using Naive Bayes Classifier

This project implements a spam detection system using a Naive Bayes classifier to distinguish between spam and ham messages.

## Overview

The project involves several steps:
  - **DATA PREPROCESSING**: Tokenization, removal of stopwords, and stemming using NLTK.
    
  - **VECTORIZATION**: Converting text data into numerical vectors using `CountVectorizer`.
    
  - **MODEL TRAINING**: Using a Multinomial Naive Bayes classifier.
    
  - **EVALUATION**: Assessing model performance with accuracy metrics, a confusion matrix, and a classification report.

## Dataset

The dataset used is `spam.csv`, containing labeled text messages:
- **ham**: Non-spam messages
- **spam**: Spam messages

## Requirements

The project requires the following Python libraries:
- pandas
- nltk
- scikit-learn
- matplotlib
- seaborn

Install the required libraries with:
```bash
pip install -r requirements.txt
