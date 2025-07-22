# Black Swan Research

## Objective
Research in market black swan events.

## Workflow
Phase 0 - Obtain Swan Beta value for each stock in SP100 & SP500

Phase I - Preselecting Stocks from SP100 & SP500 to form an initial pool

Use K-means Clustering and Dynamic Clustering to cluster stocks. Then, run the clustering method in multiple iterations with db index value to measure the density of clusters. The stocks will then be ordered by its frequency of appearance in five seeds with lowest db index score. The number of preselected stocks could be vary.

Phase II - Download data for each stock and perform data cleaning

Download each stock's data and do some feature engineering to add some features for each stock. Perform data cleaning to avoid missing values, data shifting to deal with lagging issues, and interpolations using brownian bridge to smooth the data.

Phase III

Set the optimizer to max Sharpe and run Efficient Frontier to preseleceted stocks in order to construct the final portfolio and calculate weights for each stock in the portfolio.
New research focuses on replacing the old MVO approach to using a new model called Hiearchical Risk Parity which uses Hiearchical Clustering and dendrogram structure to construct clusters. HRP will select some number of stocks from each clusters.

## Metrics
- Sharpe ratio
- Volatility
- Dropdown without protection
- Dropdown with protection
- Protection Rate

## Future Topics
- Find other clustering methods to better cluster the stocks
- Find other portfolio optimzation models to construct the portfolio in a more reseanable way.
- Use machine learning or deep learning models to find more features related to stock prices
- Add more features to better predict the price movement and connect with swan beta

