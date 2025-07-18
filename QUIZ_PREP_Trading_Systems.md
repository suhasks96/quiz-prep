# QUIZ PREP: Trading Systems & Quantitative Strategies
*Based on Module 10: Trading Systems*

## 🎯 **SYSTEMATIC TRADING FUNDAMENTALS**

### **1. INTRODUCTION TO TRADING SYSTEMS**

#### **What are Trading Systems?**
- **Definition**: Rule-based approach to trading with predetermined entry/exit criteria
- **Objective**: Remove emotions, maintain consistency, achieve repeatable results
- **Components**: Entry rules, exit rules, position sizing, risk management
- **Advantage**: Disciplined approach vs discretionary trading

#### **Systematic vs Discretionary Trading**
**Systematic Trading:**
- **Rule-based decisions**
- **Backtested strategies**
- **Consistent execution**
- **Emotional neutrality**
- **Scalable approach**

**Discretionary Trading:**
- **Intuition-based decisions**
- **Market feel and experience**
- **Flexible adaptation**
- **Subject to emotions**
- **Difficult to scale**

**💡 Quiz Tip**: Systematic trading eliminates human psychology - the biggest enemy of successful trading!

---

### **2. PAIR TRADING FUNDAMENTALS**

#### **Core Concept**
**Definition**: Simultaneously buying undervalued security and selling overvalued security in related pair

**Theoretical Foundation:**
- **Similar companies** should have similar price movements
- **Temporary divergences** create trading opportunities
- **Mean reversion**: Relationships tend to normalize over time
- **Market neutral**: Long and short positions reduce market risk

#### **Real-World Analogy: Parallel Roads**
**Two parallel roads** (HDFC Bank & ICICI Bank):
- **Normally move together** - similar business landscape
- **Tree falls on one road** (local event) - creates temporary divergence
- **Traffic eventually normalizes** - prices converge back
- **Arbitrage opportunity** exists during divergence

#### **Historical Background**
- **Invented at Morgan Stanley** in early 1980s
- **Gerry Bamberger**: First pair trader
- **Nunzio Tartaglia**: Popularized the strategy
- **DE Shaw**: Early hedge fund adopter
- **Statistical Arbitrage**: Modern evolution

---

### **3. PAIR TRADING METHODOLOGY**

#### **Method 1: Correlation-Based Approach**

**Step 1: Identifying Pairs**
**Sector-Based Selection:**
- **Banking**: HDFC Bank vs ICICI Bank
- **IT**: TCS vs Infosys
- **Auto**: Maruti vs Tata Motors
- **Pharma**: Sun Pharma vs Dr Reddy's

**Correlation Requirements:**
- **Minimum correlation**: 0.7+ over significant period
- **Stable relationship**: Consistent over different market cycles
- **Similar market cap**: Avoid size mismatch
- **Same sector**: Similar business fundamentals

#### **Step 2: Calculating Spreads**

**Types of Measurements:**
1. **Price Spread**: Stock A Price - Stock B Price
2. **Price Ratio**: Stock A Price / Stock B Price  
3. **Percentage Spread**: (Stock A - Stock B) / Stock B × 100

**Example Calculation:**
```
HDFC Bank = ₹1,600
ICICI Bank = ₹900

Spread = 1,600 - 900 = ₹700
Ratio = 1,600 / 900 = 1.78
Percentage = (1,600 - 900) / 900 × 100 = 77.8%
```

#### **Step 3: Statistical Analysis**

**Mean and Standard Deviation:**
- **Calculate historical mean** of spread/ratio
- **Calculate standard deviation** (volatility measure)
- **Define trading bands**: Mean ± 1σ, Mean ± 2σ

**Z-Score Calculation:**
```
Z-Score = (Current Value - Historical Mean) / Standard Deviation

Trading Signals:
- Z > +2: Sell Signal (spread too wide)
- Z < -2: Buy Signal (spread too narrow)
- |Z| < 1: Neutral zone
```

#### **Step 4: Signal Generation**

**Entry Signals:**
- **Z-Score > +2**: Short Stock A, Long Stock B
- **Z-Score < -2**: Long Stock A, Short Stock B
- **Divergence Confirmation**: Wait for momentum confirmation

