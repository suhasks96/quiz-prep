# QUIZ PREP: Options Theory & Professional Trading
*Based on Module 5: Options Theory for Professional Trading*

## 🎯 **OPTIONS FUNDAMENTALS**

### **1. WHAT ARE OPTIONS?**

#### **Core Definition**
**Option**: Financial contract that gives the buyer the RIGHT (not obligation) to buy/sell an underlying asset at a specific price within a specific time period

**Key Participants:**
- **Option Buyer**: Pays premium, has rights
- **Option Writer/Seller**: Receives premium, has obligations

#### **Historical Context**
**International Development:**
- **1920s**: Custom OTC options on commodities
- **1972**: Equity options on Chicago Board Options Exchange (CBOE)
- **1970s**: Currency and bond options (OTC)
- **1982**: Exchange-traded currency options (Philadelphia)
- **1985**: Interest rate options (CME)

**Indian Options Market:**
- **June 2000**: Index futures launched
- **June 2001**: Index options launched  
- **July 2001**: Stock options launched
- **November 2001**: Single stock futures launched
- **2006**: Real liquidity emergence post-Ambani split

### **2. THE LAND DEAL ANALOGY (CRUCIAL FOR UNDERSTANDING)**

#### **Ajay-Venu Agreement**
**Setup:**
- **Land Value**: ₹5,00,000 today
- **Agreement Fee**: ₹1,00,000 (non-refundable)
- **Fixed Sale Price**: ₹5,00,000 (6 months later)
- **Highway Project**: May increase land value

**Key Terms:**
- **Ajay**: Option buyer (has rights)
- **Venu**: Option seller (has obligations)
- **Premium**: ₹1,00,000 agreement fee
- **Strike Price**: ₹5,00,000 fixed sale price
- **Expiry**: 6 months from today

#### **Three Possible Scenarios**

**Scenario 1: Land Price → ₹10,00,000 (Highway approved)**
- **Ajay's Action**: Exercise right, buy at ₹5,00,000
- **Total Cost**: ₹5,00,000 + ₹1,00,000 = ₹6,00,000
- **Market Value**: ₹10,00,000
- **Ajay's Profit**: ₹10,00,000 - ₹6,00,000 = ₹4,00,000
- **Venu's Loss**: ₹4,00,000 (opportunity cost)

**Scenario 2: Land Price → ₹3,00,000 (Highway rejected)**
- **Ajay's Action**: Don't exercise, walk away
- **Ajay's Loss**: ₹1,00,000 (premium paid)
- **Venu's Profit**: ₹1,00,000 (premium kept)

**Scenario 3: Land Price → ₹5,00,000 (No change)**
- **Ajay's Action**: Don't exercise (would pay ₹6,00,000 for ₹5,00,000 asset)
- **Ajay's Loss**: ₹1,00,000 (premium paid)
- **Venu's Profit**: ₹1,00,000 (premium kept)

#### **Key Insights**
**For Ajay (Buyer):**
- **Limited Loss**: Maximum loss = Premium paid
- **Unlimited Profit**: Profit potential increases with land price
- **Win Probability**: 33.33% (only when price rises significantly)

**For Venu (Seller):**
- **Limited Profit**: Maximum profit = Premium received
- **Unlimited Loss**: Loss potential increases with land price
- **Win Probability**: 66.67% (when price falls or stays flat)

---

## 📈 **CALL OPTIONS**

### **3. CALL OPTION BASICS**

#### **Definition**
**Call Option**: Gives the buyer the right to BUY the underlying asset at a specific price (strike price) before/on expiry

#### **Stock Market Example**
**Setup:**
- **Current Stock Price**: ₹67
- **Strike Price**: ₹75
- **Premium**: ₹5
- **Expiry**: 1 month

**Three Scenarios:**

