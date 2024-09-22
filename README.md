# MotorSense: Machine Learning for Predictive Motor Diagnostics

## Overview
MotorSense is a machine learning project aimed at diagnosing motor malfunctions using data from Kaggle. The goal is to use predictive models to identify motor issues before they result in breakdowns, reducing costly downtimes in industrial applications.

This project involves data preprocessing, model training using various machine learning algorithms (e.g., SVM, KNN, DNN, XGBoost), and performance evaluation.

## Project Structure
- **Data Source**: Kaggle dataset is used for training and evaluating the models.
- **Preprocessing**: Data preprocessing includes techniques like down sampling and FFT convolution.
- **Models**: Several machine learning models such as Support Vector Machine, K-Nearest Neighbors, Deep Neural Network, and XGBoost are used to classify motor conditions.
- **Evaluation**: Model performance is evaluated using metrics like accuracy, precision, recall, F1-score, and confusion matrix.

## Installation

### Prerequisites
Ensure that you have the following libraries installed:
- `kaggle`
- `pandas`
- `numpy`
- `scikit-learn`
- `tensorflow` (for DNN)
- `xgboost`

You can install the necessary packages using:
```bash
pip install kaggle pandas numpy scikit-learn tensorflow xgboost

