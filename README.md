# Twitter Sentiment Analysis 2024






## Overview

This project implements a Twitter sentiment analysis model using multiple machine learning classifiers and advanced text feature extraction techniques. The goal is to accurately classify the sentiment of tweets as positive or negative.

## Features

- Utilizes multiple classifiers: Logistic Regression, Random Forest, XGBoost, and LightGBM
- Implements advanced text feature extraction:
  - Word2Vec embeddings
  - TF-IDF weighting
  - Bigram features
- Achieves high accuracy in sentiment classification (target: 80%)

## Requirements

- Python 3.7+
- pandas
- numpy
- scikit-learn
- gensim
- xgboost
- lightgbm
- nltk

## Usage

1. Upload your Twitter sentiment dataset to Google Colab.
2. Update the data loading line with the correct file path.
3. Run all cells in the notebook.

## Results

The script will output the accuracy for each classifier and the overall average accuracy. The target accuracy is 80%.

## Customization

- Adjust the `vector_size` parameter in the Word2Vec model for different embedding dimensions.
- Modify the `ngram_range` and `max_features` in TfidfVectorizer for different feature sets.
- Tune hyperparameters of classifiers for potentially improved performance.



