# Demand-Forecasting
To predict the future demand for an airline firm

Future forecasting for an airline company using its past 10years dataset to predict the demand for upcoming 5 years to keep the company ready to fulfill the upcoming demand
The first main step is to check the Trend, Seasonality and Residual for given dataset using trend plots for the target variable and Seasonal_dwecompose plots for the additive model of the provide data, also making the dataset stationary using the differences.
Next testing the model using ARIMA(Auto Regression Integrated Moving Average) model for the seen 3 years of the dataset and comparing with the actual values.
Final Step is to create a 5years Dataframe month wise and merging the same with the given dataset and predicting the Target value ofr the next 5years, and comparing them using the plot function.

