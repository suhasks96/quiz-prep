# QUIZ PREP: Risk Management & Trading Psychology
*Based on Module 9: Risk Management & Trading Psychology*

## 🎯 **RISK MANAGEMENT FUNDAMENTALS**

### **1. UNDERSTANDING RISK**

#### **Definition of Risk**
**Market Risk**: Probability of losing money in financial markets
**Risk-Return Trade-off**: Higher returns typically require accepting higher risk
**Risk Categories**: Systematic risk (market-wide) and unsystematic risk (company-specific)

#### **The 80-20 Rule**
**Mark Douglas Principle**: Successful trading is 80% money management and 20% strategy
**Implication**: Risk management skills more important than trading strategies
**Reality Check**: Small group makes money consistently, large group loses consistently

#### **Risk Management Levels**
**Single Position Risk**: Managing individual trade risk
**Multiple Position Risk**: Portfolio-level risk management
**Portfolio Risk**: Overall portfolio risk and correlation effects

---

## 📊 **TYPES OF RISK**

### **2. SYSTEMATIC VS UNSYSTEMATIC RISK**

#### **Unsystematic Risk (Company-Specific)**
**Definition**: Risk specific to individual companies or sectors
**Examples**:
- **Management Issues**: Leadership changes, misconduct
- **Business Performance**: Revenue decline, margin compression
- **Sector Events**: Regulatory changes affecting specific industry
- **Competition**: Market share loss to competitors

**Management**: Can be reduced through diversification

#### **Systematic Risk (Market-Wide)**
**Definition**: Risk that affects entire market simultaneously
**Examples**:
- **Economic Factors**: GDP growth, inflation, interest rates
- **Political Events**: Elections, policy changes, geopolitical tensions
- **Market Crashes**: 2008 financial crisis, COVID-19 pandemic

**Management**: Cannot be diversified away, requires hedging strategies

### **3. DIVERSIFICATION PRINCIPLES**

#### **Optimal Portfolio Size**
**Research Finding**: 15-21 stocks provide optimal diversification
**Diminishing Returns**: Beyond 21 stocks, additional benefit minimal
**Cost-Benefit**: More stocks increase tracking complexity

#### **Diversification Methods**
**Sector Diversification**: Different industries and business cycles
**Geographic Diversification**: Multiple regions and countries
**Asset Class Diversification**: Stocks, bonds, commodities, real estate
**Time Diversification**: Dollar-cost averaging and systematic investing

---

## 💰 **POSITION SIZING FUNDAMENTALS**

### **4. EQUITY ESTIMATION MODELS**

#### **Core Equity Model**
**Formula**: Available Capital = Total Equity - Margin Blocked
**Application**: Deduct allocated capital from total for next trade
**Example**: ₹5,00,000 total - ₹90,000 blocked = ₹4,10,000 available

#### **Total Equity Model**
**Formula**: Total Equity = Free Cash + Margin Blocked + Unrealized P&L
**Application**: Consider entire account value including open positions
**Advantage**: Accounts for mark-to-market gains/losses

#### **Reduced Total Equity Model**
**Formula**: Available Capital = Free Cash + Locked Profits
**Application**: Only count locked-in profits from open positions
**Advantage**: Forces disciplined stop-loss implementation
**Example**: ₹4,10,000 + ₹10,000 locked profits = ₹4,20,000

### **5. POSITION SIZING TECHNIQUES**

#### **Unit Per Fixed Amount**
**Method**: Fix number of lots/shares per ₹X capital
**Example**: 1 lot per ₹1,00,000 capital
**Advantages**: Simple to implement and understand
**Disadvantages**: 
- Ignores individual asset risk (volatility)
- Limits scalability
- Equal weight assignment regardless of risk

#### **Percentage Margin**
**Method**: Fix maximum margin percentage per trade
**Example**: Never exceed 20% of capital as margin
**Calculation**: ₹5,00,000 × 20% = ₹1,00,000 maximum margin per trade
**Advantages**: Margin-based risk control
**Disadvantages**: Ignores volatility differences between assets

