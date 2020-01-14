Project: ‘Air Quality Analysis of India’s Capital city Delhi

Problem statement:To analyse the air quality index(PM2.5) of India’s capital city given the various climatic conditions of 
the days from 2014-2018 . PM2.5 refers to atmospheric particulate matter which are known to trigger Heart and Lung Diseases 
if  its index is above 150.

Solution:Analysed various features that impact the air quality index using various techniques and achieved an accuracy of 
86% using Random Forest. The model deployed predicts the AQI for all the days in the year 2019 by analysing the data from 2014-2018 .

Language:Python (NumPy, Pandas, SkLearn, Seaborn, Matplotlib)

Demo:https://air-quality-analysis.herokuapp.com/ 

Techniques:
1.	Linear Regression
2.	Ridge & Lasso Regression
3.	Decision Trees
4.	Random Forest
5.	XGBoosting

Project Lifecycle:

Data Collection:
Created HTML files by web scrapping for my independent feature’s climate data collection from the website “tu.tiempo.com”  
Taken my dependent variable data from a third-party API “weathermap.com”. This contains hourly measurements of PM2.5

Data Preprossesing:
Performed data scrapping using Beautiful Soup and pre-processed the data to create the final dataset

Exploratory Data analysis:
Perform Feature selection and Feature Engineering using correlations, heatmaps, pairplots.
Removed Null values and improper data.
   
Model Building:
Performed Hyperparameter optimization and Model Evaluation on all the techniques above and achieved accuracy of 86% using Random Forest. After Hyperparameter tuning the error rate was lesser when compared to all other techniques used for model building.

Deployment: 
Selected Random Forest prediction model for my predictions.
Deployed on Heroku platform using Flask


