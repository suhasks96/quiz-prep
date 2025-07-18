# QUIZ PREP: Trading Systems & Algorithmic Trading
*Based on Module 10: Trading Systems*

## 🎯 **TRADING SYSTEMS FUNDAMENTALS**

### **1. WHAT IS A TRADING SYSTEM?**

#### **Definition**
**Trading System**: Quantifiable process that can be defined, backtested, and systematically executed
**Key Requirement**: Must be able to convert approach into specific rules and parameters

#### **Trading Approaches Classification**
**Systematic Deduction** (BEST): Logical, rule-based analysis
- Example: Bank Nifty premium analysis based on PSU bank weightage
- Contrarian positions based on mathematical reasoning
- Can be converted to trading systems

**Gut Feeling**: Intuitive trading (not systematic)
**Tips and Rumors**: Following others' advice (unreliable)
**Technical/Fundamental Analysis**: Can be systematized with rules

#### **Trading System Requirements**
**Quantifiable Rules**: Specific entry/exit criteria
**Backtestable**: Can test on historical data
**Systematic Execution**: Removes emotional decisions
**Parameter-Based**: Uses measurable inputs

---

## 🔄 **PAIR TRADING FUNDAMENTALS**

### **2. PAIR TRADING CONCEPT**

#### **Core Logic**
**Highway Analogy**: Two stocks move together like highway and service road
**Similar Companies**: Same sector, business model, market conditions
**Temporary Divergence**: Like tree blocking service road - creates opportunity
**Mean Reversion**: Relationship tends to normalize over time

#### **Pair Selection Criteria**
**Same Sector**: Banking, IT, pharma stocks within sector
**Similar Business**: Comparable products, services, customer base
**High Correlation**: Historical price correlation >0.8
**Liquidity**: Both stocks actively traded with tight spreads

---

## 📊 **PAIR TRADING METHOD 1: STATISTICAL APPROACH**

### **3. CORRELATION-BASED PAIR TRADING**

#### **Step 1: Pair Identification**
**Historical Analysis**: Analyze price correlation over 12-24 months
**Sector Screening**: Focus on stocks within same industry
**Market Cap**: Similar sized companies (avoid large-cap vs small-cap)

#### **Step 2: Ratio Calculation**
**Price Ratio**: Stock A ÷ Stock B
**Example**: HDFC Bank ÷ ICICI Bank = Current Ratio
**Time Series**: Track ratio changes over time
**Statistical Properties**: Calculate mean and standard deviation

#### **Step 3: Z-Score Analysis**
**Formula**: Z-Score = (Current Ratio - Mean Ratio) ÷ Standard Deviation
**Interpretation**:
- Z-Score > +2: Stock A overvalued relative to Stock B
- Z-Score < -2: Stock A undervalued relative to Stock B
- Z-Score ≈ 0: Normal relationship

#### **Step 4: Trading Signals**
**Entry Triggers**:
- Z-Score > +2.0: Short Stock A, Long Stock B
- Z-Score < -2.0: Long Stock A, Short Stock B

**Exit Triggers**:
- Z-Score returns to zero (mean reversion)
- Stop loss if Z-Score moves to ±3.0
- Time-based exit (e.g., 30 days maximum)

#### **Step 5: Position Sizing**
**Dollar Neutral**: Equal rupee amounts in both positions
**Risk Adjustment**: Consider individual stock volatilities
**Example**: ₹1,00,000 long + ₹1,00,000 short = Market neutral

---

## 📈 **PAIR TRADING METHOD 2: REGRESSION APPROACH**

### **4. LINEAR REGRESSION BASICS**

#### **Straight Line Equation**
**Formula**: Y = M × X + C
Where:
- Y = Dependent variable (Stock B)
- X = Independent variable (Stock A)  
- M = Slope (relationship strength)
- C = Intercept (constant)

#### **Simple Example**
```
X (Independent): 10, 12, 8, 9, 20, 18
Y (Dependent): 32, 38, 28, 30, 56, 52
```

**Pattern Recognition**: Y appears to be approximately 2.8 × X + 4
**Linear Relationship**: Strong positive correlation between X and Y

