# Demand prediction for shared bikes
Build a multiple linear regression model to predict the demand for shared bikes
from historical data.


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)


## General Information
Background: This project focuses on predicting the demand for shared bikes in 
the American market for BoomBikes, a US-based bike-sharing provider. 
The company aims to prepare for post-pandemic recovery and optimize 
their business strategy accordingly.

Business Problem: BoomBikes seeks to understand the factors influencing 
bike demand post-COVID-19 lockdowns. The goal is to develop a 
predictive model that helps anticipate demand fluctuations and 
adjust operational strategies to meet customer expectations effectively.

Dataset: The dataset includes daily bike demand data across various 
American markets. It encompasses factors such as weather conditions, 
holidays, and economic indicators, which are crucial in predicting bike 
rental counts. There are 730 records in the dataset which includes
2 years of data.

## Conclusions
The linear regression model effectively explains the variance in bike rental 
demand with an adjusted R2 of 0.829. Key predictors such as year (yr), \
perceived temperature (atemp), and weather conditions significantly 
influence bike rentals. The model's robustness is supported by low 
VIF scores (all < 5), indicating minimal multicollinearity among the predictors. The residuals show no significant deviations from normality, satisfying assumptions for reliable predictions of bike demand in different scenarios.

## Technologies Used
- pandas - version 1.2.4
- matplotlib - version 3.3.4
- seaborn - version 0.11.1
- statsmodels - version 0.12.2
- scikit-learn - version 0.24.1


## Contact
Created by [@ranju1729] - feel free to contact me!
