# UAS Machine Learning

## Student Information

- Name : Sulthon Arif Imadudin
- NIM : 1103223206
- Program : S1 Teknik Komputer
- University : Telkom University

---

## Repository Overview

This repository contains the implementation of end-to-end Machine Learning and Deep Learning projects for the Final Term Assignment (UAS Machine Learning).

The projects cover both classification and regression tasks, including data preprocessing, model development, hyperparameter tuning, experiment tracking, and model interpretation.

---

## Projects

### 1. Fraud Detection (Classification)

Folder: `transaction/`

Objective:

Predict whether an online transaction is fraudulent (`isFraud = 1`) or legitimate (`isFraud = 0`) using transaction data.

Main Components:

- Data Preprocessing
- Missing Value Handling
- Feature Engineering
- Deep Learning Classification
- Hyperparameter Tuning (Optuna)
- MLflow Experiment Tracking
- Model Evaluation

Evaluation Metrics:

- Accuracy
- Precision
- Recall
- F1-Score
- ROC-AUC

---

### 2. Song Year Prediction (Regression)

Folder: `regression/`

Objective:

Predict the release year of a song based on audio features using Deep Learning Regression.

Main Components:

- Data Preprocessing
- Feature Scaling
- Deep Learning Regression
- Hyperparameter Tuning (Optuna)
- MLflow Experiment Tracking
- LIME Model Interpretation

Evaluation Metrics:

- MSE
- RMSE
- MAE
- R² Score

---

## Repository Structure

```text
Midterm_ML/
│
├── README.md
│
├── transaction/
│   ├── README.md
│   ├── UAS_Transaction_ML.ipynb
│   └── requirements.txt
│
└── regression/
    ├── README.md
    ├── UAS_Regresi_ML.ipynb
    └── requirements.txt