### **5. EXCEL-BASED LINEAR REGRESSION**

#### **Setup Process**
**Data Preparation**: Clean historical prices for both stocks
**Excel Tools**: Use Data Analysis → Regression function
**Input Requirements**:
- Y Range: Dependent variable (stock prices)
- X Range: Independent variable (stock prices)
- Output options: Select residuals and statistics

#### **Key Outputs**
**Coefficients**:
- **Intercept**: Constant term in equation
- **Slope**: X variable coefficient
- **R-squared**: Strength of relationship (0-1)

**Residuals**: Difference between actual and predicted values
**Standard Error**: Standard deviation of residuals
**Standard Error of Intercept**: Variance of intercept estimate

### **6. ERROR RATIO CALCULATION**

#### **Determining X and Y Variables**
**Challenge**: Which stock should be dependent vs independent?
**Solution**: Calculate error ratio for both configurations

#### **Error Ratio Formula**
**Error Ratio = Standard Error of Intercept ÷ Standard Error**

#### **Decision Process**
**Configuration 1**: HDFC as X, ICICI as Y
**Configuration 2**: ICICI as X, HDFC as Y
**Selection Rule**: Choose configuration with LOWER error ratio
**Reason**: Lower error ratio indicates stronger statistical relationship

#### **Example Calculation**
```
HDFC as X, ICICI as Y: Error Ratio = 0.227
ICICI as X, HDFC as Y: Error Ratio = 0.401
Selection: HDFC as X (independent), ICICI as Y (dependent)
```

### **7. RESIDUALS ANALYSIS**

#### **Residual Properties**
**Definition**: Actual Price - Predicted Price (from regression)
**Time Series**: Residuals form their own time series
**Mean Reversion**: Residuals tend to return to zero over time
**Trading Signals**: Based on residual deviations

#### **Standardized Residuals**
**Calculation**: Residual ÷ Standard Deviation of Residuals
**Z-Score Equivalent**: Similar interpretation to statistical Z-scores
**Trading Thresholds**: ±2 standard deviations for entry signals

#### **Stationarity Testing**
**ADF Test**: Augmented Dickey-Fuller test for stationarity
**Requirement**: Residuals must be stationary for mean reversion
**Interpretation**: P-value < 0.05 indicates stationarity
**Trading Validity**: Only trade pairs with stationary residuals

---

## 📅 **CALENDAR SPREADS**

### **8. CALENDAR SPREAD STRATEGY**

#### **Structure**
**Definition**: Options strategy using same strike, different expiries
**Setup**: Sell near-month option, buy far-month option
**Market View**: Neutral to slightly bullish/bearish

#### **Mechanics**
**Time Decay**: Near-month option decays faster
**Volatility Play**: Benefits from volatility expansion
**Optimal Outcome**: Stock price stays near strike at near-month expiry

#### **Risk-Reward Profile**
**Maximum Profit**: When stock trades at strike at expiry
**Maximum Loss**: Premium paid for the spread
**Break-even Points**: Strike ± net premium paid

#### **Calendar Spread Applications**
**Earnings Plays**: Before earnings announcements
**Low Volatility Periods**: When expecting volatility increase
**Range-bound Markets**: When expecting limited price movement

---

## 📊 **MOMENTUM PORTFOLIOS**

### **9. MOMENTUM STRATEGY FRAMEWORK**

#### **Momentum Concept**
**Definition**: Tendency of winning stocks to continue winning
**Scientific Basis**: Behavioral finance and market inefficiencies
**Time Horizon**: Typically 3-12 months for momentum persistence

#### **Momentum Portfolio Construction**
**Universe Selection**: Large-cap, liquid stocks (e.g., Nifty 500)
**Ranking Methodology**: Sort stocks by past performance
**Portfolio Formation**: Buy top performers, sell bottom performers
**Rebalancing**: Monthly or quarterly portfolio reconstruction

#### **Implementation Steps**
**Step 1**: Calculate returns for lookback period (e.g., 6 months)
**Step 2**: Rank all stocks by returns
**Step 3**: Select top 20% (winners) and bottom 20% (losers)
**Step 4**: Equal weight long positions in winners
**Step 5**: Equal weight short positions in losers

