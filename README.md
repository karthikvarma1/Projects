# COMP 6200 Data Science Project

## Group : Group K 
## Group Members : Karthik Varma Keerthipati
##                                Utkash  Nandakumaran Menon     
##                                Bilal Qureshi
##                                Muhammad Bilal Arif
# Project Title : Analysis on the impact of lockdown on the air quality.

## Introduction:

Our lives, as we probably are aware,have grounded to a halt in the course of the most recent few months. The pandemic has diminished the greater part of our exercises and constrained us inside our own homes. While the entire circumstance, right now, appears to be somewhat depressing, but, all isn't lost. It has been ascertained that the absence of human collaboration with the outside world has prompted a positive effect on the earth. There have been reports of bluer skies, blossoming greenery and animals returning back to their natural surroundings.

### 1. INTRODUCING THE DATASET:

- Data extraction from relevant data sources [Dataset](https://discomap.eea.europa.eu/Index//)
- Merging all csv files into a single csv file using python code and file is named as Combined Data.ipynb
- Defining variables Country, PM10, NO2, PM2.5, datebegin.

### VISUALIZATION OF DATASET:

- Prelockdown : NO2, PM2.5, PM10 graphs
- Postlockdown : NO2, PM2.5, PM10 graphs
- Timeline Graphs
- Correlations Matrices
- Heatmaps

### BUILDING MODELS:

- Multiple Linear Regression Analysis
- with combined features
- with indiviual features
- ARIMA model

### MODEL PREDICTIONS:

- Model Accuracy Scores (both Pre and Post Lockdowns)
- Air Quality Level Predictions

### CONCLUSION:

To conclude, we have performed Multiple Linear Regression on the particulate matter(y variable) and days(x variable) for any particular country(unique value) and results given have a significant accuracy for both pre lock down models and post lock down models. The ARIMA model is also peformed to forecast the future values. We can say that the data is stationary by conducting the Augmented Dickey Fuller test. The model is fitting good for the predicted values. 
