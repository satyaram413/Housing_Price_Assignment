# House Price Prediction
### Problem Statement
A US-based housing company named Surprise Housing has decided to enter the Australian market. The company uses data analytics to purchase houses at a price below their actual values and flip them on at a higher price. For the same purpose, the company has collected a data set from the sale of houses in Australia.




## Table of Contents
* [Objective](#objective)
* [Conclusions](#conclusions)
* [Technologies Used](#technologies-used)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

### Objective

* Which variables are significant in predicting the price of a house, and

* How well those variables describe the price of a house.

You are required to model the price of houses with the available independent variables. This model will then be used by the management to understand how exactly the prices vary with the variables. They can accordingly manipulate the strategy of the firm and concentrate on areas that will yield high returns. Further, the model will be a good way for management to understand the pricing dynamics of a new market.


## Conclusions
  Ridge Regression can be used to predict the house prices, since it has better test r2score compared to conventional MLR and Lasso.
  The Top Predictor variables from Lasso and Ridge are:
  - Lasso Regression Coefficients with Optimum Alpha 0.001
    - Top Positive Coefficients
        1. GrLivArea
        2. OverallQual
        3. SaleCondition_Partial
        4. Neighborhood_Crawfor
        5. TotalBsmtSF
    - Top Negative Coefficient
        1. YearBuilt
        2. Neighborhood_IDOTRR
        3. Neighborhood_Edwards
        4. BsmtUnfSF
        5. Functional
- Ridge Regression Coefficients with Optimum Alpha 20
    - Top Positive Coefficients
        1. GrLivArea
        2. OverallQual
        3. TotalBsmtSF
        4. Neighborhood_Crawfor
        5. SaleCondition_Normal
    - Top Negative Coefficients
        1. YearBuilt 
        2. Neighborhood_IDOTRR
        3. Neighborhood_Edwards
        4. Condition2_PosN
        5. Neighborhood_MeadowV


<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
python3.10
sklearn
statsmodel.api

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Acknowledgements
Give credit here.
- This project was inspired by...
- References if any...
- This project was based on [this tutorial](https://www.example.com).


## Contact
Created by [@satyaram413] - feel free to contact me!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->
