# Machine Learning-Based Stroke Prediction

This repository contains the Python notebooks used for the Extended Research project:

**Machine Learning-Based Stroke Prediction: Evaluating an Effective Combination of Data Preprocessing Techniques and Classification Models**

## Project Description

This project evaluates how data preprocessing techniques and classification models can be combined effectively for machine learning-based stroke prediction. The analysis includes exploratory data analysis, missing-value handling, outlier analysis, feature preprocessing, model training and model comparison.

## Dataset

This project uses the Kaggle Stroke Prediction Dataset by Fedesoriano.

Dataset source: https://www.kaggle.com/datasets/fedesoriano/stroke-prediction-dataset

The original CSV file is not included in this repository. Users can download the dataset directly from Kaggle using the link above.

## Files

- `01_EDA.ipynb`: Exploratory data analysis
- `02_MissingValues.ipynb`: Missing-value handling
- `03_Outliers.ipynb`: Outlier analysis
- `04_Preprocessing.ipynb`: Feature preprocessing
- `05_Models.ipynb`: Model training
- `06_Comparison.ipynb`: Final model comparison

## Models

The project compares three classification models:

- Logistic Regression
- Random Forest
- XGBoost

## Final Pipeline

The final recommended pipeline used median BMI imputation, retained clinically plausible outliers, applied one-hot encoding, used model-dependent scaling, applied stratified train/test splitting and selected XGBoost as the final model.