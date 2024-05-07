# Cleveland Heart Disease Prediction
Heart disease prediction using MLP classifiers on the Cleveland dataset; includes data preprocessing, model training, and performance evaluation.

## Overview
This repository hosts the implementation of various Multi-Layer Perceptron (MLP) classifier configurations for predicting heart disease using the Cleveland dataset. The project emphasizes effective data preprocessing, diverse MLP model training, and comprehensive performance evaluation.

## Dataset
The Cleveland dataset utilized in this project contains medical and demographic information useful for predicting the presence of heart disease. Key preprocessing steps include:
- Removing rows with missing values.
- Transforming the 'num' column into a binary target feature.
- Standardizing all numerical features to ensure uniform influence on model performance.

## Model Training and Evaluation
Several MLP models with different configurations of hidden layers and activation functions (logistic and relu) are trained on the dataset. Each model is evaluated based on the following metrics:
- Accuracy
- Precision
- Recall
- F1 Score

These metrics help determine the most effective model in predicting heart disease.

## Results
The results section of the code provides a detailed comparison of each model's performance. The best-performing model is highlighted based on its accuracy, facilitating insights into the optimal neural network configuration for this specific health dataset.

For more details on the implementation and results, the code within this repository can be referred to, providing a comprehensive guide to each step of the model development and evaluation process.
