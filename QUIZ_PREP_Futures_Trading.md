# QUIZ PREP: Futures Trading & Derivatives
*Based on Module 4: Futures Trading*

## 🎯 **DERIVATIVES FUNDAMENTALS**

### **1. WHAT ARE DERIVATIVES?**

#### **Core Definition**
**Derivative**: Financial instrument whose value is derived from an underlying asset
**Underlying Assets**: Stocks, indices, commodities, currencies, bonds

#### **Types of Derivatives**
**Forwards**: Customized contracts between two parties
**Futures**: Standardized forwards traded on exchanges
**Options**: Right (not obligation) to buy/sell at specific price
**Swaps**: Exchange of cash flows between parties

#### **Key Characteristics**
- **Leverage**: Control large positions with small capital
- **Risk Management**: Hedge against price movements
- **Price Discovery**: Help determine fair value of assets
- **Speculation**: Amplify returns (and risks)

### **2. FORWARDS vs FUTURES**

#### **Forward Contracts**
**Definition**: Agreement to buy/sell asset at future date for predetermined price

**Example - Gold Forward:**
```
ABC Jewelers & XYZ Gold Dealers:
- Asset: 15 kg gold
- Price: ₹2,450 per gram
- Delivery: 3 months
- Risk: High counterparty default risk
```

**Problems with Forwards:**
- **Counterparty Risk**: No guarantee of settlement
- **Illiquidity**: Cannot trade before expiry
- **Customization**: No standardization
- **Credit Risk**: No margin or collateral system

#### **Futures Contracts**
**Definition**: Standardized forward contracts traded on exchanges

**Key Improvements:**
- **Exchange Guarantee**: Clearing corporation eliminates default risk
- **Standardization**: Fixed lot sizes, expiry dates, tick sizes
- **Daily Settlement**: Mark-to-market reduces risk
- **Liquidity**: Can square off anytime before expiry
- **Margin System**: Collateral requirement ensures performance

**Contract Specifications Example (Nifty):**
- **Lot Size**: 75 units
- **Tick Size**: ₹0.05
- **Expiry**: Last Thursday of month
- **Settlement**: Cash settled

---

## 📊 **FUTURES CONTRACT MECHANICS**

### **3. CONTRACT VALUE & CALCULATIONS**

#### **Contract Value Formula**
**Contract Value = Futures Price × Lot Size**

**Example Calculations:**
- **Nifty 50**: 18,000 × 75 = ₹13,50,000
- **Bank Nifty**: 43,000 × 25 = ₹10,75,000
- **TCS**: 3,500 × 250 = ₹8,75,000

#### **Lot Size Importance**
**Standardization**: Same for all traders
**Minimum Quantity**: Cannot buy partial lots
**Calculation Base**: All P&L calculations use lot size
**Affordability**: Different products suit different capital sizes

### **4. LONG vs SHORT POSITIONS**

#### **Long Position (Buy Futures)**
**Expectation**: Underlying price will rise
**Entry**: Buy futures contract
**Profit Condition**: Futures price > Entry price
**P&L Formula**: (Exit Price - Entry Price) × Lot Size

**Example:**
- Buy TCS Futures at ₹2,362, Lot Size: 250
- Exit at ₹2,400: Profit = (2,400 - 2,362) × 250 = ₹9,500
- Exit at ₹2,300: Loss = (2,300 - 2,362) × 250 = ₹15,500

#### **Short Position (Sell Futures)**
**Expectation**: Underlying price will fall
**Entry**: Sell futures contract first
**Profit Condition**: Futures price < Entry price
**P&L Formula**: (Entry Price - Exit Price) × Lot Size

**Example:**
- Sell TCS Futures at ₹2,362, Lot Size: 250
- Exit at ₹2,300: Profit = (2,362 - 2,300) × 250 = ₹15,500
- Exit at ₹2,400: Loss = (2,362 - 2,400) × 250 = ₹9,500

---

## ⚡ **LEVERAGE & MARGIN SYSTEM**

### **5. UNDERSTANDING LEVERAGE**

#### **Leverage Concept**
**Definition**: Ability to control large positions with small capital
**Mechanism**: Deposit margin (small amount) to trade large contract value
**Amplification**: Both profits and losses get magnified

#### **Leverage Calculation**
**Formula**: Leverage = Contract Value ÷ Margin Required

**Example:**
- **Contract Value**: ₹13,50,000 (Nifty at 18,000)
- **Margin Required**: ₹70,000
- **Leverage**: 13,50,000 ÷ 70,000 = 19.3x

**Impact**: 1% move in Nifty = 19.3% impact on margin

### **6. MARGIN SYSTEM DETAILS**

#### **Types of Margins**
**Initial Margin = SPAN Margin + Exposure Margin**

