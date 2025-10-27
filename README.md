
# House Price Prediction

## Overview
This project utilizes machine learning algorithms to predict the price of a house based on various features such as size, location, number of bedrooms, and other relevant factors.

## Dataset

### Data Sources
*  **Source 1:** https://media.geeksforgeeks.org/wp-content/uploads/20240905183434/HousePricePrediction.xlsx
*  **Description:** This dataset contains information on house prices along with other details such as size, location, bedrooms, etc.

### Data Files
*  'HousePricePrediction.xlsx': Raw housing data.
*  **Description:** This dataset contains information on house prices along with other details such as size, location, bedrooms, etc.

## Methodology

This analysis follows these steps:

1.  **Data Collection:** Downloaded from online repository.
2.  **Data Cleaning & Preprocessing:** Dropped the "Id" field and records with null values. Also, replaced SalePrice empty values with their mean values to make the data distribution symmetric.
3.  **Exploratory Data Analysis (EDA):** Used a heatmap using the seaborn library to discover different patterns and spot anomalies. Also used a bar plot to visualize the number of unique categories.
4.  **Model Training:** Used the Support Vector Machine, which works by finding the hyperplane that best divides a dataset into classes. Also used the Random Forest Regression, which constructs multiple decision trees during training where each tree in the forest is built on a random subset of the data and features, ensuring diversity in the model. And finally, Linear Regression was used for modeling the relationship between a dependent variable and one or more independent variables.
