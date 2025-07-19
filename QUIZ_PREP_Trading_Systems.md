# QUIZ PREP: Trading Systems & Algorithmic Strategies
*Based on Module 10: Trading Systems*

## 🎯 **TRADING SYSTEMS OVERVIEW**

### **1. WHAT ARE TRADING SYSTEMS?**

#### **Core Definition**
**Trading System**: Systematic approach to market analysis and trade execution based on predefined rules
**Objective**: Remove emotional bias and create consistent, repeatable trading process
**Components**: Entry rules, exit rules, position sizing, risk management
**Evolution**: From manual to algorithmic execution

#### **System Classification**
**Discretionary Systems**: Human judgment with systematic framework
**Algorithmic Systems**: Computer-executed based on mathematical rules
**Hybrid Systems**: Combination of systematic rules and human oversight
**High-Frequency Systems**: Ultra-fast automated execution systems

---

## 🔄 **SYSTEMATIC vs DISCRETIONARY TRADING COMPARISON**

### **2. TRADING APPROACH FUNDAMENTAL DIFFERENCES**

#### **Complete Trading Method Matrix**

| **Parameter** | **SYSTEMATIC TRADING** | **DISCRETIONARY TRADING** |
|---------------|----------------------|--------------------------|
| **Decision Making** | Rule-based, algorithmic | Human judgment and intuition |
| **Emotion Impact** | Minimal (rules-driven) | High (fear/greed influence) |
| **Consistency** | High consistency | Variable consistency |
| **Speed** | Very fast execution | Slower human processing |
| **Scalability** | Highly scalable | Limited by human capacity |
| **Market Adaptation** | Slower to adapt | Quick adaptation to changes |
| **Backtesting** | Extensive historical testing | Limited historical validation |
| **Capital Requirements** | Lower per-trade costs | Higher due to inefficiencies |
| **Skill Requirements** | Programming and statistics | Market intuition and experience |
| **Risk Management** | Built-in systematic controls | Human discipline required |

#### **Systematic Trading Advantages**
**Elimination of Emotional Bias**:
- No fear-based decisions
- Consistent execution regardless of market conditions
- Predetermined risk management
- Objective entry and exit criteria

**Scalability and Efficiency**:
- Can monitor multiple markets simultaneously
- Execute thousands of trades consistently
- Operate 24/7 without fatigue
- Process vast amounts of data quickly

**Backtesting and Optimization**:
- Historical performance validation
- Statistical confidence in results
- Parameter optimization
- Risk metrics calculation

#### **Discretionary Trading Advantages**
**Market Intuition and Adaptation**:
- Quick adaptation to changing market conditions
- Ability to recognize unique patterns
- Integration of qualitative factors
- Experience-based judgment calls

**Flexibility and Creativity**:
- Ability to deviate from rules when necessary
- Incorporate breaking news and events
- Adjust to unprecedented market conditions
- Creative strategy development

#### **Hybrid Approach Benefits**
**Best of Both Worlds**:
- Systematic framework with human oversight
- Rules-based entries with discretionary exits
- Algorithmic screening with manual selection
- Systematic risk management with tactical adjustments

---

## 📊 **PAIR TRADING STRATEGIES COMPARISON**

### **3. STATISTICAL ARBITRAGE TECHNIQUES**

#### **Pair Trading Method Matrix**

| **METHOD** | **STATISTICAL BASIS** | **COMPLEXITY** | **SIGNAL GENERATION** | **STABILITY** |
|------------|---------------------|---------------|---------------------|---------------|
| **Correlation-Based** | Historical correlation | Low | Price divergence | Moderate |
| **Cointegration** | Long-term relationship | High | Error correction model | High |
| **Regression-Based** | Linear regression | Medium | Residual analysis | Good |
| **Distance Method** | Normalized distance | Low | Distance threshold | Moderate |

#### **Correlation vs Cointegration Analysis**

