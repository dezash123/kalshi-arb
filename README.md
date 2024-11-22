- HFT/Arbitrage on Kalshi with Polymarket
- maybe pseudo-arbitrage on only Kalshi
## Tasks
### Environment
[DeepNote](https://deepnote.com/workspace/kalshi-hft-d84e4af1-3014-4aeb-8ab1-42b22570df38/project/DJY-Model-7ee95ebc-2f27-4dbd-b2de-bd2e7364b643/notebook/Manifold-Model-3be142d38789449dad38a519ae2b27dd)
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
- [Black-Scholes Model](https://medium.com/kalshi/applying-black-scholes-to-kalshi-markets-5cac35f21efb)?
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
