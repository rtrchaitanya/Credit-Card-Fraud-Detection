# Credit Card Fraud Detection

## Overview
This repository contains a dataset of credit card transactions made by European cardholders in September 2013. The dataset is highly imbalanced, with only 492 fraud cases out of 284,807 transactions. Our goal is to develop a model to identify whether a new credit card transaction is fraudulent based on past data.

![Credit Card Fraud Detection]( https://storage.googleapis.com/kaggle-datasets-images/310/684/3503c6c827ca269cc00ffa66f2a9c207/dataset-cover.jpg)

## Dataset
- The dataset is available on Kaggle: [Credit Card Fraud Detection Dataset](https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud/data).
- It contains transactions that occurred over two days.
- Features V1 through V28 are principal components obtained through PCA transformation, while 'Time' and 'Amount' are the only non-transformed features.
- 'Time' represents the seconds elapsed between each transaction and the first transaction in the dataset.
- 'Amount' represents the transaction amount and can be used for cost-sensitive learning.
- 'Class' is the response variable, taking a value of 1 in case of fraud and 0 otherwise.

## Problem Statement
Develop a model to detect fraudulent credit card transactions based on historical data, with a focus on handling the imbalanced nature of the dataset.

## Workflow
1. **Data Collection**: Obtain the credit card transaction dataset.
2. **Data Visualization (EDA)**: Explore and visualize the data to gain insights.
3. **Data Preprocessing**:
   - **Data Cleaning**: Handle missing values and remove duplicates.
   - **Handling Outliers**: Identify and manage outliers in the data.
   - **Correlation Analysis**: Examine correlations between features.
4. **Splitting Data**: Separate the data into dependent and independent variables.
5. **Train-Test Split**: Split the data into training and testing sets.
6. **Model Training**:
   - Logistic Regression
   - Random Forest
   - K-Nearest Neighbors (KNN) Classifier
8. **Building Predictive Model / Model Testing**: Create and evaluate the predictive models to identify fraudulent transactions.

## Evaluation
Given the class imbalance, we recommend measuring the accuracy using the Area Under the Precision-Recall Curve (AUPRC). The confusion matrix accuracy is not meaningful for unbalanced classification.

Feel free to explore this repository and contribute to our efforts in credit card fraud detection. Together, we can make financial transactions safer for everyone.

Let's work together to combat credit card fraud! 🛡️🔍👀
