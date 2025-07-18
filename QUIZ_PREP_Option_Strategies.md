# QUIZ PREP: Option Strategies & Advanced Trading
*Based on Module 6: Option Strategies*

## 🎯 **OPTION STRATEGIES OVERVIEW**

### **1. PROFESSIONAL STRATEGY APPROACH**

#### **Why Use Spreads vs Naked Positions?**
**Risk Visibility**: Spreads provide clear maximum loss scenarios
**Financing**: Sale of one option finances purchase of another
**Professional Preference**: Controlled risk over unlimited profit potential
**Probability**: Higher success rates with defined risk-reward

#### **Strategy Classification**
**Directional Strategies**: Bull/Bear spreads for trending markets
**Volatility Strategies**: Straddles/Strangles for volatile markets
**Income Strategies**: Credit spreads for range-bound markets
**Arbitrage Strategies**: Risk-free profit opportunities

---

## 📈 **BULLISH STRATEGIES**

### **2. BULL CALL SPREAD**

#### **Strategy Construction**
**Setup**: Buy lower strike call + Sell higher strike call
**Market View**: Moderately bullish (3-5% rise expected)
**Net Position**: Debit spread (pay net premium)

#### **Example**
**Stock**: ₹100, expect rise to ₹110
- **Buy**: 100 Call at ₹8
- **Sell**: 110 Call at ₹3
- **Net Cost**: ₹5
- **Max Profit**: (110-100) - 5 = ₹5
- **Max Loss**: ₹5
- **Breakeven**: 105

#### **Key Formulas**
- **Max Profit** = Strike Difference - Net Debit
- **Max Loss** = Net Debit
- **Breakeven** = Lower Strike + Net Debit

### **3. BULL PUT SPREAD**

#### **Strategy Construction**
**Setup**: Sell higher strike put + Buy lower strike put
**Market View**: Mildly bullish to neutral
**Net Position**: Credit spread (receive net premium)

#### **Example**
**Stock**: ₹100, expect to stay above ₹95
- **Sell**: 100 Put at ₹6
- **Buy**: 95 Put at ₹2
- **Net Credit**: ₹4
- **Max Profit**: ₹4
- **Max Loss**: (100-95) - 4 = ₹1
- **Breakeven**: 96

#### **Key Formulas**
- **Max Profit** = Net Credit
- **Max Loss** = Strike Difference - Net Credit
- **Breakeven** = Higher Strike - Net Credit

---

## 📉 **BEARISH STRATEGIES**

### **4. BEAR CALL SPREAD**

#### **Strategy Construction**
**Setup**: Sell lower strike call + Buy higher strike call
**Market View**: Moderately bearish to neutral
**Net Position**: Credit spread (receive net premium)

#### **Example**
**Stock**: ₹100, expect to stay below ₹105
- **Sell**: 100 Call at ₹5
- **Buy**: 105 Call at ₹2
- **Net Credit**: ₹3
- **Max Profit**: ₹3
- **Max Loss**: (105-100) - 3 = ₹2
- **Breakeven**: 103

### **5. BEAR PUT SPREAD**

#### **Strategy Construction**
**Setup**: Buy higher strike put + Sell lower strike put
**Market View**: Moderately bearish (4-5% decline expected)
**Net Position**: Debit spread (pay net premium)

#### **Example**
**Nifty**: 7485, expect decline to 7400
- **Buy**: 7600 Put at ₹165
- **Sell**: 7400 Put at ₹73
- **Net Cost**: ₹92
- **Max Profit**: (7600-7400) - 92 = ₹108
- **Max Loss**: ₹92
- **Breakeven**: 7508

#### **Key Formulas**
- **Max Profit** = Strike Difference - Net Debit
- **Max Loss** = Net Debit
- **Breakeven** = Higher Strike - Net Debit

---

## ⚡ **RATIO SPREADS**

### **6. CALL RATIO BACK SPREAD**

