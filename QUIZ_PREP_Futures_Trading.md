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

**Example - Simple Forward Contract:**
```
Farmer John & Baker Bob Agreement:
- Asset: 100 kg wheat
- Price: ₹50 per kg (Total: ₹5,000)
- Delivery: 3 months from today
- Obligation: Both parties must honor contract
```

**Characteristics:**
- **Customized**: Terms negotiated between parties
- **OTC Trading**: Over-the-counter, not exchange-traded
- **Counterparty Risk**: Risk of default by either party
- **Settlement**: Physical delivery or cash settlement

#### **Futures Contracts**
**Definition**: Standardized forward contracts traded on exchanges

**Key Improvements Over Forwards:**
- **Standardization**: Fixed contract sizes, expiry dates
- **Exchange Guarantee**: Clearing corporation eliminates counterparty risk
- **Daily Settlement**: Mark-to-market every day
- **Liquidity**: Easy to buy/sell before expiry

**Contract Specifications:**
- **Lot Size**: Fixed quantity (e.g., Nifty = 75 units)
- **Tick Size**: Minimum price movement (e.g., ₹0.05)
- **Expiry**: Last Thursday of every month
- **Settlement**: Cash settlement (no physical delivery)

---

## 📊 **FUTURES CONTRACT MECHANICS**

### **3. UNDERSTANDING FUTURES AGREEMENT**

#### **Standard Futures Contract Elements**
**Underlying Asset**: What you're trading (Nifty, stocks, commodities)
**Contract Size**: Quantity per contract (Nifty = 75 units)
**Expiry Date**: When contract expires (monthly cycle)
**Settlement**: How contract is settled at expiry

#### **Futures Price Discovery**
**Spot Price**: Current market price of underlying asset
**Futures Price**: Price for delivery at future date
**Basis**: Difference between futures and spot price
**Formula**: Basis = Futures Price - Spot Price

**Convergence**: At expiry, futures price = spot price

#### **Market Participants**
**Hedgers**: Use futures to reduce risk exposure
**Speculators**: Seek profits from price movements  
**Arbitrageurs**: Exploit price differences between markets

### **4. LONG vs SHORT POSITIONS**

#### **Long Position (Buy Futures)**
**Expectation**: Underlying asset price will rise
**Profit**: When futures price increases
**Loss**: When futures price decreases
**Settlement**: Receive money if price rises

**Example:**
- Buy Nifty futures at 18,000
- If Nifty expires at 18,200: Profit = (18,200 - 18,000) × 75 = ₹15,000
- If Nifty expires at 17,800: Loss = (17,800 - 18,000) × 75 = ₹15,000

#### **Short Position (Sell Futures)**
**Expectation**: Underlying asset price will fall
**Profit**: When futures price decreases
**Loss**: When futures price increases
**Settlement**: Receive money if price falls

**Example:**
- Sell Nifty futures at 18,000
- If Nifty expires at 17,800: Profit = (18,000 - 17,800) × 75 = ₹15,000
- If Nifty expires at 18,200: Loss = (18,000 - 18,200) × 75 = ₹15,000

### **5. THREE POSSIBLE SCENARIOS**

#### **Scenario Analysis Framework**
For any futures position, there are always three possibilities:
1. **Favorable Movement**: Profit realization
2. **Adverse Movement**: Loss realization  
3. **No Movement**: Minimal profit/loss

#### **Long Position Outcomes**
**Bullish Scenario (Price Rises):**
- Futures price > Entry price
- Positive P&L
- Settlement credit

**Bearish Scenario (Price Falls):**
- Futures price < Entry price
- Negative P&L
- Settlement debit

**Neutral Scenario (Price Unchanged):**
- Futures price ≈ Entry price
- Minimal P&L
- Transaction costs impact

#### **Short Position Outcomes**
**Bearish Scenario (Price Falls):**
- Futures price < Entry price
- Positive P&L
- Settlement credit

**Bullish Scenario (Price Rises):**
- Futures price > Entry price
- Negative P&L
- Settlement debit

**Neutral Scenario (Price Unchanged):**
- Futures price ≈ Entry price
- Minimal P&L
- Transaction costs impact

---

## ⚡ **LEVERAGE & MARGIN SYSTEM**

### **6. UNDERSTANDING LEVERAGE**

#### **Leverage Concept**
**Definition**: Ability to control large position with small capital outlay
**Mechanism**: Pay only margin (typically 10-20% of contract value)
**Amplification**: Both profits and losses are magnified