**Correlation-Based Pairs**:
- **Concept**: Stocks move together historically
- **Measurement**: Correlation coefficient (-1 to +1)
- **Threshold**: Typically >0.7 for pairs
- **Problem**: Correlation can be spurious
- **Example**: High correlation doesn't guarantee relationship continues

**Cointegration-Based Pairs**:
- **Concept**: Long-term economic relationship between stocks
- **Measurement**: Augmented Dickey-Fuller test
- **Advantage**: Statistically robust relationship
- **Complexity**: Requires advanced statistical knowledge
- **Stability**: More reliable long-term trading signals

#### **Spread Calculation Methods**

**Simple Spread**:
- **Formula**: Spread = Price(A) - Price(B)
- **Use Case**: Similar-priced stocks
- **Problem**: Doesn't account for different price levels

**Ratio Spread**:
- **Formula**: Spread = Price(A) / Price(B)
- **Use Case**: Different price level stocks
- **Advantage**: Scale-independent

**Log Spread**:
- **Formula**: Spread = ln(Price(A)) - ln(Price(B))
- **Use Case**: Statistical modeling
- **Advantage**: Normally distributed returns

**Regression-Based Spread**:
- **Formula**: Spread = Price(A) - β × Price(B)
- **Beta**: Regression coefficient
- **Advantage**: Accounts for different volatilities

---

## 📈 **MOMENTUM vs MEAN REVERSION SYSTEMS**

### **4. CONTRASTING TRADING PHILOSOPHIES**

#### **System Philosophy Comparison Matrix**

| **Aspect** | **MOMENTUM SYSTEMS** | **MEAN REVERSION SYSTEMS** |
|------------|---------------------|----------------------------|
| **Core Belief** | Trends continue | Prices return to average |
| **Market View** | Trending markets | Range-bound markets |
| **Signal Type** | Breakouts, trend following | Overbought/oversold |
| **Risk Profile** | Large wins, frequent small losses | Frequent small wins, large losses |
| **Win Rate** | Lower (30-45%) | Higher (60-75%) |
| **Average Win/Loss** | Large wins, small losses | Small wins, large losses |
| **Market Conditions** | Bull/bear trending markets | Sideways, choppy markets |
| **Time Horizon** | Medium to long-term | Short to medium-term |

#### **Momentum Strategy Characteristics**

**Trend Following Indicators**:
- **Moving Average Crossovers**: Golden cross, death cross
- **Breakout Systems**: Price breaking resistance/support
- **Momentum Indicators**: RSI, MACD divergence
- **Volume Confirmation**: High volume breakouts

**Momentum System Advantages**:
- **Large Profit Potential**: Captures big market moves
- **Compound Growth**: Riding long-term trends
- **Market Direction Agnostic**: Works in bull and bear markets
- **Objective Rules**: Clear entry and exit signals

**Momentum System Challenges**:
- **Whipsaws**: False breakouts in sideways markets
- **Lower Win Rate**: More losing trades than winners
- **Drawdown Periods**: Extended periods of poor performance
- **Late Entry**: Often enter after significant move

#### **Mean Reversion Strategy Characteristics**

**Mean Reversion Indicators**:
- **Bollinger Bands**: Price touching bands
- **RSI Extremes**: >70 overbought, <30 oversold
- **Standard Deviation**: Price deviation from mean
- **Support/Resistance**: Historical price levels

**Mean Reversion Advantages**:
- **High Win Rate**: More profitable trades
- **Quick Profits**: Faster trade resolution
- **Range-Bound Markets**: Performs well in sideways markets
- **Psychological Comfort**: More winning trades

**Mean Reversion Challenges**:
- **Trend Risk**: Losses in strong trending markets
- **Large Losses**: Occasional devastating losses
- **Market Timing**: Requires precise entry/exit timing
- **Capacity Constraints**: Limited scalability

---

## 🔬 **STATISTICAL MODELS COMPARISON**

