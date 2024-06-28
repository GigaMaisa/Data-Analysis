# Airline Customer Satisfaction Analysis

This project involves analyzing airline customer satisfaction data to predict satisfaction levels using various machine learning models. The steps include data preprocessing, feature scaling, and the application of both regression and classification models. The performance of these models is evaluated using appropriate metrics.

## Table of Contents

1. [Introduction](#introduction)
2. [Data Preprocessing](#data-preprocessing)
3. [Feature Scaling](#feature-scaling)
4. [Model Training and Evaluation](#model-training-and-evaluation)
    - [Linear Regression](#linear-regression)
    - [Decision Tree Regressor](#decision-tree-regressor)
    - [Logistic Regression](#logistic-regression)
    - [Decision Tree Classifier](#decision-tree-classifier)
5. [Conclusion](#conclusion)

## Introduction

This project aims to analyze and predict airline customer satisfaction using a dataset containing various features related to customer demographics, flight details, and customer feedback. The primary goal is to predict whether a customer is satisfied or dissatisfied with their airline experience.

## Data Preprocessing

The dataset is loaded and examined for missing values, duplicated entries, and data types. Missing values in the "Arrival Delay in Minutes" column are filled with the median value. Duplicates are checked and the data types of each column are verified. The "satisfaction" column is converted to numerical values where 'dissatisfied' is mapped to 0 and 'satisfied' is mapped to 1. Categorical columns like "Customer Type," "Type of Travel," and "Class" are converted to dummy variables.

## Feature Scaling

Numerical features such as "Age," "Flight Distance," "Departure Delay in Minutes," and "Arrival Delay in Minutes" are scaled using the `StandardScaler` to standardize the data.

## Model Training and Evaluation

### Linear Regression

A Linear Regression model is trained using both single and multiple features to predict customer satisfaction. The performance of the model is evaluated using Mean Squared Error (MSE) and R-squared (R2) score.

### Decision Tree Regressor

A Decision Tree Regressor model is also trained on the dataset. Its performance is assessed using the Mean Squared Error (MSE) and R-squared (R2) score to determine how well it predicts customer satisfaction.

### Logistic Regression

A Logistic Regression model is employed to classify customer satisfaction as either satisfied or dissatisfied. The model's performance is measured using accuracy, precision, recall, and F1 score.

### Decision Tree Classifier

A Decision Tree Classifier is used for classification purposes. Similar to the Logistic Regression model, its performance is evaluated using accuracy, precision, recall, and F1 score.

## Conclusion

This project demonstrates the application of different machine learning models to predict airline customer satisfaction. Each model is evaluated based on relevant performance metrics, providing insights into their effectiveness for this task. The analysis and results can help in understanding the key factors influencing customer satisfaction and improving the overall customer experience.
