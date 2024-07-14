House Price Prediction Using Linear Regression
This project implements a linear regression model to predict house prices based on three features: square footage, number of bedrooms, and number of bathrooms. The model aims to provide an estimate of the house price given these input features.

Overview
Predicting house prices is a common problem in real estate and data science. Accurate predictions can aid buyers, sellers, and real estate professionals in making informed decisions. This project utilizes linear regression, a fundamental machine learning algorithm, to build a predictive model for house prices.

Features
Square Footage: The total living area of the house.
Number of Bedrooms: The total number of bedrooms in the house.
Number of Bathrooms: The total number of bathrooms in the house.
Model
Linear regression is used to create a relationship between the input features and the target variable (house price). The model assumes a linear relationship between the features and the price.

Steps Involved:
Data Collection: Gathering a dataset containing house prices and their corresponding features.
Data Preprocessing: Cleaning the data and handling any missing values or outliers.
Feature Engineering: Selecting and possibly creating new features that may improve the model's performance.
Model Training: Splitting the dataset into training and testing sets, and training the linear regression model on the training data.
Model Evaluation: Evaluating the model's performance on the testing data using metrics such as Mean Absolute Error (MAE), Mean Squared Error (MSE), and R-squared.
Prediction: Using the trained model to predict house prices for new data.
Requirements
Python 3.x
Pandas
NumPy
Scikit-learn
Matplotlib (for data visualization)
