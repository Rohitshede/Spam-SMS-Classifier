# Spam SMS Classifier

## Overview:
This project aims to classify SMS messages as either spam or non-spam (ham) using machine learning techniques. Spam SMS messages are unsolicited, often containing advertisements or phishing attempts, while ham messages are legitimate user communications. By accurately identifying spam messages, this classifier helps users filter unwanted messages and improve overall SMS communication experience.

## Methodology:
The spam SMS classification process involves the following steps:

- Data Collection: Obtained a dataset of SMS messages labeled as spam or ham from kaggle.
- Data Preprocessing: Cleaned and processed the SMS data by removing punctuation, stopwords, and special characters. Tokenization and normalization techniques were applied to standardize the text data.
- Feature Extraction: Extracted relevant features from the text data, such as word frequency, n-grams, and TF-IDF (Term Frequency-Inverse Document Frequency) vectors.
- Model Training: Trained Naive Bayes model using the labeled SMS dataset.
- Evaluation: Evaluated the performance of the trained models using metrics such as accuracy, precision, recall, and F1-score on a separate test dataset or through cross-validation.
