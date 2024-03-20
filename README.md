## Overview
Using the machine learning library Keras, we develop an analytical tool to assist traders in analyzing midterm (e.g., weekly and intra-week) trading patterns. Matched with a simple trading strategy, we demonstrate the model's effectiveness on top-capitalization S&P 500 stocks through robust backtesting. Additionally, we present the potential shortcomings of the model, particularly concerning overreliance in the face of adverse and fundamentally unpredictable market conditions.

## Libraries
- Backtesting.py
- yfinance
- Requests
- Keras
- Pandas
- NumPy
- DateTime

## Data
We source historical volume, closing, opening, low, and high prices for various stocks from yfinance. Additionally, we source historical aggregated sentiment data from EODHD APIs.

## Methodology
We use Python and the above libraries to clean historical financial data and train models to create midterm forecasts from real-time data.
