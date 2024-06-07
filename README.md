# Car Price Prediction Using Linear Regression

## Introduction
This project aims to predict car prices using a linear regression model. The data is preprocessed and then used to train the model, which is evaluated using various metrics.

##Requirements
##
To run this notebook, you need the following Python libraries:
##
pandas
matplotlib
seaborn
scikit-learn
numpy
You can install these packages using pip:
##
pip install pandas matplotlib seaborn scikit-learn numpy

##Data
##
The dataset used in this notebook is cardetailsv4.csv, which contains various features of cars. Make sure this CSV file is in the same directory as the notebook.

##Steps
##
Import Libraries: Import necessary libraries for data manipulation, visualization, and model training.
Load Data: Load the dataset using pandas.
##
###Data Exploration:
Display dataset information and check for missing values.
Show the first few rows of the dataset.
Describe the dataset statistically.
Feature Selection: Select relevant features for the model.
##Data Cleaning:
##
Clean and preprocess data (e.g., convert strings to numeric values, handle missing values).
Encode categorical variables using one-hot encoding.
Data Splitting: Split the dataset into training and testing sets.
Feature Scaling: Standardize features by removing the mean and scaling to unit variance.
Model Training: Train a linear regression model using the training data.
Prediction: Predict car prices using the test data.
Evaluation: Evaluate the model using metrics such as Mean Absolute Error (MAE), Mean Squared Error (MSE), Root Mean Squared Error (RMSE), and R-squared (R²).
