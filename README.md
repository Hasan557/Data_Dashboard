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

![](https://github.com/Hasan557/Data_Dashboard/blob/master/Screenshots/Clean_files.png)

## Open your EC2 Instance in your terminal :-

![](https://github.com/Hasan557/Data_Dashboard/blob/master/Screenshots/AWS_Instance.png)

## Finally, run your app in your instance. Make sure all your files are in your instance.

![](https://github.com/Hasan557/Data_Dashboard/blob/master/Screenshots/run_app.png)


### 2. RESULTS

![World_Population](https://github.com/Hasan557/Data_Dashboard/blob/master/Screenshots/Ouput1.png)

![](https://github.com/Hasan557/Data_Dashboard/blob/master/Screenshots/part2.png)

### METHOD = GET

![](https://github.com/Hasan557/Data_Dashboard/blob/master/Screenshots/part3.png)
