# blockchain-developer-bootcamp-final-project

## Proposal

A basic platform for prediction markets, similar to [Augur](https://augur.net/). The lifecycle for a prediction market will consist of:

1. Market creation. Any user should be able to create a prediction market on some future event, defining the event criteria, range of possible outcomes to bet on, and date of final resolution. For the sake of simplicity it will be assumed only unambiguous events/outcomes are allowed.
2. Trading. Any user can buy or sell shares of the pre-defined outcomes for a given market.
3. Reporting. After the date of event resolution has passed, a reporting phase will occur where reporters will stake tokens (native to this blockchain) on one of the market's outcomes. At the end of the phase, the outcome with the most staked tokens will be declared the outcome of the event and all tokens will be redistributed to the "winning" reporters, who will also be granted a fee. 
4. Settlement. Traders who own shares in the winning outcome are able to settle their shares with the market, sans fees to the platform and market creator. Traders can be paid in [USDC](https://www.coinbase.com/usdc).
