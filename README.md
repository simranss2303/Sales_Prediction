# Sales_Prediction
# Store Sales Prediction Project

## Overview
This project aims to predict the future sales of a retail store based on historical sales data using machine learning techniques. The dataset includes sales records with dates, and the project focuses on building a Random Forest model to forecast sales.

## Objective
The goal is to predict monthly sales by analyzing historical data and building a predictive model using **Random Forest Regressor**.

## Dataset
The dataset used in this project is named `train (1).csv`, which contains the following columns:
- `date`: The date of the sale.
- `sales`: The sales amount on that date.

The dataset is preprocessed to aggregate monthly sales and perform various feature engineering steps like sales differences and lag features.

## Libraries & Technologies Used
- **Python**: The main programming language used.
- **Pandas**: For data manipulation and cleaning.
- **NumPy**: For numerical operations.
- **Matplotlib**: For visualizing the data.
- **Scikit-learn**: For building machine learning models and preprocessing.

## Steps Involved

1. **Data Preprocessing**:
   - Convert the `date` column to a datetime format.
   - Aggregate sales data by month.
   - Create new features like sales differences and lag features to enhance the predictive model.

2. **Data Visualization**:
   - Plot the monthly sales and sales difference over time to visualize trends.
   
3. **Modeling**:
   - A **Random Forest Regressor** is used to predict future sales based on historical data.
   - The data is split into training and testing sets, and features are prepared for the model.

4. **Performance Evaluation**:
   - The model's performance is evaluated using metrics such as **Mean Absolute Error (MAE)**, **Mean Squared Error (MSE)**, and **R2 Score**.

5. **Prediction & Binning**:
   - The model predicts future sales, and the actual and predicted values are binned into categories for analysis.

## Files in This Repository
- `train (1).csv`: The dataset used for training and testing.
- `sales_prediction.py`: The main script where the data is processed, the model is trained, and predictions are made.
- `README.md`: This file.

## Running the Project
1. Clone this repository to your local machine:
   ```bash
   git clone https://github.com/yourusername/store-sales-prediction.git
