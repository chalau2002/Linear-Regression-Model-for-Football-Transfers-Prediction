Football Transfer Value Prediction using Linear Regression
This project aims to predict the monetary value of football player transfers using a linear regression model. The dataset is based on historical data from Transfermarkt, including information about players, clubs, and transfers.

Two modelling scenarios were developed:

Scenario 1: Prediction based solely on player attributes and transfer context.

Scenario 2: Prediction enriched with features related to the buying club (e.g., squad size, international players, foreigner percentage).

The workflow includes:

Data cleaning and outlier removal (to focus on realistic, non-extreme transfers)

Feature engineering and categorical encoding

Normalization of numerical variables

Model training and evaluation using MSE, RMSE and R² metrics

The results show that including club-level features significantly improves prediction performance (R² = 0.84 vs 0.53), confirming the relevance of the buying club's profile in determining transfer fees.
