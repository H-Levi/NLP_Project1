Wikipedia Text Classification

This code performs text classification to categorize Wikipedia articles into medical and non-medical topics. The process involves retrieving summaries of articles from Wikipedia, preprocessing the data, and training machine learning models for classification.

Overview

Data Retrieval:

Wikipedia articles are retrieved using specific search terms for medical and non-medical topics.
The summaries of the articles are collected and stored in JSON files (medical.json and non_medical.json).

Data Preprocessing:

Text data is preprocessed to be tokenized, remove stop words, perform stemming, and lemmatization.
The data is divided into two categories: medical and non-medical.

Feature Extraction:

Features are extracted from the preprocessed text to train machine learning models.
The feature extraction process involves tokenization, lowercase conversion, and the removal of non-alphabetic characters.

Dataset Splitting:

The dataset is split into training and testing sets with an 80:20 proportion, respectively.

Model Training:

The Naive Bayes classifier is trained using the extracted features.
The performance of the model is evaluated using accuracy and a classification report.

Additional Testing:

The trained model is tested with additional sentences to check its ability to categorize new data.
The predictions of the Naive Bayes model are printed for manual verification.

Results

The Naive Bayes model achieves an accuracy of approximately 93% on the test set(the values vary with each execution). The classification report provides additional details on precision, recall, and F1-score for both medical and non-medical categories.

 The Naive Bayes model correctly classified the given additional test sets, making the manual verification of the model's predictions a successful endevour.
