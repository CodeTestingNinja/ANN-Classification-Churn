# Customer Churn Prediction using ANN

This project involves building an Artificial Neural Network (ANN) model to predict customer churn based on structured data. The objective is to classify whether a customer is likely to leave a service or remain based on their historical activity and profile.

## 📌 Project Overview

- Built and trained an ANN model using Keras and TensorFlow.
- Preprocessed the dataset: handled missing values, encoded categorical variables, and normalized features.
- Achieved ~86% accuracy on test data.
- Evaluated using metrics such as confusion matrix, precision, recall, and F1-score.

## 📂 Dataset

The dataset includes various customer attributes such as:
- Demographics
- Account information
- Service usage patterns

> *Note: The dataset used is publicly available or simulated for academic purposes.*

## 🧠 Model Architecture

- Input Layer: Number of features after preprocessing
- Hidden Layers: Dense layers with ReLU activation
- Output Layer: Sigmoid activation for binary classification
- Loss Function: Binary Crossentropy
- Optimizer: Adam

## 📊 Evaluation Metrics

- Accuracy: ~86%
- Confusion Matrix
- Precision, Recall, F1-Score

## 🚀 How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/CodeTestingNinja/churn-ann.git
   cd churn-ann
