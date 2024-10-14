The files contain the predicted Brazilian energy consumption (MWh) values up to November 2033, using four different time series models. 

The forecasting models used are SARIMA, FB Prophet, Holt Winters and TBATS, in the conditions explained in the paper below. 

The number of months mentioned in the filename is the size of the training window. The models are also trained with a smoothed version (alpha = 0.3) of the energy consumption historic data.

For the FB Prophet file, the 'yhat' column gives the predicted values, while 'yhat_upper' and 'yhat_lower' inform the upper and lower limits of the forecasting, respectively. The file for the other models contain a single column, which refers to the predicted values.

We gently ask you to please cite the paper below in case this data is used:

Serrano, André Luiz Marques, et al. "Statistical Comparison of Time Series Models for Forecasting Brazilian Monthly Energy Demand Using Economic, Industrial, and Climatic Exogenous Variables." Applied Sciences 14.13 (2024): 5846. https://doi.org/10.3390/app14135846

