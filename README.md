Problem Statement
predict sales for each Store-Day level for one month.

Project Task: Week 1

Exploratory Data Analysis (EDA) and Linear Regression:

1.      Transform the variables by using data manipulation techniques like, One-Hot Encoding 
2.      Perform an EDA (Exploratory Data Analysis) to see the impact of variables over Sales.
3.      Apply Linear Regression to predict the forecast and evaluate different accuracy metrices like RMSE (Root Mean Squared Error)
         and MAE(Mean Absolute Error) and determine which metric makes more sense. Can there be a better accuracy metric?
         a)      Train a single model for all stores, using storeId as a feature.
         b)      Train separate model for each store.
         c)      Which performs better and Why?
         d)      Try Ensemble of b) and c).
        
Project Task: Week 2
Other Regression Techniques:

1. When store is closed, sales = 0. Can this insight be used for Data Cleaning? Perform this and retrain the model. Any benefits of this step?
2. Use Non-Linear Regressors like Random Forest or other Tree-based Regressors.
       a)    Train a single model for all stores, where storeId can be a feature.
       b)    Train separate models for each store.
       Note: Dimensional Reduction techniques like, PCA and Tree’s Hyperparameter Tuning will be required. Cross-validate to find the
                  best parameters. 
3 Compare the performance of Linear Model and Non-Linear Model from the previous observations. Which performs better and why?
4. Train a Time-series model on the data taking time as the only feature. This will be a store-level training.
       a)    Identify yearly trends and seasonal months
 

Project Task: Week 3

Implementing Neural Networks:

Train a LSTM on the same set of features and compare the result with traditional time-series model.

Cluster stores using sales and customer visits as features. Find out how many clusters or groups are possible. Also visualize the results.

