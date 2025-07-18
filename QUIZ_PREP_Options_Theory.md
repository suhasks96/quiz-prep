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

---

## 📉 **PUT OPTIONS**

### **4. PUT OPTION BASICS**

#### **Definition**
**Put Option**: Gives the buyer the right to SELL the underlying asset at a specific price (strike price) before/on expiry

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

---

## 💰 **INTRINSIC VALUE & MONEYNESS**

### **5. INTRINSIC VALUE CONCEPTS**

#### **Definition**
**Intrinsic Value**: The amount of money an option buyer would make if exercising the option immediately

#### **Key Properties**
- **Cannot be Negative**: Minimum value is zero
- **Immediate Exercise Value**: Money made by exercising today
- **Real Worth**: Tangible value in the option

#### **Intrinsic Value Formulas**
**Call Option**: Intrinsic Value = Max(0, Spot Price - Strike Price)
**Put Option**: Intrinsic Value = Max(0, Strike Price - Spot Price)

#### **Calculation Examples**
**Call Option Examples:**

| Strike | Spot | Intrinsic Value | Calculation |
|--------|------|----------------|-------------|
| 280 | 310 | 30 | 310 - 280 = 30 |
| 920 | 918 | 0 | 918 - 920 = -2, but IV = 0 |

**Put Option Examples:**

| Strike | Spot | Intrinsic Value | Calculation |
|--------|------|----------------|-------------|
| 1040 | 980 | 60 | 1040 - 980 = 60 |
| 80 | 88 | 0 | 80 - 88 = -8, but IV = 0 |

### **6. MONEYNESS CLASSIFICATION**

#### **Call Option Moneyness**
**In-the-Money (ITM)**: Spot Price > Strike Price
- **Example**: Spot ₹8060, Strike ₹8000 → ITM
- **Intrinsic Value**: Positive (₹60)

**At-the-Money (ATM)**: Spot Price ≈ Strike Price
- **Example**: Spot ₹8060, Strike ₹8050 → ATM
- **Intrinsic Value**: Near zero

**Out-of-the-Money (OTM)**: Spot Price < Strike Price
- **Example**: Spot ₹8060, Strike ₹8100 → OTM
- **Intrinsic Value**: Zero

#### **Put Option Moneyness**
**In-the-Money (ITM)**: Spot Price < Strike Price
- **Example**: Spot ₹8200, Strike ₹8300 → ITM
- **Intrinsic Value**: Positive (₹100)

**At-the-Money (ATM)**: Spot Price ≈ Strike Price
- **Example**: Spot ₹8200, Strike ₹8200 → ATM
- **Intrinsic Value**: Near zero

**Out-of-the-Money (OTM)**: Spot Price > Strike Price
- **Example**: Spot ₹8200, Strike ₹8000 → OTM
- **Intrinsic Value**: Zero

#### **General Rules**
**For Call Options:**
- All strikes **below ATM** = ITM
- All strikes **above ATM** = OTM

**For Put Options:**
- All strikes **above ATM** = ITM  
- All strikes **below ATM** = OTM

#### **Deep ITM/OTM**
**Deep ITM**: Very high intrinsic value
**Deep OTM**: Very low intrinsic value
**Premium Pattern**: ITM options always more expensive than OTM options

---

## 📊 **OPTION CHAIN ANALYSIS**

### **7. UNDERSTANDING OPTION CHAINS**

#### **Option Chain Structure**
**Layout:**
- **Left Side**: Call options (CE)
- **Center**: Strike prices (ascending order)
- **Right Side**: Put options (PE)
- **Color Coding**: Yellow background for ITM, white for OTM

#### **Key Information Available**
- **Last Traded Price (LTP)**: Current premium
- **Bid-Ask Prices**: Buy/sell quotes
- **Volume**: Trading activity
- **Open Interest**: Outstanding contracts
- **Implied Volatility**: Market's volatility expectation

#### **Reading Option Chain Example**
**Underlying**: Ashoka Leyland at ₹68.70
**ATM Strike**: ₹67.50 (closest to spot)
**Call Options**: Left side, ITM strikes highlighted
**Put Options**: Right side, ITM strikes highlighted

---

## 🔢 **OPTION GREEKS**

### **8. DELTA - DIRECTIONAL SENSITIVITY**

#### **Delta Definition**
**Delta**: Measures rate of change in option premium for every 1-point move in underlying

#### **Delta Ranges**
**Call Options**: 0 to +1 (or 0 to +100)
**Put Options**: -1 to 0 (or -100 to 0)

