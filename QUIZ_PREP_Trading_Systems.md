# QUIZ PREP: Trading Systems & Algorithmic Trading
*Based on Module 10: Trading Systems*

## 🎯 **TRADING SYSTEMS FUNDAMENTALS**

### **1. WHAT IS A TRADING SYSTEM?**

#### **Definition**
**Trading System**: Quantifiable process that can be defined, backtested, and systematically executed
**Key Requirement**: Must be able to convert approach into specific rules and parameters

#### **Trading System vs Ad-hoc Trading**
**Ad-hoc Methods** (NOT Trading Systems):
- **Gut Feeling**: "I feel the market will go up"
- **Tips**: Following broker/friend/TV recommendations
- **Systematic Deduction**: Logical but not quantifiable analysis

**Trading System Requirements**:
- **Defined Process**: Clear entry and exit rules
- **Quantifiable Parameters**: Specific numbers and criteria
- **Backtestable**: Can test on historical data
- **Systematic**: Removes emotional decision-making

#### **Trading System Framework**
**Input → Process → Output → Decision**
1. **Input**: Market data, indicators, parameters
2. **Process**: System logic and calculations
3. **Output**: Buy/sell signals or risk metrics
4. **Decision**: Execute trade or wait

#### **Common Misconceptions**
**Not a Money Machine**: Systems don't guarantee profits
**Human Element**: You design system, provide inputs, make final decisions
**Market Dependent**: Effectiveness varies with market conditions
**Requires Backtesting**: Must test on historical data before live trading

---

## 🔄 **PAIR TRADING**

### **2. PAIR TRADING FUNDAMENTALS**

#### **Core Concept**
**Analogy**: Highway and service road running parallel
- **Highway**: One stock (e.g., HDFC Bank)
- **Service Road**: Similar stock (e.g., ICICI Bank)
- **Tree Obstruction**: Temporary deviation from normal relationship
- **Opportunity**: Trade the convergence back to normal relationship

#### **Pair Trading Logic**
**Similar Companies**: Same sector, similar business model, comparable size
**Expected Behavior**: Should react similarly to market events
**Relationship Breakdown**: Temporary divergence creates trading opportunity
**Mean Reversion**: Expectation that relationship will normalize

#### **Example: HDFC Bank vs ICICI Bank**
**Similarities**:
- Both private sector banks
- Similar banking products and services
- Comparable client base and geographic presence
- Same regulatory environment
- Similar business challenges and opportunities

**Trading Opportunity**: When one outperforms/underperforms the other significantly

### **3. PAIR TRADING METHOD 1: CORRELATION-BASED**

#### **Step 1: Pair Selection**
**Criteria for Good Pairs**:
- **High Correlation**: Historical correlation > 0.8
- **Same Sector**: Similar business fundamentals
- **Similar Market Cap**: Comparable company size
- **Similar Liquidity**: Both stocks actively traded

#### **Step 2: Ratio Analysis**
**Price Ratio**: Stock A Price ÷ Stock B Price
**Ratio Behavior**: Track how ratio moves over time
**Mean Reversion**: Ratio tends to return to average over time

#### **Step 3: Statistical Measures**
**Mean**: Average ratio over lookback period
**Standard Deviation**: Measure of ratio volatility
**Z-Score**: (Current Ratio - Mean) ÷ Standard Deviation

#### **Step 4: Trading Rules**
**Entry Signals**:
- **Z-Score > +2**: Ratio extremely high, sell Stock A, buy Stock B
- **Z-Score < -2**: Ratio extremely low, buy Stock A, sell Stock B

**Exit Signals**:
- **Z-Score returns to 0**: Ratio normalizes, close positions
- **Stop Loss**: If Z-Score moves further against position

#### **Step 5: Position Sizing**
**Dollar Neutral**: Equal dollar amounts in both stocks
**Beta Neutral**: Adjust for different volatilities
**Example**: ₹1,00,000 long HDFC, ₹1,00,000 short ICICI

### **4. PAIR TRADING METHOD 2: REGRESSION-BASED**

#### **Linear Regression Approach**
**Concept**: Model relationship between two stocks mathematically
**Regression Equation**: Stock A = α + β × Stock B + ε
Where:
- α = intercept (alpha)
- β = slope (beta) 
- ε = error term (residual)

#### **Cointegration Testing**
**ADF Test (Augmented Dickey-Fuller)**: Tests if residuals are stationary
**Stationarity**: Residuals revert to mean over time
**Trading Signal**: When residuals deviate significantly from mean

#### **Error Ratio Method**
**Residual Calculation**: Actual Price - Predicted Price (from regression)
**Standardized Residual**: Residual ÷ Standard Deviation of Residuals
**Trading Signals**: Based on standardized residual thresholds

#### **Advanced Concepts**
**Half-Life**: Average time for mean reversion to occur
**Hurst Exponent**: Measure of mean reversion strength
**Kalman Filter**: Dynamic parameter estimation

