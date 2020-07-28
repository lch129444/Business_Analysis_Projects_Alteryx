### Date created
2020-07-27

### Project Title
# Alteryx Projects

### Description
This project contains several projects using Alteryx,Tabluea, and Excel to do business analysis.  

### Projects

**Project 1.1 Use Linear Regression in Excel**
* Use Linear Regression to predict Diamond price with visualization in Excel, based upon previous data as predictor variables.  


**Project 1.2 Use Logistic Regression in Alteryx**
* Choose from several numerical and categorical predictor variables by testing linear relationship.  
* Used P-value to test statistical significance.  Used scatter plots to check trends.  
* Create a Logistic Regression model with Alteryx and justify it with Adjusted R-Square Values.  

**Project 4 Classification**
* For this binary classification project, need to classify customers into two types based upon previous data.
* Separate training set, cleaned the data(missing data imputation, outliers, low variability), check if there is highly-correlated variables; check scatterplot after imputation.
* Used Logistic Regression, Decision Tree, Forest Model and Boosted Tree Model to create models and compare them to pick the best.
* Use Alteryx to create models and compare models with validation data, like overall accuracy, confusion matrix, and ROC curve (receiver operating characteristic).

**Project 5 A/B Test a Market Dicision**
* Match treatment and control units from identifying control variables and checking the correlation between control variables and performance metric.  
* Use Alteryx to create the model and evaluate the results by check lift and significant level of T-test.

**Project 6 Forecasting Sales with Time-based Regressions**
* Decide holdout sample size based upon continuous time interval.    
* Determine Trend, Seasonal, and Error components (additive or multiplicative) using time series plots.
* Tried several ETS models with Alteryx with different p,d,q settings.  
* Tried several ARIMA models with Alteryx with different p,d,q and P, D, Q settings by plotting ACF and PACF to show the Time Series and Seasonal Difference after 1 or 2 differencing.
* Use AIC(Akaike Information Criteria) and calculated errors, like RMSE and MASE (below the generic 1.0) to compare the models and pick the better ones.
* Forecast with the models. Check the forecast error measurement against the holdout sample.  Use calculated error measurement, choose the best model and forecast the periods.  
* Graph showing 95% and 80% confidence interval.

**Project 7 Combine Segmentation(Clustering), Non-binary Classification, and Time-based forecasting**
* Use old store data to set up segmentation and use classification methods to classify new stores.  
* Decide optimal number of store formats based upon K-Means Cluster measurement like AR(Adjusted Rand Index) and CH(Calinski-Harabasz index) methods.    
* Use Alteryx to create K-Centroid Model to cluster the stores.
* Use Tableau to show the locations of clustered stores on map.
* Test Classification methods, like Decistion Tree, Forest Model and Boosted Model to classify new stores.
* Test and choose the best-fit time-based forecasting models using ETS and ARIMA algorithms.  
* Apply the best model to predict future production.  
* Use Tableau to demonstrate the historical data, existing stores forecasts and new stores forecasts.  


### Software used
* Alteryx
* Excel
* Atom
- Tableau

### Credits
* Those projects are assignments of [Udacity](https://www.udacity.com/) [Business Analyst Nanodegree Program](https://classroom.udacity.com/nanodegrees/nd008/parts/559898fe-b35d-4bb8-a9ad-eb08fb73ef50).
