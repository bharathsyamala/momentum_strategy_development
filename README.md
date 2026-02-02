# Momentum Strategy Development

A Python implementation of the MSCI Momentum Index methodology (Aug 2021) applied to the Indian equity market (Nifty 100). This project replicates the quantitative framework for risk-adjusted momentum scoring, semi-annual rebalancing, and conditional volatility triggers.

# Key Features

- **Momentum Scoring:** Calculates 6-month and 12-month risk-adjusted momentum values using MIBOR-adjusted excess returns.

- **Volatility Trigger:** Implements Appendix III conditional rebalancing based on the 95th percentile of monthly volatility changes in the reference index.

- **Buffer Rules:** Incorporates the MSCI selection algorithm and buffer zones to manage portfolio turnover.

- **Data Pipeline:** Automated financial data ingestion using yfinance.

# Disclaimer

This project is for educational and experimental purposes only. It is not investment advice. Past performance does not guarantee future results.
