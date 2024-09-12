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
### Volume Trends:
   - Bitcoin trading volume has increased significantly from 2018 to 2022, with 2022 being the year with the highest volume recorded.
     The upward trend in trading activity is consistent with broader market behavior and increasing institutional interest in cryptocurrencies during this period.

### Price Differences:
   - The differences between the Open and Close prices indicate market volatility. A negative difference, where the Close is lower than the Open, suggests a             bearish trend (i.e., sellers dominated the market), while positive differences indicate bullish trends.
   - From the line graph showing price differences over time, it appears that around 2021, there was considerable price volatility, reflecting large swings in           market sentiment.
   - The graph plotting the difference between the Open and Close prices shows periods of high volatility, particularly around 2021. This corresponds with          
     Bitcoin’s price surge and subsequent crash during the bull market of 2020-2021, followed by increased regulatory concerns and other macroeconomic factors.
     
### Quote asset volume Vs Volume:
   - Interpreting the the graph of quote asset volume against the volume, between 2018-2021, the quote asset volume was lower than the volume indicating a weak
     value in Bitcoin which also coincides with the crash in the crypto market.
   - However from 2021-2023 onwards the qoute asset volume exceeded the volume indicating an icnrease in the base asset as well as a strong demand for it.
   - 2023 onwards the Bitcoin market stabilised as the quote asset volume and volume were in equilibrium.

### Taker Buy Volume (BTC and USD) Vs taker buy qoute asset volume Over Time:
   - between 2018 to late 2020, taker Buy Base Asset Volume was greater than the Taker Buy Quote Asset Volume, This suggests that a large quantity of the base           asset is being purchased, but at a relatively lower price.
   - from late 2020 to mid 2022 the Taker Buy Quote Asset Volume exceeded the  Taker Buy Base Asset Volume This suggests that a significant amount of capital is         being spent on the base asset, but the actual number of units being purchased is lower, indicating higher prices per unit.
   - mid 2022 onwards we see variables align or reach equilibrium indicating a stablisation in the market.

## Summary and Historical Comparison
From 2018 to 2023, Bitcoin’s trading volume rose sharply, peaking in 2022, reflecting growing institutional interest. Price volatility surged in 2021, mirroring past market cycles of rapid growth and corrections, similar to the 2017 bull run. Lower quote asset volume before 2021 indicated weaker valuation, while the increased quote asset volume post-2021 suggests stronger demand and stabilization. Overall, Bitcoin’s recent trends align with historical patterns of volatility and market maturation.
