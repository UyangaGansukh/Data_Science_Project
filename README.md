# Data_Science_Project

This project presents a comprehensive data-driven analysis of housing prices in New York City, focusing on uncovering the price factors in housing market. Through rigorous data preprocessing, exploratory data analysis, and model development using LASSO regression, we uncovered significant insights into the dynamics of the housing market. By delving into internal and external factors affecting housing prices, we aim to contribute fresh insights that can inform decision-making in the real estate industry.

## Programs and programming languages
- Python

## Dataset
- Zillow API NYC Housing data
- Demographic data by zipcode form US Census
- Financial data by zipcode from IRS
The merged dataset contains more than 70,000 observations with over 1,500 attributes. After meticulous preprocessing, we condensed the dataset to 64 informative variables, retaining crucial information while mitigating noise and redundancy.

## Pre-processing
The pre-processing involved three phases: 
- format unification,
- handling missing/unreasonable values,
- data transformation. 

## Exploratory Data Analysis
Exploratory analysis revealed insights into housing price distributions, historical trends, and geographical patterns. We observed unexpected volatility in housing prices during the COVID-19 pandemic, particularly in Manhattan and Brooklyn.

## Model Selection
LASSO regression was chosen for its performance, suitability for high-dimensional datasets and interpretability.

## Feature Selection
The input space comprised 64 variables representing intrinsic housing characteristics, schooling conditions, demographic factors, and transaction history. Feature selection using LASSO regression identified significant predictors, including transaction-related factors associated with flipping.

## Results
Contrary to expectations, certain areas in Brooklyn exhibited higher housing prices than Manhattan, attributed to factors such as gentrification and flipping. Our findings suggest that factors related to housing transactions, particularly flipping, exert a significant influence on housing prices, challenging traditional assumptions about pricing mechanisms. 

## Files Included
- `README.md`: This file provides an overview of the project.
- `Data_preprocessing.m`, `Data_preprocessing_p2.m`: Python code for Preprocessing part of the project.
-
- `Data Science `