**SPAN Margin:**
- **Purpose**: Exchange-mandated minimum margin
- **Calculation**: Based on volatility and risk assessment
- **Maintenance**: Must be maintained overnight
- **Penalty**: Charged if insufficient

**Exposure Margin:**
- **Purpose**: Additional buffer for MTM losses
- **Rate**: 3-5% of contract value typically
- **Function**: Cushion against adverse price movements

#### **Margin Calculation Example**
**HDFC Bank Futures Trade:**
- **Contract Value**: ₹2,34,675 (938.7 × 250)
- **SPAN Margin**: 7.5% = ₹17,600
- **Exposure Margin**: 5.0% = ₹11,733
- **Total Initial Margin**: ₹29,334

### **7. MARK-TO-MARKET (M2M)**

#### **M2M Concept**
**Definition**: Daily settlement of profits/losses
**Purpose**: Eliminate accumulation of large losses
**Mechanism**: Credit profits, debit losses daily
**Reference**: Previous day's closing price

#### **M2M Process Example**
**Hindalco Futures Trade:**
- **Entry**: ₹165 on Dec 1st
- **Lot Size**: 2,000 shares

**Daily M2M Calculation:**

| Date | Closing Price | Reference | Daily M2M | Cumulative |
|------|---------------|-----------|-----------|------------|
| Dec 1 | ₹168.3 | ₹165.0 | +₹6,600 | +₹6,600 |
| Dec 2 | ₹172.4 | ₹168.3 | +₹8,200 | +₹14,800 |
| Dec 3 | ₹171.6 | ₹172.4 | -₹1,600 | +₹13,200 |
| Dec 4 | ₹170.1 | ₹171.6 | -₹3,000 | +₹10,200 |

**Daily Settlement**: Money credited/debited same day
**Price Reset**: Next day's reference = Previous day's close

#### **M2M Benefits**
**Risk Reduction**: Prevents large loss accumulation
**Fair Settlement**: Daily profit/loss distribution
**Transparency**: Clear daily position tracking
**Exchange Safety**: Reduces counterparty default risk

---

## 📈 **PAYOFF STRUCTURE & CHARACTERISTICS**

### **8. LINEAR PAYOFF STRUCTURE**

#### **Futures Payoff Properties**
**Linear Relationship**: P&L changes proportionally with price movement
**Symmetrical Risk**: Equal profit/loss potential
**No Limit**: Unlimited profit/loss potential
**Direct Correlation**: 1:1 price movement impact

#### **Payoff Diagram Characteristics**
**Long Position:**
- **Slope**: Positive (upward sloping line)
- **Breakeven**: Entry price
- **Profit**: Above entry price
- **Loss**: Below entry price

**Short Position:**
- **Slope**: Negative (downward sloping line)
- **Breakeven**: Entry price
- **Profit**: Below entry price
- **Loss**: Above entry price

### **9. ZERO-SUM GAME CONCEPT**

#### **Money Transfer vs Money Creation**
**Zero-Sum Game**: Futures trading transfers money, doesn't create it
**Winner-Loser**: Buyer's profit = Seller's loss (and vice versa)
**No Value Addition**: No new wealth created in system

**Example:**
- Buyer profit of ₹10,000 = Seller loss of ₹10,000
- Total system gain/loss = Zero
- Money flows from loser to winner

#### **Contrast with Equity Investment**
**Equity Investment**: Can create wealth through business growth
**Futures Trading**: Pure transfer mechanism
**Value Creation**: Requires actual business performance improvement

---

## 🛡️ **RISK MANAGEMENT & SETTLEMENT**

### **10. EXCHANGE SAFEGUARDS**

#### **Clearing Corporation Role**
**Guarantee**: Becomes counterparty to every trade
**Novation**: Replaces bilateral agreements
**Risk Management**: Monitors positions and margins
**Settlement**: Ensures money flow integrity

#### **Default Prevention Mechanisms**
**Margin System**: Collateral requirement
**M2M**: Daily risk crystallization
**Position Limits**: Maximum exposure limits
**Surveillance**: Real-time monitoring systems

### **11. SETTLEMENT PROCESS**

#### **Cash Settlement (Equity Futures)**
**No Physical Delivery**: Only cash exchange
**Settlement Price**: Based on spot market closing
**Final Settlement**: On expiry date
**Automatic**: No action required from trader

#### **Settlement Price Calculation**
**Equity Futures**: Average of last 30 minutes spot price
**Index Futures**: Closing value of underlying index
**Cash Flow**: Net difference paid/received

---

## 🎯 **PRACTICAL TRADING CONSIDERATIONS**

### **12. TRADING STRATEGIES**

#### **Directional Trading**
**Long Strategy**: Buy if expecting price rise
**Short Strategy**: Sell if expecting price fall
**Time Horizon**: Can be minutes to months
**Profit Objective**: Benefit from price movements

