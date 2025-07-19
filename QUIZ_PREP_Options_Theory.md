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
- **2001**: Equity options launched on NSE (National Stock Exchange)
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
- **ITM (In the Money)**: Max(Spot Price - Strike Price, 0)
- **ATM (At the Money)/OTM (Out of the Money)**: 0

**Put Option Intrinsic Value:**
- **ITM (In the Money)**: Max(Strike Price - Spot Price, 0)
- **ATM (At the Money)/OTM (Out of the Money)**: 0

**Example Calculations:**
Stock Trading at ₹8,100
- 8000 CE (Call European): Max(8100-8000, 0) = ₹100
- 8200 CE (Call European): Max(8100-8200, 0) = ₹0
- 8000 PE (Put European): Max(8000-8100, 0) = ₹0
- 8200 PE (Put European): Max(8200-8100, 0) = ₹100

### **3. OPTION MONEYNESS COMPARISON**

#### **Complete Moneyness Matrix**

| **Moneyness** | **Call Option** | **Put Option** | **Characteristics** |
|---------------|-----------------|----------------|-------------------|
| **Deep ITM (In the Money)** | Spot >> Strike | Spot << Strike | High intrinsic value, low time value |
| **ITM (In the Money)** | Spot > Strike | Spot < Strike | Some intrinsic value, moderate time value |
| **Near ATM (At the Money)** | Spot ≈ Strike | Spot ≈ Strike | No intrinsic value, maximum time value |
| **ATM (At the Money)** | Spot = Strike | Spot = Strike | Zero intrinsic value, highest time value |
| **OTM (Out of the Money)** | Spot < Strike | Spot > Strike | Zero intrinsic value, only time value |
| **Deep OTM (Out of the Money)** | Spot << Strike | Spot >> Strike | Zero intrinsic value, minimal time value |

#### **Moneyness Impact on Greeks**
**Delta Behavior:**
- ITM (In the Money) Options: Higher delta (closer to ±1)
- ATM (At the Money) Options: Delta around ±0.5
- OTM (Out of the Money) Options: Lower delta (closer to 0)

**Theta Impact:**
- ATM (At the Money) options decay fastest
- Deep ITM (In the Money)/OTM (Out of the Money) options decay slower
- Maximum time decay near expiry for ATM (At the Money)

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
**18000 CE (Call European) Price Sensitivity:**
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
| **Call ITM (In the Money)** | 0.5 to 1.0 | Positive, increases with depth | 0.8 for deep ITM (In the Money) call |
| **Call ATM (At the Money)** | Around 0.5 | Maximum sensitivity to spot | 0.5 for ATM (At the Money) call |
| **Call OTM (Out of the Money)** | 0 to 0.5 | Positive, decreases with distance | 0.2 for OTM (Out of the Money) call |
| **Put ITM (In the Money)** | -0.5 to -1.0 | Negative, more negative with depth | -0.8 for deep ITM (In the Money) put |
| **Put ATM (At the Money)** | Around -0.5 | Maximum sensitivity to spot | -0.5 for ATM (At the Money) put |
| **Put OTM (Out of the Money)** | 0 to -0.5 | Negative, less negative with distance | -0.2 for OTM (Out of the Money) put |

#### **Gamma Behavior**
**Common Characteristics:**
- Maximum gamma for ATM (At the Money) options
- Decreases for deep ITM (In the Money)/OTM (Out of the Money) options
- Increases as expiry approaches (for ATM (At the Money))
- Always positive for both calls and puts

**Theta Behavior:**
- Always negative for long options (buyers)
- Always positive for short options (sellers)
- Accelerates near expiry
- Maximum for ATM (At the Money) options

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

## 💡 **POSITION SIZING IN OPTIONS TRADING**

### **11. COMPREHENSIVE POSITION SIZING STRATEGIES**

#### **Options Position Sizing Methods**

| **METHOD** | **APPROACH** | **RISK FOCUS** | **BEST FOR** |
|------------|--------------|----------------|--------------|
| **Fixed Premium** | Same premium amount per trade | Premium loss | Conservative traders |
| **Fixed Contracts** | Same number of contracts | Simple execution | Beginners |
| **Risk-Based** | Based on maximum loss tolerance | Total portfolio risk | Professional traders |
| **Kelly Criterion** | Probability-based optimal sizing | Mathematical optimization | Advanced traders |
| **Volatility-Adjusted** | Adjust for implied volatility | Volatility risk | Experienced traders |

#### **Method 1: Fixed Premium Approach**
**Strategy**: Risk same premium amount regardless of option price
**Example**: Always risk ₹10,000 in premium per trade

