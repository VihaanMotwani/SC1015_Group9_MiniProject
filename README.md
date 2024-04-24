# SC1015 FCSB GROUP 9 MINI PROJECT

# Car Price Prediction Analysis

## Overview
This repository contains all the necessary code and datasets used in the SC1015 mini project conducted by Group 9. This project focuses on predicting car prices using various machine learning models. The analysis is performed in a Jupyter Notebook which allows for a detailed step-by-step exploration of data preprocessing, feature engineering, model building, and evaluation. 

## Problem Statement 
The objective is to construct a robust predictive model that estimates the selling price of used cars. This model will consider various car attributes such as the year of make (age), kilometers driven, fuel type, transmission type, and detailed ownership history (first owner, second owner, etc.). The aim is to leverage machine learning algorithms that can accurately predict prices based on these attributes, helping buyers and sellers achieve fair market value transactions.

## Dataset
The dataset used in this project, titled `Car details v3.csv`, includes multiple features such as car name, year, mileage, engine, max_power, and selling price. This data is vital for building regression models to estimate car prices based on their characteristics.

## Methodology
The project follows these key steps:
- **Data Cleaning and Preprocessing:** Handling missing values, converting data types, and normalizing text data.
- **Feature Engineering:** Deriving new features to improve model performance such as calculating the age of the cars.
- **Model Development:** Several regression models were trained and evaluated:
  - **Linear Regression**
  - **Elastic Net Regression**
  - **Random Forest Regressor**
  - **Gradient Boosting Regressor**
  - **XGBoost Regressor**
- **Evaluation:** Models were assessed based on Mean Absolute Error, Mean Squared Error, Root Mean Squared Error, and R-squared values.

## Results
The models displayed varying degrees of accuracy, with ensemble methods like Random Forest and Gradient Boosting generally performing better in terms of lower error metrics and higher R-squared values. The detailed analysis of each model provides insights into the suitability of each regression technique based on the dataset's characteristics.

## Contributions
- **Vihaan Motwani
- **Riddham Agarwal
- **Aaditya Gunda
- Everyone contributed equally.

## References
- Python documentation: https://www.python.org/doc/
- Scikit-learn library: https://scikit-learn.org
- XGBoost official documentation: https://xgboost.readthedocs.io
- Pandas documentation: https://pandas.pydata.org/pandas-docs/stable/
- Matplotlib documentation: https://matplotlib.org/
- Seaborn documentation: https://seaborn.pydata.org/