#### **Momentum Factors**
**Price Momentum**: Raw price returns over period
**Risk-Adjusted Momentum**: Returns adjusted for volatility
**Earnings Momentum**: Earnings surprise and revisions
**Technical Momentum**: Moving average and RSI-based signals

### **10. MOMENTUM PORTFOLIO METRICS**

#### **Performance Measurement**
**Sharpe Ratio**: Risk-adjusted returns
**Information Ratio**: Excess returns vs benchmark
**Maximum Drawdown**: Worst peak-to-trough decline
**Win Rate**: Percentage of profitable months

#### **Risk Management**
**Position Limits**: Maximum weight per stock (e.g., 5%)
**Sector Limits**: Maximum exposure per sector
**Turnover Control**: Limit transaction costs
**Stop Losses**: Individual position risk controls

---

## 🔧 **SYSTEMATIC TRADING IMPLEMENTATION**

### **11. BACKTESTING FRAMEWORK**

#### **Backtesting Requirements**
**Clean Data**: Adjusted for splits, bonuses, corporate actions
**Survivorship Bias**: Include delisted stocks in universe
**Look-ahead Bias**: Only use information available at time
**Transaction Costs**: Include brokerage, impact costs, taxes

#### **Backtesting Process**
**Data Preparation**: Clean and organize historical data
**Strategy Implementation**: Code trading rules and signals
**Performance Calculation**: Compute returns, risk metrics
**Sensitivity Analysis**: Test different parameters
**Out-of-sample Testing**: Validate on unseen data

#### **Key Metrics to Track**
**Absolute Returns**: Total returns generated
**Risk-Adjusted Returns**: Sharpe ratio, Sortino ratio
**Drawdown Analysis**: Maximum and average drawdowns
**Hit Ratio**: Percentage of winning trades
**Profit Factor**: Gross profit ÷ gross loss

### **12. TRADING SYSTEM DEVELOPMENT**

#### **System Design Principles**
**Simplicity**: Avoid over-optimization and complexity
**Robustness**: Should work across different market conditions
**Scalability**: Can handle larger capital efficiently
**Monitoring**: Regular performance tracking and maintenance

#### **Parameter Optimization**
**Grid Search**: Test multiple parameter combinations
**Walk-Forward Analysis**: Rolling optimization and testing
**Avoid Curve Fitting**: Don't over-optimize to historical data
**Economic Logic**: Parameters should make intuitive sense

#### **Risk Management Integration**
**Position Sizing**: Risk-based position sizing rules
**Portfolio Limits**: Maximum exposure and concentration
**Correlation Monitoring**: Track inter-position correlations
**Dynamic Hedging**: Adjust hedges based on market conditions

---

## 🎯 **PRACTICAL CONSIDERATIONS**

### **13. PAIR TRADING EXECUTION**

#### **Trade Implementation**
**Simultaneous Execution**: Enter both legs at same time
**Market Impact**: Consider liquidity and slippage
**Spread Monitoring**: Track relative performance continuously
**Exit Discipline**: Stick to predetermined exit rules

#### **Common Pitfalls**
**Over-leverage**: Using excessive leverage in "low-risk" strategy
**Correlation Breakdown**: Permanent structural changes
**Execution Lag**: Timing differences between legs
**Transaction Costs**: High turnover eating into profits

### **14. TECHNOLOGY REQUIREMENTS**

#### **Data Management**
**Historical Data**: Clean, corporate action-adjusted prices
**Real-time Feeds**: Live price feeds for monitoring
**Storage System**: Efficient data storage and retrieval
**Backup Systems**: Data redundancy and recovery

#### **Execution Systems**
**Order Management**: Automated order placement and management
**Risk Monitoring**: Real-time position and risk tracking
**Performance Attribution**: Track strategy performance
**Alerts and Notifications**: Exception and opportunity alerts

---

## ✅ **QUIZ SUCCESS STRATEGIES**

### **15. KEY CONCEPTS TO MEMORIZE**

