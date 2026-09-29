# house_price_prediction
## Project Overview

This project demonstrates how Machine Learning can be used to predict house prices based on different features such as area, number of bedrooms, bathrooms, house age, and location score.

A Linear Regression model is trained using a house price dataset and evaluated using different regression metrics.

## Objectives

- Load and explore the house price dataset.
- Analyze the dataset and check for missing values.
- Select relevant features for prediction.
- Split the dataset into training and testing data.
- Build a Linear Regression model.
- Predict house prices.
- Evaluate the model using regression metrics.
- Visualize actual vs predicted house prices.
- Compare models using different numbers of features.

## Technologies Used

-  Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Jupyter Notebook
## Dataset

The project uses the dataset:

"houseprice.csv"

Features Used

Feature| Description
Area| Area of the house
Bedrooms| Number of bedrooms
Bathrooms| Number of bathrooms
Age| Age of the house
Location Score| Score representing the location

Target

Price – The predicted house price.

## Project Workflow

House Price Dataset
        ↓
Data Loading
        ↓
Data Exploration
        ↓
Missing Value Checking
        ↓
Feature Selection
        ↓
Train-Test Split
        ↓
Linear Regression
        ↓
House Price Prediction
        ↓
Model Evaluation
        ↓
Visualization
        ↓
Feature Comparison

## Machine Learning Model

Linear Regression

Linear Regression is a supervised machine learning algorithm used to predict a continuous numerical value.

In this project, Linear Regression is used to predict house prices based on the selected input features.

The model uses:

Area
Bedrooms
Bathrooms
Age
Location Score
        ↓
Linear Regression
        ↓
Predicted House Price

## Model Evaluation

The model is evaluated using:

1. MAE – Mean Absolute Error

Measures the average absolute difference between the actual and predicted prices.

2. MSE – Mean Squared Error

Measures the average squared difference between actual and predicted values.

3. RMSE – Root Mean Squared Error

RMSE is the square root of MSE and represents the prediction error in the same unit as the target variable.

4. R² Score

R² score indicates how well the model explains the variation in house prices.

## Visualization

An Actual vs Predicted House Price scatter plot is created to compare the actual prices with the prices predicted by the model.

Actual Price  →  X-axis
Predicted Price → Y-axis

A reference line is also plotted to help compare actual and predicted values.

## Feature Comparison

Two Linear Regression models are compared:

Model 1 – 5 Features

- Area
- Bedrooms
- Bathrooms
- Age
- Location Score

Model 2 – 4 Features

- Area
- Bedrooms
- Bathrooms
- Location Score

The R² scores of both models are compared to understand the effect of using different features.

## Project Output

Actual vs Predicted House Price

Add your output screenshot here:

![Actual vs Predicted House Price](actual_vs_predicted.png)

## Project Structure

Day-6-Python/
│
├── dharshini day 6.ipynb
├── houseprice.csv
└── README.md

## How to Run

1. Download or clone this repository.
2. Open the Jupyter Notebook.
3. Keep "houseprice.csv" in the same folder as the notebook.
4. Install the required libraries:

pip install pandas numpy scikit-learn matplotlib

5. Open the notebook in Jupyter Notebook or Google Colab.
6. Run the cells step by step.

## Key Learning Outcomes

Through this project, I learned:

- How to load datasets using Pandas.
- How to explore and understand a dataset.
- How to check missing values.
- How to select features and target variables.
- How to split data into training and testing sets.
- How to build a Linear Regression model.
- How to make predictions.
- How to calculate MAE, MSE, RMSE, and R² score.
- How to visualize actual and predicted values.
- How feature selection can affect model performance.

