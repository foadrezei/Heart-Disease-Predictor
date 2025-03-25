# Heart Disease Predictor

## Overview
This project uses machine learning to predict the presence of heart disease based on patient health data. It implements two models—Logistic Regression and Decision Tree—trained on the UCI Heart Disease dataset. The code includes data preprocessing, exploratory data analysis (EDA), model training, cross-validation, and feature importance analysis, making it a practical example of healthcare analytics.

## Features
- Data Preprocessing: Handles missing values with imputation (medians for numeric, modes for categorical) and encodes categorical variables.
- EDA: Visualizes correlations and target distribution using heatmaps and count plots.
- Models: 
  - Logistic Regression (tuned with regularization)
  - Decision Tree (tuned with max depth)
- Evaluation: Reports accuracy, precision, recall, and confusion matrices, with 5-fold cross-validation.
- Feature Importance: Identifies key predictors using Decision Tree.

## Dataset
The project uses the [UCI Heart Disease dataset](https://www.kaggle.com/datasets/redwankarimsony/heart-disease-data) (heart_disease_uci.csv), which includes features like age, cholesterol, blood pressure, and more. Note: Features ca and thal are excluded due to excessive missing values.

## Requirements
- Python 3.x
- Libraries: pandas, numpy, matplotlib, seaborn, scikit-learn
Install dependencies with:
```bash
pip install pandas numpy matplotlib seaborn scikit-learn  
