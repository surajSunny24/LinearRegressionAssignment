# Project Name : Bike sharing assignment
> A bike-sharing system is a service in which bikes are made available for shared use to individuals on a short term basis for a price or free. Many bike share systems allow people to borrow a bike from a "dock" which is usually computer-controlled wherein the user enters the payment information, and the system unlocks it. This bike can then be returned to another dock belonging to the same system

## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Files Included](#Files-Included)
* [Contact](#Contact)

## General Information
A US bike-sharing provider BoomBikes has recently suffered considerable dips in their revenues due to the ongoing Corona pandemic. The company is finding it very difficult to sustain in the current market scenario. So, it has decided to come up with a mindful business plan to be able to accelerate its revenue as soon as the ongoing lockdown comes to an end, and the economy restores to a healthy state.
  
- Objectives
    - Which variables are significant in predicting the demand for shared bikes.
    - How well the variables describe the bike demands.

- Datset being used is data fo years 2018 & 2019 with columns as season, weekdays, holidays, number of bookings etc.

## Technologies Used
- numpy
- pandas
- Matplotlib
- Seaborn
- statsmodels
- sklearn
- Jupyter Notebook

## Conclusions
- The final model, none of the coefficients are equal to zero
- The F-statistics is quite high, and P values are 0.0000 indicates that overall model is significant.
- Error terms are of normal distribution
- The VIF are all below 5, indicating multicollinearity is not a concern
- The heatmap shows no significant corellation between the variables
- Significant variables to predict the demand for bikes
    - year
    - workingday
    - temp
    - windspeed
    - season_summer
    - season_winter
    - month_sept
    - weekday_sat
    - weathersit_moderate

## Files Included
- "LinearRegression_Assignment_SurajKumar.ipynb"  Jupyter Notebook containing the analysis, code, and visualizations.
- "LinearRegression_Subjective_Questions_SurajKumar.pdf" contains detailed explanation.
- README.md: This README file providing an overview of the project.

## Contact
 - Created by [@surajkumar] 
 - feel free to contact us via suraj.sunny24@gmail.com
