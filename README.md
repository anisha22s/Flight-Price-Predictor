# Flight-Price-Predictor
Machine Learning project for personal development- predicting prices for non-stop flights with San Francisco International Airport (SFO) as the destination using techniques- Linear Regression, Lasso Regression, Decision Trees, XG Boost and Random Forest 

Analyzed how the total fare of a flight varies as among departure/arrival times, proximity to flight date, departure locations, day of the week/month, and whether or not the flight was within the next two days. Techniques used- simple linear regression, lasso, decision trees, random forests, and XG-boosted regressions to predict total fare using numerous covariates from the Flight Prices dataset. While only the simple linear regression performed (very) poorly when tested on OOS data, the random forest predictor performed the best, with an R-squared of 0.99 and an RMSE of 18.90. Using this result, airlines could have a broader understanding of how their prices compare to other airlines and why. Additionally, customers can use this model to help budget a future flight, and plan to take the AM flights to cut down on costs.

Sections:
1. Data Cleaning
2. EDA
3. Analysis questions:
    a. Does ticket price change based on the departure time and arrival time?
    b.How prices changes as number of days before flight date changes
    c. Does ticket price change based on the day of week/ week of month ?
4. MODEL SELECTION: PRICE PREDICTION
