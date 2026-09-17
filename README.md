# S&P 500 Total Return Drawdown Optimization

## Overview

This project analyses how a short period of extreme market loss can affect long-term investment performance.

Using S&P 500 Total Return Index data, the project calculates the growth of a $100 investment from January 1, 2005 to January 1, 2025 and identifies the worst consecutive 11-calendar-day market window.

## Method

- Download S&P 500 Total Return Index data using `yfinance`
- Handle non-trading dates using the nearest available trading day
- Calculate daily market returns
- Test every consecutive 11-calendar-day window
- Identify the window with the lowest compounded return
- Compare normal buy-and-hold performance with the counterfactual portfolio value after removing the worst 11-day window

## Results

- Initial investment: **$100.00**
- Normal final value: **$723.37**
- Worst 11-day window: **2008-09-29 to 2008-10-09**
- Final value after removing the worst 11-day window: **$963.38**

## Technologies

- Python
- Pandas
- yfinance

## Key Concept

The project demonstrates how an extreme short-term market drawdown can have a significant impact on long-term compounded portfolio growth.

## Note

This is a historical counterfactual analysis. In real trading, investors cannot know the worst future market period in advance.
