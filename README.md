# Rusty Bargain: Price Prediction for Used Cars

## Project Overview

This project focuses on predicting the sale price of used vehicles for Rusty Bargain, a fictional car dealership. The goal was to develop a regression model that estimates vehicle prices based on features such as age, mileage, brand, and technical condition. The model helps support more accurate pricing decisions to remain competitive while maximizing margin.

## Objectives

- Analyze factors influencing used vehicle prices  
- Prepare and clean data for regression modeling  
- Engineer features and handle multicollinearity  
- Train and evaluate models to meet a business-defined RMSE threshold

## Tools & Technologies

- Python  
- pandas, NumPy  
- scikit-learn  
- matplotlib, seaborn  
- Jupyter Notebook  

## Modeling Approach

- Removed outliers and handled missing values  
- Converted categorical variables using encoding techniques  
- Created new features including vehicle age, mileage per year, and repair history flags  
- Trained linear regression and decision tree models  
- Evaluated performance using RMSE and cross-validation

## Key Results

- Final model achieved an RMSE below the required business threshold  
- Feature engineering significantly improved model performance  
- Insights supported better understanding of value depreciation and pricing trends

## Future Enhancements

- Experiment with ensemble models like Random Forest or XGBoost  
- Incorporate more granular vehicle specs and external pricing benchmarks  
- Deploy model in a price recommendation tool for dealership staff
