# 🪙 Bitcoin-Analysis

## Introduction
In this analysis, we explore the price movements of Bitcoin from 2018 to 2024, focusing on the difference between the open and close prices over time. The data tracks how Bitcoin's price fluctuated within various timeframes, providing insights into periods of stability and high volatility.

1. Open, High, Low, Close Prices (OHLC)
   These prices are essential for understanding price movements over a period.
    - **Open: Starting price at the given interval.**
    - **High: Highest price during the interval.**
    - **Low: Lowest price during the interval.**
    - **Close: Price at the end of the interval.**
2. Volume
   Volume: The amount of cryptocurrency traded in the period.
    - Taker buy base asset volume: The volume of the base asset bought by takers (people executing market orders).
    - Taker buy quote asset volume: The volume of the quote asset bought by takers.
3. Number of Trades
    - The total number of trades executed in the given interval.
    - Usefulness: It indicates market activity. High trade counts, combined with high volume, indicate strong market participation.

4. Quote Asset Volume
    - This is the total trading volume in terms of the quote asset (e.g., USD, BTC).


By examining this data, we aim to uncover broader trends in Bitcoin’s market behavior, identify periods of significant change, and provide insights into the underlying market conditions during these years.

The dataset can be found on Kaggle: 
> https://www.kaggle.com/datasets/rankirsh/evolution-of-top-games-on-twitch/data

## Data Cleaning and Preprocessing
 - Open and Close time variables were converted to the appropriate datetime type.
 - all other variables had the correct types associated with them.
 - no null values were found.

## Data Summary
Key Analysis:
- Volume Trends:
   - Bitcoin trading volume has increased significantly from 2018 to 2022, with 2022 being the year with the highest volume recorded.
     The upward trend in trading activity is consistent with broader market behavior and increasing institutional interest in cryptocurrencies during this period.

- Price Differences:
   - The differences between the Open and Close prices indicate market volatility. A negative difference, where the Close is lower than the Open, suggests a             bearish trend (i.e., sellers dominated the market), while positive differences indicate bullish trends.
   - From the line graph showing price differences over time, it appears that around 2021, there was considerable price volatility, reflecting large swings in           market sentiment.
