# energy_price_forecast
 Deep Learning Forecast
 Created by: Roberto Medina - EDP UNGE - DSO
 Description
 The goal of this script is to serve as a tutorial on forecasting energy prices for each hour of the day-ahead Spanish market.

 Data sources:
 OMIE Mercado Diario historical data, fetched through the EDP-DSO's application TDMI. PRECO_ES, PRECO_PT, and ENERGY is available for each day and hour. A UiPath bot has been created for this step.

 Model inputs:
 DATA, HORA, PRECO_PT, PRECO_ES, ENERGY, Wind_ES, and variables engineered from averages and lags of these variables.

 Model outputs:
 PRECO_ES_1fut, for each hour of the next day.