### **5. QUANTITATIVE ANALYSIS TECHNIQUES**

#### **Statistical Method Matrix**

| **MODEL** | **PURPOSE** | **COMPLEXITY** | **DATA REQUIREMENTS** | **ACCURACY** |
|-----------|-------------|----------------|---------------------|--------------|
| **Linear Regression** | Relationship modeling | Low | Moderate | Good for linear relationships |
| **ARIMA** | Time series forecasting | Medium | High | Good for stationary data |
| **GARCH** | Volatility modeling | High | High | Excellent for volatility |
| **Machine Learning** | Pattern recognition | Very High | Very High | Excellent with big data |

#### **Linear Regression in Trading**

**Simple Linear Regression**:
- **Formula**: Y = α + βX + ε
- **Application**: Stock A vs Stock B relationship
- **R-squared**: Measure of relationship strength
- **Residuals**: Trading signals from prediction errors

**Multiple Regression**:
- **Formula**: Y = α + β₁X₁ + β₂X₂ + ... + ε
- **Application**: Multiple factor models
- **Advantages**: Consider multiple variables
- **Challenges**: Multicollinearity issues

#### **Time Series Analysis Comparison**

**ARIMA Models**:
- **AR (Autoregressive)**: Current value depends on past values
- **I (Integrated)**: Data is differenced to achieve stationarity
- **MA (Moving Average)**: Current value depends on past errors
- **Application**: Price forecasting and trend analysis

**GARCH Models**:
- **Purpose**: Model changing volatility over time
- **Application**: Risk management and option pricing
- **Advantage**: Captures volatility clustering
- **Complexity**: Requires advanced statistical knowledge

---

## 💻 **ALGORITHMIC TRADING IMPLEMENTATION**

### **6. SYSTEM DEVELOPMENT COMPARISON**

#### **Development Platform Matrix**

| **PLATFORM** | **COST** | **COMPLEXITY** | **CUSTOMIZATION** | **BACKTESTING** |
|--------------|----------|----------------|------------------|-----------------|
| **Excel/VBA** | Low | Low | Limited | Basic |
| **Python** | Low | Medium | High | Excellent |
| **R** | Low | Medium | High | Good |
| **C++** | Low | High | Very High | Excellent |
| **Commercial Platforms** | High | Low | Limited | Good |

#### **Programming Language Comparison**

**Python Advantages**:
- **Ease of Learning**: Beginner-friendly syntax
- **Libraries**: Pandas, NumPy, scikit-learn
- **Community**: Large trading community
- **Integration**: Easy API connections
- **Backtesting**: Comprehensive frameworks

**R Advantages**:
- **Statistical Analysis**: Superior statistical capabilities
- **Visualization**: Excellent charting capabilities
- **Academic Research**: Preferred in academia
- **Time Series**: Advanced time series analysis
- **Package Ecosystem**: Comprehensive statistical packages

**C++ Advantages**:
- **Speed**: Fastest execution
- **Low Latency**: Critical for HFT
- **Memory Management**: Efficient resource usage
- **Professional**: Industry standard for speed-critical applications

#### **Backtesting Framework Comparison**

**Walk-Forward Analysis**:
- **Method**: Rolling optimization periods
- **Advantage**: More realistic performance
- **Implementation**: Complex but robust
- **Purpose**: Avoid over-optimization

**Monte Carlo Simulation**:
- **Method**: Random trade sequence generation
- **Purpose**: Assess strategy robustness
- **Metrics**: Maximum drawdown distribution
- **Advantage**: Risk assessment under various scenarios

---

## 📊 **PORTFOLIO vs SINGLE ASSET SYSTEMS**

### **7. SYSTEM SCOPE COMPARISON**

#### **Trading System Scope Matrix**

