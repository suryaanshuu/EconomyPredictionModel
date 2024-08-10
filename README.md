# Economy Prediction: Forecasting Inflation (Consumer Price Index) using LSTM (Long Short-Term Memory)

## Crux of the Research
* This repository contains the code for the Machine Learning & Deep Learning-based Economy Inflation Prediction Model. The main parameter considered for measuring inflation is CPI (Consumer Price Index).
* For reference, if CPI '24 = x and CPI '25 = y, then Inflation Rate from 2024-2025 = [(x-y)/x]*100.
* The project is developed using algorithms like Linear Regression, K-Nearest Neighbour and LSTM (Long Short-Term Memory) with each depicting certain accuracy in diverse conditions.
* Various methods have been applied in the LSTM-based model: Manual Analysis | Stop-loss | Keras Tuner | Weighted Average Ensembling - Among these, Manual Analysis proved to give the best result.
* For more information on the model, refer to the Research Paper.

## Data Sources
* CPI:  https://www.bls.gov/cpi/data.htm
* BIE:  https://www.atlantafed.org/research/inflationproject/bie.aspx
* Oil Prices:  https://tradingeconomics.com/commodity/crude-oil
* PPI:  https://fred.stlouisfed.org/series/PPIACO
* NEER:  https://fred.stlouisfed.org/series/NBUSBIS
* US Unemployment Data:  https://www.kaggle.com/datasets/axeltorbenson/unemployment-data-19482021
