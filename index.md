[CV](https://resume.creddle.io/resume/1ojqyqemcs8) | [Github Profile](https://github.com/W-Tran) | LinkedIn

### London Bike Share Forecasting - [link](https://github.com/W-Tran/london-bike-share)

A time series analysis of [hourly and daily cycle shares in London](https://www.kaggle.com/hmavrodiev/london-bike-sharing-dataset) from 1/1/2015 to 1/1/2017 which examines how weather conditions influence the number of cycle shares on a daily and hourly basis. The analysis performed was adapted from and influenced by a similar analysis on [cycling counts in Auckland, New Zealand](https://cdn.rawgit.com/nicolasfauchereau/Auckland_Cycling/master/notebooks/Auckland_cycling_and_weather.html) with a few distinct differences:

- The parameters of the forecasting model were tuned to fit the London count data
- Hourly forecasts were produced on top of daily forecasts
- Daily seasonal patterns (conditional on weekday vs weekend) were used to aid the fit of the hourly forecasting model
- [Simulated historical forecasts](https://facebook.github.io/prophet/docs/diagnostics.html) were used to evaluate the models

### Customer Segmentation - [link](https://github.com/W-Tran/online-Retail)

An analysis of two [E-commerce](https://archive.ics.uci.edu/ml/datasets/Online+Retail+II) [datasets](https://archive.ics.uci.edu/ml/datasets/online+retail) which consists of 2 year customer transaction histories for a UK based non-store online retail. I compared the performance of clustering customers based on their 1st year transaction histories using RFM features to clustering on simple monetary aggregation features by evaluating how well they segment 2nd year customers into value groups.

### Predicting next purchase month - [link](https://github.com/W-Tran/predicting-next-purchase)
Using the same online retail data set, I produced a classification model to predict whether a customer will purchase within the next month. The model is trained using the previous L (lag) month's transactions as labels whilst RFM, temporal, and monetary aggregation features were used to train the model in order to predict whether a customer will purchase within the next month.

### Uplift modelling for Direct Marketing - [link](https://github.com/W-Tran/uplift-modelling)

Who should marketers send promotional offers to in order to retain customers and increase profit? blindly contacting customers could result in the opposite intended effect due to ["sleeping dogs"](http://stochasticsolutions.com/pdf/CrossSell.pdf). This project follows the methodology of a [recent paper](https://journals.sagepub.com/doi/10.1509/jmr.16.0163) in order to show the effectiveness of uplift modelling on a popular [marketing dataset](https://blog.minethatdata.com/2008/03/minethatdata-e-mail-analytics-and-data.html). 

### (Kaggle) Advanced Regression Techniques - [link](https://github.com/W-Tran/advanced-regression-techniques)

A "knowledge" [Kaggle competition](https://www.kaggle.com/c/house-prices-advanced-regression-techniques) hosted to practice feature engineering and apply advanced regression models like random forests and gradient boosting. Many models were tried but the best performing model found in this project was a simple OLSR using engineered features selected using [Sequential Feature Selection](http://rasbt.github.io/mlxtend/user_guide/feature_selection/SequentialFeatureSelector/). A simple linear model was ideal as model interpretability was a priority and was discussed at length torwards the end of the project.   

### (Microsoft DAT102x) Predicting Evictions - [link](https://github.com/W-Tran/DAT102x-Predicting-Evictions)

Microsoft Professional Program for Data Science [capstone project](https://datasciencecapstone.org/competitions/12/predicting-evictions/) which ended May 15, 2019. Achieved top 8% on the leaderboard (42/563) using an ensemble of regression models including Random Forests and Gradient Boosted Decision Trees.

### (Microsoft DAT264x) Identifying Malaria in Blood Imagery - [link](https://github.com/W-Tran/DAT264x-identifying-malaria)

Microsoft Professional Program for Artificial Intelligence [capstone project](https://datasciencecapstone.org/competitions/12/predicting-evictions/) which ended June 30, 2019. Achieved top 2% on the leaderboard (11/465) using a 5 model ensemble of DenseNet121s.

### (Kaggle) Home Credit Risk modelling - [link](https://github.com/W-Tran/home-credit-default-risk)

A Kaggle competition that was studied and worked through using the guidance of other community member's notebooks. Gained experience with creating and aggregating relational data across multiple tables to build and automatically tune a LightGBM classifier.

### (Udacity) A/B testing by Google - [link](https://github.com/W-Tran/ab-testing-udacity)

My summary notes for the [A/B testing Udacity course](https://www.udacity.com/course/ab-testing--ud257) by Google.

### (Stanford) CS231n Convolutional Neural Networks for Visual Recognition (2018) - [link](https://github.com/W-Tran/CS231n-2018)

Completed assignments for the [Spring (2018)](http://cs231n.stanford.edu/2018/) semester. 

### (Microsoft DAT102x) Predicting Heart Disease Mortality

Microsoft Professional Program for Data Science [capstone project](https://datasciencecapstone.org/competitions/12/predicting-evictions/) which ended July 31, 2018. Achieved top 7% on the leaderboard (36/512).
