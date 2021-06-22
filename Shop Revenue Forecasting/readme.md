# Forecasting the Revenue of Shops for the whole of 2020
## A franchise wanted to know what their revenue would be for the whole of 2020, they had 3 shops and wanted to know that information. Their data contained revenue from 2017 up to october 2019. They wanted to make plans for the new year, in order to maximize their revenue and be more competitve in the market. The client franchise dealt with sports equipment. 
### I used ARIMA for the forecasting. Some data cleaning and preparation needed to be done, for example, some of the revenue were wrongly recorded. Initial data analysus showed that shop A made the most revenue with Shop C making the least. The data contained a lot of information, so decided to find the average revenue for each month to be used for the forecasting. Adfuler test were performed to confirm if the time series was stationary or not. After each store was filtered out and the model run. Hyperparamter tuning was done on the ARIMA, to find the pdq and the seasonality, with the mos optimized AIC chosen for each store. The data from 2019 was chosen was the test, and the results finally forecasted for the whole of 2020. Mean squared error was used to evaluate the performance of the model for each store. In depth analysis and coding can be found in the notebook named 'Shop Revenue Forecasting-FINAL'
#### Libraries used
##### pandas
##### numpy 
##### matplotlib
##### seaborn
##### statsmodel
##### sklearn
##### itertools
##### pylab

