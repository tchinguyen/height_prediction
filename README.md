# Growing Beyond Genes: Predicting Adolescent Height with XGBoost

## Overview

This project investigates adolescent height prediction using machine learning, specifically XGBoost, on a two-generation dataset. The study explores the relationship between early childhood growth patterns, parental characteristics, and adolescent height. The model achieves high predictive accuracy, explaining 96% of the variance in height predictions.

## Authors

Vani Singh\
Ajay Kallepalli\
Thi Nguyen

## Project Structure

final_report.pdf – Detailed analysis, methodology, and results\
data/ – Processed datasets (not included in the repository)\
scripts/ – Python scripts for data preprocessing, feature engineering, and model training\

## Key Components

### 1. Exploratory Data Analysis (EDA)
Summary statistics \
Distribution analysis of target variables\
Correlation analysis between parent and child heights\

### 2. Feature Engineering
Extraction of growth-related features (height differences, growth velocity, BMI, etc.)\
Parent-child feature relationships\
Handling of missing values using MICE imputation\

### 3. Model Training & Evaluation
Data preprocessing and group-aware train-validation split\
Hyperparameter tuning for XGBoost using grid search\
Model performance evaluation using RMSE, MAE, and R²

### 4. Heredity Analysis
Influence of parental height on child’s final height\
Analysis of pubertal growth patterns\
Impact of sex-based differences on growth trajectories

## Model Performance:
RMSE: 2.57 cm\
MAE: 1.96 cm\
R²: 0.96

## Key Findings:
Parental height is a strong predictor of child height.\
Growth velocity and age-related features are highly influential.\
Sex-based differences significantly impact growth timing and magnitude.
