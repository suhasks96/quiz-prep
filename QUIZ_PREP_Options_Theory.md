# QUIZ PREP: Options Theory & Fundamentals
*Based on Module 5: Options Theory for Professional Trading*

## 🎯 **OPTIONS FUNDAMENTALS**

### **1. WHAT ARE OPTIONS?**

#### **Definition & Key Concept**
- **Option**: A contract giving the RIGHT (not obligation) to buy/sell an asset
- **Buyer**: Pays premium, has the right to exercise
- **Seller (Writer)**: Receives premium, has obligation to fulfill if exercised
- **Premium**: Price paid for the option contract
- **Strike Price**: Predetermined price at which option can be exercised

#### **Real-World Analogy: Land Purchase Agreement**
**Ajay-Venu Example:**
- **Ajay pays ₹1,00,000** (premium) to Venu
- **Gets RIGHT** to buy land at ₹5,00,000 (strike) in 6 months
- **If land price rises to ₹10,00,000**: Ajay exercises, buys at ₹5,00,000
- **If land price falls to ₹3,00,000**: Ajay walks away, loses only ₹1,00,000
- **Venu keeps premium** in all scenarios

**💡 Quiz Tip**: Options provide asymmetric risk-reward - limited loss for buyers, unlimited profit potential!

---

### **2. TYPES OF OPTIONS**

#### **Call Options**
**Definition**: Right to BUY an asset at strike price
- **Buyer's View**: Bullish on underlying asset
- **Buyer's Right**: Can buy at strike price
- **Buyer's Risk**: Limited to premium paid
- **Buyer's Reward**: Unlimited upside potential

**Call Option Example:**
- **Reliance Current Price**: ₹2,500
- **Buy Call Option**: Strike ₹2,600, Premium ₹50
- **Breakeven**: ₹2,600 + ₹50 = ₹2,650
- **Profit if Reliance > ₹2,650**

#### **Put Options**
**Definition**: Right to SELL an asset at strike price
- **Buyer's View**: Bearish on underlying asset
- **Buyer's Right**: Can sell at strike price
- **Buyer's Risk**: Limited to premium paid
- **Buyer's Reward**: Profit if price falls below strike

**Put Option Example:**
- **Nifty Current Level**: 18,000
- **Buy Put Option**: Strike 17,800, Premium ₹100
- **Breakeven**: 17,800 - 100 = 17,700
- **Profit if Nifty < 17,700**

---

### **3. OPTION PARTICIPANTS**

#### **Option Buyer (Long Position)**
**Call Buyer:**
- **Expectation**: Asset price will rise above strike + premium
- **Maximum Loss**: Premium paid
- **Maximum Profit**: Unlimited (theoretically)
- **Breakeven**: Strike Price + Premium

**Put Buyer:**
- **Expectation**: Asset price will fall below strike - premium
- **Maximum Loss**: Premium paid
- **Maximum Profit**: Strike Price - Premium (if asset goes to zero)
- **Breakeven**: Strike Price - Premium

#### **Option Seller/Writer (Short Position)**
**Call Seller:**
- **Expectation**: Asset price will stay below strike + premium
- **Maximum Profit**: Premium received
- **Maximum Loss**: Unlimited (theoretically)
- **Obligation**: Sell asset at strike if exercised

**Put Seller:**
- **Expectation**: Asset price will stay above strike - premium
- **Maximum Profit**: Premium received
- **Maximum Loss**: Strike Price - Premium
- **Obligation**: Buy asset at strike if exercised

---

### **4. OPTION PAYOFF PROFILES**

#### **Call Option Payoffs**

**Long Call (Buyer):**
```
Profit/Loss = Max(0, Spot Price - Strike Price) - Premium
- If Spot > Strike: Profit = (Spot - Strike) - Premium
- If Spot ≤ Strike: Loss = -Premium
```

**Short Call (Seller):**
```
Profit/Loss = Premium - Max(0, Spot Price - Strike Price)
- If Spot > Strike: Loss = Premium - (Spot - Strike)
- If Spot ≤ Strike: Profit = Premium
```