**Practical Example**:
**Trading Capital**: ₹5,00,000
**Risk per Trade**: 2% = ₹10,000
**Option 1**: Nifty 18000 CE at ₹200 → Buy 50 contracts (₹10,000)
**Option 2**: Nifty 18500 CE at ₹50 → Buy 200 contracts (₹10,000)

**Advantage**: Consistent risk amount
**Disadvantage**: Different position sizes and Greeks exposure

#### **Method 2: Risk-Based Position Sizing**
**Strategy**: Size positions based on total account risk including Greeks
**Formula**: Position Size = Risk Amount ÷ Maximum Possible Loss

**Comprehensive Example**:
**Trading Capital**: ₹10,00,000
**Risk per Trade**: 3% = ₹30,000
**Trade**: Long Nifty 18000 CE at ₹200
**Maximum Loss**: Premium paid = ₹200 per contract
**Position Size**: ₹30,000 ÷ ₹200 = 150 contracts
**Total Premium**: 150 × ₹200 = ₹30,000

**Greeks Analysis**:
- **Delta**: 0.5 → Position delta = 150 × 0.5 = 75 (equivalent to 1 Nifty future)
- **Theta**: -₹50 per day → Daily decay = 150 × ₹50 = ₹7,500
- **Vega**: ₹100 per 1% IV → IV sensitivity = 150 × ₹100 = ₹15,000

#### **Method 3: Volatility-Adjusted Sizing**
**Strategy**: Adjust position size based on implied volatility levels
**Formula**: Base Size × (Normal IV ÷ Current IV)

**Detailed Example**:
**Base Position**: 100 contracts when IV is normal
**Normal IV**: 20%
**Current IV**: 30% (high volatility)
**Adjusted Position**: 100 × (20 ÷ 30) = 67 contracts

**When IV = 15%** (low volatility):
**Adjusted Position**: 100 × (20 ÷ 15) = 133 contracts

**Rationale**: High IV options are expensive, so buy fewer contracts

#### **Method 4: Kelly Criterion for Options**
**Formula**: f = (bp - q) / b
**Where**:
- f = Fraction of capital to risk
- b = Odds (average win ÷ average loss)
- p = Win probability
- q = Loss probability

**Options Trading Example**:
**Win Rate**: 40% (p = 0.4)
**Loss Rate**: 60% (q = 0.6)
**Average Win**: ₹500 per contract
**Average Loss**: ₹200 per contract (premium)
**Odds**: 500/200 = 2.5

**Kelly %**: (2.5 × 0.4 - 0.6) ÷ 2.5 = 0.16 = 16%
**Capital to Risk**: ₹10,00,000 × 16% = ₹1,60,000
**If premium is ₹200**: 1,60,000 ÷ 200 = 800 contracts

**Practical Adjustment**: Use 25% of Kelly = 200 contracts

---

## 📊 **PRACTICAL OPTIONS POSITION SIZING EXAMPLES**

### **12. REAL-WORLD SCENARIOS**

#### **Scenario 1: Conservative Long-Term Investor**
**Profile**: ₹15,00,000 capital, 1% risk per trade, buy protective puts
**Risk per Trade**: ₹15,000
**Strategy**: Buy puts to protect equity portfolio

**Equity Portfolio**: ₹12,00,000 (80% of capital)
**Protection Level**: 10% below current level
**Nifty Level**: 18,000
**Protection Level**: 16,200
**16200 PE Premium**: ₹120

**Hedge Calculation**:
- Portfolio Beta vs Nifty: Assume 1.0
- Nifty Exposure: ₹12,00,000
- Contracts Needed: ₹12,00,000 ÷ (18,000 × 75) = 8.89 ≈ 9 contracts
- **Total Premium**: 9 × ₹120 × 75 = ₹81,000
- **Risk Check**: ₹81,000 > ₹15,000 (exceeds risk limit)

**Alternative Approach**: Partial hedge with fewer contracts
**Contracts**: ₹15,000 ÷ (₹120 × 75) = 1.67 ≈ 2 contracts
**Protection Coverage**: 2 × ₹13,50,000 = ₹27,00,000 (22.5% of portfolio)

#### **Scenario 2: Active Options Trader**
**Profile**: ₹25,00,000 capital, 2% risk per trade, directional trading
**Risk per Trade**: ₹50,000
**Strategy**: Buy Nifty calls expecting 5% upward move

**Market Analysis**:
- Current Nifty: 18,000
- Target: 18,900 (5% up)
- Time Frame: 2 weeks
- Selected Option: 18200 CE at ₹150

**Position Sizing Calculation**:
- Maximum Loss: ₹150 per contract (premium)
- Position Size: ₹50,000 ÷ ₹150 = 333 contracts
- **Total Premium**: 333 × ₹150 = ₹49,950

