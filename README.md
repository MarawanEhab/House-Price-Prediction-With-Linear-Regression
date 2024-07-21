# House-Price-Prediction-With-Linear-Regression
House Price Prediction Using Linear Regression Project With a linear regression 
House Price Prediction Using Linear Regression
Project Overview
This project aims to predict house prices using a linear regression algorithm. The dataset includes various features that influence house prices, such as the size of the house, the number of rooms, the age of the house, and more. Through exploratory data analysis (EDA) and feature engineering, we develop a robust linear regression model to make accurate predictions.

Dataset
The dataset used in this project is sourced from Kaggle. It consists of 1460 rows and 81 columns, where each row represents a house and each column represents a feature of the house, including the target variable SalePrice.

Project Workflow
1. Data Preprocessing
Handling Missing Values: Missing values are imputed using median for numerical features and mode for categorical features.
Encoding Categorical Variables: One-hot encoding is used to convert categorical features into numerical format.
Feature Scaling: Standardization is applied to scale the features.
2. Exploratory Data Analysis (EDA)
Distribution Analysis: Histograms and scatter plots are used to visualize the distribution and relationships of features with the target variable.
Outlier Detection and Handling: Outliers are capped and floored based on specified limits to mitigate their impact.
3. Model Development
Feature Selection: Features highly correlated with the target variable are selected for model training.
Train-Test Split: The dataset is split into training and testing sets.
Linear Regression Model: A linear regression model is trained on the training data.
4. Model Evaluation
Performance Metrics: Mean Squared Error (MSE) and R-squared (R²) are used to evaluate the model's performance on the testing data.