#### **Strategy Construction**
**Setup**: Sell 1 ITM call + Buy 2 OTM calls
**Market View**: Neutral to very bullish with high volatility expectation
**Net Position**: Usually credit or small debit

#### **Example**
**Stock**: ₹8300
- **Sell**: 1 x 8200 Call at ₹200
- **Buy**: 2 x 8400 Call at ₹90 each
- **Net Cost**: (2×90) - 200 = -₹20 (credit)
- **Profit Zones**: Below 8200 or above 8600
- **Max Loss**: Around 8400 level

#### **Strategy Characteristics**
**Unlimited Profit**: If stock moves significantly up
**Limited Loss**: Maximum loss at higher strike
**Volatility Play**: Benefits from increased volatility

### **7. PUT RATIO BACK SPREAD**

#### **Strategy Construction**
**Setup**: Sell 1 ITM put + Buy 2 OTM puts
**Market View**: Neutral to very bearish with volatility
**Net Position**: Usually credit or small debit

#### **Profit Characteristics**
**Two Profit Zones**: Above short put or well below long puts
**Volatility Benefits**: Gains from increased implied volatility
**Time Decay**: Mixed impact depending on strikes

---

## 🔄 **SYNTHETIC STRATEGIES**

### **8. SYNTHETIC LONG**

#### **Strategy Construction**
**Setup**: Buy ATM call + Sell ATM put
**Payoff**: Replicates long futures position
**Purpose**: Alternative to buying futures

#### **Example**
**Nifty**: 8300
- **Buy**: 8300 Call at ₹120
- **Sell**: 8300 Put at ₹110
- **Net Cost**: ₹10
- **Breakeven**: 8310
- **Payoff**: Similar to long futures from 8310

#### **Applications**
**Margin Efficiency**: May require less margin than futures
**Flexibility**: Can be adjusted with different strikes
**Arbitrage**: Compare with actual futures for opportunities

### **9. SYNTHETIC SHORT**

#### **Strategy Construction**
**Setup**: Sell ATM call + Buy ATM put
**Payoff**: Replicates short futures position
**Purpose**: Alternative to shorting futures

---

## 🎢 **VOLATILITY STRATEGIES**

### **10. LONG STRADDLE**

#### **Strategy Construction**
**Setup**: Buy ATM call + Buy ATM put
**Market View**: High volatility expected, direction unknown
**Net Position**: Debit (pay both premiums)

#### **Example**
**Stock**: ₹100, expecting big move
- **Buy**: 100 Call at ₹5
- **Buy**: 100 Put at ₹5
- **Net Cost**: ₹10
- **Breakeven**: 90 and 110
- **Profit**: If stock moves beyond ₹90 or ₹110

#### **Strategy Characteristics**
**Unlimited Profit**: Both upside and downside
**High Cost**: Expensive due to buying both options
**Time Decay**: Major enemy of the strategy

### **11. SHORT STRADDLE**

#### **Strategy Construction**
**Setup**: Sell ATM call + Sell ATM put
**Market View**: Low volatility expected, range-bound
**Net Position**: Credit (receive both premiums)

#### **Risk Profile**
**Limited Profit**: Maximum = premiums collected
**Unlimited Loss**: Both upside and downside
**High Probability**: Wins if stock stays in narrow range

### **12. LONG STRANGLE**

#### **Strategy Construction**
**Setup**: Buy OTM call + Buy OTM put
**Market View**: High volatility, wider breakeven than straddle
**Net Position**: Debit (cheaper than straddle)

#### **Example**
**Stock**: ₹100
- **Buy**: 105 Call at ₹3
- **Buy**: 95 Put at ₹3
- **Net Cost**: ₹6
- **Breakeven**: 89 and 111
- **Advantage**: Lower cost than straddle

### **13. SHORT STRANGLE**

#### **Strategy Construction**
**Setup**: Sell OTM call + Sell OTM put
**Market View**: Low volatility, range-bound movement
**Higher Probability**: Wider profit zone than short straddle

---

## 🏗️ **ADVANCED COMBINATION STRATEGIES**

### **14. IRON CONDOR**