**Risk-Reward Analysis**:
- **If Nifty hits 18,900**: Option value ≈ ₹700
- **Profit**: 333 × (₹700 - ₹150) = ₹1,83,150
- **ROI**: ₹1,83,150 ÷ ₹49,950 = 367%
- **Risk-Reward Ratio**: 1:3.67

#### **Scenario 3: Income Generation Strategy**
**Profile**: ₹50,00,000 capital, sell covered calls for income
**Strategy**: Own Nifty through ETF, sell calls for premium income

**Portfolio Setup**:
- Nifty ETF Holdings: ₹40,00,000 (equivalent to ~30 Nifty lots)
- Cash Reserve: ₹10,00,000
- Strategy: Sell OTM calls monthly

**Monthly Income Calculation**:
- Nifty Level: 18,000
- Sell 18500 CE (OTM) at ₹80
- **Contracts to Sell**: 30 (matching ETF holdings)
- **Monthly Income**: 30 × ₹80 × 75 = ₹1,80,000
- **Annualized Income**: ₹1,80,000 × 12 = ₹21,60,000
- **Yield on Portfolio**: ₹21,60,000 ÷ ₹50,00,000 = 43.2%

**Risk Management**:
- **Assignment Risk**: If Nifty > 18,500 at expiry
- **Opportunity Cost**: Miss gains above 18,500
- **Protection**: Keep some cash for rolling positions

---

## ✅ **ENHANCED QUIZ STRATEGIES**

### **13. COMPARISON-BASED EXAM QUESTIONS**

#### **Expected Question Types**
**Call vs Put Mechanics** (25%):
1. Intrinsic value calculations for both
2. Moneyness classification differences
3. Exercise conditions and payoffs
4. Greek behavior comparisons

**Position Sizing** (20%):
1. Risk-based position sizing calculations
2. Premium amount vs contract-based sizing
3. Volatility-adjusted position sizing
4. Portfolio hedging calculations

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
- **Position Size (Risk-Based)**: Risk Amount ÷ Maximum Loss per Contract
- **Kelly Criterion**: f = (bp - q) / b

---

## 🔢 **DETAILED MATHEMATICAL CALCULATIONS**

### **16. STEP-BY-STEP OPTION CALCULATIONS**

#### **Call Option P&L Calculation (Buyer)**
**Formula**: P&L = Max[0, (Spot Price - Strike Price)] - Premium Paid

**Example: Bajaj Auto 2050 Call Option**
```
Strike Price: ₹2,050
Premium Paid: ₹6.35
Lot Size: 250 shares

At Different Spot Prices on Expiry:
Spot ₹1,990: P&L = Max[0, (1990-2050)] - 6.35 = 0 - 6.35 = -₹6.35 per share
Spot ₹2,050: P&L = Max[0, (2050-2050)] - 6.35 = 0 - 6.35 = -₹6.35 per share  
Spot ₹2,080: P&L = Max[0, (2080-2050)] - 6.35 = 30 - 6.35 = +₹23.65 per share
Spot ₹2,120: P&L = Max[0, (2120-2050)] - 6.35 = 70 - 6.35 = +₹63.65 per share

Breakeven Point = Strike Price + Premium = 2050 + 6.35 = ₹2,056.35
Total P&L for 1 lot = Per share P&L × 250
```

#### **Put Option P&L Calculation (Buyer)**
**Formula**: P&L = Max[0, (Strike Price - Spot Price)] - Premium Paid

**Example: Nifty 18400 Put Option**
```
Strike Price: ₹18,400
Premium Paid: ₹315
Lot Size: 75 shares

At Different Spot Prices on Expiry:
Spot ₹17,000: P&L = Max[0, (18400-17000)] - 315 = 1400 - 315 = +₹1,085 per share
Spot ₹18,100: P&L = Max[0, (18400-18100)] - 315 = 300 - 315 = -₹15 per share
Spot ₹18,400: P&L = Max[0, (18400-18400)] - 315 = 0 - 315 = -₹315 per share
Spot ₹19,000: P&L = Max[0, (18400-19000)] - 315 = 0 - 315 = -₹315 per share

Breakeven Point = Strike Price - Premium = 18400 - 315 = ₹18,085
Total P&L for 1 lot = Per share P&L × 75
```

#### **Option Seller P&L Calculations**
**Call Option Seller Formula**: P&L = Premium Received - Max[0, (Spot Price - Strike Price)]
**Put Option Seller Formula**: P&L = Premium Received - Max[0, (Strike Price - Spot Price)]

