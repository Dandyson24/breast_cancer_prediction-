# Breast Cancer Prediction

## Overview
This project focuses on predicting breast cancer malignancy (benign vs. malignant) using machine learning. The goal was to evaluate multiple models and identify the best-performing algorithm for accurate predictions. 

## Dataset
- **Source:** Kaggle  
- **Features:** 30 numeric features describing tumor characteristics  
- **Target Variable:** `benign` or `malignant`

## Models Implemented
- Ridge Regression
- Lasso Regression
- Logistic Regression
- Decision Tree Classifier
- K-Nearest Neighbors (KNN)
- Random Forest Classifier
- Support Vector Machine (SVM)
- XGBoost

## Key Features
The top 5 features contributing to model performance:
1. `num__radius_se` – 2.052295  
2. `num__texture_worst` – 1.789196  
3. `num__radius_worst` – 1.737701  
4. `num__area_worst` – 1.644090  
5. `num__concave points_mean` – 1.317916  

## Model Performance
| Model        | ROC-AUC   | RMSE     |
|-------------|-----------|----------|
| Ridge       | 0.997685  | NaN      |
| Logistic    | 0.997024  | 0.145733 |
| Lasso       | 0.996693  | 0.148629 |
| SVM         | 0.996032  | 0.135370 |
| XGBoost     | 0.994048  | 0.142386 |
| Random Forest | 0.993056 | 0.184116 |
| KNN         | 0.985450  | 0.170654 |
| Decision Tree | 0.924603 | 0.264906 |

**Observation:** Lasso Regression and Ridge Regression performed exceptionally well, achieving ROC-AUC scores above 0.996, indicating excellent predictive capability.

## Core Competencies Gained
- Data preprocessing: handling missing values, encoding, and scaling  
- Feature selection and engineering  
- Model building, hyperparameter tuning, and evaluation  
- Pipeline automation for reproducible ML workflows  
- Interpretation of model outputs and feature importance  