**Scenario 1: Stock → ₹85**
- **Action**: Exercise call option
- **Buy Price**: ₹75 (strike price)
- **Total Cost**: ₹75 + ₹5 = ₹80
- **Market Value**: ₹85
- **Profit**: ₹85 - ₹80 = ₹5

**Scenario 2: Stock → ₹65**
- **Action**: Don't exercise
- **Loss**: ₹5 (premium paid)
- **Reason**: No point buying at ₹75 when market price is ₹65

**Scenario 3: Stock → ₹75**
- **Action**: Don't exercise
- **Loss**: ₹5 (premium paid)
- **Reason**: Would pay ₹80 total for ₹75 stock

#### **Call Option Characteristics**
**Buyer Profile:**
- **Expectation**: Stock price will rise above strike + premium
- **Maximum Loss**: Premium paid
- **Maximum Profit**: Unlimited (as stock price rises)
- **Breakeven**: Strike Price + Premium paid

**Seller Profile:**
- **Expectation**: Stock price will stay below strike price
- **Maximum Profit**: Premium received
- **Maximum Loss**: Unlimited (as stock price rises)
- **Breakeven**: Strike Price + Premium received

### **4. CALL OPTION PAYOFF ANALYSIS**

#### **Buyer Payoff Formula**
**At Expiry:**
- **If Stock Price > Strike Price**: Payoff = Stock Price - Strike Price - Premium
- **If Stock Price ≤ Strike Price**: Payoff = -Premium

#### **Moneyness Classification**
**In-the-Money (ITM)**: Stock Price > Strike Price
- **Example**: Stock at ₹80, Strike at ₹75
- **Intrinsic Value**: ₹80 - ₹75 = ₹5

**At-the-Money (ATM)**: Stock Price = Strike Price
- **Example**: Stock at ₹75, Strike at ₹75
- **Intrinsic Value**: ₹0

**Out-of-the-Money (OTM)**: Stock Price < Strike Price
- **Example**: Stock at ₹70, Strike at ₹75
- **Intrinsic Value**: ₹0

---

## 📉 **PUT OPTIONS**

### **5. PUT OPTION BASICS**

#### **Definition**
**Put Option**: Gives the buyer the right to SELL the underlying asset at a specific price (strike price) before/on expiry

#### **Put Option Example**
**Setup:**
- **Current Stock Price**: ₹67
- **Strike Price**: ₹60
- **Premium**: ₹3
- **Expiry**: 1 month

**Three Scenarios:**

**Scenario 1: Stock → ₹50**
- **Action**: Exercise put option
- **Sell Price**: ₹60 (strike price)
- **Premium Paid**: ₹3
- **Net Received**: ₹60 - ₹3 = ₹57
- **Market Value**: ₹50
- **Profit**: ₹57 - ₹50 = ₹7

**Scenario 2: Stock → ₹70**
- **Action**: Don't exercise
- **Loss**: ₹3 (premium paid)
- **Reason**: No point selling at ₹60 when market price is ₹70

**Scenario 3: Stock → ₹60**
- **Action**: Indifferent (may or may not exercise)
- **Net Result**: ₹3 loss due to premium

#### **Put Option Characteristics**
**Buyer Profile:**
- **Expectation**: Stock price will fall below strike - premium
- **Maximum Loss**: Premium paid
- **Maximum Profit**: Strike Price - Premium (when stock goes to zero)
- **Breakeven**: Strike Price - Premium paid

**Seller Profile:**
- **Expectation**: Stock price will stay above strike price
- **Maximum Profit**: Premium received
- **Maximum Loss**: Strike Price - Premium received
- **Breakeven**: Strike Price - Premium received

### **6. PUT OPTION PAYOFF ANALYSIS**

#### **Buyer Payoff Formula**
**At Expiry:**
- **If Stock Price < Strike Price**: Payoff = Strike Price - Stock Price - Premium
- **If Stock Price ≥ Strike Price**: Payoff = -Premium

