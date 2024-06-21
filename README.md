# Device Failures Prediction

## Introduction
This project aims to develop a predictive model to forecast device failures by analyzing historical data on past failures and various device attributes to identify patterns and relationships that signal an increased risk of future breakdowns.

## Libraries
- Pandas
- NumPy
- Scikit-learn
- TensorFlow
- Keras
- Matplotlib
- Seaborn

## Data Import
The dataset containing historical data on device failures is imported.

## Preprocessing
Data preprocessing steps include scaling and encoding.

## EDA
Exploratory data analysis is conducted to understand the dataset, including checking the class imbalance and inspecting class-wise statistics.

## Dimensionality Reduction
PCA is used for dimensionality reduction to visualize relationships between attributes.

## Baseline Models
- Naive-Model: Always predicts 0
- Distance from mean of classes: Uses the mean vectors of the two classes to classify data points
- Logistic Regression: A traditional approach to binary classification
- Gaussian Naive-Bayes: Assumes that features are conditionally independent
- BalancedRandomForestClassifier: A tree-based ensemble method that handles class imbalance by adjusting class weights

## Conclusion
This README provides an overview of the project, outlining the steps involved in developing a predictive model for device failures. Further details can be found in the project files.
