# ByM
Pronóstico de Billetes y Monedas (ByM) en Circulación

On this repository I am trying to forecast the circulation ammount of banknotes and coins (Billetes y Monedas en Circulación). This time series is very important for the country economy, the economists suggest the cash demmand is determinyin by three principal variables:

- Growth Amount (PIB - Producto Interno Bruto)
- Inflation Rate (Tasa inflacionaria)
- Interbank Target Rate (Tasa objetivo - TIIE)

It is very common using traditional econometrics models (ARDL & ARIMAX) to forecast this amount along the time, but currently we have access to other methods and algorithms based on machine learning models, I am trying to fit three models for this time series: Kernel Ridge Regression, K-Neighboorhoods Regressor and XGBoost Regressor, I am going to evaluate the models basing on two metrics: Mean Squared Error and Mean Absolute Error, also I am plotting the proposed forecast vs original time series to show them.

The main conclutions are that the XGBoost is fitting in the correct way getting MSE = 38,674,393, that it is making sense given that there is moreless 2,000,000,000 in circulation. The error is lower compared with the circulation amount. Other models don't have such good fittings, but some other variables could give a better performance to model.
