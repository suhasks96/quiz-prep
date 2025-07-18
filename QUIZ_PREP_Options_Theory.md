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
- **1982**: Exchange-traded currency options

**Indian Development:**
- **2001**: Equity options launched on NSE
- **2003**: Index options introduced
- **2008**: Currency options started
- **2017**: Commodity options began

---

## 🔄 **CALL vs PUT OPTIONS: COMPREHENSIVE COMPARISON**

### **2. DETAILED CALL vs PUT ANALYSIS**

#### **Fundamental Differences Matrix**

| **Parameter** | **CALL OPTION** | **PUT OPTION** |
|---------------|-----------------|----------------|
| **Right Given** | Right to BUY | Right to SELL |
| **Buyer Expectation** | Stock price will RISE | Stock price will FALL |
| **Seller Expectation** | Stock price will NOT rise significantly | Stock price will NOT fall significantly |
| **Exercise Condition** | When market price > strike price | When market price < strike price |
| **Maximum Profit (Buyer)** | Unlimited (stock can rise infinitely) | Limited (stock can only fall to zero) |
| **Maximum Loss (Buyer)** | Premium paid | Premium paid |
| **Maximum Profit (Seller)** | Premium received | Premium received |
| **Maximum Loss (Seller)** | Unlimited | Strike price - Premium received |

#### **Intrinsic Value Calculations**

**Call Option Intrinsic Value:**
- **ITM**: Max(Spot Price - Strike Price, 0)
- **ATM/OTM**: 0

**Put Option Intrinsic Value:**
- **ITM**: Max(Strike Price - Spot Price, 0)
- **ATM/OTM**: 0

**Example Calculations:**
Stock Trading at ₹8,100
- 8000 CE: Max(8100-8000, 0) = ₹100
- 8200 CE: Max(8100-8200, 0) = ₹0
- 8000 PE: Max(8000-8100, 0) = ₹0
- 8200 PE: Max(8200-8100, 0) = ₹100

### **3. OPTION MONEYNESS COMPARISON**

#### **Complete Moneyness Matrix**

| **Moneyness** | **Call Option** | **Put Option** | **Characteristics** |
|---------------|-----------------|----------------|-------------------|
| **Deep ITM** | Spot >> Strike | Spot << Strike | High intrinsic value, low time value |
| **ITM** | Spot > Strike | Spot < Strike | Some intrinsic value, moderate time value |
| **Near ATM** | Spot ≈ Strike | Spot ≈ Strike | No intrinsic value, maximum time value |
| **ATM** | Spot = Strike | Spot = Strike | Zero intrinsic value, highest time value |
| **OTM** | Spot < Strike | Spot > Strike | Zero intrinsic value, only time value |
| **Deep OTM** | Spot << Strike | Spot >> Strike | Zero intrinsic value, minimal time value |

#### **Moneyness Impact on Greeks**
**Delta Behavior:**
- ITM Options: Higher delta (closer to ±1)
- ATM Options: Delta around ±0.5
- OTM Options: Lower delta (closer to 0)

**Theta Impact:**
- ATM options decay fastest
- Deep ITM/OTM options decay slower
- Maximum time decay near expiry for ATM

---

## ⚡ **OPTION PRICING FACTORS**

### **4. BLACK-SCHOLES PRICING INPUTS**

#### **Six Key Pricing Factors**

| **Factor** | **Impact on Call** | **Impact on Put** | **Reasoning** |
|------------|-------------------|-------------------|---------------|
| **Spot Price ↑** | Price ↑ | Price ↓ | Higher spot makes calls more valuable, puts less valuable |
| **Strike Price ↑** | Price ↓ | Price ↑ | Higher strike makes calls cheaper, puts more expensive |
| **Time to Expiry ↑** | Price ↑ | Price ↑ | More time = more opportunities for favorable movement |
| **Volatility ↑** | Price ↑ | Price ↑ | Higher volatility = higher probability of favorable moves |
| **Interest Rate ↑** | Price ↑ | Price ↓ | Higher rates favor calls over puts |
| **Dividends ↑** | Price ↓ | Price ↑ | Dividends reduce spot price, favoring puts |

#### **Practical Example**
**Stock**: Nifty at 18,000
**18000 CE Price Sensitivity:**
- If Nifty moves to 18,200: Call price increases
- If volatility increases from 15% to 20%: Call price increases
- If time to expiry reduces: Call price decreases (theta decay)
- If interest rates rise: Call price slightly increases