#### **Percentage Volatility**
**Method**: Equal volatility exposure across positions
**Calculation**: Uses Average True Range (ATR) for volatility
**Example**: 
- Capital: ₹5,00,000, Max volatility exposure: 2%
- Stock ATR: ₹76, Max risk: ₹10,000
- Position Size: ₹10,000 ÷ ₹76 = 131 shares

**Advantages**: Equal risk exposure regardless of asset
**Disadvantages**: May require fractional positions

#### **Percentage Risk**
**Method**: Risk fixed percentage of capital per trade
**Rule**: Never risk more than 1-3% capital per trade
**Calculation**:
```
Entry: ₹393.65, Stop Loss: ₹390, Capital: ₹5,00,000
Risk per share: ₹393.65 - ₹390 = ₹3.65
Max Risk: ₹5,00,000 × 1.5% = ₹7,500
Position Size: ₹7,500 ÷ (₹3.65 × lot size) = Number of lots
```

**Professional Standard**: Most professional traders use this method

---

## 🎲 **KELLY'S CRITERION**

### **6. OPTIMAL BET SIZING**

#### **Kelly Formula**
**Formula**: Kelly % = W - [(1-W)/R]
Where:
- **W** = Win Rate (winning trades ÷ total trades)
- **R** = Win/Loss Ratio (average win ÷ average loss)

#### **Kelly Calculation Example**
```
Trading System Results:
- Total Trades: 10
- Winning Trades: 6
- Average Win: ₹4,532
- Average Loss: ₹3,274

W = 6/10 = 0.6
R = 4,532/3,274 = 1.384
Kelly % = 0.6 - [(1-0.6)/1.384] = 0.6 - 0.289 = 0.311 = 31%
```

#### **Modified Kelly Approach**
**Problem**: Pure Kelly can suggest excessive position sizes
**Solution**: Cap maximum position size (e.g., 5% of capital)
**Application**: Use Kelly % of capped amount
- Kelly 30% → 30% of 5% cap = 1.5% position
- Kelly 70% → 70% of 5% cap = 3.5% position

---

## 📈 **PORTFOLIO RISK ANALYSIS**

### **7. VALUE AT RISK (VaR)**

#### **VaR Definition**
**Concept**: Maximum expected loss over specific time period at given confidence level
**Example**: "95% confident that portfolio won't lose more than ₹50,000 in one day"

#### **VaR Calculation Methods**
**Historical Method**: Use past return distribution
**Parametric Method**: Assume normal distribution
**Monte Carlo Method**: Simulate thousands of scenarios

#### **VaR Limitations**
**Tail Risk**: Doesn't capture extreme loss scenarios
**Model Risk**: Based on historical data and assumptions
**Correlation Changes**: Relationships change during crises

### **8. EQUITY CURVE ANALYSIS**

#### **Equity Curve Importance**
**Definition**: Plot of portfolio value over time
**Analysis**: Reveals system performance and characteristics
**Smoothness**: Indicates consistency of returns

#### **Equity Curve Metrics**
**Maximum Drawdown**: Largest peak-to-trough decline
**Recovery Time**: Time to reach new equity high
**Drawdown Duration**: Length of underwater periods
**Sharpe Ratio**: Risk-adjusted return measure

---

## 🧠 **TRADING PSYCHOLOGY**

### **9. COGNITIVE BIASES**

#### **Confirmation Bias**
**Definition**: Seeking information that confirms existing beliefs
**Trading Impact**: Ignoring negative news about held positions
**Solution**: Actively seek contradictory evidence

#### **Anchoring Bias**
**Definition**: Over-relying on first piece of information
**Trading Impact**: Fixating on purchase price or recent high/low
**Solution**: Use systematic analysis methods

#### **Loss Aversion**
**Definition**: Feeling losses more intensely than equivalent gains
**Trading Impact**: Holding losing positions too long, taking profits too early
**Solution**: Set systematic stop-losses and profit targets

#### **Overconfidence Bias**
**Definition**: Overestimating ability to predict outcomes
**Trading Impact**: Excessive trading, inadequate risk management
**Solution**: Track performance metrics, maintain trading journal

