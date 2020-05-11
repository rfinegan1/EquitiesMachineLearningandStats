# EquitiesMachineLearningandStats
Simple Machine Learning and RSI Stochastic Algorithms for individual investing

^EquitiesMachineLearningandStats
The first cell is just to vizualize if the equity has been somewhat linear throughout 15 years.
The second cell is two functions to predict stock prices using sklearn and linear regression. 
The third cell is for calculating RSI. I used one to calculate RSI the normal way, and then in the 
myRSI function I did some things different by measuring the returns instead of just if the 
stock experienced a positive or negative daily return. In the fourth cell is the RSI Stochastic 
Oscillator which I use for my stock trading now. It's pretty cool to see how the stock goes from 
overbought to oversold in an oscillating manner. The last cell is using keras and sklearn to 
predict the next days stock price. I am still experimenting with that one and will update shortly. 

^indexarb
Conclusions to Binary dataset whether a stock/index would have a positive return in a single day.
SPY would be up 80% of the time if ^N100,^STOXX, and IMOEX.ME is up.
SPY would be up 79% of the time if ^N100 and IMOEX.ME is up.
SPY would be up 73% of the time if ^N100 is up.
SPY would be up 74% of the time if ^N100 and ^STOXX are up.
QQQ would be up 76% of the time when ^N100,^STOXX, and IMOEX.ME are up.
QQQ is up up 72% of the time when ^N100 is up.
QQQ would be up 74% of the time when ^N100 and ^STOXX are up.
XLK is up 75% of the time when ^N100,IMOEX.ME and ^STOXX are up.
XLK is up 70.74% of the time when ^N100 is up.
XLK is up 71% of the time when ^N100 and ^STOXX are up.
T-Mobile: Is up 76.59% of the time when their equity in Tokyo was up.
