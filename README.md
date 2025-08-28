# Fake-News-Detection-Model
This project is a Fake News Detection system built using machine learning algorithms in Python. It classifies news articles as either fake or real based on their textual content, utilizing popular models and evaluation metrics for robust performance assessment.

Project Description
Fake News Detection Using Machine Learning
This repository contains a machine learning pipeline for detecting fake news in text articles. The project leverages Python and Scikit-learn to preprocess data, train models, and evaluate predictions.

Key Features
Data Preprocessing: Utilizes TF-IDF vectorization to convert text into numerical features for model training.

Model Training: Implements both Logistic Regression and Passive Aggressive Classifier to classify news articles as fake or true.

Performance Evaluation: Computes accuracy, precision, recall, F1-score, and confusion matrices for both models to assess their effectiveness.

Sample Predictions: Demonstrates real-time prediction on example news snippets, highlighting the model's usability.

Workflow
Load and Inspect Data: Reads a cleaned news dataset containing text and labels.

Split Dataset: Divides the data into training and testing sets using stratified splitting for balanced representation.

Feature Extraction: Transforms text data into TF-IDF features for model input.

Model Training: Fits both Logistic Regression and Passive Aggressive models on the training data.

Performance Metrics: Evaluates predictions using classification reports and confusion matrices.

Sample Prediction: Provides predictions for custom news examples to illustrate functionality.



Results
Logistic Regression:

Accuracy: ~98%

Passive Aggressive Classifier:

Accuracy: ~99%

Detailed classification reports and confusion matrices included
