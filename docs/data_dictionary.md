## • Data Dictionary
| features | dtype | mean value | standard deviation | min | max | description |
| :-: | :-: | :-: | :-: | :-: | :-: | :-: |
| Date | object | n/a | n/a | n/a | n/a | The date of the trading session in YYYY-MM-DD format. |
| Open | float64 | 13.1 | 17.1 | 0.0 | 72.3 | The stock price in USD at the start of the trading session. |
| High | float64 | 13.2 | 17.2 | 0.0 | 73.3 | The highest price reached during the trading day in USD. |
| Low | float64 | 13.0 | 17.0 | 0.0 | 71.9 | The lowest price recorded during the trading day in USD. |
| Close | float64 | 13.1 | 17.1 | 0.0 | 72.8 | The final stock price at market close in USD. |
| Volume | int64 | 9390436.3 | 7959269.2 | 76800.0 | 124169000.0 | The total number of shares traded on that day. |
| ticker | object | n/a | n/a | n/a | n/a | The standard ticker symbol for The Coca-Cola Company on the NYSE: 'KO'. |
| name | object | n/a | n/a | n/a | n/a | The full name of the company: 'The Coca-Cola Company'. |

## • Key Features
### Daily OHLCV Data: The dataset contains essential Open, High, Low, Close, and Volume metrics for each trading day.
### Comprehensive History: Includes data from Coca-Cola's early trading history to the present, offering a long-term perspective.
### High-Quality Data: The data is clean and sourced from a reliable financial API, ideal for direct use in analysis and modeling.
### Regular Updates: The dataset is designed for regular, automated updates to ensure data freshness for time-sensitive projects.

## • Data Collection
### The data for this dataset is collected using the yfinance Python library, which pulls information directly from the Yahoo Finance API.