#### **Put Option Moneyness**
**In-the-Money (ITM)**: Stock Price < Strike Price
- **Example**: Stock at ₹55, Strike at ₹60
- **Intrinsic Value**: ₹60 - ₹55 = ₹5

**At-the-Money (ATM)**: Stock Price = Strike Price
- **Example**: Stock at ₹60, Strike at ₹60
- **Intrinsic Value**: ₹0

**Out-of-the-Money (OTM)**: Stock Price > Strike Price
- **Example**: Stock at ₹65, Strike at ₹60
- **Intrinsic Value**: ₹0

---

## 💰 **OPTION PRICING & GREEKS**

### **7. FACTORS AFFECTING OPTION PRICES**

#### **Primary Factors**
**1. Underlying Price (S)**
- **Call Options**: Price increases with underlying price
- **Put Options**: Price decreases with underlying price

**2. Strike Price (K)**
- **Call Options**: Price decreases with higher strikes
- **Put Options**: Price increases with higher strikes

**3. Time to Expiry (T)**
- **Both Options**: Price decreases as expiry approaches (time decay)

**4. Volatility (σ)**
- **Both Options**: Price increases with higher volatility

**5. Risk-free Rate (r)**
- **Call Options**: Price increases with higher rates
- **Put Options**: Price decreases with higher rates

**6. Dividends (D)**
- **Call Options**: Price decreases with higher expected dividends
- **Put Options**: Price increases with higher expected dividends

#### **Option Price Components**
**Total Option Price = Intrinsic Value + Time Value**

**Intrinsic Value:**
- **Call**: Max(Stock Price - Strike Price, 0)
- **Put**: Max(Strike Price - Stock Price, 0)

**Time Value:**
- **Definition**: Premium paid for time remaining until expiry
- **Calculation**: Option Price - Intrinsic Value
- **Decay**: Decreases as expiry approaches

### **8. THE GREEKS**

#### **Delta (Δ)**
**Definition**: Rate of change of option price with respect to underlying price

**Call Delta:**
- **Range**: 0 to 1
- **ITM Calls**: Delta approaches 1
- **OTM Calls**: Delta approaches 0
- **ATM Calls**: Delta around 0.5

**Put Delta:**
- **Range**: -1 to 0
- **ITM Puts**: Delta approaches -1
- **OTM Puts**: Delta approaches 0
- **ATM Puts**: Delta around -0.5

**Practical Use:**
- **Portfolio Hedging**: Delta-neutral strategies
- **Risk Management**: Understanding price sensitivity

#### **Gamma (Γ)**
**Definition**: Rate of change of delta with respect to underlying price

**Characteristics:**
- **Highest for ATM options**: Maximum gamma at-the-money
- **Decreases for ITM/OTM**: Lower gamma for deep options
- **Time Decay Effect**: Increases as expiry approaches

**Practical Use:**
- **Delta Hedging**: Frequency of rebalancing required
- **Risk Assessment**: Convexity of option positions

#### **Theta (Θ)**
**Definition**: Rate of change of option price with respect to time (time decay)

**Characteristics:**
- **Always Negative**: Options lose value with time
- **Accelerating Decay**: Faster decay near expiry
- **ATM Maximum**: Highest theta for at-the-money options

**Practical Use:**
- **Time Value Assessment**: Daily time decay calculation
- **Strategy Selection**: Time-sensitive strategies

#### **Vega (ν)**
**Definition**: Rate of change of option price with respect to volatility

**Characteristics:**
- **Always Positive**: Higher volatility increases option value
- **ATM Maximum**: Highest vega for at-the-money options
- **Time Dependent**: Decreases as expiry approaches

**Practical Use:**
- **Volatility Trading**: Exploit volatility changes
- **Risk Management**: Volatility exposure assessment

#### **Rho (ρ)**
**Definition**: Rate of change of option price with respect to interest rates

**Characteristics:**
- **Call Rho**: Positive (higher rates increase call value)
- **Put Rho**: Negative (higher rates decrease put value)
- **Long-term Impact**: More significant for longer expiries

