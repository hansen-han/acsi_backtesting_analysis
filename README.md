# Backtesting 
This repository hosts a collection of analyses exploring different trading strategies across various asset classes and consumer satisfaction scores. The research spans the realms of stocks, cryptocurrencies, and the correlation between American Customer Satisfaction Index (ACSI) scores and stock market returns.

## Repositories:
### 1. ```stocks```
This section is focused on understanding whether trend following and/or mean reversion strategies outperform the buy and hold strategy, particularly with the S&P 500.

**Data Source**: Hourly data for the past two years obtained using the yfinance library.  

**Strategies Tested**:
- Mean Reversion w/ Shorting
- Mean Reversion w/o Shorting
- SMA Crossover w/ Shorting
- SMA Crossover w/o Shorting
  
**Key Insights** : SMA Crossover strategies generally outperformed Mean Reversion strategies, with SMA Crossover w/ Shorting beating the S&P 500 buy and hold in over 50% of the test runs.
Detailed Analysis & Code

### 2.```bitcoin```
A deep dive into trend following and mean reversion strategies to understand their effectiveness in trading Bitcoin.

**Data Source**: 1-minute Bitcoin data from 2014 to 2019.  

**Strategies Tested**:  
- SMA Crossover
- Mean Reversion
  
**Key Insights**: While some strategy runs did outperform the buy and hold method, after incorporating fees, the majority of runs using random parameters did not. However, SMA Crossover seems to be a more favorable strategy for Bitcoin trading than Mean Reversion.  
Detailed Analysis & Code

### 3. ```consumer_satisfaction``` (ACSI Score Analysis for Investment Strategies)
This section evaluates whether high ACSI scores can be predictive of superior stock market returns.

**Data Source**: Consumer satisfaction scores from 1996 to 2021 for various companies, obtained from the ACSI website.  

**Companies Analyzed** : Out of 564 companies with ACSI scores, 318 were publicly traded, represented by 235 unique tickers.

**Key Insights**: The analysis seeks to determine any correlation between a company's ACSI scores and its stock market performance.  
Detailed Analysis & Code
