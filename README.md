# House prices Regression Project
Estimation of the house price values based on houses' parameters and locations (regression model)

# Content
-->Data analysis, visualization and preparation;
-->Models Building and Tuning;
-->Cross-validation scores:
    -ElasticNet Model
    -Ridge Regression
    -Linear Regression
    -Voting Regressor
    -Random Forest Regressor
    -Boosting Regressor


# Steps
-->Upload the Housing_Regression.csv and read the data;
-->Investigate the dataset and make the visualisation;
-->Pprepare the data;
-->Build the regression models and make models' tuning;
-->Create an ensemble using VotingRegressor;
-->Use RandomForestRegressor and tune it;
-->Use Gradient Boosting Regressor (or AdaBoostRegressor) and tune it.


# Conclusion
-->ElasticNet, LinearRegression, Ridge have been choosen for review which had showed the best results after tuning;
-->VotingRegressor didn't improove result;
-->R2 scores of the RandomForestRegressor after tuning were increased to 71,7% for test and 76,5%; 
-->R2 scores of the GradientBoostingRegressor after tuning gave the best result (about 76,6% for test and 82,3% for training).
