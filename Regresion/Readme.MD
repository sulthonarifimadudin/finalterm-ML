# UAS Machine Learning - Song Year Prediction Regression

## Student Information

- Name : Sulthon Arif Imadudin
- NIM : 1103223206

---

## Project Overview

This project implements an end-to-end deep learning regression pipeline to predict the release year of a song based on audio features.

The workflow includes data preprocessing, feature scaling, model training using Deep Learning, hyperparameter tuning with Optuna, experiment tracking using MLflow, and model interpretation using LIME.

---

## Dataset

Dataset: `midterm-regresi-dataset.csv`

Description:

- The first column represents the target variable (song release year).
- The remaining columns represent numerical audio features extracted from songs.
- The objective is to predict the release year based on the provided audio characteristics.

---

## Methodology

### 1. Data Preprocessing
- Data Loading
- Data Exploration (EDA)
- Missing Value Checking
- Outlier Analysis
- Feature Scaling using StandardScaler

### 2. Data Splitting
- Training Set (80%)
- Testing Set (20%)

### 3. Deep Learning Regression
- TensorFlow / Keras Sequential Model
- Dense Neural Network Architecture

### 4. Hyperparameter Tuning
- Optuna
- Optimization of hidden layer sizes

### 5. Experiment Tracking
- MLflow

### 6. Model Interpretation
- LIME (Local Interpretable Model-Agnostic Explanations)

---

## Evaluation Metrics

The model was evaluated using:

- Mean Squared Error (MSE)
- Root Mean Squared Error (RMSE)
- Mean Absolute Error (MAE)
- R-Squared (R²)

---

## Best Hyperparameters (Optuna)

```python
{
    "units1": 238,
    "units2": 43
}
```

Best RMSE:

```text
10.3539
```

---

## Repository Structure

```text
regression/
│
├── README.md
├── UAS_Regresi_ML.ipynb
└── requirements.txt
```

---

## Libraries Used

- Pandas
- NumPy
- Matplotlib
- Scikit-Learn
- TensorFlow
- Optuna
- MLflow
- LIME

---

## Conclusion

An end-to-end deep learning regression model was successfully developed to predict song release year from audio features.

The project covers data preprocessing, model development, hyperparameter tuning using Optuna, experiment tracking using MLflow, and model interpretation using LIME.

The resulting model demonstrates the ability of deep learning techniques to learn meaningful patterns from audio feature datasets and perform regression-based predictions.
