# Stock Risk Report

A Python tool that pulls live market data for any ticker and produces a complete risk report — metrics, a returns chart, and a formatted Excel workbook.

## What It Does

- Pulls historical price data from Yahoo Finance
- Calculates daily returns, volatility, and performance metrics
- Generates a returns chart with volatility bands
- Exports everything to Excel with the chart embedded

## Metrics Calculated

- Annualized volatility
- Average daily return
- Total return over the period
- Best and worst single days
- Count and percentage of up days

## Sample Output

![SPY Returns](SPY_returns.png)

## How to Run

Change the settings at the top of the script:

```python
TICKER = "SPY"
PERIOD = "3y"
FOLDER = "your/output/path/"
```

Then run it. The script produces a PNG chart and an Excel file named after the ticker.

## Built With

pandas · numpy · yfinance · matplotlib · openpyxl
