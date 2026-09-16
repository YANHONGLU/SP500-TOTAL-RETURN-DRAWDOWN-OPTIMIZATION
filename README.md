# S&P 500 Total Return Drawdown Optimization

## Overview

This project analyses how a short period of extreme market loss can affect long-term investment performance.

Using S&P 500 Total Return Index data from 2005 to 2025, the project calculates the growth of a hypothetical $100 investment and identifies the worst consecutive 11-calendar-day market window.

## Method

- Download S&P 500 Total Return Index data using `yfinance`
- Calculate daily market returns
- Test every consecutive 11-calendar-day window
- Identify the window with the lowest compounded return
- Compare normal buy-and-hold performance with the result after removing the worst window

## Technologies

- Python
- Pandas
- yfinance

## Key Concept

The project measures how an extreme short-term market drawdown can have a significant impact on long-term compounded portfolio growth.

## Note

This is a historical counterfactual analysis. In real trading, investors cannot know the worst future market period in advance.
