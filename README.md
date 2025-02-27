# Hallucination Detection using Logistic Regression

This repository contains a Python implementation of a binary hallucination detection classifier using logistic regression. The classifier is trained on the [XSum Hallucination dataset](https://github.com/google-research-datasets/xsum_hallucination_annotations/blob/master/factuality_annotations_xsum_summaries.csv) to determine whether a given text is hallucinated or not.

## Overview

- **Dataset**: The XSum Hallucination dataset is used, where the `summary` field serves as the input text and `is_factual` as the label.
- **Model**: Logistic Regression is implemented from scratch without using any machine learning libraries.
- **Evaluation Metrics**: Accuracy, Precision, Recall, F1 Score, and a Confusion Matrix are used to assess the model's performance.
- **Cross-Validation**: K-Fold Cross-Validation is implemented to evaluate the model's robustness.

## Contents

1. **Data Preprocessing**: Cleaning and preparing the dataset for training.
2. **Model Implementation**: Custom implementation of Logistic Regression for binary classification.
3. **Model Training**: Training the model with hyperparameter tuning.
4. **Model Evaluation**: Calculating accuracy, precision, recall, F1 score, and creating a confusion matrix.
5. **Cross-Validation**: Implementing k-fold cross-validation for robustness assessment.
6. **Error Analysis**: Identifying misclassified examples and suggesting improvements.
