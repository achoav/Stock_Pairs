# Stock_Pairs
Basic Stock Pairs

# Get stock data from
To access current data, you can manually download the files from Yahoo Finance.
https://finance.yahoo.com/quote/FDX/history?p=FDX
I created 4 CSV files with ONE year history: FDX, UPS, COKE, PEP


# Normalize data
In order to compare moves between differently priced assets, we need to normalize the data.

According to Wikipedia,
In statistics and applications of statistics, normalization can have a range of meanings. In the simplest cases, normalization of ratings means adjusting values measured on different scales to a notionally common scale, often prior to averaging.
https://en.wikipedia.org/wiki/Normalization_(statistics)

# Plot paired stocks on same axe
Analyzed the differences

# Getting some stats - cointegration and correlation
Target when stock pairing
  * High Correlation (close to 1)
  * Low Cointegration (p value less than 0.05)
  
# Measuring separatation and spikes highlights
We simply subtract the two related and normalized series

# We still have to calculate:
  Pair - Sharpe's ratio
  Pair - VaR
  Evaluate if the strategy works - that is a tough one.....
