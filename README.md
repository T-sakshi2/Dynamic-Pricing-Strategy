# Dynamic Pricing Prediction

## Introduction

This project focuses on predicting ride costs using dynamic pricing. The dataset includes various features related to rides, such as expected ride duration, historical cost, and vehicle type. The objective is to analyze and model ride costs dynamically based on demand and supply conditions.

## Project Structure

The project structure is organized as follows:

1. **Data Exploration:**
   - **Data Loading and Inspection:** Load the dataset, inspect its structure, check for missing values, and understand its distribution.
   - **Visualizations:** 
     - Scatter plot of expected ride duration vs. historical cost of ride.
     - Box plot of historical cost distribution by vehicle type.
     - Correlation matrix heatmap.

2. **Dynamic Pricing Calculation:**
   - **Demand Multiplier:** Calculate based on percentile thresholds for high and low demand.
   - **Supply Multiplier:** Calculate based on percentile thresholds for high and low supply.
   - **Adjusted Ride Cost:** Compute using demand and supply multipliers.
   - **Profitability Analysis:** Calculate and visualize profit percentages to determine profitable and loss rides.

3. **Data Preprocessing:**
   - **Handling Missing Values:** Fill missing values in numeric and categorical features.
   - **Outlier Detection:** Handle outliers using Interquartile Range (IQR).
   - **Categorical Encoding:** Convert categorical variables to numeric.

4. **Model Training:**
   - **Regression Model:** Train a RandomForestRegressor to predict adjusted ride costs.

5. **Model Evaluation:**
   - **Performance Metrics:** Evaluate model performance using scatter plots of actual vs. predicted values.

6. **Prediction:**
   - **Prediction Function:** Predict ride costs based on user-defined inputs.

## Features

- **Data Preprocessing:**
  - Techniques for handling missing values and outliers.
  - Encoding of categorical variables.

- **Exploratory Data Analysis (EDA):**
  - Data visualization to understand relationships and distributions.

- **Dynamic Pricing Calculation:**
  - Demand and supply multipliers.
  - Adjusted ride cost computation and profitability analysis.

- **Model Training:**
  - RandomForestRegressor for predicting ride costs.

- **Model Evaluation:**
  - Scatter plots comparing actual and predicted values.

- **Prediction Function:**
  - Predict ride costs using input values.

## Contributing

Contributions are welcome! Please create a new branch and submit a pull request for review.
