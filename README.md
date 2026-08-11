# Predictive Analytics Using Historical Sales Data

## Project Overview

This project uses historical monthly sales data to build a predictive model for forecasting future sales trends.

The project demonstrates data cleaning, preprocessing, visualization, regression modeling, model evaluation, and future forecasting using Python.

## Objectives

- Clean and preprocess historical sales data
- Analyze historical sales trends
- Build a predictive regression model
- Evaluate model performance
- Forecast future sales
- Visualize actual and predicted sales

## Technologies Used

- Python
- Pandas
- Matplotlib
- Scikit-learn
- Jupyter Notebook

## Dataset

The dataset contains monthly sales information from January 2024 to December 2025.

Columns:

- Month
- Sales

## Methodology

1. Created and loaded historical sales data
2. Checked for missing values
3. Converted dates into proper date format
4. Removed duplicate records
5. Created a numerical time variable
6. Split the data into training and testing sets
7. Built a Linear Regression model
8. Generated predictions
9. Evaluated the model using MAE and R² Score
10. Forecasted sales for the next six months

## Model

A Linear Regression model was used to identify the relationship between time and sales.

## Evaluation Metrics

The model was evaluated using:

- Mean Absolute Error (MAE)
- R² Score

## Future Forecast

The model predicts monthly sales for:

- January 2026
- February 2026
- March 2026
- April 2026
- May 2026
- June 2026

## Project Structure

```text
Predictive_Analytics_Project
│
├── Dataset
│   └── historical_sales.csv
│
├── Output
│   ├── future_sales_predictions.csv
│   └── sales_forecast.png
│
├── Predictive_Analytics.ipynb
└── README.md