#### **Leverage Calculation**
**Formula**: Leverage = Contract Value ÷ Margin Required

**Example:**
```
Nifty Futures Contract:
- Spot Price: 18,000
- Lot Size: 75 units
- Contract Value: 18,000 × 75 = ₹13,50,000
- Margin Required: ₹1,35,000 (10%)
- Leverage: 13,50,000 ÷ 1,35,000 = 10x
```

**Implications:**
- **1% move in Nifty** = **10% move in your capital**
- **Profit Amplification**: Small favorable moves = large gains
- **Loss Amplification**: Small adverse moves = large losses

#### **Leverage Benefits & Risks**
**Benefits:**
- **Capital Efficiency**: Control large positions with small capital
- **Higher Returns**: Amplified profits on favorable moves
- **Hedging**: Protect portfolio with smaller outlay

**Risks:**
- **Magnified Losses**: Small adverse moves cause large losses
- **Margin Calls**: Additional margin required if position moves against you
- **Forced Liquidation**: Positions closed if margin inadequate

### **7. MARGIN SYSTEM**

#### **Types of Margins**

**SPAN Margin (Initial Margin):**
- **Purpose**: Cover potential overnight loss
- **Calculation**: Based on worst-case scenario analysis
- **Typical Range**: 10-20% of contract value

**Exposure Margin:**
- **Purpose**: Additional buffer beyond SPAN
- **Calculation**: Fixed percentage of contract value
- **Typical Range**: 3-5% of contract value

**Total Margin Required:**
- **Formula**: SPAN Margin + Exposure Margin
- **Example**: ₹1,20,000 (SPAN) + ₹15,000 (Exposure) = ₹1,35,000

#### **Why Margins Are Charged**
**Risk Management**: Protect exchange from default risk
**Daily Settlement**: Ensure sufficient funds for M2M
**Leverage Control**: Limit excessive speculation
**Market Stability**: Prevent systemic risk

#### **Margin Calculation Factors**
**Volatility**: Higher volatility = higher margins
**Liquidity**: Less liquid stocks = higher margins
**Time to Expiry**: Longer expiry = higher margins
**Market Conditions**: Stressed markets = higher margins

### **8. MARK-TO-MARKET (M2M)**

#### **Daily Settlement Process**
**Concept**: All positions are marked to market daily
**Timing**: After market close each day
**Price Reference**: Settlement price determined by exchange

#### **M2M Calculation**
**For Long Position:**
- **Profit**: Settlement Price > Previous Settlement Price
- **Loss**: Settlement Price < Previous Settlement Price

**For Short Position:**
- **Profit**: Settlement Price < Previous Settlement Price
- **Loss**: Settlement Price > Previous Settlement Price

**Formula**: P&L = (Settlement Price - Previous Settlement Price) × Lot Size

#### **Cash Flow Impact**
**Daily Credit/Debit:**
- **Profits**: Credited to trading account
- **Losses**: Debited from trading account
- **Margin Impact**: Available margin adjusted daily

**Example:**
```
Day 1: Buy Nifty futures at 18,000
Day 2: Settlement at 18,100
- M2M Profit: (18,100 - 18,000) × 75 = ₹7,500 (credited)

Day 3: Settlement at 17,950
- M2M Loss: (17,950 - 18,100) × 75 = ₹11,250 (debited)
```

#### **Margin Call Scenario**
**Trigger**: When available margin falls below maintenance margin
**Action Required**: Add funds or reduce positions
**Timeline**: Usually same day or next trading day
**Consequences**: Forced liquidation if margin not added

---

## 📈 **NIFTY FUTURES TRADING**

### **9. INDEX FUTURES ADVANTAGES**

#### **Why Trade Nifty Futures?**
**Diversification**: Single contract represents 50 large-cap stocks
**Liquidity**: High trading volume, tight bid-ask spreads
**Lower Impact Cost**: Cheaper than buying all 50 stocks individually
**Market View**: Easy way to take overall market view

#### **Nifty Futures Specifications**
**Underlying**: Nifty 50 Index
**Lot Size**: 75 units
**Contract Months**: 3 monthly contracts available
**Expiry**: Last Thursday of every month
**Settlement**: Cash settlement based on closing index value

#### **Impact Cost Comparison**
**Buying Nifty Stocks Individually:**
- **50 different transactions**: Higher brokerage costs
- **Market Impact**: Large orders may move individual stock prices
- **Liquidity Issues**: Some stocks may have wider spreads

