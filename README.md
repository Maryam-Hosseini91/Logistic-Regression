# Logistic-Regression
#### What is Logistic-Regression?

Logistic regression is a statistical modeling technique used to predict the probability of a binary outcome based on one or more independent variables. It is commonly used in machine learning and statistics for classification tasks.
The term "regression" might be misleading since logistic regression is primarily used for classification rather than regression analysis. However, it is called "regression" because it uses a similar framework as linear regression.
The main goal of logistic regression is to estimate the probability of an event occurring, given a set of predictor variables. It is especially useful when the dependent variable is binary, meaning it can take only two possible values (e.g., yes or no, true or false, 0 or 1).
The logistic regression model assumes a linear relationship between the independent variables and the log-odds (logit) of the dependent variable. The log-odds are then transformed using the logistic function (also known as the sigmoid function) to obtain the predicted probabilities. The logistic function maps any real-valued number to a value between 0 and 1, making it suitable for representing probabilities.

## Project:
In this project we will be working with a fake advertising data set, This data set contains the following features:

* 'Daily Time Spent on Site': consumer time on site in minutes
* 'Age': cutomer age in years
* 'Area Income': Avg. Income of geographical area of consumer
* 'Daily Internet Usage': Avg. minutes a day consumer is on the internet
* 'Ad Topic Line': Headline of the advertisement
* 'City': City of consumer
* 'Male': Whether or not consumer was male
* 'Country': Country of consumer
* 'Timestamp': Time at which consumer clicked on Ad or closed window
* 'Clicked on Ad': 0 or 1 indicated clicking on Ad

## Purpose:
We will try to create a model that will predict whether or not they will click on an ad based off the features of that user.
Data is analyzed step by step, please refer to [Logistic Regression Project.ipynb](https://github.com/Maryam-Hosseini91/Logistic-Regression/blob/main/Logistic%20Regression%20Project.ipynb)
