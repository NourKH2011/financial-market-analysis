# Financial Market Analysis | Tech Stocks (2020–2025)

### Performance and Risk Analysis Using Python

## Project Overview

This project analyzes the historical stock market performance of five major technology companies: Apple (AAPL), Microsoft (MSFT), Amazon (AMZN), Alphabet (GOOGL), and Tesla (TSLA).

The objective is to compare financial returns, volatility, risk-adjusted performance, and maximum drawdowns using Python-based data analytics and interactive visualizations.

**Analysis Period:** January 2, 2020 – December 30, 2025

**Data Source:** Yahoo Finance, accessed using the `yfinance` Python library.

## Technologies Used

- Python
- Pandas and NumPy
- yfinance
- Matplotlib
- Plotly
- Google Colab

## Key Performance Indicators

| Company | Total Return (%) | Daily Volatility (%) | Sharpe Ratio | Maximum Drawdown (%) |
|---|---:|---:|---:|---:|
| TSLA | 1484.26 | 4.19 | 1.03 | -73.63 |
| GOOGL | 362.08 | 2.05 | 0.95 | -44.32 |
| AAPL | 276.83 | 2.00 | 0.86 | -33.36 |
| MSFT | 219.65 | 1.86 | 0.81 | -37.15 |
| AMZN | 145.03 | 2.25 | 0.60 | -56.15 |

## Key Findings

- **Tesla:** Highest historical return, accompanied by the highest volatility and deepest drawdown.
- **Alphabet:** Second-highest total return and Sharpe ratio.
- **Apple:** Smallest maximum drawdown among the selected companies.
- **Microsoft:** Lowest daily volatility.
- **Amazon:** Lowest historical Sharpe ratio in the comparison.

## Methodology

Historical adjusted closing prices were used to calculate total returns, daily percentage returns, volatility, annualized Sharpe ratios, and maximum drawdowns.

The Sharpe ratio assumes a zero risk-free rate and 252 trading days per year.

Average daily trading volume was calculated separately from the reported trading volumes.

## Project Files

- `01_financial_market_analysis.ipynb` — Python data collection, processing, financial KPI calculations, and visualizations.
- `financial_dashboard.html` — Interactive financial performance and risk dashboard.
- `dashboards/financial_dashboard.html` — Interactive financial performance and risk dashboard.

## Limitations

This is a historical analysis for educational and portfolio purposes. It does not constitute investment advice or predict future stock performance. Transaction costs, taxes, and investor-specific constraints are excluded.
