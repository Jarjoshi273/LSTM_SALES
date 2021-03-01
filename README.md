Problem Statement
predict sales for each Store-Day level for one month.
Exploratory Data Analysis (EDA) and Linear Regression:
1.      Transformed the variables by using data manipulation techniques like, One-Hot Encoding 
2.      Performed an EDA (Exploratory Data Analysis) to see the impact of variables over Sales.
3.      Applied Linear Regression to predicted the forecast and evaluated different accuracy metrices like RMSE (Root Mean Squared Error)
         and MAE(Mean Absolute Error).
         
         a)      Trained a single model for all stores, using storeId as a feature.
         b)      Trained separate model for each store.
        

1. When store is closed, sales = 0.  Performed this and retrained the model.
2. Used Non-Linear Regressors like Random Forest and Tree-based Regressors.

    Trained separate models for each store.
    (performed Dimensional Reduction techniques like, PCA and Tree’s Hyperparameter Tuning and Cross-validate to find the best parameters.) 
      


4. Trained a Time-series model based on  date and sale .

       a)    Identified yearly trends and seasonal months.
 




Implementied Neural Networks:

       a)   Trained a LSTM on the same set of features and compare the result with traditional time-series model.

       b)   Cluster stores using sales and customer visits as features. Find out how many clusters or groups are possible. Also visualized the results.

