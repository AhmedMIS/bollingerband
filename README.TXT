Main Functions
###############

simpleMovingAverage: It takes two input one is window which is 20 in our case and the other is the list of prices of stocks.
It sliced the whole data in form of sliding window of 20, then dividing by average to form new data for simpleMovingAverage.

standardDeviation: It calculate the stock prices for the 20 days and calculate mean, variance and standardDeviation. 

upparBand: It take 3 argument stock prices, moving average (for 20 days window), standardDeviation (for 20 days respective stock prices). It adds the average +(standardDeviation).
Then combines with the dates for display with respective to dates.

lowerBand: It take 3 argument stock prices, moving average (for 20 days window), standardDeviation (for 20 days respective stock prices). It subtract the average - (standardDeviation).
Then combines with the dates for display with respective to dates.

Small Methods like map, reduce are used in the es6 format.
