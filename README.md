# Caught in the Web: Detecting Phishing Websites with Machine Learning

## Project Overview

Phishing websites are fraudulent sites designed to steal sensitive information such as passwords, credit card numbers, and banking credentials by mimicking legitimate websites. Given the increasing sophistication of phishing attacks, our project investigates whether machine learning models can effectively distinguish phishing sites from legitimate ones based on structural and behavioral traits. Using a dataset of 10,000 labeled websites, we analyzed key features and trained multiple models to enhance detection accuracy.

## Key Findings

**Analysis**

Phishing URLs often contain more dashes, longer hostnames, and random strings.

Behavioral indicators like disabled right-clicking and hidden form actions were common in phishing sites.

Security indicators, such as missing HTTPS, increased the likelihood of a website being phishing.

**Models**

XGBoost: Achieved the highest F1 score (98.7%), effectively balancing precision and recall.

Logistic Regression: A point system that weighs different features to make a yes/no decision.

Decision Tree: A flowchart of yes/no questions leading to a prediction.

Random Forest: Many decision trees voting together for better accuracy.

K-Nearest Neighbors: Judges a URL by the company it keeps.

Neural Network: Multiple layers of artificial neurons learning patterns like a simplified brain.

Gradient Boosting: A team of models where each new member fixes previous mistakes.

## Data sources

Labeled Website Dataset: 10,000 websites (50% phishing, 50% legitimate)

Feature Categories:

URL Structure: Length, dashes, special characters

Security Indicators: HTTPS presence, IP address usage

Website Content: External links, missing titles

Behavioral Features: Right-click disabled, hidden redirects

Real-Time Interaction Data: Redirect patterns, form submission behavior

## Project Structure

data/ → Raw and processed website dataset

notebooks/ → Jupyter notebooks for data analysis and model training

presentations/ → PDFs summarizing findings and results

articles/ → Blog posts or LinkedIn articles detailing the project

## Conclusion

Machine learning provides a powerful tool for detecting phishing websites in real time. By analyzing both structural and behavioral indicators, our models can identify fraudulent sites with high accuracy. The implementation of such models in browsers, firewalls, or cybersecurity solutions can help mitigate phishing threats and protect users from online fraud.
