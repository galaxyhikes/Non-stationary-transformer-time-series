A predictive model was built to forecast the total coffee pod sales for Keurig and the entire coffee pod market. The predictive model was built in 2 phases:
1. Times series forecasting model with the use of a (non-stationary) transformer. A normal transformer was first built, then more elements of non-stationarity was introduced. The time series model uses a rolling window approach where 2 years of data was used as training to predict for the upcoming year.
2. Residuals from the time series model were then modelled using XGBoost with the use of external data, which aims to refine the prediction made with the time series model.

Due to confidentiality of original data, sample datasets are made available instead, with brand names replaced, and pod volumes randomised between 50 to 50000. 

External data was sourced directly from public sources, thus no anonymisation was done.
