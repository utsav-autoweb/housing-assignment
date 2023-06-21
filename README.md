# Project Name
> A US-based housing company named Surprise Housing has decided to enter the Australian market. The company uses data analytics to purchase houses at a price below their actual values and flip them on at a higher price. For the same purpose, the company has collected a data set from the sale of houses in Australia. The data is provided in the CSV file below.

 

> The company is looking at prospective properties to buy to enter the market. You are required to build a regression model using regularisation in order to predict the actual value of the prospective properties and decide whether to invest in them or not.

 

> The company wants to know:

> Which variables are significant in predicting the price of a house, and

> How well those variables describe the price of a house.

 

> Also, determine the optimal value of lambda for ridge and lasso regression.


## Table of Contents
* [Business Goal](#business-goal)
* [General Information](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)
* [License](#license)


<!-- You can include any other section that is pertinent to your problem -->

## Business-Goal

> You are required to model the demand for shared bikes with the available independent variables. It will be used by the management to understand how exactly the demands vary with different features. They can accordingly manipulate the business strategy to meet the demand levels and meet the customer's expectations. Further, the model will be a good way for management to understand the demand dynamics of a new market. 


## General Information 

- We will be using Multiple Liear Regression in Python to predit the demand for the bike service based o the historical data provided
- The repo contains a jupiter notebook with the implementation of the same


## Conclusions
- Final List of Features ['GrLivArea',
 'MSSubClass_160',
 'Exterior1st_BrkComm',
 'AgeofProperty',
 'MSZoning_FV']
- Model Scores
- Lasso : 

For Lasso Regression Model (Original Model: alpha=0.001):
 ****************************************

For Train Set:
R2 score: 0.9019474700026279 
MSE score: 0.09805252999737218 
MAE score: 0.23405506075964555 
RMSE score: 0.3131334060705951

For Test Set:
R2 score: 0.8770073292451306 
MSE score: 0.11923329229545877 
MAE score: 0.2391499145128579 
RMSE score: 0.3453017409389341 
 ****************************************

 - Model Score Ridge: 
For Ridge Regression Model (Original Model, alpha=8.0):
 ****************************************

For Train Set:
R2 score: 0.9020986970982194 
MSE score: 0.0979013029017806 
MAE score: 0.2341494309807371 
RMSE score: 0.312891838982388

For Test Set:
R2 score: 0.8746762894461556 
MSE score: 0.12149308182598677 
MAE score: 0.24183489189131332 
RMSE score: 0.34855857732379325 
 ****************************************


<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
- Python 3
- Pandas
- Numpy
- matplotlib.pyplot
- seaborn
- sklearn.model_selection
- MinMaxScaler from sklearn.preprocessing 
- statsmodels.api
- variance_inflation_factor from statsmodels.stats.outliers_influence
- RFE from sklearn.feature_selection
- LinearRegression from sklearn.linear_model
- Lasso & Ridge

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Acknowledgements
- This project was inspired by an assignment by upgrad


## Contact
Created by [@rubol] - feel free to contact me!


<!-- Optional -->
 ## License

- GNU 3.0 

<!-- You don't have to include all sections - just the one's relevant to your project -->