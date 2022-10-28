# USA-Unemployment-Prediction

## Introduction

Unemployment has been a major issue for both developing and developed countries. Here, I first perform basic data analysis on USA unemployment data to analyze the trends in the unemployment rates over the years based on education, race and, gender. I then build a linear regression model to predict the unemployment rate in a given month for a given gender (male/ female).

## About the Data:

The dataset can be found in the csv file linked with this repository. It contains monthly unemplyment rates data for eleven years(2010-2020). The rates have been recorded for different levels of education, different races and different genders.

The data is clean and has no null values. To exclude the anomaly caused due to COVID-19, I have ignored the data for the year 2020. 

Upon performing basic data analysis, it is found that the unemployment rate has decreased across all categories over the years.

## Predicting Unemployment rate based on gender

I have further taken a subset of the above data to prepare a model to predict the unemployment rate for a given gender. 

I have used Linear Regression to prepare my model, considering Date and Gender as the input attributues and the unemployment rate as the target attribute.

The R-score for the model was found to be 95%.
