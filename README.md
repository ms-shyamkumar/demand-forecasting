# demand-forecasting
Time series forecasting
This repo contains a demand forecasting model for estimating electricity demand in India based on historical data from POSOCO reports. The go to model was **fbprophet** which provides a good estimate for all regions. These estimates are useful for capacity planner to decide when to start capacity upgrades based on lead times for upgradation.
Also, **GluonTS DeepAR** model is also explored to understand how different models perform and time required to produce a reasonable forecast.

Data Source: POWER SYSTEM OPERATION CORPORATION LIMITED (https://posoco.in/reports/monthly-reports/)
