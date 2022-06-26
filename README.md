# Freight Price Estimate
The goal of this project will be to build a machine learning model to estimate the freight price of an online order. 

We will work with an ecommerce public dataset. The dataset has nine tables with multiple information (about the product, seller, customer, etc) of more them 100k orders from 2016 to 2018 made at multiple marketplaces in Brazil. 

We chose to separate the project in two files to not make the notebooks extremely large.

The first notebook ‘creating_and_treating_df’ consists of:

+ Select the relevant infos from the database 
+ Merge everything in a single DataFrame 
+ Treat missing values 
+ Initial Feature Selection 

The second notebook ‘freight_price_estimate’ consists of:

+ Feature Engineering
+ Feature Selection and Dealing with Outliers 
+ Establish metrics and baseline
+ Build and evaluate two models (XGBoost and RandomForest)
+ Parameter Tuning