#### **Put Option Payoffs**

**Long Put (Buyer):**
```
Profit/Loss = Max(0, Strike Price - Spot Price) - Premium
- If Spot < Strike: Profit = (Strike - Spot) - Premium
- If Spot ≥ Strike: Loss = -Premium
```

**Short Put (Seller):**
```
Profit/Loss = Premium - Max(0, Strike Price - Spot Price)
- If Spot < Strike: Loss = Premium - (Strike - Spot)
- If Spot ≥ Strike: Profit = Premium
```

---

### **5. OPTION PRICING FACTORS**

#### **Intrinsic Value**
**For Call Options:**
- **Intrinsic Value** = Max(0, Current Price - Strike Price)
- **In-the-Money (ITM)**: Current Price > Strike Price
- **At-the-Money (ATM)**: Current Price = Strike Price
- **Out-of-the-Money (OTM)**: Current Price < Strike Price

**For Put Options:**
- **Intrinsic Value** = Max(0, Strike Price - Current Price)
- **In-the-Money (ITM)**: Current Price < Strike Price
- **At-the-Money (ATM)**: Current Price = Strike Price
- **Out-of-the-Money (OTM)**: Current Price > Strike Price

#### **Time Value**
**Option Premium = Intrinsic Value + Time Value**

**Time Decay (Theta):**
- **Time Value decreases** as expiry approaches
- **Accelerates in final weeks** before expiry
- **Benefits option sellers**, hurts option buyers

#### **Key Pricing Factors (The Greeks)**

**Delta**: Price sensitivity to underlying movement
- **Call Delta**: 0 to 1 (positive)
- **Put Delta**: -1 to 0 (negative)
- **ATM Options**: Delta ≈ 0.5 (calls) or -0.5 (puts)

**Gamma**: Rate of change of delta
- **Highest for ATM options**
- **Important for dynamic hedging**

**Theta**: Time decay
- **Negative for option buyers**
- **Positive for option sellers**

**Vega**: Volatility sensitivity
- **Higher volatility** = Higher option prices
- **ATM options** most sensitive to volatility

**Rho**: Interest rate sensitivity
- **Less significant** for short-term options

---

### **6. VOLATILITY - THE MOST IMPORTANT FACTOR**

#### **Types of Volatility**

**Historical Volatility:**
- **Actual price movements** in the past
- **Calculated from historical data**
- **Annualized standard deviation** of returns

**Implied Volatility (IV):**
- **Market's expectation** of future volatility
- **Derived from option prices**
- **Key factor** in option valuation

#### **Volatility Impact**
- **High Volatility**: Higher option premiums
- **Low Volatility**: Lower option premiums
- **Volatility Smile**: IV varies across strikes
- **Earnings/Events**: Cause volatility spikes

#### **Volatility Trading Strategy**
**Buy Options when:**
- **IV is low** compared to historical levels
- **Expecting significant** price movement
- **Before earnings/events**

**Sell Options when:**
- **IV is high** compared to historical levels
- **Expecting price stability**
- **After earnings/events** (IV crush)

---

### **7. PRACTICAL OPTION STRATEGIES**

#### **Basic Strategies**

**1. Long Call (Bullish)**
- **When**: Expecting price rise + moderate volatility
- **Risk**: Limited to premium
- **Reward**: Unlimited upside

**2. Long Put (Bearish)**
- **When**: Expecting price fall + moderate volatility
- **Risk**: Limited to premium
- **Reward**: Limited to strike price

**3. Short Call (Neutral to Bearish)**
- **When**: Expecting price stability or decline
- **Risk**: Unlimited upside
- **Reward**: Limited to premium

**4. Short Put (Neutral to Bullish)**
- **When**: Expecting price stability or rise
- **Risk**: Limited to strike price
- **Reward**: Limited to premium

#### **Risk Management for Option Sellers**
1. **Never sell naked calls** without hedge
2. **Use stop losses** at 2x premium received
3. **Diversify across strikes** and expiries
4. **Monitor margins** continuously
5. **Close positions** before expiry if ITM

