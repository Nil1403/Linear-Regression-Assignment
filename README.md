# Project Name
> Build a multiple linear regression model for the prediction of demand for shared bikes


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
- Provide general information about your project here.
- BoomBikes company wants to know:
  1. Which variables are significant in predicting the demand for shared bikes.
  2. How well those variables describe the bike demands

- Business Goal:
  You are required to model the demand for shared bikes with the available independent variables. It will be used by the management to understand how exactly the demands vary with different features. They can accordingly manipulate the business strategy to meet the demand levels and meet the customer's expectations. Further, the model will be a good way for management to understand the demand dynamics of a new market.
  
- Dataset is being used is "day.csv"



## Conclusions

- FINAL RESULT COMPARISON:
	Test data r^2 : 78.32
	Train data r^2 : 80.84
	Test data adjusted r^2 : 77.5
	Train data adjusted r^2 : 80.53
	
	This seems to be a really good model that can very well 'Generalize' various datasets.

- As per our final Model, the below predictor variables influences bike booking :

	1.Temperature (temp)
	2.September Month
	3.Year -2019
	4.Summer Seaon
	5.Winter Seson
	6.If its a holiday
	7.If the weather is clear/Good
	8.Speed of the Wind


## Technologies Used
- import numpy as np
- import pandas as pd
- import warnings
- import matplotlib.pyplot as plt
- import seaborn as sns
- import sklearn
- import statsmodels.api as sm
- from sklearn.model_selection import train_test_split
