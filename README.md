# Linear regression casestudy - Boom Bikes project
This case study is to give an idea of applying concepts of linear regression to build Machine learning models in a real business scenario as part of EPGP course


## Table of Contents
* Introduction
* Business understanding
* Business objectives
* Approach 



## Introduction
Concepts learnt in python for Data science , Exploratory Data Analsysis, Machine learning 1 - linear regression are used to solve the problem statement with Python 3.0.


## Business understanding
A bike-sharing system is a service in which bikes are made available for shared use to individuals on a short term basis for a price or free. Many bike share systems allow people to borrow a bike from a "dock" which is usually computer-controlled wherein the user enters the payment information, and the system unlocks it. This bike can then be returned to another dock belonging to the same system.


A US bike-sharing provider BoomBikes has recently suffered considerable dips in their revenues due to the ongoing Corona pandemic. The company is finding it very difficult to sustain in the current market scenario. So, it has decided to come up with a mindful business plan to be able to accelerate its revenue as soon as the ongoing lockdown comes to an end, and the economy restores to a healthy state. 


In such an attempt, BoomBikes aspires to understand the demand for shared bikes among the people after this ongoing quarantine situation ends across the nation due to Covid-19. They have planned this to prepare themselves to cater to the people's needs once the situation gets better all around and stand out from other service providers and make huge profits.


They have contracted a consulting company to understand the factors on which the demand for these shared bikes depends. Specifically, they want to understand the factors affecting the demand for these shared bikes in the American market. The company wants to know:

    Which variables are significant in predicting the demand for shared bikes.
    How well those variables describe the bike demands

Based on various meteorological surveys and people's styles, the service provider firm has gathered a large dataset on daily bike demands across the American market based on some factors. 


## Business goal
You are required to model the demand for shared bikes with the available independent variables. It will be used by the management to understand how exactly the demands vary with different features. They can accordingly manipulate the business strategy to meet the demand levels and meet the customer's expectations. Further, the model will be a good way for management to understand the demand dynamics of a new market. 

## Approach
1. Necessary libraries imported
2. Data sourcing is executed to read the data from the loan dataset
3. Data understanding and cleaning performed to understand more about the data and removing unnnecessary columns from the dataset
4. Target variable column is the cnt
5. Prepared the data by converting categorical variables into dummy variables.
6. Dropped irrelevant and categorical variables from the data.
7. Split the data into test and train datasets in a 70:30 ratio.
8. Rescaled numerical variables using MinMax method.
9. Defined a heatmap to check collinearity among all the variables and identified temp to be the most significant feature.
10. Built a model using only temp feature with 41% adjusted R-Square.
11. Adopted RFE for feature selection and built 5 other models to increase adjusted R-square to 84.2%.
12. Performed residual analysis to confirm assumption of residuals hold true.
13. Made predictions on the train data.
14. Evaluated the model on test data with 81% accuracy.


## Contact
Created by [@priyapython] - feel free to contact me!
