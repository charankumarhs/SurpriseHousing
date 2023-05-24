# Machine Learning Predictive model for Surprise Housing company
This is part of Advanced Regression Model demonstartion on a housing sales data from the skills gained during the course study.

## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)


## General Information
Surprise Housing is an US-based housing company, which has decided to enter the Australian market. The company uses data analytics to purchase houses at a price below their actual values and flip them on at a higher price.The company is looking at prospective properties to buy to enter the market and is looking for a predictive model which can predict the actual value of the prospective properties and decide whether to invest in them or not.

#### Essentially, the company wants to know - 
* Which variables are significant in predicting the price of a house, and

* How well those variables describe the price of a house.

### Business Goal:
Model the price of houses with the available independent variables, which will then be used by the management to understand how exactly the prices vary with the variables. Management can accordingly manipulate the strategy of the firm and concentrate on areas that will yield high returns. Further, the model will be a good way for management to understand the pricing dynamics of a new market.

## Conclusions

1. Advanced linear regression models with the log data transformation of SalePrice is built using Ridge and Lasso regression algorithms
2. The optimal lambda/alpha for Ridge regression is 0.25, with accuracy of 89-91.1%
3. The optimal lambda/alpha for Lasso regression is 0.001, with accuracy of 89-90.6%
4. The top 5 features 'GrLivArea','OverallQual','TotalBsmtSF','YearSold_Minus_YearBuilt','OverallCond' will predict about 83% of changes in SalePrice and these could be used for making business decisions.

NOTE: 
* GrLivArea : Above grade (ground) living area square feet<br>
* OverallQual : Rates the overall material and finish of the house on a scale of 1 to 10 with 1 being very poor and 10 being very excellent
* TotalBsmtSF : Total square feet of basement area
* YearSold_Minus_YearBuilt : It is the age of the house when it is sold, a derived feature
* OverallCond : Rates the overall condition of the house on a scale of 1 to 10 with 1 being very poor and 10 being very excellent


## Technologies Used
- library -  numpy  version  1.21.5
- library -  pandas  version  1.4.3
- library -  matplotlib  version  3.5.2
- library -  seaborn  version  0.11.2
- library -  sklearn  version  1.1.1
- library -  statsmodels  version  0.13.2
- library -  scipy  version  1.7.3
- library -  IPython  version  8.4.0
- library -  warnings
- library -  itertools

## Acknowledgements

- This project was done as part of the Machine Learning and Artificial Intelligence Master Degree program by upGrad in asssociation with IIIT-B and LJMU.


## Contact
Created by [@charankumarhs] - feel free to contact me!