---

### **8. EXERCISE & ASSIGNMENT**

#### **Exercise Methods**
**European Style:**
- **Exercise only at expiry**
- **Most index options** in India
- **Nifty/Bank Nifty** options

**American Style:**
- **Exercise anytime** before expiry
- **Individual stock options** in India
- **Higher premium** due to flexibility

#### **Assignment Process**
- **Random assignment** among short option holders
- **Settlement**: Cash settled for indices
- **Physical delivery**: For stock options (if applicable)
- **Assignment risk**: Higher near expiry for ITM options

---

## 💰 **BUSINESS & ENTREPRENEURSHIP APPLICATIONS**

### **9. CORPORATE APPLICATIONS**

#### **Employee Stock Options (ESOPs)**
- **Incentive Mechanism**: Align employee-company interests
- **Vesting Period**: Usually 3-4 years
- **Exercise Price**: Below market price at grant
- **Wealth Creation**: Employees benefit from company growth

#### **Risk Management**
**Portfolio Insurance:**
- **Protective Puts**: Insurance for stock portfolios
- **Cost**: Premium paid for downside protection
- **Benefit**: Participate in upside, limited downside

**Revenue Hedging:**
- **Export businesses**: Use currency options
- **Commodity businesses**: Hedge raw material costs
- **Benefit**: Predictable cash flows

### **10. INVESTMENT STRATEGIES**

#### **Income Generation**
**Covered Calls:**
- **Strategy**: Own stock + sell call options
- **Income**: Earn premium + dividends
- **Risk**: Cap upside potential

**Cash-Secured Puts:**
- **Strategy**: Hold cash + sell put options
- **Income**: Earn premium while waiting to buy
- **Risk**: May have to buy at higher than market price

#### **Speculation vs Investment**
**Option Buying (Speculation):**
- **High Risk**: 80% options expire worthless
- **High Reward**: Leverage amplifies gains
- **Time Sensitive**: Fighting time decay

**Option Selling (Income):**
- **Higher Probability**: Time decay works in favor
- **Limited Profit**: Capped at premium received
- **Risk Management**: Essential for success

---

## 🎯 **QUIZ SUCCESS STRATEGIES**

### **Key Concepts to Master**
1. **Options vs Futures**: Rights vs obligations
2. **Asymmetric Payoffs**: Limited loss, unlimited gain (buyers)
3. **Time Decay**: Theta works against buyers
4. **Volatility Impact**: Higher vol = higher premiums
5. **Greeks Understanding**: Delta, gamma, theta, vega

### **Important Formulas**
- **Call Intrinsic Value**: Max(0, Spot - Strike)
- **Put Intrinsic Value**: Max(0, Strike - Spot)
- **Option Premium**: Intrinsic Value + Time Value
- **Call Breakeven**: Strike + Premium
- **Put Breakeven**: Strike - Premium

### **Critical Numbers**
- **Nifty Option Lot Size**: 50 units
- **Bank Nifty Option Lot Size**: 25 units
- **Typical Theta Decay**: Accelerates in last 30 days
- **Assignment Probability**: Increases near expiry for ITM options
- **Margin for Selling**: Usually 10-20% of contract value

### **Risk Management Rules**
1. **Option Buying**: Risk only 2-5% of capital per trade
2. **Option Selling**: Never sell naked calls
3. **Diversification**: Don't concentrate in single strike/expiry
4. **Exit Strategy**: Plan before entering trade
5. **Volatility Awareness**: Buy low IV, sell high IV

### **Real-World Applications**
- **Corporate Finance**: ESOPs and hedging strategies
- **Portfolio Management**: Insurance and income generation
- **Speculation**: Leveraged directional bets
- **Risk Management**: Asymmetric risk-reward profiles

**Remember**: Options are sophisticated instruments. The key advantage is asymmetric risk-reward for buyers. However, 80% of options expire worthless, so proper strategy selection and risk management are crucial. Focus on understanding intrinsic value, time decay, and volatility impact for quiz success! 