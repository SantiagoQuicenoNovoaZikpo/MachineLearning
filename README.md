# MachineLearning
This project uses Machine Learning to predict customer churn. Steps include normalizing data, creating dummy variables, splitting data into training and testing sets, scaling features, training models (Logistic Regression, Decision Tree, Random Forest, XGBoost), and optimizing hyperparameters to improve predictions.
# Churn Prediction with Machine Learning

This project applies Machine Learning techniques to predict customer churn. The dataset is preprocessed, normalized, and then used to train various models. Hyperparameter optimization is performed to improve model performance.

## Table of Contents

- [Introduction](#introduction)
- [Dataset](#dataset)
- [Preprocessing](#preprocessing)
- [Modeling](#modeling)
- [Results](#results)
- [Hyperparameter Optimization](#hyperparameter-optimization)
- [Conclusion](#conclusion)
- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

## Introduction

In this project, we utilize various Machine Learning algorithms to predict customer churn. The focus is on preprocessing the data, model training, and hyperparameter optimization to achieve the best possible performance.

## Dataset

The dataset used in this project contains customer information and their churn status. Key features include demographic details, transaction history, and customer engagement metrics.

## Preprocessing

The dataset is cleaned and preprocessed by:
- Handling missing values
- Encoding categorical variables
- Scaling numerical features

## Modeling

The following models were trained:
- Logistic Regression
- Decision Tree Classifier
- Random Forest Classifier
- XGBoost Classifier

Cross-validation was used to evaluate the performance of each model.

## Results

The models were evaluated using metrics such as AUC-ROC, precision, recall, and F1-score. Confusion matrices were generated to visualize the performance.

## Hyperparameter Optimization

Optuna was used to perform hyperparameter optimization on the Random Forest model, resulting in improved AUC-ROC scores.

## Conclusion

The optimized Random Forest model achieved the highest performance, with an AUC-ROC 

## Installation

To run this project, install the required dependencies:

```bash
pip install -r requirements.txt
