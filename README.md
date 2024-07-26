# Call of Duty Betting Predictor

This project is designed to predict Call of Duty Over/Under kill props. The notebook utilizes historical game data and various statistical methods to generate accurate predictions.

### Table of Contents

1. Introduction
2. Setup and Installation
3. Data Collection and Preprocessing
4. Exploratory Data Analysis
5. Modeling
6. Evaluation

### Introduction

This project aims to leverage machine learning techniques to predict the performance of players in Call of Duty, specifically for PrizePicks props. The notebook includes data collection, preprocessing, exploratory data analysis (EDA), model training, and evaluation.

### Setup and Installation

To run this notebook, you need to have Python installed along with the following packages:
- !pip install pandas numpy matplotlib seaborn scikit-learn xgboost

### Data Collection and Preprocessing

The data used in this project includes historical game statistics for Call of Duty Black Ops players. The data preprocessing steps include:

- Loading the dataset
- Handling missing values
- Feature engineering
- Data normalization and scaling

### Exploratory Data Analysis

EDA is performed to understand the distribution and relationships in the data. This includes:

- Summary statistics
- Visualizations (histograms, box plots, correlation heatmaps)
- Insights from the data

### Modeling

The notebook includes multiple machine learning models to predict player performance, such as:

- Linear Regression
- Random Forest
- XGBoost
  
The models are trained on the preprocessed data and their performance is evaluated using appropriate metrics.

### Evaluation

The models are evaluated based on:

- Mean Squared Error (MSE)
- R-squared (R²)
- Mean Absolute Error (MAE)
  
The notebook compares the performance of different models and selects the best one based on these metrics.