#### **Herd Mentality**
**Definition**: Following crowd behavior
**Trading Impact**: Buying at tops, selling at bottoms
**Solution**: Contrarian analysis, independent research

### **10. EMOTIONAL CONTROL**

#### **Fear and Greed Cycle**
**Fear Emotions**: Panic selling, paralysis, over-caution
**Greed Emotions**: FOMO trading, excessive risk-taking
**Balance**: Systematic approach reduces emotional decisions

#### **Trading Psychology Rules**
**Rule 1**: Never trade based on emotions
**Rule 2**: Stick to predetermined plan
**Rule 3**: Accept losses as part of business
**Rule 4**: Don't revenge trade after losses
**Rule 5**: Take breaks after significant wins/losses

---

## 🛡️ **PRACTICAL RISK MANAGEMENT**

### **11. POSITION SIZING IN PRACTICE**

#### **Multi-Asset Portfolio Example**
```
Portfolio: ₹10,00,000
Risk per trade: 2%
Max positions: 5

Trade 1 - Nifty Futures:
Entry: 18,000, Stop: 17,800, Lot size: 75
Risk per lot: (18,000-17,800) × 75 = ₹15,000
Max risk: ₹10,00,000 × 2% = ₹20,000
Position: ₹20,000 ÷ ₹15,000 = 1.33 → 1 lot

Remaining capital: ₹10,00,000 - ₹13,50,000 = ₹-3,50,000 (leveraged)
```

#### **Leverage Management**
**Maximum Leverage**: Never exceed 3:1 for equity, 2:1 for derivatives
**Margin Buffer**: Keep 20-30% cash buffer for mark-to-market
**Position Correlation**: Avoid highly correlated positions

### **12. STOP LOSS STRATEGIES**

#### **Stop Loss Types**
**Fixed Percentage**: 5-10% below entry price
**Technical Stops**: Based on support/resistance levels
**Volatility Stops**: ATR-based dynamic stops
**Time Stops**: Exit after predetermined time period

#### **Stop Loss Placement Rules**
**Support/Resistance**: Place beyond key technical levels
**Volatility**: Allow normal price fluctuation room
**Risk-Reward**: Ensure minimum 1:2 risk-reward ratio
**Portfolio Impact**: Consider correlation with other positions

---

## 📊 **PERFORMANCE MEASUREMENT**

### **13. RISK-ADJUSTED RETURNS**

#### **Sharpe Ratio**
**Formula**: (Portfolio Return - Risk-free Rate) ÷ Portfolio Standard Deviation
**Interpretation**: Higher is better (>1 is good, >2 is excellent)
**Application**: Compare different strategies or time periods

#### **Maximum Drawdown**
**Calculation**: (Peak Value - Trough Value) ÷ Peak Value × 100
**Importance**: Measures worst-case scenario experience
**Professional Standard**: Keep below 20% for most strategies

#### **Calmar Ratio**
**Formula**: Annual Return ÷ Maximum Drawdown
**Application**: Risk-adjusted performance over longer periods
**Advantage**: Focuses on downside risk specifically

### **14. PORTFOLIO MONITORING**

#### **Daily Risk Checks**
**Position Size**: Verify no position exceeds limits
**Correlation**: Check for concentration risk
**Drawdown**: Monitor current drawdown levels
**Volatility**: Track portfolio volatility changes

#### **Monthly Portfolio Review**
**Performance Attribution**: Which positions contributed to results
**Risk Metrics**: Calculate updated Sharpe ratio, drawdown
**Position Adjustments**: Rebalance if necessary
**Strategy Evaluation**: Assess if modifications needed

---

## ✅ **QUIZ SUCCESS STRATEGIES**

### **15. KEY FORMULAS TO MEMORIZE**

#### **Position Sizing**
- **Kelly %** = W - [(1-W)/R]
- **Position Size** = Risk Amount ÷ (Entry Price - Stop Loss) × Lot Size
- **Portfolio Variance** = w₁²σ₁² + w₂²σ₂² + 2w₁w₂σ₁σ₂ρ₁₂
- **Sharpe Ratio** = (Return - Risk-free Rate) ÷ Standard Deviation

