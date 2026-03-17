# Crypto Market Data Pipeline & Analysis

This project demonstrates a simple end-to-end data workflow using live cryptocurrency market data from the CoinGecko API.

The goal of this project is to explore cryptocurrency market structure using Python and basic data analysis techniques.

---

## Project Workflow

The notebook follows a typical data science workflow:

1. **Data Collection**
   - Retrieve cryptocurrency market data from the CoinGecko API.

2. **Data Preparation**
   - Convert API responses into a structured pandas DataFrame.
   - Select relevant market features.

3. **Exploratory Data Analysis (EDA)**
   - Market capitalization ranking
   - Price change distribution
   - Volume comparison

4. **Visualization**
   - Distribution of 24h price changes
   - Market cap vs price relationship (log scale)

5. **Feature Engineering**
   - Identify highly volatile cryptocurrencies based on 24h price change.

---

## Tools & Libraries

Python libraries used:

- pandas
- numpy
- matplotlib
- requests

---

## Key Insights

- Cryptocurrency market capitalization is dominated by a small number of large assets.
- Smaller coins tend to show higher short-term price volatility.
- Trading volume is concentrated among top market-cap cryptocurrencies.
- Log-scale visualization is useful for comparing assets with large differences in market size.

---

## Repository Structure

---

## Data Source

CoinGecko Public API

https://www.coingecko.com/en/api

---

## Author

Becson
