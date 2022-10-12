# Shipping Price Estimate

On an e-commerce site, the shipping price can be a determining factor in deciding whether the user will complete the purchase or not. The delivery service is offered by third parties, and because its price depends on a number of factors, there will not always be tools that perform the price calculation automatically. Thus, in this situation, a model that predicts the amount of freight to be charged assertively can allow the reduction of the amounts charged and consequently help in converting purchases, generating value for the business.

Therefore, the goal of this project will be to build a machine learning model to estimate the freight price of an online order.We will work with an ecommerce public dataset. The dataset has nine tables with multiple information (about the product, seller, customer, etc) of more them 100k orders from 2016 to 2018 made at multiple marketplaces in Brazil. 

We chose to separate the project in two files to not make the notebooks extremely large.

***The first notebook ‘creating_and_treating_df’ consists of:***

+ Select the relevant infos from the database 
+ Merge everything in a single DataFrame 
+ Treat missing values 
+ Initial Feature Selection 

***The second notebook ‘shipping_price_estimate’ consists of:***

+ Feature Engineering
+ Feature Selection
+ Dealing with Outliers 
+ Establish metrics and baseline
+ Hyperparameter Tuning with grid search (XGBoost and RandomForest)
+ Model selection - evaluation between three models(XGBoost, RandomForest and Linear Regression)
+ Overfitting/Underfitting Analysis with learning curve
