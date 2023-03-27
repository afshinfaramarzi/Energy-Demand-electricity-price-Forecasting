# Energy-Demand_electricity_price-Forecasting

## Project and data set explanations:

This project deals with a time series forecasting problem where two distinct datasets of energy and weather data are used. The energy consumption and weather data from various cities in Spain are combined to create a multivariate time series forecasting problem. The energy dataset contains features related to the generation of energy from different sources like fossil fuels, wind, and coal. On the other hand, the weather dataset contains features related to various weather metrics such as temperature, humidity, pressure, wind speed, etc.

The dataset includes a four-year record of weather data <a href="https://openweathermap.org/api">https://openweathermap.org/api</a> 
electrical consumption, pricing, and generation data for Spain <a href="https://transparency.entsoe.eu/dashboard/show">ENTOSE website</a> . The public ENTSOE portal was used to retrieve the consumption and generation data, while 
the Spanish TSO Red Electric España was used to obtain the settlement prices <a href="https://www.esios.ree.es/en/market-and-prices?date=27-03-2023#">TSO website</a>. 

## Inspiration:

This dataset is noteworthy for its hourly data on electrical consumption, and the corresponding forecasts by the TSO 
for consumption and pricing, making it possible to compare prospective forecasts to the current state-of-the-art 
industry forecasts.

The following questions may be explored using this dataset:

* How do the load and marginal supply curves appear? 
* What weather measurements and cities have the most significant influence on electrical demand, prices, and generation capacity?
* Can we improve upon the TSO's 24-hour advance forecast? 
* Can we predict the electrical price by the time of day better than the TSO?
* Can we forecast intraday price or electrical demand hour-by-hour?

## Methods used in this project : 

#### 1. Machine learning : 
 * XGboost Regressor
#### 2. Deep learning/Stacked models :
* GRU 
* LSTM 
* CNN 
* CNN-LSTM 
* LSTM-Attention 
#### 3. Hybrid methods:   
* GRU-XGBoost 
* LSTM-Attention-XGBoost 
 
 
