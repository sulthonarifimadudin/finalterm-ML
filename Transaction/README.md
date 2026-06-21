# UAS Machine Learning - Fraud Detection

## Student Information

- Name : Sulthon Arif Imadudin
- NIM : 1103223206

---

## Project Overview

This project develops an end-to-end machine learning and deep learning pipeline for fraud detection using online transaction data.

The objective is to predict whether a transaction is fraudulent (`isFraud`) or legitimate based on transaction-related features.

The project includes data preprocessing, missing value handling, feature encoding, model training, hyperparameter tuning using Optuna, experiment tracking using MLflow, and model evaluation.

---

## Dataset

Dataset: `train_transaction.csv`

### Description

The dataset contains online transaction records where:

- `isFraud = 1` → Fraudulent transaction
- `isFraud = 0` → Legitimate transaction

Each transaction contains multiple numerical and categorical features related to transaction information.

---

## Methodology

### 1. Data Preprocessing
- Data Loading
- Missing Value Analysis
- Feature Selection
- Missing Value Imputation
- Categorical Encoding
- Feature Scaling

### 2. Data Splitting
- Train Set (80%)
- Test Set (20%)

### 3. Fraud Detection Modeling
- Deep Learning Neural Network (TensorFlow/Keras)

### 4. Hyperparameter Tuning
- Optuna

### 5. Experiment Tracking
- MLflow

---

## Evaluation Metrics

The model performance was evaluated using:

- Accuracy
- Precision
- Recall
- F1-Score
- ROC-AUC Score

---

## Libraries Used

- Pandas
- NumPy
- Matplotlib
- Scikit-Learn
- TensorFlow
- Optuna
- MLflow

---

## Repository Structure

```text
transaction/
│
├── README.md
├── UAS_Transaction_ML.ipynb
└── requirements.txt
```

---

## Conclusion

An end-to-end fraud detection pipeline was successfully developed using transaction data. The workflow included preprocessing, feature engineering, model training, hyperparameter optimization with Optuna, and experiment tracking using MLflow. The resulting model can classify fraudulent and non-fraudulent transactions based on historical transaction patterns.
