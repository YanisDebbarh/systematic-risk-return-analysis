# Systematic Risk & Return Analysis
### FX, Rates & Equities — Quantitative Research Note

## Overview
Quantitative analysis of real market data covering FX (EUR/USD, USD/JPY), 
US Interest Rates (10Y, 30Y Treasuries), and Equities (S&P 500 + 11 sectors) 
over 2019-2024.

## Key Findings
- EUR/USD Sharpe: -0.89 → dollar dominance over period
- SPY Max Drawdown: -33.72% → COVID crash March 2020
- IV-RV Gap on EUR/USD: ~11-13 vol points → vol structurally overpriced
- Bear steepening detected 2023 → rates trade opportunity

## Structure
| Notebook | Content |
|---|---|
| 01_market_setup | Data collection via yfinance |
| 02_sql_cleaning | SQLite database & cleaning |
| 03_risk_metrics | Sharpe, VaR, Drawdown, Correlations |
| 04_performance_attribution | Sector heatmap & annual returns |
| 05_excel_export | Excel model export |
| 06_research_report | Full research note & trade ideas |

## Tech Stack
Python, Pandas, NumPy, Matplotlib, Seaborn, SQLite, Excel

## Author
Yanis Debbarh
