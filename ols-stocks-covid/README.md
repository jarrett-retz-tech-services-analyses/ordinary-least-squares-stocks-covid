<h1 align="center">Ordinary Least Squares Regression: U.S COVID-19 Deaths, Cases, and US Equities</h1>

## Abstraction

The analysis looked to evaluate the variation in equity prices based on COVID-19 based predictors from April-September 2020. Data was gathered from online resources and then normalized, visualized, and analyzed with the Python programming language in a Jupyter Notebook.

During analysis, an ordinary least squares linear regression model explained 55.7% (Adj. R-squared) of the variation in the Boeing (BA) equity price using the 7-day rolling average for U.S COVID-19 deaths. This predictor was found to be statistically signficant with a p-value close to zero. 

## Introduction

Halfway through the year I wanted to relearn basic statistics and set a goal to perform an ANOVA on data (and write about it). Furthermore, I wanted to use Python to perform this analysis. 

There are a few reasons why I chose to examine the data that I did:
 - COVID-19 data is readily available
 - U.S equity prices are readily available
 - The COVID-19 pandemic has had a significant impact on many U.S equity prices
 
I hypothesized that I would find some sort of relationship between price and reported COVID-19 cases. The structure of an the analysis was relaxed, however, at the end I knew that I wanted to perform an ordinary least squares regression analysis and interpret the results. 

Initially, I thought that I could simply find a relationship between S&P500 daily returns and reported COVID-19 cases.

By the end, I was using the seven-day daily reported death rate to predict the variation in Boeing (BA) price, which is more reactive to the pandemic than the SPDR S&P 500 ETF Trust (SPY). 