#### **Delta Calculation Example**
**Given:**
- **Nifty**: 8288
- **8250 CE Premium**: ₹133
- **Delta**: 0.55

**If Nifty moves to 8310 (+22 points):**
- **Premium Change**: 22 × 0.55 = 12.1
- **New Premium**: 133 + 12.1 = ₹145.1

**If Nifty moves to 8200 (-88 points):**
- **Premium Change**: -88 × 0.55 = -48.4
- **New Premium**: 133 - 48.4 = ₹84.6

#### **Delta Applications**
**Strike Selection**: Higher delta options give more profit for favorable moves
**Example**: 100-point Nifty move
- **Option 1 (Delta 0.05)**: Premium change = 5 points
- **Option 2 (Delta 0.20)**: Premium change = 20 points
- **Choice**: Option 2 is better for bullish views

#### **Delta Characteristics**
**Call Options:**
- **ITM calls**: Delta closer to 1
- **ATM calls**: Delta around 0.5
- **OTM calls**: Delta closer to 0

**Put Options:**
- **ITM puts**: Delta closer to -1
- **ATM puts**: Delta around -0.5  
- **OTM puts**: Delta closer to 0

### **9. GAMMA - DELTA'S ACCELERATION**

#### **Gamma Definition**
**Gamma**: Rate of change of delta itself as underlying moves

#### **Gamma Characteristics**
**Highest**: ATM options have highest gamma
**Importance**: Shows how quickly delta changes
**Impact**: Higher gamma = more volatile delta
**Time Effect**: Gamma increases as expiry approaches

### **10. THETA - TIME DECAY**

#### **Theta Definition**  
**Theta**: Rate of premium decline due to passage of time

#### **Theta Characteristics**
**Always Negative**: For option buyers (premium decreases with time)
**Accelerates**: Time decay faster near expiry
**ATM Impact**: ATM options have highest theta
**Time Value**: Theta affects time value, not intrinsic value

#### **Time Decay Example**
- **Monday**: Option premium ₹50
- **Tuesday**: Option premium ₹48 (if no price movement)
- **Theta**: -₹2 per day

### **11. VEGA - VOLATILITY SENSITIVITY**

#### **Vega Definition**
**Vega**: Rate of change in premium due to change in volatility

#### **Volatility Impact**
**Higher Volatility**: Increases option premiums
**Lower Volatility**: Decreases option premiums
**ATM Effect**: ATM options most sensitive to volatility
**Time Factor**: Longer expiry options more sensitive

#### **Vega Example**
- **Current Premium**: ₹25
- **Vega**: 0.15
- **Volatility increase**: 1% → Premium becomes ₹25.15

---

## 💡 **OPTION PRICING FACTORS**

### **12. BLACK-SCHOLES PRICING MODEL**

#### **Key Pricing Factors**
1. **Spot Price**: Current price of underlying
2. **Strike Price**: Exercise price of option
3. **Time to Expiry**: Days remaining until expiration
4. **Volatility**: Expected price fluctuation
5. **Risk-free Rate**: Government bond yields
6. **Dividends**: Expected dividend payments

#### **Factor Impact on Premiums**
**Call Options:**
- **↑ Spot Price**: ↑ Premium
- **↑ Strike Price**: ↓ Premium  
- **↑ Time**: ↑ Premium
- **↑ Volatility**: ↑ Premium
- **↑ Interest Rate**: ↑ Premium

**Put Options:**
- **↑ Spot Price**: ↓ Premium
- **↑ Strike Price**: ↑ Premium
- **↑ Time**: ↑ Premium
- **↑ Volatility**: ↑ Premium
- **↑ Interest Rate**: ↓ Premium

### **13. PREMIUM COMPONENTS**

#### **Premium Breakdown**
**Option Premium = Intrinsic Value + Time Value**

**Time Value**: Extra amount paid above intrinsic value
**Calculation**: Time Value = Premium - Intrinsic Value

#### **Time Value Characteristics**
**Maximum**: ATM options have highest time value
**Decay**: Decreases as expiry approaches
**Zero at Expiry**: Time value becomes zero at expiration
**Volatility**: Higher volatility = higher time value

---

## 🎯 **PRACTICAL TRADING CONCEPTS**

### **14. OPTION STRATEGIES BASICS**

#### **Directional Strategies**
**Bullish View**: Buy calls or sell puts
**Bearish View**: Buy puts or sell calls
**Neutral View**: Sell straddles or strangles

