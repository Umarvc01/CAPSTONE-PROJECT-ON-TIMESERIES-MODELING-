# CAPSTONE-PROJECT-ON-TIMESERIES-MODELING-
FORECASTING SALES ON TRUCK FOR THE NEXT FOUR YEARS 
Objective: Forecast monthly truck sales using time series modeling (SARIMA) after performing full exploratory data analysis and preprocessing.
The data set used is Truck Data yearly sales; source: https://www.kaggle.com/datasets/ddosad/dummy-truck-sales-for-time-series
Dataset Overview
We examine the structure of the dataset including: 
preview of the dataset
rows and columns
data types
memory usage
basic statistics of the dataset
RESULT AND CONCLUSION
The Mean Absolute Error (MAE) of approximately 21.46 indicates that, on average, the forecasted values deviate from the actual observations by about 21 units. Considering the scale of the data, this level of deviation is relatively small and suggests that the model provides reasonably accurate predictions.
The Root Mean Squared Error (RMSE) value of 25.96 measures the square root of the average squared differences between predicted and observed values. Since RMSE penalizes larger errors more heavily than MAE, the relatively close values of MAE and RMSE suggest that the model does not produce large forecasting errors or extreme deviations.
The Root Mean Square (RMS) value is identical to the RMSE in this case, confirming the consistency of the residual-based error calculations.
The Mean Absolute Percentage Error (MAPE) is 3.30%, which indicates that the model's predictions differ from the actual values by an average of only 3.3%. In time series forecasting, a MAPE value below 10% is generally considered to represent excellent forecasting performance. Therefore, the SARIMA model demonstrates strong predictive accuracy
CONCLUSION
This study applied a Seasonal Autoregressive Integrated Moving Average (SARIMA) model to analyze and forecast the time series data. The model was fitted after examining the trend and seasonal patterns present in the dataset and selecting appropriate parameters.
The evaluation results show that the model performs well in capturing the underlying structure of the data. The relatively low MAE and RMSE values indicate that the forecast errors are small and stable. Additionally, the very low MAPE value of 3.30% suggests that the model provides highly accurate predictions relative to the magnitude of the observed data.
Overall, the SARIMA model proves to be an effective tool for forecasting the given time series. The results demonstrate that the model can reliably predict future values with a high degree of accuracy, making it suitable for forecasting and decision-making purposes based on the analyzed dataset.