| **SYSTEM TYPE** | **SINGLE ASSET** | **PORTFOLIO SYSTEM** |
|-----------------|------------------|---------------------|
| **Complexity** | Lower | Higher |
| **Diversification** | None | Built-in |
| **Risk Management** | Individual position | Portfolio-wide |
| **Correlation** | Not considered | Critical factor |
| **Scalability** | Limited | High |
| **Capital Efficiency** | Lower | Higher |
| **Monitoring** | Single asset focus | Multiple asset tracking |

#### **Single Asset System Characteristics**

**Advantages**:
- **Simplicity**: Easier to develop and understand
- **Focus**: Deep analysis of single instrument
- **Speed**: Faster decision making
- **Specialization**: Expertise in specific market

**Disadvantages**:
- **Concentration Risk**: All eggs in one basket
- **Market Dependency**: Performance tied to single market
- **Limited Opportunities**: Fewer trading signals
- **Volatility**: Higher portfolio volatility

#### **Portfolio System Characteristics**

**Advantages**:
- **Diversification**: Risk spread across multiple assets
- **Opportunity**: More trading opportunities
- **Smoother Returns**: Reduced portfolio volatility
- **Market Neutral**: Less market direction dependency

**Disadvantages**:
- **Complexity**: More complex to develop and manage
- **Correlation Risk**: Assets may correlate during crises
- **Capital Requirements**: Higher capital needed
- **Transaction Costs**: Multiple positions increase costs

---

## 🎯 **STRATEGY PERFORMANCE EVALUATION**

### **8. SYSTEM PERFORMANCE METRICS COMPARISON**

#### **Performance Measurement Matrix**

| **METRIC** | **CALCULATION** | **PURPOSE** | **INTERPRETATION** |
|------------|-----------------|-------------|-------------------|
| **Total Return** | (End Value - Start Value) / Start Value | Overall performance | Higher is better |
| **Sharpe Ratio** | (Return - Risk-free rate) / Volatility | Risk-adjusted return | >1 is good, >2 excellent |
| **Maximum Drawdown** | Peak to trough decline | Worst-case loss | Lower is better |
| **Win Rate** | Winning trades / Total trades | Strategy consistency | Higher generally better |
| **Profit Factor** | Gross profit / Gross loss | Strategy efficiency | >1.5 preferred |

#### **Strategy Comparison Framework**

**Momentum Strategy Metrics**:
- **Lower Win Rate**: 35-45% typical
- **Higher Average Win**: Large profitable trades
- **Longer Drawdowns**: Extended losing periods
- **Trend Dependency**: Performance varies with market regime

**Mean Reversion Metrics**:
- **Higher Win Rate**: 60-75% typical
- **Smaller Average Win**: Quick, small profits
- **Shorter Drawdowns**: Quick recovery
- **Range Dependency**: Performance in sideways markets

#### **Risk-Adjusted Performance**

**Sortino Ratio**:
- **Focus**: Downside volatility only
- **Advantage**: More relevant for investors
- **Calculation**: Return / Downside deviation
- **Preference**: Higher values better

**Calmar Ratio**:
- **Focus**: Return relative to maximum drawdown
- **Calculation**: Annual return / Maximum drawdown
- **Purpose**: Drawdown-adjusted performance
- **Interpretation**: Higher values preferred

---

## ✅ **ENHANCED QUIZ STRATEGIES**

### **9. TRADING SYSTEMS EXAM PREPARATION**

#### **Expected Question Types**
**System Classification** (25%):
1. Systematic vs discretionary trading differences
2. Momentum vs mean reversion characteristics
3. Single asset vs portfolio system comparison
4. Algorithmic vs manual execution

**Statistical Methods** (25%):
1. Correlation vs cointegration analysis
2. Linear regression applications
3. Time series analysis methods
4. Backtesting framework evaluation

**Pair Trading** (20%):
1. Spread calculation methods
2. Signal generation techniques
3. Risk management in pairs
4. Statistical relationship validation

**Performance Evaluation** (20%):
1. Strategy performance metrics
2. Risk-adjusted return measures
3. Drawdown analysis
4. Strategy comparison frameworks

