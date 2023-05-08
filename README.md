# A Deep Learning Forcasting project done during Quantitative Research Internship at QTG Capital in Spring 2023 instructed by mentor Jackson Xing

Attempted ConvLSTM2D + Conv2D Deep Learning structure to forecast At-The-Money implied volatility return on Chinese 50ETF option market.

The Implied Volatility Surface is constructed by 
1. Skew calculated by 25 Delta
2. Skew calculated by 10 Delta
3. Kurtosis calculated by 25 Delta
4. Kurtosis calculated by 10 Delta
5. At-The-Money Volatility

The input data includes all the trading days' Call, Put, Strike price in between Jan 2015 and Mar 2023 with respect to three due days (This month, Next Month, Next Quarter)

The forcasting was initially done on the daily basis and later dived into hourly and minutely time frame.
