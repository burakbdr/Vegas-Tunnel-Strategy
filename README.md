# Vegas-Tunnel-Strategy
The Vegas Tunnel Strategy is a trend-following trading technique often used in forex markets, and it can be adapted for different intervals on various assets, including stocks and cryptocurrencies.

## Model

1) **Setting Up the Tunnel**
The strategy revolves around using two Exponential Moving Averages (EMAs):

* EMA-144: Represents the longer-term trend.
* EMA-169: Represents the medium-term trend.

    These two EMAs together form the "tunnel," which helps to smooth out price fluctuations and reveal the underlying trend.

2) **Entry Criteria**

- **Long Position:** When the price breaks above both the 144 and 169 EMAs and stays above them, it signals a potential uptrend. Look for price consolidation or a minor pullback before entering a buy position.
- **Short Position:** When the price drops below both the 144 and 169 EMAs and remains below, it indicates a potential downtrend. Wait for a pullback or consolidation before entering a sell position.

3) **Confirmation Indicators**

    Momentum indicators like RSI (Relative Strength Index) to confirm the strength of the trend.
* For a long position, RSI above 50 and a bullish MACD crossover can act as confirmation.
* For a short position, RSI below 50 and a bearish MACD crossover can be used for confirmation.

4) **Calculating Targets**

    Setting the profit target and stop-loss based on ATR.

### Backtest

Backtesting framework helps evaluate the strategy’s performance on historical data and can be further optimized or modified based on your requirements.

**Intial Balance:** 10.000 TL

**Final Balance:** 20.677 TL 

In the next stage we can add transaction costs, sharpe ratio and test with different EMA and ATR values to improve our model. 



