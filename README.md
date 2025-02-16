# Credit Card Customer Attrition Prediction

## Overview

This project aims to predict credit card customer attrition (churn) using machine learning models. By analyzing a dataset with over 10,000 data points and 21 features, the goal is to identify patterns that can help banks reduce customer turnover. The models applied include Logistic Regression, Decision Tree, Random Forest, and Light GBM.

## Problem Statement

Customer retention is crucial in the competitive credit card industry, as higher retention rates contribute directly to profitability. By predicting which customers are at risk of attrition, banks can take proactive measures, such as offering targeted incentives or enhancing customer experience, to retain valuable clients.

## Approach

- **Data Exploration & Cleaning**: The dataset was thoroughly cleaned to handle missing values, encode categorical variables, and scale features for consistency.
  
- **Model Selection**: Four models were tested—Logistic Regression, Decision Tree, Random Forest, and Light GBM—chosen for their relevance to classification tasks and their ability to capture different patterns in the data.
  
- **Evaluation**: The models were evaluated based on accuracy, precision, recall, F1 score, and ROC-AUC. Hyperparameter tuning was performed using RandomizedSearchCV to optimize performance.

## Results

After evaluating the models, Light GBM performed the best, especially when trained on an under-sampled dataset. Key features influencing attrition include transaction behavior and customer engagement metrics.

## Conclusion

The project demonstrates the effectiveness of machine learning in predicting credit card customer churn, with Light GBM emerging as the top performer. Future work could focus on further model optimization, the inclusion of more data, and exploring advanced ensembling methods.
