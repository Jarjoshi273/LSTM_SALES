Problem Statement
predict sales for each Store-Day level for one month.

Project Task: Week 1

Exploratory Data Analysis (EDA) and Linear Regression:
1.      Transformed the variables by using data manipulation techniques like, One-Hot Encoding 
2.      Performed an EDA (Exploratory Data Analysis) to see the impact of variables over Sales.
3.      Applied Linear Regression to predicted the forecast and evaluated different accuracy metrices like RMSE (Root Mean Squared Error)
         and MAE(Mean Absolute Error).
         
         a)      Trained a single model for all stores, using storeId as a feature.
         b)      Trained separate model for each store.
         c)      Tried Ensemble of b) and c).
        

Project Task: Week 2
Other Regression Techniques:

1. When store is closed, sales = 0.  Performed this and retrained the model.
2. Used Non-Linear Regressors like Random Forest and Tree-based Regressors.
a)    Trained a single model for all stores, where storeId can be a feature.
b)    Trained separate models for each store.
      (performed Dimensional Reduction techniques like, PCA and Tree’s Hyperparameter Tuning and Cross-validate to find the best parameters.) 
      
3 Compared the performance of Linear Model and Non-Linear Model from the previous observations.

4. Trained a Time-series model on the data taking time as the only feature. This was a store-level training.
a)    Identified yearly trends and seasonal months.
 

Project Task: Week 3

Implementied Neural Networks:

Trained a LSTM on the same set of features and compare the result with traditional time-series model.

Cluster stores using sales and customer visits as features. Find out how many clusters or groups are possible. Also visualized the results.

