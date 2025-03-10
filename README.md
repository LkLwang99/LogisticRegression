# LogisticRegression


## Introduction 
This is an independent Project to find out more about logistic regression and the uses of logistic regression in identifying potential high earning companies in the stocks listed. The aims of the project is to find out more about logistic regression model and compare the accuracy when using logistic regression to identify between two classes and three classes.
## Aims
The aim of the project is to achieve the following:
-Gathering Data through webscraping
-Creating visualizations to identify key patterns
-Creating different classes to separate the categories of companies
-Creating a baseline model and gather the results of the evaluation metrics
-Creating a logistic regression that performs better than the baseline model
-hypertuning the parameters of the logistic regression model
-Compare between two classes and three classes' results for the model.


## Data Preparation
The data is webscraped from the first 500 companies from stockanalysis.com through utilizing the SELENIUM library and pandas library to create a dataframe in pandas dataframe. The data is then cleaned and transformed with these methodologies.
1) The data is cleaned by removing unnecessary words and transforming the numbers in the numerical columns into integers and float
2) Creating a new column in the dataframe where we create a financial ratio of market cap to revenue and use this ratio to define which companies is defined as a high earning company.
3) 
