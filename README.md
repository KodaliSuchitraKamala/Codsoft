# 🧠 Codsoft – Data Science Internship Projects

[![Python](https://img.shields.io/badge/python-3.8%2B-blue)]()
[![Libraries](https://img.shields.io/badge/libraries-pandas%2C%20scikit--learn%2C%20matplotlib%2C%20seaborn-green)]()
[![License: MIT](https://img.shields.io/badge/license-MIT-yellow.svg)]()

## 🚀 Overview

Welcome to **Codsoft**, a collection of data science projects completed during my internship. These projects showcase practical applications of machine learning—from classification to regression and anomaly detection. Each task includes:

- 📁 A Jupyter Notebook (`.ipynb`) detailing the analysis, code, and visualization  
- 📄 A PDF report summarizing methods, results, and insights  

---

## 📚 Projects

### 1. Titanic Survival Prediction
- **Goal:** Predict survival on the Titanic using passenger data.
- **Techniques:** Exploratory Data Analysis, feature engineering, Logistic Regression, Random Forest.
- **Notebook:** `CODSOFT_task_1_Titanic_Survival_Predictions.ipynb`
- **PDF:** `CODSOFT_task_1_Titanic_Survival_Predictions.pdf`

### 2. Movie Rating Prediction
- **Goal:** Estimate IMDb ratings of Indian movies.
- **Techniques:** Data cleansing, feature extraction (genre, cast), Regression models (Linear, Ridge, XGBoost).
- **Notebook:** `CODSOFT_task_2_Movies_IMDb_Rating_Prediction.ipynb`
- **PDF:** `CODSOFT_task_2_Indian_Movies_IMDb_Rating_Predictions.pdf`

### 3. Iris Flower Classification
- **Goal:** Classify Iris species based on flower measurements.
- **Techniques:** EDA, Model comparison: K‑NN, Decision Tree, SVM, metrics: accuracy, confusion matrix.
- **Notebook:** `CODSOFT_task_3_Classification_of_IRIS_flower.ipynb`
- **PDF:** `CODSOFT_task_3_Classification_of_IRIS_flower.pdf`

### 4. Sales Prediction with Advertising
- **Goal:** Forecast sales based on advertising spend.
- **Techniques:** Simple Linear Regression, diagnostics, evaluation (R², RMSE), visualization.
- **Notebook:** `CODSOFT_task_4_Sales_Predictions_by_Advertising_Costs.ipynb`
- **PDF:** `CODSOFT_task_4_Sales_Predictions_by_Advertising_Costs.pdf`

### 5. Credit Card Fraud Detection
- **Goal:** Identify fraudulent transactions.
- **Techniques:** Class imbalance handling (SMOTE), model: Random Forest or Logistic Regression, evaluation using precision, recall, F1‑score, ROC‑AUC.
- **Notebook:** `CODSOFT_task_5_Credit_Card_Fraud_Detection.ipynb`
- **PDF:** `CODSOFT_task_5_Credit_Card_Fraud_Detection.pdf`

---

## 🛠️ Installation & Setup

To run these notebooks locally:

```bash
git clone https://github.com/KodaliSuchitraKamala/Codsoft.git
cd Codsoft
python3 -m venv venv
source venv/bin/activate       # MacOS/Linux
venv\Scripts\activate.bat      # Windows
pip install -r requirements.txt
jupyter notebook