**Example: Selling Bajaj Auto 2050 Call**
```
Premium Received: ₹6.35

At Expiry:
Spot ₹1,990: P&L = 6.35 - Max[0, (1990-2050)] = 6.35 - 0 = +₹6.35 per share
Spot ₹2,080: P&L = 6.35 - Max[0, (2080-2050)] = 6.35 - 30 = -₹23.65 per share
Spot ₹2,120: P&L = 6.35 - Max[0, (2120-2050)] = 6.35 - 70 = -₹63.65 per share

Maximum Profit = Premium Received = ₹6.35 per share
Maximum Loss = Unlimited (as stock can rise infinitely)
```

#### **Delta Calculation with Premium Change**
**Formula**: Expected Premium Change = Delta × Change in Underlying

**Example: Nifty 8250 Call Option**
```
Initial Setup:
- Spot Price: ₹8,292
- Option Premium: ₹144
- Delta: 0.6

Scenario 1: Nifty moves to ₹8,355
Change in Underlying = 8355 - 8292 = 63 points
Expected Premium Change = 0.6 × 63 = 37.8 points
New Premium = 144 + 37.8 = ₹181.8

Scenario 2: Nifty moves to ₹8,200  
Change in Underlying = 8200 - 8292 = -92 points
Expected Premium Change = 0.6 × (-92) = -55.2 points
New Premium = 144 - 55.2 = ₹88.8
```

#### **Put Option Delta Calculation**
**Example: Nifty 8300 Put Option**
```
Initial Setup:
- Spot Price: ₹8,268  
- Option Premium: ₹128
- Delta: -0.55

Scenario 1: Nifty moves to ₹8,310
Change in Underlying = 8310 - 8268 = 42 points
Expected Premium Change = -0.55 × 42 = -23.1 points
New Premium = 128 - 23.1 = ₹104.9

Scenario 2: Nifty moves to ₹8,230
Change in Underlying = 8230 - 8268 = -38 points  
Expected Premium Change = -0.55 × (-38) = +20.9 points
New Premium = 128 + 20.9 = ₹148.9
```

#### **Portfolio Delta Calculation**
**Formula**: Portfolio Delta = Σ(Position Size × Option Delta)

**Example: Multi-Option Portfolio**
```
Position 1: Long 100 lots Nifty 18800 CE (Delta: 0.4)
Position 2: Short 150 lots Nifty 18900 CE (Delta: 0.25) 
Position 3: Long 200 lots Nifty 18700 PE (Delta: -0.6)

Portfolio Delta Calculation:
= (100 × 0.4) + (-150 × 0.25) + (200 × -0.6)
= 40 - 37.5 - 120  
= -117.5

Interpretation: Portfolio behaves like being short 117.5 Nifty futures
For every 1-point Nifty move up, portfolio loses ₹117.5 × 75 = ₹8,812
```

#### **Put-Call Parity Calculation**
**Formula**: Call Premium + PV(Strike) = Put Premium + Spot Price

**Example: Verification**
```
Stock: TCS
Spot Price: ₹2,350
Strike Price: ₹2,350 (ATM)
Risk-free Rate: 7%
Time to Expiry: 30 days

PV(Strike) = 2350 × e^(-0.07 × 30/365) = 2350 × 0.9943 = ₹2,336.6

Observed Prices:
Call Premium: ₹45
Put Premium: ₹31.6

Put-Call Parity Check:
LHS = Call + PV(Strike) = 45 + 2336.6 = 2381.6
RHS = Put + Spot = 31.6 + 2350 = 2381.6

Result: LHS = RHS ✓ (Put-call parity holds)
```

#### **Black-Scholes Input Example**
**Example: ICICI Bank 280 Call Option**
```
Inputs Required:
- Spot Price: ₹272.7
- Strike Price: ₹280  
- Risk-free Rate: 7.48%
- Time to Expiry: 1 day
- Implied Volatility: 43.55%
- Dividend: ₹0

Black-Scholes Outputs:
- Theoretical Call Price: ₹1.2
- Theoretical Put Price: ₹8.4
- Delta: 0.15
- Gamma: 0.02
- Theta: -2.1
- Vega: 1.8
```

---

**REMEMBER**: Options provide asymmetric risk-reward profiles with limited downside (premium) and potentially unlimited upside. Call and put options are complementary instruments with opposite directional exposures. Position sizing is crucial - never risk more than 2-3% of capital per trade. Understanding moneyness, Greeks behavior, and put-call parity is essential for options trading and risk management.

**EXAM FOCUS**: Master the differences between calls and puts, understand moneyness classification, practice intrinsic value calculations, know Greek behavior patterns, understand position sizing methodologies, and understand European vs American exercise styles. Position sizing calculations are increasingly important in professional options trading.

---
*Rights • Obligations • Premiums • Probabilities*
*Master the Asymmetry, Understand the Greeks* 