---

## 🔢 **OPTION GREEKS COMPARISON**

### **5. GREEKS BEHAVIOR MATRIX**

#### **Delta Comparison**

| **Option Type** | **Delta Range** | **Characteristics** | **Example** |
|-----------------|-----------------|-------------------|-------------|
| **Call ITM** | 0.5 to 1.0 | Positive, increases with depth | 0.8 for deep ITM call |
| **Call ATM** | Around 0.5 | Maximum sensitivity to spot | 0.5 for ATM call |
| **Call OTM** | 0 to 0.5 | Positive, decreases with distance | 0.2 for OTM call |
| **Put ITM** | -0.5 to -1.0 | Negative, more negative with depth | -0.8 for deep ITM put |
| **Put ATM** | Around -0.5 | Maximum sensitivity to spot | -0.5 for ATM put |
| **Put OTM** | 0 to -0.5 | Negative, less negative with distance | -0.2 for OTM put |

#### **Gamma Behavior**
**Common Characteristics:**
- Maximum gamma for ATM options
- Decreases for deep ITM/OTM options
- Increases as expiry approaches (for ATM)
- Always positive for both calls and puts

**Theta Behavior:**
- Always negative for long options (buyers)
- Always positive for short options (sellers)
- Accelerates near expiry
- Maximum for ATM options

---

## 📊 **EUROPEAN vs AMERICAN OPTIONS**

### **6. EXERCISE STYLE COMPARISON**

#### **Detailed Comparison Matrix**

| **Feature** | **European Options** | **American Options** |
|-------------|---------------------|-------------------|
| **Exercise Timing** | Only on expiry date | Any time before/on expiry |
| **Flexibility** | Lower | Higher |
| **Premium** | Lower (less flexibility) | Higher (more flexibility) |
| **Early Exercise** | Not allowed | Allowed |
| **Complexity** | Simpler to price | More complex to price |
| **Indian Market** | Most index options | Most stock options |

#### **Early Exercise Scenarios**
**When American Calls Exercised Early:**
- Stock goes ex-dividend before expiry
- Deep ITM calls with minimal time value
- Interest rate considerations

**When American Puts Exercised Early:**
- Deep ITM puts (especially if stock price very low)
- High interest rate environment
- Dividend considerations

#### **Practical Implications**
**For Option Buyers:**
- American options provide more strategic flexibility
- Higher premium cost for the flexibility
- Need to monitor for optimal exercise timing

**For Option Sellers:**
- Face early assignment risk with American options
- Need to manage positions more actively
- Assignment can happen any time

---

## 💰 **OPTIONS PAYOFF COMPARISONS**

### **7. STRATEGY PAYOFF ANALYSIS**

#### **Basic Position Payoffs**

| **Position** | **Max Profit** | **Max Loss** | **Breakeven** | **Market View** |
|--------------|----------------|--------------|---------------|-----------------|
| **Long Call** | Unlimited | Premium paid | Strike + Premium | Bullish |
| **Short Call** | Premium received | Unlimited | Strike + Premium | Bearish/Neutral |
| **Long Put** | Strike - Premium | Premium paid | Strike - Premium | Bearish |
| **Short Put** | Premium received | Strike - Premium | Strike - Premium | Bullish/Neutral |

#### **Payoff Comparison Examples**
**Nifty at 18,000, 18000 CE at ₹200, 18000 PE at ₹180**

**Long Call Payoff:**
- At 17,800: Loss = ₹200 (full premium)
- At 18,000: Loss = ₹200 (full premium)
- At 18,200: Breakeven
- At 18,500: Profit = ₹300

**Long Put Payoff:**
- At 18,200: Loss = ₹180 (full premium)
- At 18,000: Loss = ₹180 (full premium)
- At 17,820: Breakeven
- At 17,500: Profit = ₹320

---

## 📈 **VOLATILITY CONCEPTS**

### **8. HISTORICAL vs IMPLIED VOLATILITY**

#### **Volatility Types Comparison**

| **Type** | **Historical Volatility** | **Implied Volatility** |
|----------|---------------------------|-------------------------|
| **Definition** | Past price movement volatility | Market's expectation of future volatility |
| **Calculation** | Standard deviation of past returns | Derived from option prices using Black-Scholes |
| **Usage** | Reference for normal volatility | Current market sentiment |
| **Impact** | Academic/analytical | Direct impact on option premiums |
| **Time Frame** | Historical periods (30, 60, 90 days) | Forward-looking |