**Practical Use:**
- **Interest Rate Risk**: Limited practical impact for short-term options
- **LEAPS Trading**: Important for long-term options

---

## 📊 **OPTION PRICING MODELS**

### **9. BLACK-SCHOLES MODEL**

#### **Model Assumptions**
1. **Constant Volatility**: Volatility remains constant
2. **Constant Risk-free Rate**: Interest rates don't change
3. **No Dividends**: Or known dividend yield
4. **European Exercise**: Only exercise at expiry
5. **No Transaction Costs**: Frictionless markets
6. **Continuous Trading**: Markets always open

#### **Black-Scholes Formula (Conceptual)**
**Call Option Price**: Based on current stock price, strike price, time to expiry, risk-free rate, and volatility
**Put Option Price**: Derived using put-call parity relationship

#### **Model Limitations**
- **Constant Volatility**: Real volatility changes
- **European Exercise**: Many options are American style
- **No Dividends**: Doesn't account for dividend changes
- **Perfect Liquidity**: Assumes no bid-ask spreads

### **10. BINOMIAL MODEL**

#### **Model Concept**
**Tree Structure**: Price can move up or down at each time step
**Flexibility**: Can handle American options and dividends
**Convergence**: Approaches Black-Scholes with more steps

#### **Advantages Over Black-Scholes**
- **American Options**: Can handle early exercise
- **Dividends**: Easy to incorporate dividend payments
- **Intuitive**: More intuitive understanding
- **Flexible**: Can modify assumptions easily

---

## 🎯 **PRACTICAL OPTIONS TRADING**

### **11. BASIC OPTION STRATEGIES**

#### **Long Call (Bullish)**
**Setup**: Buy call option
**Expectation**: Stock price will rise significantly
**Max Profit**: Unlimited
**Max Loss**: Premium paid
**Breakeven**: Strike + Premium

#### **Short Call (Bearish/Neutral)**
**Setup**: Sell call option
**Expectation**: Stock price will stay below strike
**Max Profit**: Premium received
**Max Loss**: Unlimited
**Breakeven**: Strike + Premium

#### **Long Put (Bearish)**
**Setup**: Buy put option
**Expectation**: Stock price will fall significantly
**Max Profit**: Strike - Premium (when stock goes to zero)
**Max Loss**: Premium paid
**Breakeven**: Strike - Premium

#### **Short Put (Bullish/Neutral)**
**Setup**: Sell put option
**Expectation**: Stock price will stay above strike
**Max Profit**: Premium received
**Max Loss**: Strike - Premium
**Breakeven**: Strike - Premium

### **12. OPTION SELECTION CRITERIA**

#### **Strike Price Selection**
**ITM Options:**
- **Higher Premium**: More expensive
- **Higher Delta**: More sensitive to stock moves
- **Lower Time Value**: Less time decay

**ATM Options:**
- **Balanced Premium**: Moderate cost
- **Maximum Gamma**: Highest acceleration
- **Maximum Time Value**: Most time decay

**OTM Options:**
- **Lower Premium**: Cheaper
- **Lower Delta**: Less sensitive initially
- **Higher Time Value**: More time decay risk

#### **Expiry Selection**
**Near-term Expiry (1-2 weeks):**
- **Pros**: Lower premium, high gamma
- **Cons**: High time decay, limited time for move

**Medium-term Expiry (1-3 months):**
- **Pros**: Balanced time vs cost
- **Cons**: Moderate premium

**Long-term Expiry (3+ months):**
- **Pros**: More time for thesis to play out
- **Cons**: Higher premium, lower gamma

### **13. VOLATILITY CONCEPTS**

#### **Historical Volatility**
**Definition**: Actual volatility observed in past stock prices
**Calculation**: Standard deviation of stock returns
**Usage**: Compare with implied volatility