**Exit Signals:**
- **Mean Reversion**: Z-Score returns to 0
- **Stop Loss**: Z-Score moves further (±2.5 or ±3)
- **Time Stop**: No convergence within predetermined period

---

### **4. POSITION SIZING & RISK MANAGEMENT**

#### **Equal Dollar Approach**
**Method**: Invest equal rupee amounts in both stocks
```
Portfolio Size = ₹10,00,000
Per Stock Investment = ₹5,00,000

HDFC Bank @ ₹1,600: 5,00,000 / 1,600 = 312 shares
ICICI Bank @ ₹900: 5,00,000 / 900 = 555 shares
```

#### **Beta-Neutral Approach**
**Method**: Adjust position sizes based on stock volatilities
```
Beta Adjustment Factor = Beta of Stock A / Beta of Stock B
Position Size B = Position Size A × Beta Adjustment
```

#### **Risk Management Rules**
1. **Maximum Risk**: 2-3% of capital per pair trade
2. **Stop Loss**: Z-Score > ±3 (or predetermined level)
3. **Time Stop**: Close if no convergence in 30-60 days
4. **Correlation Check**: Monitor relationship strength
5. **Diversification**: Maximum 20% in single sector pairs

---

### **5. ADVANCED PAIR TRADING CONCEPTS**

#### **Cointegration Analysis**
**Statistical Cointegration:**
- **More sophisticated** than correlation
- **Tests for long-term relationship** between price series
- **Augmented Dickey-Fuller Test**: Statistical test for cointegration
- **Error Correction Model**: Mean reversion mechanism

#### **Kalman Filter Approach**
**Dynamic Hedge Ratio:**
- **Adapts to changing** market conditions
- **Optimal hedge ratio** calculation
- **Real-time adjustment** of positions
- **More complex** but potentially more profitable

#### **Machine Learning Applications**
**Modern Approaches:**
- **Clustering algorithms**: Identify similar stocks
- **Neural networks**: Pattern recognition
- **Support vector machines**: Classification
- **Ensemble methods**: Combine multiple models

---

### **6. PAIRS TRADING EXAMPLE**

#### **HDFC Bank vs ICICI Bank Case Study**

**Step 1: Data Collection**
- **Time Period**: 2 years daily data
- **Correlation**: 0.85 (strong positive)
- **Ratio Mean**: 1.75
- **Ratio Std Dev**: 0.15

**Step 2: Signal Identification**
```
Current Ratio = 1.95
Z-Score = (1.95 - 1.75) / 0.15 = +1.33

Signal: Neutral (|Z| < 2)
```

**Step 3: Trade Execution (if Z > 2)**
- **Short HDFC Bank**: Overvalued relative to ICICI
- **Long ICICI Bank**: Undervalued relative to HDFC
- **Equal dollar amounts** or beta-adjusted

**Step 4: Exit Strategy**
- **Target**: Z-Score returns to 0 (ratio = 1.75)
- **Stop Loss**: Z-Score > 3 (ratio > 2.20)
- **Time Stop**: 45 days maximum holding

---

### **7. ALGORITHMIC TRADING SYSTEMS**

#### **System Architecture**
**Components:**
1. **Data Feed**: Real-time price data
2. **Signal Generation**: Mathematical models
3. **Risk Management**: Position sizing and stops
4. **Order Management**: Automated execution
5. **Portfolio Management**: Overall portfolio monitoring

#### **Popular System Types**

**Mean Reversion Systems:**
- **Assumption**: Prices revert to mean
- **Indicators**: RSI, Bollinger Bands
- **Markets**: Range-bound, sideways

**Trend Following Systems:**
- **Assumption**: Trends persist
- **Indicators**: Moving averages, momentum
- **Markets**: Trending, directional

**Momentum Systems:**
- **Assumption**: Strength continues
- **Indicators**: Rate of change, MACD
- **Markets**: Breakout, high volatility

**Statistical Arbitrage:**
- **Assumption**: Price relationships persist
- **Methods**: Pair trading, factor models
- **Markets**: Relative value opportunities

---

### **8. BACKTESTING & VALIDATION**

#### **Backtesting Process**
**Steps:**
1. **Historical Data**: Clean, adjusted data
2. **Strategy Rules**: Precise entry/exit criteria
3. **Transaction Costs**: Include brokerage, slippage
4. **Position Sizing**: Consistent methodology
5. **Performance Metrics**: Risk-adjusted returns

