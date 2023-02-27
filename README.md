## Institutional-ownership-impact-on-stocks-near-one-dollar

### Objective
The objective of this investment idea is to examine the impact of insider and institutional ownership on returns when a company's stock price falls below $1 on the NYSE. The NYSE has minimum requirements for companies listed on the exchange, including a minimum liquidity, market capitalization, and a share price higher than $1. If a stock price falls below $1 for more than 90 days, the company may choose to do a reverse split, get delisted and move to a different exchange, or hope the stock price recovers.

We hypothesize that companies with high insider and institutional ownership will have a better chance of maintaining their stock price above $1 and achieving positive returns. This is because insiders and institutions have a vested interest in keeping the stock price above $1 and may take actions such as releasing positive news or buying up stock to increase the price.

We want to test this hypothesis by looking at historical data of companies in the NYSE over the past 10-15 years and creating portfolios based on insider and institutional ownership of their stocks. The goal is to determine if there is a correlation between high insider and institutional ownership and positive returns for stocks targeting a $1 minimum price on the NYSE.

### Methodology
Pull pricing and returns data for the relevant securities.
Retrieve ownership data for the same securities. (WRDS institutional, Form 13 alternative for SEC)
Analyze the relationship between returns and ownership.
Study the relationship between returns and ownership when the price is approaching $1 or less.
Create portfolios of securities sorted by ownership concentration.
Long the top quintile of ownership-concentrated portfolios and short the bottom quintile (equal weighting).
Set the investment horizon to 90 days.
Regress the returns of the portfolios against the Fama-French factors during the same time periods and determine the statistical significance of alpha.
Investigate the relationship between price changes and ownership concentration during the investment horizon. Check for any pattern, such as increase followed by decrease.

### Expected results
Findings are expected to include:
Figures showing the correlation between ownership concentration and returns (both overall and when prices are approaching $1 from either direction)
Figures showing the regression statistics of long-short portfolio vs FF factors

### Running our code
To run our code you'll need to clone this repository and then download the data for it serperately.

The data can be downloaded from the following [link](https://utexas.box.com/s/qxblujtpmofzpqm2fxj5w7a0jqzw2913) <br>
You'll have to download all the files and place them in the data directory like so:

├── data <br>
│   ├── price_data_2005_2022.csv <br>
│   ├── instituional_ownership_2005_2022.csv <br>
│   ├── merged_data_2005_2022.pkl



### Track our progress
We use [Github projects](https://github.com/AmritSd/Institutional-ownership-impact-on-stocks-near-one-dollar/projects) to plan and track our progress
