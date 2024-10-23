# Spam filter Using Multiple Models

This project focuses on performing Spam filter using a variety of machine learning and deep learning models. We aim to compare these models and evaluate their performance using metrics such as accuracy, precision, recall, and F1-score. The dataset used for this task contains labeled text data for positive and negative sentiments.

## Table of Contents
- [Overview](#overview)
- [Models Implemented](#models-implemented)
- [Evaluation Metrics](#evaluation-metrics)
- [Results and Analysis](#results-and-analysis)
- [Installation](#installation)
- [Usage](#usage)
- [Contributors](#contributors)
- [License](#license)

## Overview
Spam filter is the process of identifying the emotional tone behind a body of text. This can be useful for understanding the attitudes, opinions, and emotions expressed in online reviews, social media comments, or any other textual content.

In this project, we implement and evaluate various machine learning and deep learning models to determine which one performs best for Spamclassification tasks. The models range from traditional machine learning algorithms like Naive Bayes to deep learning models like LSTMs and GRUs.

## Models Implemented
The following models are implemented for Spam classification:
- **RNN (Recurrent Neural Network)**
- **Deep RNN** (Multi-layered RNN)
- **LSTM (Long Short-Term Memory)**
- **Deep LSTM** (Multi-layered LSTM)
- **GRU (Gated Recurrent Unit)**
- **Bi-GRU** (Bidirectional GRU)
- **Naive Bayes**
- **Multinomial Naive Bayes**
- **Bernoulli Naive Bayes**
- **Complement Naive Bayes**
- **Random Forest**
- **SVM (Support Vector Machine)**

Each model is trained and tested on the dataset, and performance metrics are recorded to assess their effectiveness in predicting sentiment.

## Evaluation Metrics
The models are evaluated using the following metrics:
- **Accuracy**: The proportion of correctly classified sentiments out of the total sentiments.
- **Precision**: The ratio of true positive results to the sum of true positive and false positive results.
- **Recall**: The ratio of true positive results to the sum of true positive and false negative results.
- **F1 Score**: The harmonic mean of precision and recall, providing a balanced metric for model evaluation.

```python
Evaluation Metrics:
    - Accuracy: acc_score
    - Precision: precision_score
    - Recall: recall_score
    - F1 Score: fscore_score