**Buying Nifty Futures:**
- **Single transaction**: Lower brokerage costs
- **Minimal Impact**: Deep liquidity in futures market
- **Efficiency**: Instant exposure to entire portfolio

### **10. FUTURES PRICING THEORY**

#### **Cost of Carry Model**
**Theoretical Fair Price**: Spot Price + Cost of Carry - Dividend Yield

**Cost of Carry Components:**
- **Interest Cost**: Risk-free rate × Time to expiry
- **Storage Costs**: Usually nil for financial assets
- **Convenience Yield**: Usually nil for financial assets

**Simplified Formula**: F = S × e^(r-d)×t
- **F**: Futures Price
- **S**: Spot Price  
- **r**: Risk-free rate
- **d**: Dividend yield
- **t**: Time to expiry

#### **Practical Pricing Factors**
**Interest Rates**: Higher rates = higher futures premium
**Dividends**: Expected dividends reduce futures premium
**Time to Expiry**: Longer expiry = higher cost of carry
**Market Sentiment**: Demand/supply can cause deviations

#### **Arbitrage Opportunities**
**Cash & Carry Arbitrage**: When futures overpriced
- Buy underlying, sell futures
- Borrow money for spot purchase
- Lock in risk-free profit

**Reverse Cash & Carry**: When futures underpriced
- Sell underlying, buy futures
- Invest proceeds at risk-free rate
- Lock in risk-free profit

---

## 🛡️ **RISK MANAGEMENT & SHORTING**

### **11. SHORT SELLING IN FUTURES**

#### **Shorting Concept**
**Definition**: Selling asset you don't own, expecting price to fall
**Futures Advantage**: Can short easily without borrowing constraints
**Profit Mechanism**: Buy back at lower price, pocket the difference

#### **Spot Market Shorting vs Futures Shorting**
**Spot Market Limitations:**
- **Borrowing Required**: Must borrow shares from others
- **Limited Availability**: Not all stocks available for shorting
- **Higher Costs**: Stock borrowing fees
- **Regulatory Restrictions**: Various compliance requirements

**Futures Market Advantages:**
- **No Borrowing**: Direct short position creation
- **Easy Execution**: Same as buying, but sell first
- **Lower Costs**: Only margin and transaction costs
- **Regulatory Friendly**: Designed for both long and short

#### **Short Selling Risk Management**
**Unlimited Loss Potential**: Prices can rise indefinitely
**Margin Calls**: Adverse moves require additional margin
**Time Decay**: Costs accumulate over time
**Forced Covering**: Margin inadequacy leads to forced buying

### **12. POSITION MANAGEMENT**

#### **Entry Strategies**
**Trend Following**: Enter in direction of established trend
**Mean Reversion**: Enter expecting price to return to average
**Breakout Trading**: Enter when price breaks key levels
**Calendar Spreads**: Simultaneously trade different expiry contracts

#### **Exit Strategies**
**Profit Targets**: Predetermined profit levels
**Stop Losses**: Predetermined loss limits
**Time-based**: Exit before expiry
**Technical Levels**: Exit at support/resistance

#### **Position Sizing**
**Risk-based Sizing**: Determine position size based on risk tolerance
**Volatility Adjustment**: Larger positions in less volatile assets
**Correlation Management**: Avoid highly correlated positions
**Portfolio Impact**: Consider overall portfolio effect

---

## 🔧 **MARGIN CALCULATOR & PRACTICAL TOOLS**

### **13. USING MARGIN CALCULATORS**

#### **Key Inputs Required**
**Script**: Choose underlying asset (Nifty, Bank Nifty, stocks)
**Action**: Buy or Sell
**Product Type**: MIS (intraday) or NRML (overnight)
**Quantity**: Number of lots
**Price**: Entry price for calculation

#### **Output Information**
**SPAN Margin**: Risk-based margin requirement
**Exposure Margin**: Additional buffer margin
**Total Margin**: SPAN + Exposure
**Available Leverage**: Based on total margin

#### **Product Types Impact**
**MIS (Margin Intraday Square-off):**
- **Lower Margin**: Reduced requirement for intraday
- **Mandatory Square-off**: Must close before market close
- **Higher Leverage**: Can take larger positions

**NRML (Normal):**
- **Higher Margin**: Full overnight margin requirement
- **Carry Forward**: Can hold positions overnight
- **Standard Leverage**: Based on exchange margins

### **14. ADVANCED ORDER TYPES**

