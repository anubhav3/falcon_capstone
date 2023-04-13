# Predicting successful landing of Falcon 9 Rocket

## Introduction

FALCON 9 rocket launches by SpaceX cost 62 Million USD whereas other providers cost 165 Million USD. This is because SpaceX can reuse first stage of the rocket. Therefore, investors would be interested to know if the first stage of future rocket lauches will land or not.

## Methodology

* Data collection methodology: 
  * Used SpaceX API and making a get request
  * Used Web Scraping on HTML table of Falcon 9 from the Wikipedia
* Performed data wrangling
  * Executed SQL queries on table loaded in a Db2 database
* Performed exploratory data analysis (EDA) using visualization and SQL
* Performed interactive visual analytics using Folium and Plotly Dash
* Performed predictive analysis using classification models: 
  * SVM, Classification Trees, Logistic Regression and KNN

## Results
* The launch success increased from 2013 to 2020.
* Decision tree model had the highest accuracy in predicting launch of Falcon 9 rocket’s first stage with an accuracy of 0.95 while logistic regression, KNN and SVM had accuracies of 0.833.
* Any of the above four models can be used for predicting launch success rate.
