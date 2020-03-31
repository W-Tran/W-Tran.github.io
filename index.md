[CV](https://resume.creddle.io/resume/1ojqyqemcs8) | [Github Profile](https://github.com/W-Tran) | LinkedIn

### Customer Segmentation - [link](https://github.com/W-Tran/online-Retail)

An analysis of 2 years of transaction history data from a real UK based online retailer. Both years of the dataset can be found on the UCI Machine Learning Repository ([first year](https://archive.ics.uci.edu/ml/datasets/Online+Retail+II), [second year](https://archive.ics.uci.edu/ml/datasets/Online+Retail)).

The analysis shows that highly profitable customer value groups can be identified by segmenting customers based on their first year purchasing behaviour. The highest value customer groups ended up making the largest number of high value purchases in their second year of purchasing. Attempting to segment customers into value groups based on their RFM statistics resulted in notable second year outliers which were customers identified to be low value but ended up purchasing a large amount in their second year. Using a GMM allows for a soft segmentation where customers are assigned cluster label probabilities which is useful for distinguishing between customers who are most likely to be high value. 

### London Bike Share Forecasting - [link](https://github.com/W-Tran/london-bike-share)

A time series analysis of [hourly and daily cycle shares in London](https://www.kaggle.com/hmavrodiev/london-bike-sharing-dataset) from 1/1/2015 to 1/1/2017 which examines how weather conditions influence the number of cycle shares on a daily and hourly basis. The analysis performed was adapted from and influenced by a similar analysis on [cycling counts in Auckland, New Zealand](https://cdn.rawgit.com/nicolasfauchereau/Auckland_Cycling/master/notebooks/Auckland_cycling_and_weather.html) with a few distinct differences:

- The parameters of the forecasting model were tuned to fit the London count data
- Hourly forecasts were produced on top of daily forecasts
- Daily seasonal patterns (conditional on weekday vs weekend) were used to aid the fit of the hourly forecasting model
- [Simulated historical forecasts](https://facebook.github.io/prophet/docs/diagnostics.html) were used to evaluate the models

### Uplift modelling for Direct Marketing - [link](https://github.com/W-Tran/uplift-modelling)

Who should marketers send promotional offers to in order to retain customers and increase profit? blindly contacting customers could result in the opposite intended effect [("sleeping dogs")](http://stochasticsolutions.com/pdf/CrossSell.pdf). This project follows the methodology of a [recent paper](https://journals.sagepub.com/doi/10.1509/jmr.16.0163) in order to show the effectiveness of uplift modelling on a popular [marketing dataset](https://blog.minethatdata.com/2008/03/minethatdata-e-mail-analytics-and-data.html). I use the Pylift package which implements the transformed outcome method for uplift modelling. 

### Predicting next purchase month - [link](https://github.com/W-Tran/predicting-next-purchase)
Using the same dataset and daily aggregation statistics as in the [Customer Segmentation project](https://github.com/W-Tran/online-retail), I built a ML classifier to predict whether a customer will purchase within the next month. The data was split into holdout and calibration sets, akin to time series cross validation, to avoid data leakage.

### (Kaggle) Advanced Regression Techniques - [link](https://github.com/W-Tran/advanced-regression-techniques)

A "knowledge" [Kaggle competition](https://www.kaggle.com/c/house-prices-advanced-regression-techniques) hosted to practice feature engineering and apply advanced regression models like random forests and gradient boosting. Many models were tried but the best performing model found for this data was a simple OLSR using engineered features selected using [Sequential Feature Selection](http://rasbt.github.io/mlxtend/user_guide/feature_selection/SequentialFeatureSelector/). A simple linear model was ideal as model interpretability was a priority and was discussed at length torwards the end of the project notebook.   

### (Microsoft DAT102x) Predicting Evictions - [link](https://github.com/W-Tran/DAT102x-Predicting-Evictions)

Microsoft Professional Program for Data Science [capstone project](https://datasciencecapstone.org/competitions/12/predicting-evictions/) which ended May 15, 2019. Achieved top 8% on the leaderboard (42/563) using an ensemble of regression models including Random Forests and Gradient Boosted Decision Trees.

### (Microsoft DAT264x) Identifying Malaria in Blood Imagery - [link](https://github.com/W-Tran/DAT264x-identifying-malaria)

Microsoft Professional Program for Artificial Intelligence [capstone project](https://datasciencecapstone.org/competitions/12/predicting-evictions/) which ended June 30, 2019. Achieved top 2% on the leaderboard (11/465) using a 5 model ensemble of DenseNet121s.

### (Kaggle) Home Credit Risk modelling - [link](https://github.com/W-Tran/home-credit-default-risk)

A Kaggle competition that was studied and worked through using the guidance of other community member's notebooks. Gained experience creating and aggregating data across multiple relational tables and using it to build a LightGBM classifier which scales well with the large amount of data being utilied. Also automatically tune the classifier using [HyperOpt](https://github.com/hyperopt/hyperopt).

### (Udacity) A/B testing by Google - [link](https://github.com/W-Tran/ab-testing-udacity)

My summary notes for the [A/B testing Udacity course](https://www.udacity.com/course/ab-testing--ud257) by Google.

### (Stanford) CS231n Convolutional Neural Networks for Visual Recognition (2018) - [link](https://github.com/W-Tran/CS231n-2018)

Completed assignments for the [Spring (2018)](http://cs231n.stanford.edu/2018/) semester. 

### (Microsoft DAT102x) Predicting Heart Disease Mortality

Microsoft Professional Program for Data Science [capstone project](https://datasciencecapstone.org/competitions/12/predicting-evictions/) which ended July 31, 2018. Achieved top 7% on the leaderboard (36/512).
