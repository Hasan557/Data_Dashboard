# Data_Dashboard_using_AWS

## Introduction
The purpose of this exercise is to make a Visualization Dashboard of World Population and hence making use of RESTFUL APIs (In this case, Method=GET is used). 

The exercise is conducted over AWS Platform using EC2 Instance.
### Requirements
import pandas as pd
import plotly.graph_objs as go
import json, plotly
from flask import render_template,Flask,jsonify,request
### 1. Data Preparation
This is commonly denoted as 80% of the process. From working with missing data to finding a way to work with categorical variables. Firstly, we defined a function for cleaning the 4 csv files given here. We took 'Country Name' and Years from '1990 to 2015' as our analysis period.



### 4. Modeling
Since none of our questions requires machine learning techniques, descriptive or inferential statistics are used to create a compelling answers to all questions.

### 5. Evaluation
Results are the findings from our wrangling and analysis using visualizations. These are the answers I have found to each of the questions.

1. **Trends of top 15 countries affected by COVID-19 (2019–2020):**

If we look at the top 15 countries affected most in our analysis, we would see some interesting trends. USA and countries in Europe are most affected by Covid-19. However, China, SPAIN and Germany are the ones which has most recovered cases to date till 11th April 2020. This could be seen in the graphs below.

![Top_15_Countries_(Confirmed_Cases)](https://github.com/Hasan557/Data_Science_Blog/blob/master/Pics/Top_15_Countries_(Confirmed_Cases).png)
![Top_15_Countries_(Active_Cases)](https://github.com/Hasan557/Data_Science_Blog/blob/master/Pics/Top_15_Countries_(Active_Cases).png)
![Top_15_Countries_(Deaths_Cases)](https://github.com/Hasan557/Data_Science_Blog/blob/master/Pics/Top_15_Countries_(Deaths_Cases).png)
![Top_15_Countries_(Recovered_Cases).png](https://github.com/Hasan557/Data_Science_Blog/blob/master/Pics/Top_15_Countries_(Recovered_Cases).png)

2. **Trends comparision between different cases and analyze which country has doubling of cases:**

Over the period of time, analyze which country has seen a trendline of the rise in Covid-19. It could be seen that China has the most number of confirmed cases in the 1st 7 days of the spread of the virus after which the graph shows a quadratic rise instead of a linear line. It can be seen that all countries are in the range of every second day and every 4 days. Compared to all, Japan has the slowest increase in the spread of the virus.

![Trend_Comparison_between_Countries(confirmed)](https://github.com/Hasan557/Data_Science_Blog/blob/master/Pics/Trend_Comparison_between_Countries(confirmed).png)

3. **Mortality rate curve for all Continents:**

It could be seen that Europe has the highest mortality rate and most affected by the virus i.e 8.1% of people died. Asia's death rate has the lowest variations.

![Mortality_rate](https://github.com/Hasan557/Data_Science_Blog/blob/master/Pics/Mortality%20rate.png)
