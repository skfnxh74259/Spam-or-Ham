# Spam or Ham Email Classification

## Overview

Developed a binary text classification system to distinguish spam emails from legitimate messages using Logistic Regression and Scikit-learn. Applied feature engineering techniques to extract meaningful characteristics from email content and evaluated model performance using classification metrics and ROC analysis.

The project focused on transforming raw email data into predictive features and building an interpretable machine learning model for spam detection.

## Tools & Technologies

* Python
* Pandas
* NumPy
* Scikit-learn
* Matplotlib
* Jupyter Notebook
* Git/GitHub

## Skills Demonstrated

* Machine Learning
* Classification
* Logistic Regression
* Feature Engineering
* Text Analytics
* Data Preprocessing
* Model Evaluation
* ROC Analysis
* Predictive Modeling
* Statistical Learning
* Data Visualization

## Project Highlights

* Developed a spam email classifier using Logistic Regression
* Processed a dataset containing 8,348 labeled email messages
* Engineered multiple text-based predictive features
* Evaluated model performance using classification metrics and ROC analysis
* Achieved 91.6% training accuracy
* Identified important indicators associated with spam emails

## Objective

The goal of this project was to develop a machine learning model capable of automatically classifying email messages as spam or non-spam based on textual and structural characteristics.

## Dataset

The dataset consisted of 8,348 labeled email messages containing both spam and non-spam examples.

Features included:

* Email Subject Content
* Email Body Content
* Message Length
* Reply Indicators
* Capitalization Patterns
* Keyword Occurrences
* Spam Labels

## Methodology

### Data Preparation

* Loaded and processed labeled email data
* Extracted target labels for classification
* Converted raw email information into machine learning features
* Prepared structured datasets for model training and evaluation

### Feature Engineering

Engineered predictive features including:

* Spam-related keyword indicators
* Email character count
* Reply detection using "RE:" indicators
* Uppercase character ratios

These features transformed unstructured email content into numerical inputs suitable for machine learning.

### Model Development

* Trained a Logistic Regression classifier using Scikit-learn
* Learned relationships between engineered features and spam labels
* Generated probability estimates for spam classification
* Applied classification thresholds to produce predictions

### Model Evaluation

Evaluated model performance using:

* Classification Accuracy
* Confusion Matrix Metrics
* ROC Analysis
* Probability-Based Predictions

## Results

### Model Performance

| Metric            |        Value |
| ----------------- | -----------: |
| Training Accuracy |        91.6% |
| Dataset Size      | 8,348 Emails |

### Key Findings

* Logistic Regression successfully distinguished spam from non-spam messages using engineered text features.
* Keyword-based indicators provided strong predictive signals for spam detection.
* Message structure features such as capitalization and email length improved classification performance.
* ROC analysis provided insight into classification tradeoffs across decision thresholds.

## Key Takeaways

* Feature engineering plays a critical role in text classification performance.
* Logistic Regression provides an effective and interpretable baseline for spam detection.
* Combining textual and structural email characteristics improves predictive accuracy.
* Classification metrics and ROC analysis are valuable tools for evaluating machine learning models.
* Real-world text data can be transformed into meaningful features for predictive modeling.
