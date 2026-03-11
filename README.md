# Long–Short U.S. Equity Strategies

This project proposes and evaluates several behavioral long–short equity investment strategies designed to capture mispricing in U.S. equity markets.

## Strategies Proposed

### 1 Analyst Fatigue Arbitrage
This strategy exploits investor neglect when firms lose analyst coverage and renewed attention when coverage expands.

Long: companies gaining analyst coverage  
Short: companies losing analyst coverage  

The strategy captures the attention and liquidity premium created by analyst visibility.

---

### 2 Insider Silence Momentum
This strategy analyzes insider trading behavior during market rallies.

Long: companies with zero insider sales during market rallies  
Short: companies with high insider selling relative to market cap  

The hypothesis is that insider silence signals internal confidence about future performance.

---

### 3 Employee Optimism Arbitrage
This strategy uses employee sentiment signals.

Long: firms with increasing employee satisfaction ratings  
Short: firms with declining employee ratings  

Improving morale often precedes operational improvements and higher productivity.

---

## Optional Backtest

An additional experiment tests the **Alphabetical Attention Strategy**.

Investors often process information alphabetically. Early-letter tickers may receive more attention than late-letter tickers.

Strategy:

Long: stocks near the end of the alphabet  
Short: stocks near the beginning of the alphabet  

Data Source: WRDS CRSP Database  
Period: 2010–2024  

## Example Results

Annualized Return: 3.6%  
Volatility: 11.2%  
Sharpe Ratio: 0.32  
Maximum Drawdown: -9.4%

## Tools Used

Python  
WRDS CRSP Database  
Pandas  
NumPy  

## Skills Demonstrated

Quantitative finance research  
Long-short portfolio design  
Behavioral finance hypothesis development  
Python financial data analysis
