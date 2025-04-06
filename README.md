# Football Transfer Value Prediction using Linear Regression

This project aims to predict the monetary value of football player transfers using a linear regression model. The dataset is based on historical data from [Transfermarkt](https://www.transfermarkt.com/), including information about players, clubs, and transfers.

## Project Description

Two modelling scenarios were developed:

- **Scenario 1**: Prediction based solely on player attributes and basic transfer context.
- **Scenario 2**: Prediction enriched with features related to the buying club (e.g., squad size, international players, foreigner percentage).

The main steps in the pipeline include:

- ✅ Data cleaning and outlier removal  
- ✅ Feature engineering and categorical encoding with OneHotEncoder  
- ✅ Normalization of numerical variables using MinMaxScaler  
- ✅ Train/test split and model training  
- ✅ Evaluation using MSE, RMSE, and R² metrics

## Results

| Scenario         | RMSE (€)    | R² Score |
|------------------|------------:|---------:|
| Without Clubs     | ~7.79M      | 0.5358   |
| With Clubs        | **~4.29M**  | **0.8414** |

The results demonstrate that including club-level features significantly improves predictive performance, confirming that the profile of the buying club plays a major role in determining transfer fees.

## Dataset

- Source: [Kaggle - Transfermarkt Data](https://www.kaggle.com/datasets/davidcariboo/player-scores)
- Datasets used: `players.csv`, `clubs.csv`, `transfers.csv`


