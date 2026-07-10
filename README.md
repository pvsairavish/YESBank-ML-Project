# YESBank-ML-Project
Regression models (Linear, Random Forest, Gradient Boosting) to predict Yes Bank monthly Closing Price. Achieved R² Score of 0.979 with hyperparameter tuning and model deployment readiness.
# Yes Bank Stock Closing Price Prediction - Machine Learning

## 📋 Project Overview
This repository contains the **Machine Learning** part of the Yes Bank Stock Price project. The goal is to predict the monthly **Closing Price** using Open, High, and Low prices.

## 🎯 Objective
Build accurate regression models to forecast Yes Bank’s Closing Price and provide deployment-ready solution for investors and analysts.

## 📊 Models Implemented
1. **Linear Regression**
2. **Random Forest Regressor**
3. **Gradient Boosting Regressor** ← **Best Model**

## 📈 Model Performance
- **Best Model**: Gradient Boosting Regressor
- **R² Score**: ~0.979
- **RMSE**: ~13.82

## 🔧 Methodology
- Feature Engineering (Year, Month, HL_Pct, OC_Pct)
- Outlier Handling using Capping
- Data Scaling (StandardScaler)
- Train-Test Split (80:20)
- Hyperparameter Tuning using GridSearchCV
- Model Saving using Joblib

## 🛠️ Tech Stack
- Python, Scikit-learn
- Pandas, NumPy
- Joblib (Model Deployment)

## 📁 Files
- `Yes_Bank_ML_Model.ipynb` → Main ML Notebook
- `yes_bank_stock_predictor.joblib` → Trained Model
- `data_YesBank_StockPrices.csv`

## 🚀 Deployment Ready
The final model is saved and can be loaded for real-time predictions.

## 📈 Business Impact
- Helps investors predict future stock prices
- Supports risk management during volatile periods
- Enables data-driven trading decisions

---

**Linked Project**: [Yes Bank EDA Repository](https://github.com/yourusername/Yes-Bank-EDA)
