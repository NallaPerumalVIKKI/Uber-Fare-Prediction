# Uber-Fare-Prediction
INTRODUCTION
The topic of the project is taxi fare prediction. In this project R and excel is utilized to create an interactive R shiny dashboard. The dashboard helps us better understand the data, as well as the methods used to create a prediction model.

PROBLEM STATEMENT
In this project, the data set given is explored using various graphs and plots and a model (s) is built to predict the fare given, distance and weather conditions like humidity, wind speed etc.

METHODOLOGY USED
Multiple linear regression (MLR), also known simply as multiple regression, is a statistical technique that uses several explanatory variables to predict the outcome of a response variable. The goal of multiple linear regression (MLR) is to model the linear relationship between the explanatory (independent) variables and response (dependent) variable. We considered price to be the dependent variable and surge multiplier, distance, cab name, rainfall measurement etc. to the independent(explanatory) variables. Accordingly, predictions were made. Based on these variables a price prediction calculator was developed. A standard price prediction calculator concerning source and destination is also developed. Exploratory data analysis of various variables were also done in order to get a clearer understanding of the data.

DATASET
The data was obtained from ‘kaggle.com’. The database has real time data collected using Uber & Lyft API queries and corresponding weather conditions. The data was split into two csv files. Together the data has around 6 lakh and 18 columns (Out of which only 7 are usable as predictors). One file contains all the information about the ride. This data set includes 10 variables, which included price, distance, 13-digit UNIX time stamp, product ID, cab provider (Uber or Lyft), cab type (XL, pool, ...), pickup location, destination and surge multiplier. The other file contains all the weather-related information on a given time in any particular location. This set of data consists of location, 10-digit UNIX time stamp, temperature, clouds, pressure, rain, humidity and wind.

RESULT
Distance along with the categorical variable cab name is found to be the most appropriate variable for prediction with minimum residual error and maximum adjusted R-squared value
Prices don’t surge for higher tier cabs.
Rain exhibits a negative correlation with respect to price.
