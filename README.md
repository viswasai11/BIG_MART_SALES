# Sales Prediction for Big Mart Outlets using Regression

## Problem Statement 

The data scientists at BigMart have collected 2013 sales data for 1559 products across 10 stores in different cities. Also, certain attributes of each product and store have been defined. The aim is to build a predictive model and predict the sales of each product at a particular outlet.

Using this model, BigMart will try to understand the properties of products and outlets which play a key role in increasing sales.

Please note that the data may have missing values as some stores might not report all the data due to technical glitches. Hence, it will be required to treat them accordingly. 

### Aim of the project

This is a summary of the objective and approach of a data analysis project. The goal is to use regression machine learning models to estimate the "Item_Outlet_Sales" variable for a test data set, based on the training data set of the big mart sales. The regression models will use various features from the data, such as item type, outlet size, outlet location, etc., to learn the relationship between the input and output variables and make predictions for the test data set.

## Data Description 

We have train (8523) and test (5681) data set, train data set has both input and output variable(s). You need to predict the sales for test data set.



Train file: CSV containing the item outlet information with sales value

| Variable	| Description | 
|----------------|:--------------------|
| Item_Identifier|Unique product ID |
|Item_Weight|Weight of product|
|Item_Fat_Content|Whether the product is low fat or not|
|Item_Visibility|The % of total display area of all products in a store allocated to the particular product|
|Item_Type |The category to which the product belongs|
|Item_MRP|Maximum Retail Price (list price) of the product|
|Outlet_Identifier|Unique store ID|
|Outlet_Establishment_Year|The year in which store was established|
|Outlet_Size|The size of the store in terms of ground area covered|
|Outlet_Location_Type| The type of city in which the store is located|
|Outlet_Type|Whether the outlet is just a grocery store or some sort of supermarket|
|Item_Outlet_Sales|Sales of the product in the particular store. This is the outcome variable to be predicted.|
 

Test file: CSV containing item outlet combinations for which sales need to be forecasted

|Variable	|Description|
|------------|:-----------|
|Item_Identifier|Unique product ID|
|Item_Weight|Weight of product|
|Item_Fat_Content|Whether the product is low fat or not|
|Item_Visibility|The % of total display area of all products in a store allocated to the particular product|
|Item_Type|The category to which the product belongs|
|Item_MRP|Maximum Retail Price (list price) of the product|
|Outlet_Identifier|Unique store ID|
|Outlet_Establishment_Year|The year in which store was established|
|Outlet_Size|The size of the store in terms of ground area covered|
|Outlet_Location_Type|The type of city in which the store is located|
|Outlet_Type|Whether the outlet is just a grocery store or some sort of supermarket|


### The project involves the following key steps:
**Data Collection: analytics vidhya hackathon:** https://datahack.analyticsvidhya.com/contest/practice-problem-big-mart-sales-iii/

Linear regression is a widely used statistical technique that models the relationship between a dependent variable and one or more independent variables. It can be used for various purposes, such as predicting future outcomes, estimating causal effects, and testing hypotheses. The process of applying linear regression to a dataset consists of three main steps: data preprocessing, model training, and model evaluation.

***Data preprocessing*** is the process of cleaning and preparing the dataset for the linear regression analysis. It involves handling missing values, outliers, and inconsistencies that may affect the quality and reliability of the results. Data preprocessing also includes transforming categorical variables into numerical representations, such as dummy variables or one-hot encoding, normalizing numeric features to have a common scale, and splitting the dataset into training and testing subsets to avoid overfitting and underfitting problems.

***Model training*** is the process of implementing linear regression and other regression models using appropriate libraries or frameworks, such as scikit-learn in Python or TensorFlow in R. The model training process involves fitting the model to the training data, estimating the coefficients (slope and intercept) that define the best-fit line, and optimizing the model's performance by minimizing the residual errors between the predicted and actual values. The residual errors are also known as the cost function or the loss function, and they can be reduced by using different optimization algorithms, such as gradient descent or stochastic gradient descent.

***Model evaluation*** is the process of assessing the performance of the trained linear regression model using evaluation metrics that measure how well the model predicts the values and indicate its overall accuracy. Some of the common evaluation metrics for linear regression are mean squared error (MSE), root mean squared error (RMSE), and R-squared. MSE is the average of the squared differences between the predicted and actual values, RMSE is the square root of MSE, and R-squared is the proportion of variance explained by the model. A lower MSE or RMSE indicates a better fit, while a higher R-squared indicates a higher explanatory power.


### Acknowledgments
- The dataset used in this project is sourced from: (https://datahack.analyticsvidhya.com/contest/practice-problem-big-mart-sales-iii/)
- The Gradient Boosting Machine algorithm is implemented using the scikit-learn library.
