# Overview
This repository contains all of the code for my projects for BAT3305 - Machine Learning at Trinity University. 

The course description is

> The study and implementation of machine learning algorithms to solve problems that involve big data sets in business analytics and related applications. Topics include logistic regression, k-nearest neighbors, linear discriminant analysis, classification trees, k-means clustering, principal component analysis, text mining and sentiment analysis among others, as well as how to choose the best analytic strategy in different business scenarios.

# Projects

## KaggleHousingProject
[/KaggleHousingProject](KaggleHousingProject)

### Description
Machine Learning Project where the goal is to predict the Sales Price of a house based on features of a house. Tasks include:

* Cleaning of the data (handling missing values, combining category levels, creating new variables, removing irrelevant variables)
* Picking predictors to create a plain vanilla model that will predict SalePrices
* Doing diagnostic tests of the original plain vanilla model (e.g. normality of error terms, homosckedasticity, multicollinearity) and transforming the dependent variable if this tests are violated
* After doing diagnostic tests, do the plain vanilla model again to see if the prescriptions used to fix violations of any assumptions improve the model performance 
* Employing linear and non-linear regression modelling techniques to predict SalePrice, including forward selection using AIC, backward selection using AIC, Ridge regression, lasso regression, bagging, random forest regression, and boosting regression
* Determine the best model based on the Kaggle score (Boosting performed the best out of all model techniques performed)
  
