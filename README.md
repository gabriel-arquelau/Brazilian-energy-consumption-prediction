The files contain the predicted Brazilian energy consumption (MWh) values up to November 2033, using four different time series models. 

The forecasting models used are SARIMA, FB Prophet, Holt Winters and TBATS, in the conditions explained in the paper below. 


We gently ask you to please cite the paper in case this data is used.

The number of months mentioned in the filename is the size of the training window. The models are also trained with a smoothed version (alpha = 0.3) of the energy consumption historic data.

For the FB Prophet file, the 'yhat' column gives the predicted values, while 'yhat_upper' and 'yhat_lower' inform the upper and lower limits of the forecasting, respectively. The file for the other models contain a single column, which refers to the predicted values.