#### **Key Performance Metrics**

**Return Metrics:**
- **Total Return**: Absolute performance
- **Annualized Return**: Time-adjusted performance
- **Risk-Adjusted Return**: Sharpe ratio, Sortino ratio

**Risk Metrics:**
- **Maximum Drawdown**: Largest peak-to-trough decline
- **Volatility**: Standard deviation of returns
- **Value at Risk (VaR)**: Downside risk measure

**Efficiency Metrics:**
- **Win Rate**: Percentage of profitable trades
- **Profit Factor**: Gross profit / Gross loss
- **Average Trade**: Mean profit per trade

#### **Avoiding Backtesting Pitfalls**
1. **Look-ahead Bias**: Using future information
2. **Survivorship Bias**: Only successful stocks
3. **Data Snooping**: Over-optimization
4. **Transaction Costs**: Ignoring real costs
5. **Market Regime Changes**: Strategy decay over time

---

## 💰 **BUSINESS & ENTREPRENEURSHIP APPLICATIONS**

### **9. QUANTITATIVE FUND MANAGEMENT**

#### **Hedge Fund Strategies**
**Market Neutral Funds:**
- **Pair trading** as core strategy
- **Beta neutral** portfolios
- **Alpha generation** through stock selection
- **Risk parity** across positions

**Long-Short Equity:**
- **Fundamental analysis** + quantitative tools
- **Sector rotation** strategies
- **Factor-based** investing

#### **Robo-Advisory Platforms**
**Automated Investing:**
- **Algorithm-driven** portfolio management
- **Rebalancing strategies**
- **Tax optimization**
- **Low-cost** wealth management

### **10. CORPORATE TREASURY APPLICATIONS**

#### **Currency Hedging**
**Systematic Approaches:**
- **Quantitative models** for hedging decisions
- **Dynamic hedging** ratios
- **Cost optimization**
- **Risk measurement**

#### **Working Capital Management**
**Quantitative Methods:**
- **Cash flow forecasting** models
- **Optimal inventory** levels
- **Credit risk** assessment
- **Liquidity management**

---

## 🎯 **QUIZ SUCCESS STRATEGIES**

### **Key Concepts to Master**
1. **Pair Trading Logic**: Buy undervalued, sell overvalued
2. **Statistical Measures**: Correlation, Z-score, cointegration
3. **Risk Management**: Position sizing, stop losses
4. **System Components**: Data, signals, execution, monitoring
5. **Performance Metrics**: Risk-adjusted returns, drawdowns

### **Important Formulas**
- **Z-Score**: (Current Value - Mean) / Standard Deviation
- **Correlation**: Measure of relationship strength (-1 to +1)
- **Sharpe Ratio**: (Return - Risk-free rate) / Volatility
- **Maximum Drawdown**: Largest peak-to-trough decline
- **Beta**: Stock volatility relative to market

### **Critical Trading Rules**
1. **Entry**: |Z-Score| > 2 for signal generation
2. **Exit**: Z-Score returns to 0 (mean reversion)
3. **Stop Loss**: |Z-Score| > 3 (relationship breakdown)
4. **Position Size**: 2-3% risk per trade
5. **Diversification**: Multiple uncorrelated pairs

### **System Development Process**
1. **Hypothesis**: Develop trading idea
2. **Data Collection**: Gather historical data
3. **Model Building**: Create mathematical model
4. **Backtesting**: Test on historical data
5. **Validation**: Out-of-sample testing
6. **Implementation**: Live trading with monitoring

### **Common Pitfalls**
- **Over-optimization**: Curve fitting to historical data
- **Ignoring costs**: Transaction costs and slippage
- **Data mining**: Finding patterns that don't persist
- **Regime changes**: Market structure shifts
- **Risk management**: Inadequate position sizing

### **Real-World Applications**
- **Hedge Funds**: Market neutral strategies
- **Prop Trading**: Quantitative arbitrage
- **Corporate Finance**: Treasury management
- **Wealth Management**: Systematic investing

**Remember**: Systematic trading is about probability, not certainty. The goal is to find edges that work over many trades, not to predict individual outcomes. Risk management is more important than being right - protect capital first, profits will follow! 