#### **Critical Concepts for Exams**
- **Correlation Threshold**: >0.7 for pair trading
- **Cointegration**: Long-term statistical relationship
- **Sharpe Ratio**: >1 good, >2 excellent
- **Win Rate**: Momentum 35-45%, Mean reversion 60-75%
- **Maximum Drawdown**: Key risk metric
- **Profit Factor**: >1.5 preferred minimum

#### **Statistical Formula Reference**
- **Correlation**: Cov(X,Y) / (σₓ × σᵧ)
- **Sharpe Ratio**: (Rₚ - Rᶠ) / σₚ
- **Beta**: Cov(stock, market) / Var(market)
- **Linear Regression**: Y = α + βX + ε
- **R-squared**: 1 - (SSᵣₑₛ / SSₜₒₜ)

---

## 🏆 **ADVANCED TRADING SYSTEM CONCEPTS**

### **10. INSTITUTIONAL LEVEL SYSTEMS**

#### **High-Frequency vs Low-Frequency Trading**

| **PARAMETER** | **HIGH-FREQUENCY** | **LOW-FREQUENCY** |
|---------------|-------------------|------------------|
| **Holding Period** | Milliseconds to minutes | Days to months |
| **Technology** | Ultra-low latency | Standard systems |
| **Capital Requirements** | Very high | Moderate |
| **Profit per Trade** | Very small | Larger |
| **Volume** | Very high | Moderate |
| **Risk** | Technology and execution | Market and strategy |

#### **Machine Learning in Trading**

**Supervised Learning**:
- **Classification**: Buy/sell/hold decisions
- **Regression**: Price prediction
- **Examples**: Random Forest, SVM, Neural Networks
- **Data**: Historical prices, fundamentals, sentiment

**Unsupervised Learning**:
- **Clustering**: Market regime identification
- **Dimensionality Reduction**: Factor analysis
- **Examples**: K-means, PCA
- **Purpose**: Pattern discovery

**Reinforcement Learning**:
- **Application**: Dynamic strategy optimization
- **Advantage**: Adapts to changing markets
- **Complexity**: Very high implementation difficulty
- **Future**: Emerging area in trading

#### **Alternative Data Integration**

**Traditional Data vs Alternative Data**:
- **Traditional**: Price, volume, fundamentals
- **Alternative**: Satellite data, social sentiment, news
- **Advantage**: Information edge and alpha generation
- **Challenge**: Data quality and integration complexity

---

**REMEMBER**: Trading systems provide consistency and remove emotional bias from trading decisions. The choice between momentum and mean reversion depends on market conditions and personal preference. Backtesting is crucial but beware of over-optimization. Statistical validation is essential for pair trading strategies.

---

## 🔢 **DETAILED MATHEMATICAL CALCULATIONS**

### **11. STEP-BY-STEP TRADING SYSTEM CALCULATIONS**

#### **Pair Trading - Complete Mathematical Example**

**Stock Selection**: HDFC Bank (X - Independent) vs ICICI Bank (Y - Dependent)

**Step 1: Linear Regression Analysis**
```
Given Historical Data (252 trading days):
HDFC Bank closing prices: [₹1,400, ₹1,425, ₹1,440, ...]
ICICI Bank closing prices: [₹291, ₹295, ₹298, ...]

Linear Regression Equation: Y = mX + c
Where: ICICI = β × HDFC + α
```

**Step 2: Calculate Error Ratios for Both Combinations**
```
Combination 1: HDFC as X, ICICI as Y
- Standard Error of Intercept: 45.8
- Standard Error of Residuals: 12.3
- Error Ratio = 45.8 ÷ 12.3 = 3.72

Combination 2: ICICI as X, HDFC as Y  
- Standard Error of Intercept: 127.4
- Standard Error of Residuals: 42.6
- Error Ratio = 127.4 ÷ 42.6 = 2.99

Selection: Choose Combination 2 (lower error ratio)
Final Assignment: ICICI = X (Independent), HDFC = Y (Dependent)
```

