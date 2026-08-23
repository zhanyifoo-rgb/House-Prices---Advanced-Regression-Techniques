# House Prices – Advanced Regression Techniques

A machine learning project based on Kaggle's **House Prices: Advanced Regression Techniques** competition. The goal is to predict residential house sale prices using property features.

## Project Overview

This project covers the main stages of a regression machine learning workflow:

* Exploratory data analysis
* Data cleaning and missing-value handling
* Numerical feature scaling
* Categorical feature encoding
* Feature preprocessing using Scikit-learn
* Ridge Regression
* Hyperparameter tuning using different `alpha` values
* Model evaluation using **Root Mean Squared Logarithmic Error (RMSLE)**

## Model

The main model used is **Ridge Regression**. Different regularization strengths (`alpha`) were tested using a validation set to identify a suitable value for the model.

## Results

**Kaggle Score: 0.15510 RMSLE**

## Technologies

* Python
* Pandas
* NumPy
* Scikit-learn
* Matplotlib
* Jupyter Notebook

## Dataset

The project uses the **Ames Housing Dataset** provided through Kaggle's House Prices competition.

## Project Structure

```text
├── Data/
├── house_prices.ipynb
├── submission.csv
└── README.md
```

## Reference

[Kaggle – House Prices: Advanced Regression Techniques](https://www.kaggle.com/competitions/house-prices-advanced-regression-techniques)
