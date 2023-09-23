# Project Name
> Advance  regression using Lasso and Ridge 

## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
A US-based housing company named Surprise Housing has decided to enter the Australian market. The company uses data analytics to purchase houses at a price below their actual values and flip them on at a higher price. For the same purpose, the company has collected a data set from the sale of houses in Australia. The data is provided in the CSV file below.

The company is looking at prospective properties to buy to enter the market. You are required to build a regression model using regularisation in order to predict the actual value of the prospective properties and decide whether to invest in them or not.

The company wants to know:
Which variables are significant in predicting the price of a house, and
How well those variables describe the price of a house.
Also, determine the optimal value of lambda for ridge and lasso regression.

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
Lasso:- Train R2 Square :  0.94 Test R2 Square :  0.87
Ridge:- Train R2 Square :  0.93 Test R2 Square :  0.88

5 most significatnt feature in Lasso

PoolArea  0.220
PoolQC_Fa 0.199
GrLivArea 0.111
PavedDrive_Y -0.070
OverallQual 0.066

5 most significatnt feature in Ridge

OverallQual 0.054
GrLivArea   0.044
PavedDrive_Y -0.036
OverallCond 0.033
1stFlrSF    0.031   
<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
Python

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Acknowledgements
Give credit here.
This project was inspired by learning of upgrade materials ...


## Contact
Created by Ravi Shekhar - feel free to contact me!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->