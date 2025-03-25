# Marchmania

Kaggel exercise

Input Data:
Read M data into dataframes, join data based on Team ID's.

Dataset 1: Team x Perfromance + perfromance prediction mapping
The Basics

This section provides everything you need to build a simple prediction model and submit predictions.

Data Section 2 - Team Box Scores

This section provides game-by-game stats at a team level (free throws attempted, defensive rebounds, turnovers, etc.) for all regular season, conference tournament, and NCAA® tournament games since the 2003 season (men) or since the 2010 season (women).

Data Section 3 - Geography

This section provides city locations of all regular season, conference tournament, and NCAA® tournament games since the 2010 season

Data Section 4 - Public Rankings

This section provides weekly team rankings (men's teams only) for dozens of top rating systems - Pomeroy, Sagarin, RPI, ESPN, etc., since the 2003 season

Data Section 5 - Supplements

This section contains additional supporting information, including coaches, conference affiliations, alternative team name spellings, bracket structure, and game results for NIT and other postseason tournaments.

Regression to Classfication Problem?
Regress on scores -> predict with classification

EDA:

- Understand underlying data
- Think out possible features
- Numerical, Categorical
- Treat Missing data
- Data Normalisation/Standardisation

Model:

Linear Regression - Baseline
XGBoost Regression - Challengers
Tree based Regression

Feedback Loop => Important features => Improve hyperparameters

Evaluation:
RMSE
R^2
MSE
