# Bike Selling Price Analysis and Prediction

This project involves the analysis and prediction of bike selling prices using a dataset named BIKE.csv. The analysis includes exploratory data analysis (EDA), data visualization, data cleaning, and building a simple linear regression model to predict the selling price of bikes based on various features. The project is implemented in Python and makes use of popular data science libraries such as Pandas, NumPy, Matplotlib, Seaborn, and Scikit-Learn.

# Table of Contents
1. Introduction
2. Project Structure
3. Data Description
4. Exploratory Data Analysis
5. Data Cleaning
6. Data Visualization
7. Linear Regression Model
8. Evaluation Metrics
9. Requirements
10. Usage
11. Conclusion
    
# Introduction
The goal of this project is to understand the factors influencing the selling price of bikes and to build a predictive model using linear regression. By analyzing and visualizing the data, we aim to gain insights that can help in making informed decisions.

# Project Structure
The project consists of the following key steps:
Data Loading and Initial Exploration
Data Visualization
Data Cleaning and Preparation
Linear Regression Model Building
Model Evaluation

# Data Description
The dataset BIKE.csv contains various features related to bikes and their selling prices. Key features include:
selling_price: The price at which the bike is sold.
year: The year of manufacture.
owner: The ownership status of the bike.
seller_type: The type of seller (e.g., dealer, individual).
ex_showroom_price: The showroom price of the bike.

# Exploratory Data Analysis
Initial exploration of the dataset includes:
Displaying the first few rows of the dataset.
Checking the shape of the DataFrame.
Generating a concise summary of the DataFrame.
Descriptive statistics of numerical features.
Identifying missing values.

# Data Visualization
To understand the relationships between different variables, the following visualizations are created:
Scatter Plot: Relationship between selling_price and year.
Histogram: Distribution of the owner column.
Bar Plot: Counts of different seller_type values.

# Data Cleaning
Data cleaning steps include:
Dropping rows with missing values.
Converting the selling_price column to float.
Filling missing values in the ex_showroom_price column with the column mean.

# Data Visualization
Additional visualizations to explore the data further:
Box Plot: Distribution of selling_price.
Box Plot: Distribution of selling_price grouped by owner.

# Linear Regression Model
The following steps are taken to build the linear regression model:
Setting up the feature x (year) and target y (selling price).
Splitting the data into training and test sets with a 70-30 split.
Training a LinearRegression model using the training data.
Making predictions on both training and test data.
Plotting the predicted vs actual values for training data.

# Evaluation Metrics
The performance of the linear regression model is evaluated using the following metrics:
Mean Squared Error (MSE)
Root Mean Squared Error (RMSE)
Mean Absolute Error (MAE)
R-squared (R2) Score

# Requirements
The project requires the following Python libraries:
numpy
pandas
matplotlib
seaborn
scikit-learn

# Conclusion
This project provides insights into the factors affecting bike selling prices and demonstrates the use of linear regression for predictive analysis. The model's performance metrics indicate its effectiveness in predicting bike selling prices based on the year of manufacture. Future improvements could include exploring additional features and advanced modeling techniques to enhance prediction accuracy.