**Step 3: Final Regression Output**
```
HDFC = 7.613 × ICICI - 663.677

Key Statistics:
- Beta (β): 7.613
- Intercept (α): -663.677
- R-squared: 0.94
- Standard Error: 22.776
- Observations: 252
```

**Step 4: Calculate Residuals and Test Stationarity**
```
For each day: Residual = Actual HDFC - Predicted HDFC
Residual = HDFC_actual - (7.613 × ICICI - 663.677)

Example for Day 1:
HDFC_actual = ₹1,914
ICICI = ₹291
Predicted HDFC = 7.613 × 291 - 663.677 = ₹1,551
Residual = ₹1,914 - ₹1,551 = ₹363
```

**Step 5: ADF Test for Stationarity**
```
Null Hypothesis: Series has unit root (non-stationary)
Alternative: Series is stationary

ADF Test Result:
- ADF Statistic: -3.84
- P-value: 0.012
- Critical Value (5%): -2.87

Conclusion: P-value < 0.05, reject null hypothesis
Residuals are stationary → Stocks are cointegrated
```

**Step 6: Calculate Trading Signals**
```
Residual Statistics:
- Mean: 0.52
- Standard Deviation: 22.78
- Current Residual: -57.8

Z-Score = (Current Residual - Mean) ÷ Standard Deviation
        = (-57.8 - 0.52) ÷ 22.78
        = -2.56

Trading Signal: Z-score < -2.5 → Long Pair Signal
```

#### **Pair Trading Position Sizing Example**

**Trade Setup based on above signals:**
```
Signal: Long Pair (Buy HDFC, Sell ICICI)
Beta Ratio: 7.613 (need 7.613 ICICI shares for 1 HDFC share)

Position Sizing:
Available Capital: ₹10,00,000
Risk per Trade: 2% = ₹20,000

Current Prices:
HDFC: ₹1,914
ICICI: ₹291

For 1:7.613 Ratio:
Cost of 1 HDFC + Margin for 7.613 ICICI short
= ₹1,914 + (7.613 × ₹291 × 20% margin)
= ₹1,914 + ₹444
= ₹2,358 per set

Maximum Sets = ₹10,00,000 ÷ ₹2,358 = 424 sets
Conservative Approach: Use 10% = 42 sets

Final Position:
Long: 42 shares of HDFC = ₹80,388
Short: 320 shares of ICICI (42 × 7.613)
```

#### **Momentum Portfolio Construction - Mathematical Process**

**Universe Selection**: BSE 500 stocks (tracking universe)

**Step 1: Return Calculation (1-Year Period)**
```
Example Stocks and Returns:
Stock A: Start ₹1,000, End ₹1,350 → Return = (1,350-1,000)/1,000 = 35%
Stock B: Start ₹500, End ₹520 → Return = (520-500)/500 = 4%
Stock C: Start ₹800, End ₹720 → Return = (720-800)/800 = -10%
```

**Step 2: Ranking Process**
```
Sort 500 stocks by return (highest to lowest):
Rank 1: Asian Paints (+45.2%)
Rank 2: HDFC Bank (+38.7%)
Rank 3: Infosys (+32.1%)
...
Rank 498: Stock X (-18.4%)
Rank 499: Stock Y (-22.8%)
Rank 500: Stock Z (-28.5%)
```

**Step 3: Portfolio Selection**
```
Select Top 15 stocks (Top 3% of universe)
Selected Portfolio:
1. Asian Paints: +45.2%
2. HDFC Bank: +38.7%
3. Infosys: +32.1%
...
15. TCS: +24.8%
```

**Step 4: Equal Weight Allocation**
```
Portfolio Size: ₹15,00,000
Per Stock Allocation = ₹15,00,000 ÷ 15 = ₹1,00,000

Position Sizes:
Asian Paints: ₹1,00,000 ÷ ₹2,450 = 41 shares
HDFC Bank: ₹1,00,000 ÷ ₹1,680 = 60 shares
Infosys: ₹1,00,000 ÷ ₹1,250 = 80 shares
... and so on
```

