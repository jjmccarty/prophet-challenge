# prophet-challenge
AI Bootcamp Module 8 challenge

## Overview
As part of the module 8 exercise we are asked to find unusal patterns in google search traffic for a company called Mercado Libre.  Once patterns are identified we are looking for seasonality in search traffic data and are evaluating if the search traffic has any relationship to stock price patterns for the company. 


## Step 1 - Analysizing traffic for unusual patterns
In step one we are reading provided search data into a dataframe then evaluating as follows:
1. Locate data isolated the month of May (2020-05-01 to 2020-05-31)
2. The search data is plotted by date to determine if a pattern exists
3. Data is evaluated against the median for all months and evaluating to determine if a pattern exists for search data vs. finanical results release.


## Step 2 - Evaluate traffic for seasonality
In step two we are evaluating data for seasonality. 
1. Data is grouped by the hour of the day for the search traffic and plotted to identify any patterns. 
2. Data is further grouped by the day of the week .
3. Data is further grouped by the week of the year.
4. Trends are evaluated for all three groupings. 

## Step 3 - Related traffic to stock patterns
Our third task is to evaluate if search traffic has any impact or relationship to stock price. 
1. First we will concatenate the data for search traffic and stock price into a single dataframe
2. Data to research will inlude data only from the first half of 2020 (2020-01 through 2020-06) and be plotted for visualization
3. Next we will evaluate lagged search trends since the search trend by one hour 
4. Two addition columns for Stock Volatility and Hourly Stock Return will be created in the dataframe
5. Data is evaluated to determine if there is a pattern between the stock data and search terms. 


## Step 4 - Create a time series model
Our final step is to set up a forecast for the search trend data utilizing Prophet. 

This data is plotted and time series information is pushed for the componenets of the model to determine if a relationship exists. 