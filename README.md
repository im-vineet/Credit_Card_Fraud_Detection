# Credit Card Fraud Detection

This repository contains a simple implementation of a Credit Card Fraud Detection model using logistic regression. The model is built using Python and popular data science libraries such as NumPy, pandas, and scikit-learn.

**Overview**

Credit card fraud detection is an essential application in the financial sector to prevent unauthorized transactions. The dataset used in this project contains transactions labeled as fraudulent or legitimate, and the model aims to classify transactions into these two categories.

**Dataset**

The dataset used in this project is creditcard.csv, which contains a mix of legitimate and fraudulent transactions.
The dataset includes various features that describe each transaction.

**Project Structure**

creditcard.csv: The dataset containing credit card transactions.
fraud_detection.py: The Python script containing the model implementation.

**Code Explanation**
The code follows these steps:

**Data Loading:** The dataset is loaded using pandas.
**Data Exploration:** Displays basic information about the dataset.

**Data Preprocessing:**

Separate the dataset into legitimate (Class = 0) and fraudulent (Class = 1) transactions.
Create a balanced dataset by sampling an equal number of legitimate transactions as the fraudulent ones.
Define feature set X and target variable Y.

**Model Training:**

Split the dataset into training and testing sets.
Train a logistic regression model using the training data.
Model Evaluation:
Evaluate the model using accuracy scores on both training and test datasets.

**Usage**

To run the project, simply execute the Python script:

**Results**

Training Data Accuracy: Indicates how well the model performs on the training dataset.
Test Data Accuracy: Indicates how well the model generalizes to unseen data.

**License**

This project is licensed under the MIT License. Feel free to use, modify, and distribute this code.

**Acknowledgments**

The dataset is sourced from Kaggle, a popular platform for data science and machine learning competitions.
