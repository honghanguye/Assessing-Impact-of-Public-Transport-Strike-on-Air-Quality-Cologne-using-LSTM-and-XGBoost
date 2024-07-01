# Assessing-Impact-of-Public-Transport-Strike-on-Air-Quality-Cologne-using-LSTM-and-XGBoost

# Introduction

This project utilised LSTM and XGBoost to assess the impact of a public transport strike on air quality in Cologne, Germany.


# Data
The data was obtained from (https://www.umweltbundesamt.de/daten/luft/luftdaten/luftqualitaet/) and . The data was collected from 2022-2024 and included air quality data, weather data, and public transport strike data.

# Method
XGBoost (non-parametric decision tree ensemble method) and LSTM (Long Short-Term Memory) were used to model the business-as-usual scenerio (the normal condition had the strikes not occured).The Python package skforecast was used to simplify the model configuration and training process.

# Evaluation
The models were evaluated using MSE (Mean Squared Error),  MAE (Mean Absolute Error), and R2 metrics. The models which performed the best were then used to predict the air quality in Cologne during the strike period. The predictions were then compared to the actual air quality data during the strike period. The assessments were mean differences and mean percentage differences.


