# 🏥 Medical Insurance Premium Prediction

This project builds and compares multiple machine learning models to predict medical insurance costs based on individuals information. It includes exploratory data analysis (EDA), feature engineering, model evaluation using cross-validation, and experiment tracking using MLflow.

---

## 📊 Project Overview

The main goal is to predict insurance premium charges using patient demographic and lifestyle features. The workflow includes:

- ✅ Exploratory Data Analysis (EDA)
- ✅ Baseline model creation (using MAE)
- ✅ Feature engineering (including polynomial features)
- ✅ Model selection: Ridge, SVR, Random Forest, and XGBoost
- ✅ Hyperparameter tuning using `RandomizedSearchCV`
- ✅ ML Pipelines for preprocessing + modeling
- ✅ Model comparison and tracking with MLflow
- ✅ Saving the best model for deployment

---


## 🧪 Models Trained

| Model          | Notes                          |
|----------------|--------------------------------|
| Ridge Regression | Regularized linear model |
| Support Vector Regressor (SVR) | Non-linear regression |
| XGBoost Regressor | Gradient boosting |
| Random Forest Regressor | Ensemble of decision trees |

Each model was:
- Tuned using `RandomizedSearchCV`
- Wrapped in a pipeline with preprocessing
- Evaluated using cross-validation
- Logged and tracked with **MLflow**

---

---

## 🛠️ Tech Stack

- Python
- Pandas, NumPy, Matplotlib, Seaborn
- Scikit-learn
- XGBoost
- MLflow

---

## 📈 Model Evaluation Metrics

Tracked via MLflow:
- Mean Absolute Error (MAE)
- Root Mean Squared Error (RMSE)
- R² Score
- Best hyperparameters
- Preprocessing pipeline steps

---