# InventoryForecast

Pipeline on how to forecast the demand of drugs in order to minimize costs and avoid shortages. 

## Methods

### ARIMA
The ARIMA code shows a pipeline on how to automatically estimate the model parameters for any give time series, then creates a one step ahead forecast on the demand for any given drug. 

### Moving and Exponencial Average
The code performs a SlidingWindow estimation for any given time series calculating the both the Moving and Exponiencial Averages. The result is used as an estimate for the demand on the next period for any given drug.

### Exponential Smoothing and Holt Winters Filter
The code fits the best model according to different exponencial paramenters for any given time series. The result is a one step ahead forecast on the demand for any given drug.  

### Results
This code ouputs the metrics and compares the fit of all the methods previously computed. 

