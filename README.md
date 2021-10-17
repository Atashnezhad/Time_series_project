# Time series project

The goal of this repository is to develop a model for temperature prediction using both classical and modern tools for time series analysis. The classical models including Auto Regression (AR) and Auto Regression Integrated Moving Average (ARIMA) are selected for temperature modeling. The Long Short Term Memory (LSTM) is a modern tool for dealing with time series type of data and is used in this study.

The analysis began by studying whether the temperature data set is stationary or not. The data is available from the keras website example for time series and users can easily download it through url connection specified in the code P01_01_Data part of this repository.


Using the LSTM model, the user would be able to analyze the temperature time series data for any number of timestamps in the future while still considering the lags information. Also, the LSTM model or any ML algorithm is able to consider more than one-time series data at the same time for analysis, unlike the classical methods.





## AR and ARIMA modelsl - short term forcasting
<p align="center">
  <img width="2000" src="Figures/AR_GIF.gif" >
  <img width="2000" src="Figures/GIF.gif" >
</p>



<p align="center">
  <img width="2000" src="Figures/P02_01_EDA_fixing_mean_stationary_windo_[500, 2000, 5000]_T_(degC).png" >
 <img width="2000" src="Figures/P02_01_EDA_fixing_std_stationary_HIST_windo_[500, 2000, 5000]_p_(mbar).png" >
</p>


<p align="center">
  <img width="2000" src="Figures/P02_01_EDA_fixing__stdstationary_windo_[500, 2000, 5000]_T_(degC).png" >
</p>


## AR models at four different lag timesl - short term forcasting
<p align="center">
  <img width="2000" src="Figures/P03_02_AR_GIF.gif" >
</p>


AR and ARIMA models typically are well for short-term forecasting. The auto regression part of these models
converge to the mean of data for long-term forecasting.


## LSTM model - short term forcasting

<p align="center">
  <img width="2000" src="Figures/P03_02_LSTM_GIF.gif" >
</p>




