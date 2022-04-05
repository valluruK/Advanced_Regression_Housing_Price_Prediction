# Advanced Regression - Housing Price Prediction
This assignment is a programming assignment as part of upGrad IIIT-B Executive Post Graduate program to build advanced regression model using regularisation for the prediction of Housing Prices.

### Problem Statement
A US-based housing company named Surprise Housing has decided to enter the Australian market. The company uses data analytics to purchase houses at a price below their actual values and flip them on at a higher price. For the same purpose, the company has collected a data set from the sale of houses in Australia.

The company is looking at prospective properties to buy to enter the market. We are required to build a regression model using regularisation in order to predict the actual value of the prospective properties and decide whether to invest in them or not.

The company wants to know:
- Which variables are significant in predicting the price of a house, and
- How well those variables describe the price of a house.

Also, determine the optimal value of lambda for ridge and lasso regression.


### Business Goal:
We are required to model the price of houses with the available independent variables. This model will then be used by the management to understand how exactly the prices vary with the variables. The management can accordingly manipulate the strategy of the firm and concentrate on areas that will yield high returns. Further, the model will be a good way for management to understand the pricing dynamics of a new market.


### Dataset 
The below link has the dataset used for this assignment 
- https://ml-course3-upgrad.s3.amazonaws.com/Assignment_+Advanced+Regression/train.csv


## Conclusions

Below are the TOP 10 variables which are significant in predicting the Sale Price.
- GrLivArea: Above grade (ground) living area square feet.
- OverallQual: Rates the overall material and finish of the house.
- GarageCars: Size of garage in car capacity.
- OverallCond: Rates the overall condition of the house.
- LotArea: Lot size in square feet
- Neighborhood_StoneBR: Physical locations within Ames city limits - Stone Brook
- MSZoning_RL: Identifies residential with Low Density zone.
- BsmtQual: Evaluates the height of the basement
- TotalBsmtSF: Total square feet of basement area
- MSZoning_FV: Identifies residential with Floating Village Residential 

#### Ridge Regression
- R2 score(Train): 91.63%
- R2 score(Test): 87.76%
#### Lasso Regression
- R2 score(Train): 91.33%
- R2 score(Test): 87.95%




### Technologies Used
- Python - version 3.0



#### Contact
Created by [@valluruK] - feel free to contact me!

