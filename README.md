# 311_sentiment_analysis
Machine Learning for Cities spring 2023 final project. Conducting sentiment analysis on NYC 311 calls &amp; inquiries and predicting via decision trees


# Description:

This project aims to create a metric to measure the severity of 311 calls and service requests in New York City Census Tracts using sentiment analysis. We then aim to predict the severity of 311 calls and requests using socio-economic, racial & ethnic, and urban infrastructure regressors via decision trees and potentially Random Forest Regression. We hypothesize that census tracts with lower incomes and higher minority populations will log calls and requests with higher severity compared to tracts with higher income and predominantly white populations. 

# Methodology:

**Step 1:** Create the severity index via sentiment analysis of 311 complaint logs

* First, we will attempt to create metric using NLTK built-in sentiment analysis VADAR

* If this does not output sufficient results, we will build a custom sentiment analysis using 311 complaint descriptions

**Step 2:** Cluster sentiment analysis outputs to visualize the spatial distribution of the severity metric across neighborhoods in New York City.

**Step 3:** Obtain regressors from supplemental datasets, such as U.S. Census Bureau and American Community Survey. Regressors include:
  
* Racial & Ethnic Population Density

* Income

* Poverty Rate

* Educational Attainment

* Road Density (per area)


**Step 4:** Build a decision tree to predict 311 severity using the above regressors.

# Data: 

* [311 Call Center Inquiries](https://data.cityofnewyork.us/City-Government/311-Call-Center-Inquiry/wewp-mm3p)

* [311 Web Content](https://data.cityofnewyork.us/dataset/311-Web-Content-Services/vwpc-kje2)

* [All 311 Complaints (w/ coordinates)](https://data.cityofnewyork.us/Social-Services/311-Service-Requests-from-2010-to-Present/erm2-nwe9)

# Collaborators:

* Ananya Rajesh: ananyarajesh

* Ahmad Nasrieh: ahmadnasrieh

* Claire Chen: CC-ClaireChen