---

## 📅 **CALENDAR SPREADS**

### **5. CALENDAR SPREAD TRADING**

#### **Structure**
**Definition**: Options strategy using same strike, different expiries
**Setup**: Sell near-month option, buy far-month option
**Objective**: Profit from time decay differential and volatility changes

#### **Calendar Spread Types**
**Call Calendar**: Using call options
**Put Calendar**: Using put options
**Neutral Strategy**: Profits from sideways market movement

#### **Profit Drivers**
**Time Decay**: Near-month option decays faster
**Volatility**: Benefits from volatility increase in far-month
**Price Movement**: Optimal when stock stays near strike price

#### **Risk Factors**
**Large Price Moves**: Can cause losses if stock moves significantly
**Volatility Crush**: Reduction in implied volatility hurts position
**Early Assignment**: Risk with short options (mainly puts)

---

## 📊 **MOMENTUM PORTFOLIOS**

### **6. MOMENTUM STRATEGY**

#### **Momentum Concept**
**Definition**: Stocks that have performed well recently tend to continue performing well
**Academic Support**: Documented market anomaly across global markets
**Time Horizon**: Typically 3-12 months

#### **Portfolio Construction**
**Universe Selection**: Start with broad stock universe (e.g., Nifty 500)
**Ranking**: Rank stocks by recent performance (e.g., 6-month returns)
**Portfolio Formation**: Buy top performers, sell/avoid bottom performers
**Rebalancing**: Monthly or quarterly portfolio updates

#### **Implementation Methods**
**Top-Bottom Approach**: Buy top 10%, short bottom 10%
**Long-Only**: Buy only top performers
**Sector Neutral**: Equal weight to each sector

#### **Risk Management**
**Position Limits**: Maximum weight per stock
**Sector Limits**: Avoid concentration in single sector
**Volatility Control**: Adjust position sizes based on stock volatility
**Stop Losses**: Individual stock and portfolio level stops

---

## ⚡ **VOLATILITY-BASED STRATEGIES**

### **7. DELTA HEDGING**

#### **Concept**
**Delta**: Rate of change of option price with respect to underlying price
**Delta Hedging**: Maintaining delta-neutral portfolio
**Objective**: Profit from volatility while minimizing directional risk

#### **Implementation**
**Long Volatility**: Buy options, hedge with underlying
**Short Volatility**: Sell options, hedge with underlying
**Dynamic Hedging**: Continuously adjust hedge ratios

#### **Profit Sources**
**Realized vs Implied Volatility**: Profit when realized ≠ implied
**Gamma Scalping**: Profit from frequent rehedging
**Time Decay**: Benefit from theta in short volatility strategies

---

## 🔧 **SYSTEM DEVELOPMENT PROCESS**

### **8. TRADING SYSTEM DEVELOPMENT**

#### **Step 1: Strategy Conceptualization**
**Market Inefficiency**: Identify exploitable market patterns
**Hypothesis Formation**: Develop testable trading hypothesis
**Logic Definition**: Create clear rules for entry/exit

#### **Step 2: Parameter Definition**
**Input Parameters**: Data sources and indicators
**Threshold Values**: Specific numbers for signals
**Risk Parameters**: Stop losses, position sizes, exposure limits

#### **Step 3: Signal Generation**
**Entry Signals**: Conditions for initiating positions
**Exit Signals**: Conditions for closing positions
**Filter Rules**: Additional conditions to improve signal quality

#### **Step 4: Risk Management**
**Position Sizing**: How much to invest per trade
**Portfolio Limits**: Maximum exposure to strategy
**Drawdown Controls**: Actions when losses exceed limits

### **9. BACKTESTING FRAMEWORK**

#### **Data Requirements**
**Quality Data**: Clean, adjusted price data
**Survivorship Bias**: Include delisted stocks in universe
**Point-in-Time Data**: Use only information available at time of decision

#### **Backtesting Metrics**
**Return Metrics**: Total return, CAGR, Sharpe ratio
**Risk Metrics**: Maximum drawdown, volatility, VaR
**Trade Statistics**: Win rate, average win/loss, profit factor

#### **Common Pitfalls**
**Look-Ahead Bias**: Using future information
**Overfitting**: Too many parameters, good backtest but poor live performance
**Transaction Costs**: Ignoring brokerage, slippage, market impact

---

## 📈 **SYSTEM PERFORMANCE EVALUATION**

### **10. PERFORMANCE METRICS**

#### **Return Metrics**
**Total Return**: Overall percentage gain/loss
**CAGR**: Compound Annual Growth Rate
**Risk-Adjusted Returns**: Sharpe ratio, Sortino ratio

#### **Risk Metrics**
**Maximum Drawdown**: Largest peak-to-trough decline
**Volatility**: Standard deviation of returns
**Value at Risk**: Maximum expected loss at confidence level