#### **Bracket Orders (BO)**
**Components**: Entry + Target + Stop Loss (all in one order)
**Automatic Execution**: Target and stop loss placed automatically
**Risk Management**: Predefined risk-reward ratio
**Margin Benefit**: Lower margin due to built-in risk management

#### **Cover Orders (CO)**
**Components**: Entry + Compulsory Stop Loss
**Immediate Stop Loss**: Stop loss placed as soon as entry fills
**Margin Benefit**: Lower margin requirement
**Risk Control**: Limited loss potential

#### **Trailing Stop Loss**
**Concept**: Stop loss that moves with favorable price movement
**Mechanism**: Trails by fixed points or percentage
**Benefit**: Locks in profits while allowing for further gains
**Risk**: May get triggered by temporary price movements

---

## 🎯 **TRADING STRATEGIES & APPLICATIONS**

### **15. HEDGING STRATEGIES**

#### **Portfolio Hedging**
**Long Portfolio + Short Index Futures:**
- **Protection**: Against market decline
- **Cost**: Margin requirement and opportunity cost
- **Effectiveness**: Beta-weighted hedge ratio

**Example:**
```
Portfolio Value: ₹50,00,000 (Beta = 1.2)
Hedge Ratio: 1.2 × 50,00,000 ÷ 13,50,000 = 4.4 contracts
Action: Sell 4 Nifty futures contracts
```

#### **Selective Hedging**
**Individual Stock Futures**: Hedge specific stock positions
**Sector ETF Futures**: Hedge sector-specific exposure
**Currency Futures**: Hedge foreign exchange risk

### **16. SPECULATIVE STRATEGIES**

#### **Directional Trading**
**Long Futures**: Bullish view on underlying
**Short Futures**: Bearish view on underlying
**Risk Management**: Stop losses and position sizing

#### **Spread Trading**
**Calendar Spreads**: Different expiry, same underlying
**Inter-commodity Spreads**: Related commodities
**Index Spreads**: Different indices correlation

#### **Arbitrage Trading**
**Cash-Futures Arbitrage**: Exploit pricing inefficiencies
**Inter-exchange Arbitrage**: Price differences across exchanges
**Statistical Arbitrage**: Mean reversion strategies

---

## 🎯 **QUIZ SUCCESS STRATEGIES**

### **Key Futures Concepts to Master**
1. **Derivative Definition**: Financial instruments derived from underlying assets
2. **Forwards vs Futures**: Customized vs standardized contracts
3. **Long vs Short**: Direction-based position analysis
4. **Leverage Calculation**: Contract value divided by margin
5. **Margin System**: SPAN, Exposure, and total requirements
6. **Mark-to-Market**: Daily settlement process
7. **Futures Pricing**: Cost of carry model
8. **Risk Management**: Position sizing and stop losses

### **Important Formulas**
- **Leverage**: Contract Value ÷ Margin Required
- **M2M P&L**: (Settlement Price - Previous Price) × Lot Size
- **Futures Fair Value**: Spot × e^(r-d)×t
- **Hedge Ratio**: (Portfolio Value × Beta) ÷ Index Futures Value

### **Key Numbers to Remember**
- **Nifty Lot Size**: 75 units
- **Typical Margin**: 10-20% of contract value
- **Expiry**: Last Thursday of every month
- **Settlement**: T+1 for futures
- **Maximum Leverage**: Usually 5-10x

### **Common Quiz Topics**
**Contract Specifications:**
- Understanding lot sizes and tick values
- Expiry and settlement mechanisms
- Margin calculations and requirements

**Position Analysis:**
- Long vs short position outcomes
- Profit/loss calculations
- Scenario-based analysis

**Risk Management:**
- Margin call situations
- Stop loss placement
- Position sizing principles

**Practical Applications:**
- Hedging portfolio with index futures
- Arbitrage opportunities
- Speculation vs hedging distinctions

### **Quiz Tips**
- **Master Basic Calculations**: Focus on P&L and margin calculations
- **Understand Leverage Impact**: Know how small moves affect positions
- **Scenario Analysis**: Practice different market outcomes
- **Risk Management**: Always consider downside protection
- **Real-world Applications**: Understand practical use cases

**Remember**: Futures are powerful tools that can provide both leverage and risk management. The key to success is understanding how leverage amplifies both gains and losses, proper position sizing, and disciplined risk management. Always remember that while futures can enhance returns, they can also lead to significant losses if not used carefully! 