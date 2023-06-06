# The power of Dollar Cost Averaging (DCA) in Bitcoin (BTC)

## Project Overview

This project undertakes an exploration of the effectiveness of a Dollar Cost Averaging (DCA) investment strategy applied to the cryptocurrency asset, Bitcoin. The DCA strategy involves dividing a fixed amount of money into equal parts and investing those parts at regular intervals, regardless of the price of the asset. The project uses historical data from the years 2013 to 2018 to determine whether a DCA strategy can potentially mitigate the impact of volatility and enhance overall returns when investing in Bitcoin.

**The complete report was published on [Rpubs](https://rpubs.com/camello_7/994438)

## Buisness understanding

The investment strategies under analysis involve the allocation of a fixed percentage of an average US full-time employee's income. The average monthly income was calculated to be approximately $5,083.82 [Statista](https://www.statista.com/statistics/612519/average-annual-real-wages-united-states/), and it was determined that 10% of this income (or about $508.38) would be used to execute the DCA strategy. The investment strategies were based on different timeframes: monthly, weekly, and daily. The monthly strategy involved making a single investment of the entire budget at the start of each month, while the weekly and daily strategies involved making 4 weekly investments of $127.10 and 365 daily investments of $16.95. respectively.

## Data Understanding

The project employed a dataset named "coin_bitcoin" sourced from [kaggle](https://www.kaggle.com/datasets/sudalairajkumar/cryptocurrencypricehistory?select=coin_Bitcoin.csv). This dataset contains comprehensive information on the historical prices and trading volume of Bitcoin, covering several years of Bitcoin's trading history. The dataset was meticulously chosen for its wide-ranging data that allows for a thorough analysis of the investment strategies. The historical data used was from 2013-2018, which includes one halving period of Bitcoin

## Modeling and Evaluation

The analysis computed the amount of Bitcoin that would be bought using the daily, weekly, and monthly budgets based on the closing price of Bitcoin for each day. The strategies resulted in different amounts of Bitcoin being accumulated over the 5-year period: 

* 80.25 BTC for the daily strategy
* 86.04 BTC for the weekly strategy 
* 80.97 BTC for the monthly strategy 

The dollar value of the accumulated Bitcoin was then calculated using the closing price of Bitcoin each day of the end of time framework for each strategy:

* 721,245.06 $ for the daily stategy
* 768,385.40 $ for the weekly strategy 
* 788.951.40 $ for the monthly strategy


## Conclusions

The following recomendations could be present to the stakeholders, this recomendations are based on the feature importances of the Random Forest Model: (`last_evaluation`, `number_project`, `tenure`, `overworked`), to retain employees:

* Adopting an investment strategy that allocates 10% of the average full-time US employee's salary to the BTC cryptocurrency via Dollar-Cost Averaging (DCA) can really have powerful impact on financial future of the investor. 
* It has been concluded that the frequency of DCA purchases —whether daily, weekly, or monthly— does not show a substancial difference in investment performance.
* Our findings further indicate that the Return on Investment (ROI) surpasses 2000% after a period of 5 years, derived from the unrealized gains on the final day of purchases across each investment interval (daily, weekly, monthly). This demonstrates the potential of a substantial long-term profit margin.
