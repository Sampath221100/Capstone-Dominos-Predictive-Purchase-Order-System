# Capstone-Dominos-Predictive-Purchase-Order-System

## Problem Statement

Dominos aims to optimize inventory management by predicting future sales and generating accurate purchase orders. By forecasting demand, the company can maintain appropriate stock levels of ingredients, reducing waste, minimize costs, and preventing stockouts. This project leverages historical sales data and ingredient information to develop a predictive model and an efficient purchase order system.

## Business Use Cases

- **Inventory Management:** Maintain optimal ingredient stock levels based on forecasted sales.
- **Cost Reduction:** Minimize waste from overstocking and reduce costs tied to expired or excess inventory.
- **Sales Forecasting:** Predict future sales trends to guide inventory decisions, promotions, and business strategies.
- **Supply Chain Optimization:** Streamline the purchase ordering process to align with sales forecasts, preventing disruptions.

## Approach

### 1. Data Preprocessing and Exploration
- **Data Cleaning:** Identify and handle missing data, outliers, and inconsistencies to prepare the dataset.
- **Exploratory Data Analysis (EDA):** Analyze sales trends, seasonality, and patterns to identify key features affecting demand, using visualizations.

### 2. Sales Prediction
- **Feature Engineering:** Create features like day of the week, month, holiday effects, and promotional periods from the sales data.
- **Model Selection:** Choose a forecasting model such as ARIMA, SARIMA, Prophet, LSTM, or a Regression Model.
- **Model Training:** Train the chosen model on historical sales data.
- **Model Evaluation:** Use Mean Absolute Percentage Error (MAPE) to evaluate the model's predictive performance.

### 3. Purchase Order Generation
- **Sales Forecasting:** Predict Dominos' sales for the next week (or a different specified period) using the trained model.
- **Ingredient Calculation:** Determine the quantities of ingredients required to meet the forecasted sales based on ingredient usage data.
- **Purchase Order Creation:** Generate a detailed purchase order listing the quantities of each ingredient needed for the forecasted sales period.

## Conclusion

This project focuses on developing a predictive model to optimize Dominos’ sales forecasting and inventory management. By accurately predicting demand and creating efficient purchase orders, Dominos can streamline its supply chain, reduce waste, and ensure continuous product availability for its customers.
