# Credit Card Fraud Detection

This project focuses on building a machine learning model to detect fraudulent credit card transactions. Given the highly imbalanced nature of credit card fraud datasets, this project employs techniques such as under-sampling to handle class imbalance and uses logistic regression to classify transactions.

## Overview

Credit card fraud detection is a critical task in financial systems to prevent monetary losses and ensure secure transactions. This project uses logistic regression to detect fraudulent transactions, balancing the dataset by selecting a subset of normal transactions and all fraudulent ones. The model is evaluated on accuracy for both training and testing data.

## Project Goals
The main aim of this project is the detection of fraudulent credit card transactions, as it is essential to figure out the fraudulent transactions so that customers do not get charged for the purchase of products that they did not buy. Fraudulent Credit card transactions will be detected with multiple ML techniques. Then, a comparison will be made between the outcomes and results of each method to find the best and most suited model for detecting fraudulent credit card transactions; graphs and numbers will also be provided. In addition, it explores previous literature and different techniques used to distinguish Fraud within a dataset

## Dataset

The dataset, [credit_card](https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud), consists of anonymized credit card transaction data, which includes:
- **Time**: Time of transaction
- **Amount**: Transaction amount
- **Class**: Target variable, where `0` indicates a normal transaction, and `1` indicates a fraudulent transaction

This dataset is highly imbalanced, with fraudulent transactions being a small fraction of total transactions.


## Steps in the Project

1. **Data Loading and Exploration**: Load the dataset, view basic info, check for missing values, and analyze the distribution of transactions (normal vs. fraud).
2. **Data Preparation**:
    - Separate the dataset into normal and fraudulent transactions.
    - Perform statistical analysis on transaction amounts for both classes.
3. **Under-sampling**:
    - Create a balanced dataset by taking a random sample of normal transactions to match the count of fraudulent transactions.
4. **Feature and Target Separation**: Split the data into features (X) and target (Y) variables.
5. **Data Splitting**: Divide the dataset into training and testing sets, with stratification based on the target variable to maintain class balance.
6. **Model Training**: Train a Logistic Regression model on the training data.
7. **Model Evaluation**: Calculate accuracy on both training and testing data to evaluate model performance.

## Results

The model's accuracy is measured on both the training and testing sets. The output provides the following accuracy scores:

- **Training Accuracy**: Evaluates how well the model fits the training data.
- **Testing Accuracy**: Indicates the model's generalization to unseen data.