#### **Volatility Trading Strategies**
**High IV Environment** (Sell volatility):
- Sell straddles/strangles
- Collect high premiums
- Expect volatility to decrease

**Low IV Environment** (Buy volatility):
- Buy straddles/strangles
- Pay low premiums
- Expect volatility to increase

---

## 🎯 **OPTIONS CHAIN ANALYSIS**

### **9. INTERPRETING OPTION CHAINS**

#### **Option Chain Components**

| **Component** | **Call Options** | **Put Options** | **Information Provided** |
|---------------|------------------|-----------------|--------------------------|
| **OI (Open Interest)** | Number of outstanding call contracts | Number of outstanding put contracts | Market interest at strike |
| **Volume** | Calls traded today | Puts traded today | Liquidity indicator |
| **LTP** | Last traded price | Last traded price | Current market price |
| **Bid/Ask** | Best buy/sell prices | Best buy/sell prices | Spread and liquidity |
| **IV** | Implied volatility | Implied volatility | Market expectation |

#### **Chain Analysis Techniques**
**Max Pain Theory**: Strike with maximum put + call OI (where most options expire worthless)
**PCR Analysis**: Put-Call Ratio for market sentiment
**Support/Resistance**: High OI strikes act as support/resistance levels
**Volatility Skew**: Different IVs across strikes indicating market bias

---

## 🔄 **ARBITRAGE OPPORTUNITIES**

### **10. PUT-CALL PARITY**

#### **Put-Call Parity Formula**
**Equation**: Call Price + Present Value of Strike = Put Price + Spot Price
**Rearranged**: C + K/(1+r)^t = P + S

**Where:**
- C = Call option price
- P = Put option price  
- S = Spot price
- K = Strike price
- r = Risk-free rate
- t = Time to expiry

#### **Arbitrage Example**
**Given**: Nifty at 18,000, 18000 CE at ₹250, 18000 PE at ₹200, Risk-free rate 6%
**Theoretical Put Price**: ₹250 + 18,000/(1.06)^0.25 - 18,000 = ₹233
**Actual Put Price**: ₹200
**Arbitrage**: Put is underpriced by ₹33

**Strategy**: Buy underpriced put, sell overpriced call, buy spot, lend at risk-free rate

---

## ✅ **ENHANCED QUIZ STRATEGIES**

### **11. COMPARISON-BASED QUESTIONS**

#### **Expected Question Types**
**Call vs Put Mechanics** (25%):
1. Intrinsic value calculations for both
2. Moneyness classification differences
3. Exercise conditions and payoffs
4. Greek behavior comparisons

**European vs American** (15%):
1. Exercise style differences
2. Early exercise scenarios
3. Premium differences and reasons
4. Practical applications

**Volatility Concepts** (20%):
1. Historical vs implied volatility
2. Impact on call vs put premiums
3. Volatility trading strategies
4. Market expectations interpretation

**Option Chain Analysis** (20%):
1. Reading option chain data
2. Put-call ratio interpretation
3. Open interest analysis
4. Support/resistance identification

#### **Critical Numbers to Remember**
- **ATM Delta**: Calls ≈ +0.5, Puts ≈ -0.5
- **ITM Call Delta**: 0.5 to 1.0
- **ITM Put Delta**: -0.5 to -1.0
- **Maximum Gamma**: ATM options
- **Maximum Theta**: ATM options
- **Volatility Impact**: Same direction for both calls and puts

#### **Formula Quick Reference**
- **Call Intrinsic Value**: Max(S - K, 0)
- **Put Intrinsic Value**: Max(K - S, 0)
- **Put-Call Parity**: C + PV(K) = P + S
- **Time Value**: Option Premium - Intrinsic Value

---

**REMEMBER**: Options provide asymmetric risk-reward profiles with limited downside (premium) and potentially unlimited upside. Call and put options are complementary instruments with opposite directional exposures. Understanding moneyness, Greeks behavior, and put-call parity is essential for options trading and risk management.

**EXAM FOCUS**: Master the differences between calls and puts, understand moneyness classification, practice intrinsic value calculations, know Greek behavior patterns, and understand European vs American exercise styles. Comparison questions are fundamental to options knowledge.

---
*Rights • Obligations • Premiums • Probabilities*
*Master the Asymmetry, Understand the Greeks* 