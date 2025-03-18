## What we will do

- Download SP500 stocks price data
- Calculate different technical indicators and features for each stock
- Aggregate on monthly level and filter for each month only top 150 most liquid stocks
- Download Fama-French Factors and calculate rolling factor betas for each stock
- For each month fit a K-means clustering model to group similar assets based on their features
- For each month select assets based on cluster and form a portfolio based on Efficient Frontier max sharpe ratio portfolio optimization
- Visualize the portfolio returns and compare to SP500 returns