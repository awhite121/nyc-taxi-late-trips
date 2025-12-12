# NYC Taxi Trip Analysis & Modeling

This repository contains our groups exploratory data analysis (EDA), regression modeling, classification modeling and analysis for NYC taxi trip data.  
The goal of the project is to understand trip patterns, build predictive models, and evaluate key factors that influence trip outcomes.

## Contents

### 1. Exploratory Data Analysis
- Trip volumes by hour, day, and location
- Distributions of distance, duration, and fare
- Outlier detection and cleaning steps
- Correlation analysis and variable relationships

### 2. Regression Modeling
- Baseline linear model
- Feature selection and transformations
- XGBoost, AdaBoost, Random Forest models
- Evaluation metrics (RMSE, MAE, R²)
- Interpretation of coefficients and model fit

### 4. Classification Modeling
- Late label definition (duration > 1.2 × typical median for similar trips)
- Handling class imbalance and choice of late class metrics
- Logistic Regression and Random Forest classifiers
- CatBoost classifier with class weighting and probability threshold tuning
- Evaluation metrics (precision, recall, F1, ROC AUC, PR AUC) and model comparison

### 5. Airport Taxi Timing Advisor
- Example workflow for scoring new trips and estimating late trip risk
- Threshold choices for different user views (traveler vs operations)
- Plots and figures used in the blog report
