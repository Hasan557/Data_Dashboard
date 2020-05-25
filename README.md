# Data_Dashboard_using_AWS

## Introduction
A data dashboard is an information management tool that visually tracks, analyzes and displays key performance indicators (KPI), metrics and key data points to monitor the health of a business, department or specific process. They are customizable to meet the specific needs of a department and company. Behind the scenes, a dashboard connects to your files, attachments, services and API’s, but on the surface displays all this data in the form of tables, line charts, bar charts and gauges. A data dashboard is the most efficient way to track multiple data sources because it provides a central location for businesses to monitor and analyze performance. Real-time monitoring reduces the hours of analyzing and long line of communication that previously challenged businesses.

## Purpose
The purpose of this exercise is to make a Visualization Dashboard of World Population and hence making use of RESTFUL APIs (To know more about Restful APIs [here](https://pusher.com/tutorials/understanding-rest-api)).The exercise is conducted over AWS Platform using EC2 Micro Instance.

### 1. Data Preparation
This is commonly denoted as 80% of the process. From working with missing data to finding a way to work with categorical variables. Firstly, we defined a function for cleaning the 4 csv files. We took 'Country Name' and Years from '1990 to 2015' as our analysis period.

![](https://github.com/Hasan557/Data_Dashboard/blob/master/Screenshots/Clean_files.png)

### Open your EC2 Instance in your terminal :-

![](https://github.com/Hasan557/Data_Dashboard/blob/master/Screenshots/AWS_Instance.png)

### Finally, run your app in your instance. Make sure all your files are in your instance.

![](https://github.com/Hasan557/Data_Dashboard/blob/master/Screenshots/run_app.png)


### 2. RESULTS

![World_Population](https://github.com/Hasan557/Data_Dashboard/blob/master/Screenshots/Ouput1.png)

![](https://github.com/Hasan557/Data_Dashboard/blob/master/Screenshots/part2.png)

### METHOD = GET

![](https://github.com/Hasan557/Data_Dashboard/blob/master/Screenshots/part3.png)

### Requirements
pandas,plotly.graph_objs,json, plotly,flask.