#### **Strategy Construction**
**Setup**: Bull put spread + Bear call spread
**Market View**: Range-bound, low volatility
**Four Legs**: Sell middle strikes, buy outside strikes

#### **Example**
**Stock**: ₹100, expect to stay between ₹95-₹105
- **Sell**: 95 Put at ₹2
- **Buy**: 90 Put at ₹1
- **Sell**: 105 Call at ₹2
- **Buy**: 110 Call at ₹1
- **Net Credit**: ₹2
- **Profit Zone**: Between 97 and 103

#### **Key Features**
**Limited Profit**: Net credit received
**Limited Loss**: Strike difference minus credit
**High Probability**: Profitable in wide range

### **15. IRON BUTTERFLY**

#### **Strategy Construction**
**Setup**: Sell ATM straddle + Buy protective wings
**Market View**: Very low volatility, pin risk at center strike
**Higher Premium**: More credit than iron condor

---

## 💰 **ARBITRAGE STRATEGIES**

### **16. PUT-CALL PARITY ARBITRAGE**

#### **Arbitrage Equation**
**Formula**: Long Call + Short Put + Short Futures = 0 (theoretical)
**Opportunity**: When equation doesn't equal zero

#### **Example**
**Setup**: Nifty 7300 options, futures at 7316
- **Long**: 7300 Call at ₹79.5
- **Short**: 7300 Put at ₹73.85
- **Short**: Futures at 7316
- **Expected Payoff**: ₹10.35 regardless of expiry level

#### **Execution Considerations**
**Transaction Costs**: Brokerage, taxes, STT impact
**Carry Costs**: Interest on margin requirements
**Viability**: Profit must exceed all costs

---

## 📊 **GREEKS ANALYSIS FOR STRATEGIES**

### **17. DELTA NEUTRAL STRATEGIES**

#### **Portfolio Delta Calculation**
**Method**: Add up individual position deltas
**Example**: Bull put spread
- **Short Put Delta**: +0.342 (opposite sign)
- **Long Put Delta**: -0.618
- **Net Delta**: -0.276 (bearish bias)

#### **Delta Applications**
**Strategy Direction**: Positive delta = bullish, negative = bearish
**Zero Delta**: Market neutral strategies
**Risk Management**: Monitor and adjust delta exposure

### **18. THETA MANAGEMENT**

#### **Time Decay Impact**
**Credit Strategies**: Benefit from theta decay
**Debit Strategies**: Hurt by theta decay
**ATM Options**: Highest theta exposure

### **19. VEGA CONSIDERATIONS**

#### **Volatility Impact**
**Long Options**: Benefit from increased volatility
**Short Options**: Hurt by increased volatility
**Strategy Selection**: Match volatility expectation

---

## 🎯 **STRATEGY SELECTION FRAMEWORK**

### **20. MARKET CONDITION MAPPING**

#### **Trending Markets**
**Strong Bullish**: Bull call spread, long calls
**Strong Bearish**: Bear put spread, long puts
**Moderate Trends**: Credit spreads in trend direction

#### **Range-Bound Markets**
**Low Volatility**: Iron condors, short strangles
**High Volatility**: Long straddles, long strangles
**Income Generation**: Credit spreads

#### **Volatile Markets**
**Direction Unknown**: Long straddles, ratio back spreads
**Volatility Crush Expected**: Short straddles, short strangles

### **21. STRIKE SELECTION CRITERIA**

#### **Aggressive vs Conservative**
**Aggressive**: ATM or slightly ITM short strikes
**Conservative**: OTM short strikes for safety margin
**Risk-Reward**: Closer strikes = higher probability, lower reward

#### **Expiry Selection**
**Short-term**: Higher theta decay, more precise timing needed
**Long-term**: More time for thesis to play out, higher cost

---

## ✅ **QUIZ SUCCESS STRATEGIES**

### **22. KEY FORMULAS TO MEMORIZE**

