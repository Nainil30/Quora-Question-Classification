# Quora Questions Classification - NLP Project

## Problem Definition
This project aims to classify questions posted on Quora into **"sincere"** or **"insincere"** categories using Natural Language Processing (NLP).

- **Sincere Questions**: Seek helpful information and contribute to knowledge-sharing.
- **Insincere Questions**: May violate Quora's "Be Nice, Be Respectful" policy by being false, offensive, or divisive.

## Data Preparation
We utilized `train.csv` and `test.csv` from the [Quora Insincere Questions Classification Kaggle Dataset](https://www.kaggle.com/c/quora-insincere-questions-classification).

- `train.csv` contains columns for question ID, text, and target labels.
- Data preprocessing included bag of words, stemming, stop word removal, and TF-IDF vectorization.

## Models Implemented
- **Logistic Regression**
- **Naive Bayes**
- **Convolutional Neural Network (CNN)**
- **BERT Implementation** for a Streamlit application.

## Performance Metrics
Models were evaluated based on:
- Accuracy
- Precision
- Recall
- F1 score

## Exploratory Data Analysis (EDA) 🔍
We included Word Cloud Visualization to identify the most frequent words and Bigram Frequency Analysis for both sincere and insincere questions.

## Feature Extraction 🛠️
We analyzed text characteristics crucial for classification, including:
- Word count
- Unique word count
- Character count
- Stopwords count
- Punctuation count
- Title and uppercase words count
- Average word length

## Baseline Model Implementation 🏗️
- **Logistic Regression**: Implemented using `sklearn` with evaluation metrics like accuracy, precision, recall, and F1 score.
- **Naive Bayes**: Known for its efficiency in binary classification tasks.

## Advanced Model Implementation 🔬
- **CNN (Convolutional Neural Network)**: Chosen for its strong performance in capturing complex patterns in text data.

## Streamlit Application BERT Implementation 🌐
We developed a Streamlit application that leverages the DistilBERT model for real-time text classification, enabling:
- Text input
- CSV upload for model evaluation
- Display of classification results and model performance metrics

## Strengths, Weaknesses, and Improvements 📈
We discussed the strengths and weaknesses of each model and proposed improvements for future iterations.

## Conclusions
- CNNs showed strong performance but with higher computational costs.
- Logistic Regression and Naive Bayes offered computational efficiency but were less powerful.
- The Streamlit application with DistilBERT proved to be effective for real-time classification.

