# House Price Prediction Assignment
> A US-based housing company named Surprise Housing has decided to enter the Australian market. The company uses data analytics to purchase houses at a price below their actual values and flip them on at a higher price. For the same purpose, the company has collected a data set from the sale of houses in Australia.The company is looking at prospective properties to buy to enter the market. We are required to build a regression model using regularisation in order to predict the actual value of the prospective properties and decide whether to invest in them or not.


## Table of Contents
* [General Info](#general-information)
* [Conclusions](#conclusions)
* [Libraries Used](#technologies-used)




## General Information
- We are required to model the price of houses with the available independent variables. This model will then be used by the management to understand how exactly the prices vary with the variables. They can accordingly manipulate the strategy of the firm and concentrate on areas that will yield high returns. 
- Further, the model will be a good way for management to understand the pricing dynamics of a new market.
- The dataset has 81 distinct columns and 1460 rows.


## Conclusions
- Based on the heatmap,GarageCars,BsmtUnfSF,TotRmsAbvGrd and GarageYrBlt were higly correlated.
- Sales price increases with the increase in overall quality of house, mean sales price increases if the house has central air and if Kitchen,Basement and External qual is excellent , then the sales price increases.
- Train R2 for Ridge - 0.885 , Test R2 for Ridge - 0.875 , Best Alpha for Ridge - 20.0
- Train R2 for Lasso - 0.927 , Test R2 for Lasso - 0.905 , Best Alpha for Lasso - 0.001


## Libraries Used
- python 3.10.9
- numpy 1.23.5
- pandas 1.5.3
- matplotlib 3.7.0
- seaborn 0.12.2
- sklearn - version 1.2.1



## Contact
Created by [Kushagra007-dev] - feel free to contact me!