#### **Risk Metrics**
- **VaR** = Portfolio Value × Z-score × Standard Deviation
- **Maximum Drawdown** = (Peak - Trough) ÷ Peak × 100
- **Correlation** = Covariance(X,Y) ÷ (σₓ × σᵧ)

### **16. IMPORTANT CONCEPTS**

#### **Must-Know Principles**
**Position Sizing**: Never risk more than 1-3% per trade
**Diversification**: 15-21 stocks provide optimal benefit
**Risk Types**: Systematic (market-wide) vs Unsystematic (company-specific)
**Kelly's Criterion**: Optimal bet sizing based on win rate and win/loss ratio

#### **Professional Standards**
**Risk Management**: 80% of trading success
**Stop Losses**: Mandatory for all positions
**Drawdown Limit**: Keep below 20% maximum
**Correlation**: Monitor portfolio concentration risk

### **17. COMMON EXAM TOPICS**

**Position Sizing** (30%):
1. Different sizing methods and calculations
2. Equity estimation models
3. Kelly's Criterion application
4. Risk percentage calculations

**Portfolio Theory** (25%):
1. Variance and covariance calculations
2. Correlation interpretation
3. Diversification benefits
4. Efficient frontier concepts

**Risk Types** (20%):
1. Systematic vs unsystematic risk
2. Diversification principles
3. VaR calculations
4. Risk-adjusted returns

**Trading Psychology** (25%):
1. Common cognitive biases
2. Emotional control techniques
3. Performance measurement
4. Practical risk management

### **18. CALCULATION PRACTICE TIPS**

#### **Step-by-Step Approach**
1. **Identify Risk Type**: Position, portfolio, or system risk
2. **Choose Method**: Select appropriate sizing technique
3. **Calculate Parameters**: Win rate, win/loss ratio, volatility
4. **Apply Formula**: Use correct formula for situation
5. **Verify Reasonableness**: Check if result makes practical sense

#### **Common Mistakes to Avoid**
- **Over-sizing**: Using pure Kelly without position limits
- **Ignoring Correlation**: Not considering portfolio concentration
- **Emotional Sizing**: Letting feelings override systematic approach
- **Static Approach**: Not adjusting for changing market conditions

---

## 🏆 **ADVANCED RISK CONCEPTS**

### **19. DYNAMIC HEDGING**

#### **Portfolio Hedging Strategies**
**Index Futures**: Hedge systematic risk for equity portfolios
**Options Strategies**: Protective puts, covered calls
**Sector Rotation**: Move between defensive and cyclical sectors
**Currency Hedging**: For international investments

### **20. STRESS TESTING**

#### **Scenario Analysis**
**Historical Scenarios**: 2008 financial crisis, COVID-19 pandemic
**Hypothetical Scenarios**: Custom stress test situations
**Monte Carlo**: Simulate thousands of possible outcomes
**Correlation Breakdown**: Test portfolio during crisis periods

### **21. BEHAVIORAL FINANCE**

#### **Market Anomalies**
**Momentum Effect**: Stocks trending continue trending
**Mean Reversion**: Extreme movements tend to reverse
**Calendar Effects**: January effect, weekend effect
**Size Effect**: Small caps outperform large caps

#### **Investor Behavior Patterns**
**Disposition Effect**: Holding losers, selling winners
**Home Bias**: Over-investing in domestic markets
**Recency Bias**: Overweighting recent events
**Mental Accounting**: Treating money differently based on source

---

**REMEMBER**: Risk management is the foundation of successful trading and investing. Position sizing determines your survival in markets, not your entry/exit techniques. Kelly's Criterion provides mathematical framework for optimal bet sizing, but must be used with position limits. Most trading failures result from poor risk management, not poor market analysis.

**EXAM FOCUS**: Master position sizing calculations, understand systematic vs unsystematic risk, practice Kelly's Criterion application, and know common trading biases. Risk management is both mathematical and psychological - excel in both aspects for trading success.

---
*Position Sizing • Psychology • Risk Control • Performance*
*Survive First, Profit Second, Manage Risk Always* 