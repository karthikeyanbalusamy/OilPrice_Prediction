# OilPrice Prediction
The goal of this repo is to build a model to predict the Oil price using Linear Regression.

Oil price in the international market fluctuates everyday. Many industry that rely on oil as input. Certainly, this model helps the downstream companies to predict the oil price and invest accordingly.

# DataSource
Europe Brent and WTI (Western Texas Intermediate) Spot Prices (Annual/ Monthly/ Weekly/ Daily) from EIA U.S. (Energy Information Administration). This series is available through the EIA open data API
Europe Brent Spot Price FOB (Dollars per Barrel) - From 20 May 1987 till today. However, I have considered 2019 data till April. Primarily, excel data has "Date" & "Price" (Daily).
https://www.eia.gov/dnav/pet/hist/RBRTEd.htm



# Data Profiling
While doing the analysis, noticed that the data does not have any null values and found to be valid. 
However, always been a challenge especially when plotting the date series. It requires series of conversions, which helps to plot the data.

1. Set the index to Date field
2. Convert Index to a DateTimeIndex
3. Convert DateTiemIndex to Day elapsed
4. Plot the Time series data

# Split Data - Train & Test