#### **Risk-Reward Profiles**
**Long Options**: Limited loss, unlimited profit potential
**Short Options**: Limited profit, unlimited loss potential
**Spreads**: Limited profit and loss

### **15. VOLATILITY CONCEPTS**

#### **Types of Volatility**
**Historical Volatility**: Past price movements
**Implied Volatility**: Market's expectation of future volatility
**Important**: IV affects all option premiums

#### **Volatility Trading**
**High IV**: Consider selling options
**Low IV**: Consider buying options
**IV Rank**: Compare current IV to historical range

---

## ✅ **QUIZ SUCCESS STRATEGIES**

### **16. KEY FORMULAS TO MEMORIZE**

#### **Intrinsic Value**
- **Call IV** = Max(0, Spot - Strike)
- **Put IV** = Max(0, Strike - Spot)

#### **Delta Applications**
- **Premium Change** = Delta × Underlying Price Change
- **Call Delta Range**: 0 to +1
- **Put Delta Range**: -1 to 0

#### **Premium Components**
- **Option Premium** = Intrinsic Value + Time Value
- **Time Value** = Premium - Intrinsic Value

### **17. IMPORTANT CONCEPTS**

#### **Must-Know Classifications**
**Moneyness**: ITM, ATM, OTM for both calls and puts
**Greeks Impact**: Delta for direction, theta for time, vega for volatility
**Premium Patterns**: ITM > ATM > OTM in terms of premium cost
**Time Decay**: Accelerates near expiry, especially for ATM options

#### **Critical Relationships**
**Spot vs Strike**: Determines moneyness
**Time vs Premium**: More time = higher premium
**Volatility vs Premium**: Higher volatility = higher premium
**Delta vs Moneyness**: ITM high delta, OTM low delta

### **18. COMMON EXAM TOPICS**

**Option Basics** (30%):
1. Call vs put option definitions
2. Rights vs obligations concept
3. Premium, strike, expiry terminology
4. Intrinsic value calculations

**Moneyness Classification** (25%):
1. ITM, ATM, OTM identification
2. Call vs put moneyness rules
3. Deep ITM/OTM concepts
4. Premium patterns across strikes

**Option Greeks** (25%):
1. Delta calculations and applications
2. Understanding gamma, theta, vega
3. Greeks impact on different strikes
4. Time decay concepts

**Practical Applications** (20%):
1. Option chain reading
2. Strike selection criteria
3. Volatility impact understanding
4. Basic strategy concepts

### **19. CALCULATION PRACTICE TIPS**

#### **Step-by-Step Approach**
1. **Identify**: Call or put option
2. **Determine**: Current spot vs strike price
3. **Calculate**: Intrinsic value using correct formula
4. **Classify**: ITM, ATM, or OTM
5. **Apply**: Greeks for price change impact

#### **Common Mistakes to Avoid**
- **Wrong Moneyness**: Confusing call vs put ITM/OTM rules
- **Negative Intrinsic Value**: Remember IV cannot be negative
- **Delta Confusion**: Call delta positive, put delta negative
- **Time Value Error**: Mixing up intrinsic value and time value

---

## 🏆 **ADVANCED CONCEPTS**

### **20. VOLATILITY SMILE**

#### **IV Patterns**
**ATM Options**: Usually have lowest implied volatility
**ITM/OTM Options**: Higher implied volatility
**Smile Effect**: Graph of IV vs strike looks like smile

### **21. ASSIGNMENT AND EXERCISE**

#### **Exercise Scenarios**
**American Options**: Can exercise anytime before expiry
**European Options**: Can exercise only on expiry
**Automatic Exercise**: ITM options exercised automatically at expiry

#### **Assignment Risk**
**Short Option Positions**: Can be assigned anytime
**Random Assignment**: Exchange randomly assigns exercise notices
**Early Assignment**: Usually on dividend dates for ITM options

---

**REMEMBER**: Options provide asymmetric risk-reward profiles through limited loss potential for buyers and unlimited profit potential. Master the Greeks to understand how premiums change, focus on intrinsic value calculations, and always consider time decay impact. The land deal analogy is the foundation - understand it thoroughly!

**EXAM FOCUS**: Practice intrinsic value calculations extensively, memorize ITM/OTM rules for calls vs puts, understand delta applications, and be clear about the components that make up option premiums.

---
*Rights • Obligations • Greeks • Time Decay • Volatility*
*Master the Asymmetry, Respect the Greeks, Time is Your Enemy or Friend* 