#### **Implied Volatility**
**Definition**: Market's expectation of future volatility
**Extraction**: Derived from option prices using Black-Scholes
**Usage**: Assess if options are cheap or expensive

#### **Volatility Trading**
**High IV**: Options expensive, consider selling
**Low IV**: Options cheap, consider buying
**IV Rank**: Compare current IV to historical range
**IV Percentile**: Position of current IV in annual range

---

## 🛡️ **RISK MANAGEMENT**

### **14. POSITION SIZING**

#### **Risk-Based Sizing**
**Rule**: Never risk more than 2-5% of capital on single trade
**Formula**: Position Size = Risk Amount ÷ Maximum Loss per Unit
**Example**: ₹10,000 risk ÷ ₹100 max loss per option = 100 options maximum

#### **Probability-Based Sizing**
**Win Rate Consideration**: Higher win rate allows larger positions
**Risk-Reward Ratio**: Better ratios allow larger positions

### **15. COMMON MISTAKES**

#### **Buying OTM Options Near Expiry**
**Problem**: High time decay, low probability of profit
**Solution**: Buy ITM or ATM with adequate time

#### **Ignoring Volatility**
**Problem**: Buying expensive options, selling cheap options
**Solution**: Always check implied volatility levels

#### **No Exit Plan**
**Problem**: Holding losing positions hoping for recovery
**Solution**: Set profit targets and stop losses before entry

#### **Over-leverage**
**Problem**: Risking too much capital on single trade
**Solution**: Proper position sizing and diversification

---

## 🎯 **QUIZ SUCCESS STRATEGIES**

### **Key Options Concepts to Master**
1. **Call vs Put Options**: Rights, obligations, and payoffs
2. **Moneyness**: ITM, ATM, OTM classifications
3. **Option Pricing Factors**: Six primary factors affecting prices
4. **The Greeks**: Delta, Gamma, Theta, Vega understanding
5. **Time Value vs Intrinsic Value**: Component breakdown
6. **Black-Scholes Model**: Basic understanding and assumptions
7. **Basic Strategies**: Long/short calls and puts
8. **Risk Management**: Position sizing and common mistakes

### **Important Formulas**
- **Call Intrinsic Value**: Max(Stock Price - Strike, 0)
- **Put Intrinsic Value**: Max(Strike - Stock Price, 0)
- **Call Breakeven**: Strike Price + Premium Paid
- **Put Breakeven**: Strike Price - Premium Paid
- **Time Value**: Option Price - Intrinsic Value

### **Key Numbers to Remember**
- **ATM Delta**: ~0.5 for calls, ~-0.5 for puts
- **Maximum Gamma**: At-the-money options
- **Time Decay**: Accelerates in final month
- **Options Expiry**: Last Thursday of every month
- **Nifty Options Lot Size**: 50 units

### **Common Quiz Topics**
**Payoff Calculations:**
- Profit/loss at different stock prices
- Breakeven point calculations
- Maximum profit/loss scenarios

**Greeks Impact:**
- How delta affects option prices
- Time decay (theta) effects
- Volatility (vega) sensitivity

**Strategy Selection:**
- When to buy vs sell options
- Strike and expiry selection
- Risk-reward analysis

**Practical Applications:**
- Portfolio hedging with options
- Speculation vs hedging distinctions
- Volatility trading concepts

### **Quiz Tips**
- **Master the Land Analogy**: Foundation for understanding options
- **Practice Payoff Diagrams**: Visual representation crucial
- **Understand Risk Profiles**: Limited vs unlimited risk/reward
- **Know the Greeks**: Impact of each Greek on option prices
- **Time Value Decay**: How time affects option values

**Remember**: Options provide tremendous flexibility for both speculation and hedging. The key is understanding that option buyers have limited risk but unlimited profit potential (for calls), while option sellers have limited profit potential but unlimited risk (for calls). Always consider time decay, volatility, and proper position sizing in your trading decisions! 