#### **Trade Analysis**
**Win Rate**: Percentage of profitable trades
**Profit Factor**: Gross profit ÷ gross loss
**Average Win/Loss**: Risk-reward characteristics

#### **Consistency Metrics**
**Monthly/Quarterly Returns**: Distribution of periodic returns
**Winning/Losing Streaks**: Longest consecutive periods
**Correlation with Market**: Independence from market direction

### **11. SYSTEM OPTIMIZATION**

#### **Parameter Optimization**
**Grid Search**: Test multiple parameter combinations
**Walk-Forward Analysis**: Rolling optimization and testing
**Out-of-Sample Testing**: Reserve data for final validation

#### **Regime Detection**
**Market Regimes**: Bull, bear, sideways markets
**Regime-Dependent Parameters**: Adjust parameters based on market state
**Adaptive Systems**: Self-adjusting parameters

---

## 🚨 **RISK MANAGEMENT IN TRADING SYSTEMS**

### **12. SYSTEM-LEVEL RISK CONTROLS**

#### **Position-Level Controls**
**Maximum Position Size**: Limit per individual trade
**Sector Concentration**: Limits on sector exposure
**Correlation Limits**: Avoid highly correlated positions

#### **Portfolio-Level Controls**
**Total Exposure**: Maximum capital allocated to system
**Leverage Limits**: Maximum borrowed capital usage
**Drawdown Limits**: Stop trading if losses exceed threshold

#### **System-Level Controls**
**Performance Monitoring**: Real-time system performance tracking
**System Shutdown**: Automatic stop if system malfunctions
**Manual Override**: Ability to intervene in extreme situations

### **13. COMMON SYSTEM FAILURES**

#### **Model Breakdown**
**Regime Change**: Market structure changes invalidate model
**Parameter Drift**: Historical relationships break down
**Overfitting**: System too optimized to historical data

#### **Implementation Issues**
**Technology Failures**: System downtime, data feed issues
**Execution Problems**: Slippage, partial fills, timing delays
**Human Errors**: Wrong parameters, manual intervention mistakes

#### **Solution Approaches**
**Robust Design**: Build systems that work across market conditions
**Multiple Timeframes**: Test across different time periods
**Conservative Assumptions**: Assume higher costs, lower returns

---

## 🎯 **QUIZ SUCCESS STRATEGIES**

### **Key Trading System Concepts to Master**
1. **System Definition**: Quantifiable vs ad-hoc approaches
2. **Pair Trading**: Correlation-based and regression-based methods
3. **Calendar Spreads**: Time decay and volatility strategies
4. **Momentum Strategies**: Portfolio construction and rebalancing
5. **Delta Hedging**: Volatility trading concepts
6. **Backtesting**: Proper methodology and common pitfalls
7. **Risk Management**: System-level controls and limits
8. **Performance Evaluation**: Metrics and optimization

### **Important Calculations**
- **Z-Score**: (Current Value - Mean) ÷ Standard Deviation
- **Linear Regression**: Y = α + βX + ε
- **Sharpe Ratio**: (Return - Risk-free Rate) ÷ Standard Deviation
- **Maximum Drawdown**: (Peak Value - Trough Value) ÷ Peak Value

### **Key Numbers to Remember**
- **Good Correlation**: > 0.8 for pair trading
- **Z-Score Thresholds**: ±2 for entry signals
- **Good Sharpe Ratio**: > 1.0 (> 2.0 excellent)
- **Typical Rebalancing**: Monthly or quarterly for momentum

### **Common Quiz Topics**
**Pair Trading:**
- Pair selection criteria and methods
- Z-score calculation and interpretation
- Entry/exit signal generation
- Risk management in pair trades

**System Development:**
- Difference between system and ad-hoc trading
- Backtesting methodology and pitfalls
- Performance metrics calculation
- Risk control implementation

**Strategy Types:**
- Calendar spread profit/loss drivers
- Momentum portfolio construction
- Delta hedging concepts
- Volatility trading strategies

### **Quiz Tips**
- **Understand System Logic**: Know why each strategy works
- **Master Calculations**: Z-scores, correlations, performance metrics
- **Know Risk Controls**: Understand importance of risk management
- **Backtesting Concepts**: Common biases and proper methodology
- **Real Examples**: Relate concepts to actual market situations

### **Quick Reference**
**Pair Trading**: High correlation pairs, Z-score ±2 signals
**Calendar Spreads**: Sell near, buy far expiry options
**Momentum**: Buy recent winners, avoid/short losers
**Delta Hedging**: Maintain delta-neutral, profit from volatility
**Backtesting**: Avoid look-ahead bias, include transaction costs

**Remember**: Trading systems provide disciplined, quantifiable approaches to trading. Success depends on proper system design, rigorous backtesting, robust risk management, and disciplined execution. No system works all the time, but good systems provide edge over random trading and help remove emotional decision-making! 