# Project III – Time Series Forecasting 📈⏱️

This repository contains the work for **Project III** of the Data Science Master’s program at Nuclio Digital School. The focus of this project is on **time series forecasting** using the AFS dataset, aiming to deliver competitive predictions in a Kaggle environment.

## 🎯 Objective

The goal of this project is to:
- Develop a **robust time series forecasting model** to predict the target variable for the AFS dataset.
- Apply advanced feature engineering and model ensembling techniques to optimize predictive performance.
- Compete in the Kaggle competition and extract actionable insights from model behavior.

## 📂 Dataset

- **Name:** Time series data (`ts_kaggle_sales_test_mean.csv`, `ts_kaggle_test.csv`)
- **Origin:** Public Kaggle competition dataset
- **Entries:** 14.484 entries
- **Format:** CSV (time-indexed tabular data)

## ⚙️ Project Scope

All steps were implemented within a single Jupyter Notebook:

- **Exploratory Data Analysis (EDA):**
  - Time series decomposition and visualization of trends, seasonality, and residuals
  - Stationarity tests and autocorrelation analysis
- **Feature Engineering:**
  - Creation of lag features and rolling statistics
  - Extraction of date/time components (e.g., hour, day, month)
  - Handling missing values and detecting outliers
- **Model Development:**
  - Training multiple forecasting models (e.g., ARIMA, Prophet, XGBoost Regressor)
  - Hyperparameter tuning using rolling-window cross-validation
- **Ensembling & Finalization:**
  - Weighted averaging of top-performing models
  - Post-processing and smoothing of predictions
  - Preparation of the submission file

## 📊 Results Summary

- **Kaggle Competition Rank:** 3rd place  
- **Final Score:** 2.73 (lower is better)  
- **Key Takeaways:**
  - Lagged rolling statistics significantly improved short-term forecast accuracy
  - Ensemble methods reduced overall error by approximately 10% compared to individual models
  - Feature importance analysis highlighted **[insert top features]** as critical predictors

## 📄 Repository Contents

- `TimeSeries_AFS.ipynb`  
  Jupyter Notebook containing the complete workflow: EDA, feature engineering, model training, and ensembling.


## 🚀 How to Run

1. Install dependencies:  
   ```bash
      pip install pandas numpy matplotlib statsmodels prophet xgboost


2. Launch the noteboosk:
   
TimeSeries_AFS.ipynb

This project is part of the Data Science Master’s program at Nuclio Digital School and demonstrates competitive time series forecasting skills.

