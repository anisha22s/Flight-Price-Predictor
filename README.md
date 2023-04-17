# **Flight-Price-Predictor**

This machine learning project was developed to predict prices for non-stop flights with San Francisco International Airport (SFO) as the destination using techniques such as Linear Regression, Lasso Regression, Decision Trees, XG Boost, and Random Forest. The dataset was obtained from Kaggle.

## **Project Overview**

In this project, we analyzed how the total fare of a flight varies with departure/arrival times, proximity to the flight date, departure locations, day of the week/month, and whether or not the flight was within the next two days. We used simple linear regression, lasso, decision trees, random forests, and XG-boosted regressions to predict the total fare using numerous covariates from the Flight Prices dataset. While only the simple linear regression performed poorly when tested on out-of-sample (OOS) data, the random forest predictor performed the best, with an R-squared of 0.99 and an RMSE of 18.90.

Our analysis can help airlines gain a broader understanding of how their prices compare to other airlines and why. Additionally, customers can use this model to help budget a future flight and plan to take the AM flights to cut down on costs.

## **Sections**

The project is divided into the following sections:

Data Cleaning: This section covers the steps we took to clean and preprocess the raw data  
Exploratory Data Analysis (EDA): This section contains visualizations and descriptive statistics used to gain insights into the data  
Analysis Questions: This section answers the following questions:  
Does ticket price change based on the departure time and arrival time?  
How does price change as the number of days before the flight date changes?  
Does ticket price change based on the day of the week/week of the month?  
Model Selection: Price Prediction: This section covers the model selection process and provides details on the models used for price prediction.  

## **Getting Started## **

To get started with the project, you will need to clone the repository and install the required packages.

## **Prerequisites## **

To run this project, you will need to install the following packages:

numpy  
pandas  
matplotlib  
seaborn  
sklearn  
xgboost
statsmodel

## **Running the Code## **

To run the code, you can simply open the Jupyter Notebook and execute the code cells sequentially. The notebook contains detailed comments to guide you through the code.

## **Acknowledgments## **

I would like to thank Kaggle for providing the Flight Prices dataset, which was used for this project.