#### **Performance Metrics Calculation Examples**

**Sharpe Ratio Calculation**
```
Portfolio Performance Data:
Annual Return: 18.5%
Risk-free Rate: 7%
Portfolio Volatility: 16.8%

Sharpe Ratio = (Portfolio Return - Risk-free Rate) ÷ Portfolio Volatility
             = (18.5% - 7%) ÷ 16.8%
             = 11.5% ÷ 16.8%
             = 0.685

Interpretation: Good risk-adjusted returns (>0.5 acceptable, >1.0 excellent)
```

**Maximum Drawdown Calculation**
```
Portfolio Value Journey:
Start: ₹10,00,000
Peak: ₹13,20,000 (Month 8)
Trough: ₹10,56,000 (Month 11)
Recovery: ₹13,80,000 (Month 15)

Maximum Drawdown = (Peak - Trough) ÷ Peak
                 = (₹13,20,000 - ₹10,56,000) ÷ ₹13,20,000
                 = ₹2,64,000 ÷ ₹13,20,000
                 = 20%

Recovery Time = Month 15 - Month 8 = 7 months
```

**Win Rate Analysis**
```
Trading System Performance (50 trades):
Winning Trades: 32
Losing Trades: 18

Win Rate = Winning Trades ÷ Total Trades
         = 32 ÷ 50
         = 64%

Average Win: ₹3,500
Average Loss: ₹2,100
Profit Factor = (Win Rate × Avg Win) ÷ (Loss Rate × Avg Loss)
              = (0.64 × ₹3,500) ÷ (0.36 × ₹2,100)
              = ₹2,240 ÷ ₹756
              = 2.96 (Excellent - Above 2.0 preferred)
```

#### **Calendar Spread Calculation Example**

**Nifty Calendar Spread Setup:**
```
Current Nifty: 17,800
Current Month Future: 17,825 (25 points premium)
Next Month Future: 17,860 (60 points premium)
Spread = 17,860 - 17,825 = 35 points

Trade Setup: Sell Current Month, Buy Next Month
Capital Required: Spread margin ≈ ₹40,000 per lot

Profit Scenarios:
If spread narrows to 25 points: Profit = 35 - 25 = 10 points = ₹750
If spread widens to 45 points: Loss = 45 - 35 = 10 points = ₹750

Historical Analysis:
Spread usually trades between 20-50 points
Current 35 points is near middle of range
Mean reversion expected
```

#### **Risk Management Calculations**

**Portfolio Risk Analysis:**
```
Individual Stock Weights and Volatilities:
Stock A: 20% weight, 25% volatility
Stock B: 30% weight, 18% volatility  
Stock C: 50% weight, 22% volatility

Correlation Matrix:
A-B: 0.65, A-C: 0.58, B-C: 0.72

Portfolio Variance = Σ(Wi² × σi²) + Σ(2×Wi×Wj×σi×σj×ρij)
                   = (0.2²×25²) + (0.3²×18²) + (0.5²×22²) + 
                     2×(0.2×0.3×25×18×0.65) + 2×(0.2×0.5×25×22×0.58) + 
                     2×(0.3×0.5×18×22×0.72)
                   = 25 + 29.16 + 121 + 35.1 + 63.8 + 85.54
                   = 359.6

Portfolio Volatility = √359.6 = 18.96%
```

**EXAM FOCUS**: Master the differences between systematic and discretionary approaches, understand the statistical concepts behind pair trading, know the characteristics of momentum vs mean reversion systems, and be familiar with performance evaluation metrics. System development and testing methodologies are increasingly important in modern trading.

---
*Systematic • Statistical • Backtested • Optimized*
*Code the Rules, Test the Logic, Trade the System* 