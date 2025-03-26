# Marchmania

Kaggel exercise

**Regular Matches**

Input Data:
Read M data into dataframes, join data based on Team ID's.

Dataset 1: Team x Perfromance + perfromance prediction mapping
The Basics

This section provides everything you need to build a simple prediction model and submit predictions.

Features:
Attack score
Defensive score
Home/Away Game

Data:

Team 1: Attack score | Defensive Score | Home/Away
Team 2: Attack score | Defensive Score | Home/Away

Attack score - real
defensive score - real
home/away/neutral - categorical - one hot encoding - 00, 01,10

Concatenate: team 1 | Team 2
Predict: Win/Loss  - 1/0

Dataset -> 
1. Team1 | Team2 -> 1
2. Team2 | Team1 -> 0

Note: 

EDA:

- Numerical, Categorical
- Data Normalisation/Standardisation

Risk: Data Leakage
Make sure train data and test data are from different periods
1985 - 2023
2024 -> predict
Model:

Logistic Regression


Evaluation:
RMSE
R^2
MSE
