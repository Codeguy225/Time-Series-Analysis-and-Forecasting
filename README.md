![image](https://github.com/Codeguy225/Time-Series-Analysis-and-Forecasting/assets/117793811/ab96d902-0f4a-4c34-9181-f3cbe88afa73)


# **Time-Series-Analysis-and-Forecasting**

## **Business Problem:**
Time series analysis comprises methods for analyzing time series data in order to extract meaningful statistics and other characteristics fo the data. Time series forecasting is the use of a model to predict future values based on previously observed values. Time series are widely used for non-stationary data, like economic, weather, stock price, and retail sales in this post. We will demonstrate different approaches for forecasting retail sales time series. Let’s get started! 

### **Data:**
There are several categories in the Superstore sales data, we start from time series analysis and forecasting for furniture salses. We have a good 4-years of furniter sales data. 

## **Methods**
The step we take are data preprocessing where we remove columns we do not need, check missing values, aggregate sales bu date and so on. Then We Visualizing Furniture Sales Time Series Data. 

## **Results**
### Model 1  
![image](https://github.com/Codeguy225/Time-Series-Analysis-and-Forecasting/assets/117793811/0c8a68d9-0dba-4c04-b7c5-b3da15cdc7e5)
Some distinguishable patterns appear when we plot the data. The time-series has seasonality pattern, such as sales are always low at the beginning of the year and high at the end of the year. There is always an upward trend within any single year with a couple of low months in the middle of the year.

Top Highlight is that we can also visualize our data using a method called time-series decomposition that allows us to decompose our time series into three distinct components: trend, seasonality, and noise.

### Model 2 
![image](https://github.com/Codeguy225/Time-Series-Analysis-and-Forecasting/assets/117793811/5ea7ecf2-3883-456a-a4cd-cbb4a5f00dbb)
The plot above clearly shows that the sales of furniture is unstable, along with its obvious seasonality.

## **Describe your final model**
Validating forecasts: To help us understand the accuracy of our forecasts, we compare predicted sales to real sales of the time series, and we set forecasts to start at 2017–01–01 to the end of the data.
![image](https://github.com/Codeguy225/Time-Series-Analysis-and-Forecasting/assets/117793811/f4336ff7-2d1a-466c-9dae-2acad32904db)
The line plot is showing the observed values compared to the rolling forecast predictions. Overall, our forecasts align with the true values very well, showing an upward trend starts from the beginning of the year and captured the seasonality toward the end of the year.

## **Model Performance**

## **Recommendations:**

## **Limitations & Next Steps**