#### **Pair Trading Formulas**
- **Z-Score** = (Current Ratio - Mean Ratio) ÷ Standard Deviation
- **Linear Regression**: Y = M × X + C
- **Error Ratio** = Standard Error of Intercept ÷ Standard Error
- **Residual** = Actual Price - Predicted Price

#### **Critical Thresholds**
- **Z-Score Entry**: ±2.0 standard deviations
- **Z-Score Exit**: Return to 0 (mean)
- **Correlation Requirement**: >0.8 for pair selection
- **ADF Test**: P-value <0.05 for stationarity

### **16. IMPORTANT CONCEPTS**

#### **Must-Know Principles**
**Mean Reversion**: Basis for pair trading profitability
**Stationarity**: Required for valid statistical arbitrage
**Cointegration**: Long-term equilibrium relationship
**Market Neutrality**: Dollar-neutral or beta-neutral positioning

#### **Statistical Requirements**
**Clean Data**: Adjusted for corporate actions
**Adequate History**: Minimum 1-2 years for analysis
**Liquidity**: Both stocks must be actively traded
**Stability**: Relationship should be persistent over time

### **17. COMMON EXAM TOPICS**

**Pair Trading Mechanics** (40%):
1. Correlation analysis and pair selection
2. Z-score calculation and interpretation
3. Linear regression setup and outputs
4. Residual analysis and stationarity testing

**Implementation Details** (30%):
1. Position sizing and risk management
2. Entry and exit signal generation
3. Error ratio calculation method
4. ADF test interpretation

**Strategy Concepts** (20%):
1. Calendar spread mechanics
2. Momentum portfolio construction
3. Statistical arbitrage principles
4. Market neutral strategies

**Practical Considerations** (10%):
1. Transaction costs and slippage
2. Technology and data requirements
3. Backtesting methodology
4. Risk management integration

### **18. CALCULATION PRACTICE TIPS**

#### **Step-by-Step Approach**
1. **Data Preparation**: Clean and align price series
2. **Statistical Analysis**: Calculate correlation, regression
3. **Signal Generation**: Compute Z-scores or residuals
4. **Risk Assessment**: Determine position sizes
5. **Performance Tracking**: Monitor P&L and risk metrics

#### **Common Mistakes to Avoid**
- **Ignoring Stationarity**: Trading non-stationary relationships
- **Over-optimization**: Curve-fitting to historical data
- **Execution Issues**: Not accounting for slippage and costs
- **Correlation Changes**: Not monitoring relationship stability

---

## 🏆 **ADVANCED CONCEPTS**

### **19. STATISTICAL ARBITRAGE**

#### **Beyond Pair Trading**
**Multi-Asset Models**: More than two securities
**Factor Models**: Based on risk factors (size, value, momentum)
**Machine Learning**: AI-driven pattern recognition
**High-Frequency Trading**: Millisecond execution strategies

### **20. PORTFOLIO MANAGEMENT**

#### **Risk Budgeting**
**Strategy Allocation**: Divide capital across different strategies
**Risk Parity**: Equal risk contribution from each strategy
**Dynamic Allocation**: Adjust based on market conditions
**Correlation Management**: Monitor inter-strategy correlations

### **21. REGIME DETECTION**

#### **Market Regime Analysis**
**Trend vs Mean-Reversion**: Identify current market state
**Volatility Regimes**: High vs low volatility periods
**Strategy Adaptation**: Adjust parameters for different regimes
**Dynamic Models**: Models that adapt to changing conditions

---

**REMEMBER**: Trading systems require systematic, quantifiable approaches that can be backtested and executed consistently. Pair trading exploits temporary deviations in normally correlated securities through statistical arbitrage. Linear regression and stationarity testing are crucial for validating trading relationships. Always account for transaction costs, market impact, and changing correlations in system development.

**EXAM FOCUS**: Master pair trading calculations (Z-scores, linear regression, error ratios), understand the difference between systematic and discretionary trading, practice statistical concepts like stationarity and cointegration, and know the implementation challenges of systematic strategies.

---
*Systems • Statistics • Execution • Performance*
*Quantify the Edge, Test the Logic, Execute with Discipline* 