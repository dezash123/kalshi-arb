- HFT/Arbitrage on Kalshi with Polymarket
- maybe pseudo-arbitrage on only Kalshi
## Tasks
### Environment
[[DeepNote]]
### APIs
- Manifold
- Kalshi
- Polymarket
- sports betting markets?
### Backtesting
- odds bias
	- odds of true/false given different prediction buckets at different lags
	- raise granularity closer to accuracy 
#### End result
linear model to determine true odds
##### Factors
- time to expiry
- current odds
- market liquidity / number of actors
- [[Black-Scholes Model]]?
### Arbitrage
#### Between Markets
- Methods
	- pseudo-arbitrage
		- very not optimal
		- "last resort"
	- predictors
		- higher liquidity to predict lower
		- polymarket predicts kalshi
	- Actual
		- illegal for what I see
- all require NLP-pairing algo
#### Within Market
- more complex pairing
- free returns
- requires riskier pairing algo
## Tasks
- Apis
	- kalshi
	- polymarket
- linear model
	- market odds vs true odds
	- time dependence
	- liquidity effect
- entry matching
	- between markets
	- within markets
