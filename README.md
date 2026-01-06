# phishing-url-detection-ml
Machine learning project for detecting phishing URLs using handcrafted URL features and Random Forest.
# Phishing URL Detection using Machine Learning

## Problem Statement
Phishing attacks use malicious URLs to trick users into revealing sensitive information.
This project aims to classify URLs as phishing or legitimate using machine learning techniques.

## Dataset
The dataset contains URLs labeled as phishing or legitimate.
URLs are transformed into numerical features before training the model.

## Feature Engineering
The following features were extracted from URLs:
- URL length
- Number of dots
- Number of hyphens
- Presence of `@` symbol
- Presence of IP address
- Digit count
- HTTPS usage

## Models Used
- Logistic Regression (baseline)
- Random Forest Classifier (final model)

## Evaluation Metrics
The models were evaluated using:
- Accuracy
- Precision
- Recall
- F1-score

Random Forest performed better than Logistic Regression, especially in detecting phishing URLs.

## Results
- Improved phishing detection compared to baseline
- Better recall for phishing URLs
- Reduced false negatives

## Notebook
The complete implementation is available on Kaggle:
[https://www.kaggle.com/code/jayshreerathore/phising-urls-01]

## Future Improvements
- Add more URL-based features
- Try advanced models like XGBoost
- Improve recall further
