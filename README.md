# Customer Churn Prediction using Artificial Neural Network (ANN)

## Project Overview

This project predicts whether a bank customer will leave the bank (Churn) using an Artificial Neural Network (ANN). The model is built using TensorFlow and Keras after preprocessing the customer data.

---

## Problem Statement

Banks lose customers due to competition. Predicting customer churn helps the bank retain valuable customers by taking preventive actions.

---

## Dataset

Dataset: Churn_Modelling.csv

Features include:

- Credit Score
- Geography
- Gender
- Age
- Tenure
- Balance
- Number of Products
- Has Credit Card
- Is Active Member
- Estimated Salary

Target:

Exited
- 0 = Customer Stays
- 1 = Customer Leaves

---

## Technologies Used

- Python
- Pandas
- NumPy
- Scikit-Learn
- TensorFlow
- Keras
- Matplotlib

---

## Project Workflow

1. Import Libraries
2. Load Dataset
3. Data Cleaning
4. Feature Encoding
5. Feature Scaling
6. Train-Test Split
7. Build ANN Model
8. Train Model
9. Evaluate Model
10. Predict Customer Churn

---

## ANN Architecture

Input Layer

↓

Dense Layer (11 Neurons, ReLU)

↓

Dense Layer (8 Neurons, ReLU)

↓

Output Layer (1 Neuron, Sigmoid)

---

## Model Compilation

Optimizer:
Adam

Loss Function:
Binary Crossentropy

Evaluation Metric:
Accuracy

---

## Results

- Training Accuracy
- Validation Accuracy
- Confusion Matrix
- Classification Report

---

## Future Improvements

- Hyperparameter Tuning
- Dropout Regularization
- Batch Normalization
- Early Stopping
- Streamlit Deployment

---

## Author

Aditya Maurya
