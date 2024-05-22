# Housing Price Prediction
> Will determine which variables are significant in predicting the price of a house, and
> and how well those variables describe the price of a house.


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
- A US-based housing company named Surprise Housing has decided to enter the Australian market. The company uses data analytics to purchase houses at a price below their actual values and flip them on at a higher price. For the same purpose, the company has collected a data set from the sale of houses in Australia. The data is provided in the CSV file below.
- The company is looking at prospective properties to buy to enter the market. You are required to build a regression model using regularisation in order to predict the actual value of the prospective properties and decide whether to invest in them or not.
- The company wants to know:
    * Which variables are significant in predicting the price of a house, and
    * How well those variables describe the price of a house.
    * Also, determine the optimal value of lambda for ridge and lasso regression.
-Business Goal 
    * You are required to model the price of houses with the available independent variables. This model will then be used by the management to understand how exactly the prices vary with the variables. They can accordingly manipulate the strategy of the firm and concentrate on areas that will yield high returns. Further, the model will be a good way for management to understand the pricing dynamics of a new market.
<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
-  Variables like GrLivArea, OverallQual, MasVnrArea, KitchenQual, GarageCars, BsmtQual are significant predictor of the price.
-  How well variables is related can be determine by correlation value which is calucated as below:
  * GrLivArea with SalesPrice:0.7086244776126515
  * OverAllQual with SalePrice:0.7909816005838053
  * GarageCars with SalePrice:0.6404091972583519
  * KitchenQual with SalesPrice:-0.589188778299423
  * BsmtQual with SalePrice:-0.6208861300191687
-  Optimal value of lambda for ridge is 4 and lasso is 0.0001

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
- Jupyter Notebook 

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Acknowledgements
- This project was part of assignment


## Contact
Created by [@githubusername] - feel free to contact me!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->