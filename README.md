# IBM-Hotel-booking-demand-prediction-project
Machine learning project for predicting daily hotel booking demand using historical booking data and time-based features.
## Project Overview

This project focuses on predicting daily hotel booking demand using historical hotel booking data and machine learning techniques.

The project follows a complete machine learning workflow including data preprocessing, exploratory data analysis, feature engineering, model training, evaluation, model comparison, and prediction on new/unseen input.

## Problem Statement

Hotels need reliable estimates of booking demand for better operational planning.

Daily booking demand can vary based on time-related patterns and recent booking history. This project uses historical booking data and engineered temporal features to predict daily hotel booking demand.

## Objective

The main objectives of this project are:

- Predict daily hotel booking demand.
- Analyze historical demand patterns.
- Create time-based and lag features.
- Train and compare multiple regression models.
- Evaluate model performance using MAE, RMSE and R².
- Demonstrate prediction using new/unseen input.

## Dataset

### Dataset Description

The project uses historical hotel booking data that was processed and aggregated into daily demand records.

- Prepared observations: **793 daily observations**
- Target variable: **demand**
- Target meaning: Daily hotel booking demand

### Important Features

- day_of_week
- month
- year
- week_of_year
- is_weekend
- lag_1
- lag_7
- rolling_7

## Technologies Used

- Python
- Jupyter Notebook
- Pandas
- NumPy
- Matplotlib
- Scikit-learn
- StandardScaler
- Random Forest
- Gradient Boosting
- Artificial Neural Network

## Project Workflow

      
Historical Booking Data
        ↓
Data Cleaning & Preprocessing
        ↓
Daily Demand Aggregation
        ↓
Exploratory Data Analysis
        ↓
Feature Engineering
        ↓
Time-Based Train/Test Split
        ↓
Model Training
        ↓
Model Evaluation
        ↓
Model Comparison
        ↓
Final Model Selection
        ↓
New/Unseen Input Prediction
