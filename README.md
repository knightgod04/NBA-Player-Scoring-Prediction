# NBA Player Scoring Prediction Using Machine Learning

## Overview

This project focuses on predicting NBA player scoring performance using historical game-level statistics. Statistical modelling and machine learning techniques were applied to analyse player performance patterns and estimate future points scored.

## Objectives

- Analyse NBA player performance data
- Engineer features representing player form and consistency
- Develop regression models for scoring prediction
- Identify important factors influencing scoring performance

## Dataset

The dataset was collected using the NBA API through the Python package nba_api.

The dataset contains player game-level statistics including:

- Points scored
- Minutes played
- Field goal attempts
- Rebounds
- Assists
- Recent game averages
- Season average scoring performance

## Methodology

The project workflow:

1. Data Collection using NBA API
2. Data Cleaning and Preprocessing
3. Feature Engineering
4. Exploratory Analysis
5. Predictive Modelling
6. Model Evaluation

## Models Used

### Multiple Linear Regression

Used as a baseline statistical model to analyse relationships between player statistics and scoring output.

### Random Forest Regression

Used to capture possible non-linear relationships and identify feature importance.

## Results

Linear Regression Performance:

- MAE: 4.98
- RMSE: 6.43
- R² Score: 0.517

Random Forest Performance:

- MAE: 5.09
- RMSE: 6.57
- R² Score: 0.495

## Technologies Used

- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- NBA API

## Author

Anubhav Roy