#### **Hedging Applications**
**Portfolio Hedge**: Protect equity portfolio with index futures
**Single Stock Hedge**: Use stock futures to hedge positions
**Risk Reduction**: Limit downside exposure

#### **Arbitrage Opportunities**
**Spot-Futures Arbitrage**: Exploit price differences
**Calendar Spread**: Trade different expiry months
**Risk-Free Profit**: Theoretical profit with proper execution

### **13. IMPORTANT TRADING RULES**

#### **Position Management**
**Square Off**: Close position before expiry
**Rollover**: Move to next month contract
**Physical Settlement**: Avoid for equity futures
**Timing**: Monitor expiry dates carefully

#### **Risk Control**
**Stop Loss**: Define maximum acceptable loss
**Position Size**: Based on available margin
**Diversification**: Don't put all margin in one contract
**Market Hours**: 9:15 AM to 3:30 PM

---

## ✅ **QUIZ SUCCESS STRATEGIES**

### **14. KEY FORMULAS TO MEMORIZE**

#### **Essential Calculations**
- **Contract Value** = Futures Price × Lot Size
- **P&L (Long)** = (Exit Price - Entry Price) × Lot Size
- **P&L (Short)** = (Entry Price - Exit Price) × Lot Size
- **Leverage** = Contract Value ÷ Margin Required
- **Initial Margin** = SPAN Margin + Exposure Margin

#### **M2M Calculation**
- **Daily M2M** = (Today's Close - Previous Close) × Lot Size × Position
- **Position**: +1 for long, -1 for short

### **15. IMPORTANT CONCEPTS**

#### **Must-Know Features**
**Standardization**: Fixed lot sizes, expiry dates, tick sizes
**Leverage Effect**: Small margin controls large positions
**Linear Payoff**: Proportional profit/loss relationship
**Zero-Sum Game**: Money transfer, not creation
**Daily Settlement**: M2M prevents loss accumulation

#### **Risk Factors**
**Leverage Risk**: Amplified losses possible
**Time Decay**: Approaching expiry affects prices
**Basis Risk**: Futures-spot price differences
**Liquidity Risk**: May be difficult to exit

### **16. COMMON EXAM TOPICS**

**Contract Specifications** (25%):
1. Lot sizes for major contracts
2. Margin calculations and types
3. Settlement mechanisms
4. Contract value computations

**P&L Calculations** (30%):
1. Long and short position outcomes
2. M2M profit/loss scenarios
3. Multi-day trade examples
4. Leverage impact analysis

**Conceptual Understanding** (25%):
1. Forwards vs futures differences
2. Zero-sum game concept
3. Linear payoff structure
4. Exchange guarantee mechanism

**Risk Management** (20%):
1. Margin system purpose
2. M2M risk reduction
3. Default prevention measures
4. Settlement safeguards

### **17. CALCULATION PRACTICE TIPS**

#### **Step-by-Step Approach**
1. **Identify**: Long or short position
2. **Calculate**: Contract value (Price × Lot Size)
3. **Determine**: Entry and exit prices
4. **Apply**: Correct P&L formula
5. **Verify**: Check calculation logic

#### **Common Mistakes to Avoid**
- **Wrong Formula**: Using incorrect P&L formula for position type
- **Lot Size Error**: Forgetting to multiply by lot size
- **Sign Error**: Mixing up profit/loss calculations
- **M2M Confusion**: Wrong reference price for daily settlement

---

## 🏆 **ADVANCED CONCEPTS**

### **18. FUTURES PRICING FACTORS**

#### **Fair Value Calculation**
**Cost of Carry Model**: Theoretical futures price
**Factors**: Interest rates, dividends, storage costs
**Arbitrage**: When actual price deviates from fair value

#### **Basis Behavior**
**Normal Market**: Futures > Spot (contango)
**Inverted Market**: Futures < Spot (backwardation)
**Convergence**: Basis approaches zero at expiry

### **19. MARKET EFFICIENCY**

#### **Price Discovery**
**Information Integration**: Futures reflect all available information
**Lead-Lag Relationship**: Futures often lead spot prices
**Arbitrage**: Keeps prices in line between markets

#### **Liquidity Considerations**
**Volume**: Higher volume = better liquidity
**Open Interest**: Total outstanding contracts
**Bid-Ask Spread**: Liquidity indicator

---

**REMEMBER**: Futures are powerful leverage instruments that amplify both profits and losses. Master the margin system, understand M2M mechanics, and always respect the linear payoff structure. The key to success is proper position sizing, risk management, and clear understanding of the zero-sum nature of futures trading.

**EXAM FOCUS**: Practice P&L calculations extensively, memorize standard lot sizes, understand the difference between forwards and futures, and be clear about how the margin and M2M system protects against default risk.

---
*Leverage • Linear Payoff • Zero-Sum Game • Daily Settlement*
*Master the Math, Manage the Risk, Profit from Price Movements* 