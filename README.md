# Time-Series-Analysis-

Objective : To predict the sales of the product for the next 3 months

1. Imported the dataset
2. Visualize the Sales varible where we have found that data is not stationary by looking at it.
3. Points of analysis(POA)
Time Series is not Stationary
We Observe seasonality twice
It falls in the mid of the year.
Rises in the mid of the year.
we see that there is autocorelation in the data.
4.validated the data is not stationary by running AD Fuller Test and found p-value is greater than 0.05 so we fail to reject null hypothesis i;e Data is Non-stationary
In order to make data stationary we took first order difference.
5. After performimg the first order difference then again running the AD fuller test we found out p-value is less than 0.05 hence rejecting the null hypothesis.
6. then fitted arima and sarima model into the dataset 
7. for finding the value of the p,d,q plotted acf and pacf plot and found the appropriate value.
8. Arima model was not able to predict the sales correctly as there was seasonality present in the data
9. we fitted sarima model into the data and got near accurate predictions.

Image of actual vs predicted values
![image](https://user-images.githubusercontent.com/107911669/196172609-122f8593-1ff6-4c02-9a40-0f702dcd8b17.png)