#### **Credit Spreads**
- **Max Profit** = Net Credit Received
- **Max Loss** = Strike Difference - Net Credit
- **Breakeven (Put)** = Higher Strike - Net Credit
- **Breakeven (Call)** = Lower Strike + Net Credit

#### **Debit Spreads**
- **Max Profit** = Strike Difference - Net Debit
- **Max Loss** = Net Debit Paid
- **Breakeven (Call)** = Lower Strike + Net Debit
- **Breakeven (Put)** = Higher Strike - Net Debit

#### **Straddles/Strangles**
- **Long Breakevens** = Strike ± Premium (straddle)
- **Short Profit Zone** = Between breakevens
- **Max Profit (Short)** = Total premiums collected

### **23. IMPORTANT STRATEGY CHARACTERISTICS**

#### **Must-Know Features**
**Credit vs Debit**: Who pays/receives money initially
**Limited vs Unlimited**: Profit and loss potential
**Volatility Impact**: Long benefits, short suffers from vol increase
**Time Decay**: Credit strategies benefit, debit strategies suffer

#### **Risk Profiles**
**Spreads**: Limited profit and loss
**Naked Options**: Unlimited risk for sellers
**Straddles**: Unlimited profit, limited loss (long)
**Ratio Spreads**: Mixed risk profiles

### **24. COMMON EXAM TOPICS**

**Strategy Construction** (30%):
1. Identifying legs for different strategies
2. Credit vs debit classification
3. Strike selection impact
4. Expiry considerations

**Payoff Calculations** (25%):
1. Maximum profit/loss scenarios
2. Breakeven point calculations
3. P&L at various expiry levels
4. Greeks impact on strategies

**Strategy Selection** (25%):
1. Matching strategies to market views
2. Volatility environment considerations
3. Risk-reward trade-offs
4. Probability assessments

**Advanced Concepts** (20%):
1. Synthetic positions construction
2. Arbitrage identification
3. Greeks portfolio analysis
4. Risk management techniques

### **25. CALCULATION PRACTICE TIPS**

#### **Step-by-Step Approach**
1. **Identify Strategy Type**: Spread, straddle, synthetic
2. **Determine Net Position**: Credit or debit
3. **Calculate Max Profit/Loss**: Using appropriate formulas
4. **Find Breakeven Points**: Based on strategy type
5. **Analyze Risk-Reward**: Probability vs payoff

#### **Common Mistakes to Avoid**
- **Wrong Formula**: Mixing up credit vs debit formulas
- **Strike Confusion**: Using wrong strike for calculations
- **Sign Errors**: Positive vs negative deltas for short positions
- **Greeks Misunderstanding**: Direction of impact on strategies

---

## 🏆 **ADVANCED TRADING CONCEPTS**

### **26. PORTFOLIO APPROACH**

#### **Strategy Combinations**
**Multiple Strategies**: Combining different strategies
**Risk Diversification**: Spreading across market views
**Greeks Management**: Balancing overall portfolio Greeks

### **27. ADJUSTMENT TECHNIQUES**

#### **Mid-Trade Management**
**Rolling**: Moving to different strikes/expiries
**Closing**: Taking profits or cutting losses
**Adding Legs**: Converting to different strategies

### **28. MARKET MAKING CONCEPTS**

#### **Bid-Ask Dynamics**
**Spread Capture**: Profiting from bid-ask spreads
**Volume Considerations**: Liquidity impact on execution
**Slippage**: Cost of market orders vs limit orders

---

**REMEMBER**: Option strategies provide defined risk-reward profiles suitable for different market conditions. Master the basic spreads first, understand Greeks impact, and always calculate maximum profit, loss, and breakeven points. Professional traders prefer spreads over naked positions for better risk visibility and probability of success.

**EXAM FOCUS**: Practice strategy construction extensively, memorize key formulas for different strategy types, understand when to use each strategy based on market conditions, and be clear about the risk-reward characteristics of each approach.

---
*Spreads • Greeks • Risk-Reward • Probability*
*Master the Mechanics, Understand the Greeks, Manage the Risk* 