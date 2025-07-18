# QUIZ PREP: Futures Trading & Derivatives
*Based on Module 4: Futures Trading*

## 🎯 **FUTURES FUNDAMENTALS**

### **1. WHAT ARE FUTURES CONTRACTS?**

#### **Definition & Core Concept**
- **Futures**: Standardized contract to buy/sell an asset at predetermined price on future date
- **Standardization**: Exchange-traded, standardized quantity, quality, delivery date
- **Obligation**: Both parties legally bound to fulfill the contract
- **Settlement**: Can be cash-settled or physical delivery

#### **Evolution: Forwards → Futures**
**Forward Contracts (Customized):**
- **Private Agreement**: Between two parties
- **Flexible Terms**: Customizable quantity, date, price
- **Counterparty Risk**: Risk of default by other party
- **No Exchange**: Over-the-counter (OTC) trading

**Futures Contracts (Standardized):**
- **Exchange-Traded**: NSE, BSE for derivatives
- **Standard Terms**: Fixed lot sizes, expiry dates
- **No Counterparty Risk**: Exchange acts as intermediary
- **Daily Settlement**: Mark-to-market (M2M) system

**💡 Quiz Tip**: Futures eliminate counterparty risk through exchange guarantee and daily settlements!

---

### **2. FUTURES TRADING MECHANICS**

#### **Key Components**
- **Underlying Asset**: Stock, index, commodity, currency
- **Lot Size**: Minimum tradeable quantity
- **Expiry Date**: Last Thursday of expiry month (equity)
- **Margin**: Upfront amount required to trade
- **Settlement**: Cash settled for indices, physical for commodities

#### **Contract Specifications (Nifty Futures Example)**
- **Underlying**: Nifty 50 Index
- **Lot Size**: 50 units (Nifty × 50)
- **Tick Size**: 0.05 points
- **Expiry**: Last Thursday of month
- **Settlement**: Cash settled
- **Trading Hours**: 9:15 AM - 3:30 PM

### **3. LEVERAGE & MARGIN SYSTEM**

#### **Leverage Concept**
**Leverage = Contract Value / Margin Required**

**Example:**
- **Nifty Level**: 18,000
- **Contract Value**: 18,000 × 50 = ₹9,00,000
- **Margin Required**: ~₹90,000 (10%)
- **Leverage**: 9,00,000 / 90,000 = 10x

#### **Types of Margins**
**Initial Margin:**
- **SPAN**: Standardized Portfolio Analysis of Risk
- **Exposure Margin**: Additional buffer (usually 3-5%)
- **Total Initial Margin**: SPAN + Exposure margin

**Maintenance Margin:**
- **Minimum Balance**: Required to keep position open
- **Margin Call**: If margin falls below maintenance level

#### **Mark-to-Market (M2M)**
**Daily Settlement Process:**
- **Daily P&L**: Calculated based on closing price
- **Profit**: Added to margin account
- **Loss**: Deducted from margin account
- **Margin Call**: If margin insufficient, add funds or close position

---

### **4. FUTURES PAYOFF PROFILES**

#### **Long Futures Position**
**Profit Formula**: (Sell Price - Buy Price) × Lot Size
- **Unlimited Upside**: Profit increases as price rises
- **Unlimited Downside**: Loss increases as price falls
- **Linear Payoff**: 1:1 relationship with underlying movement

#### **Short Futures Position**
**Profit Formula**: (Sell Price - Buy Price) × Lot Size
- **Limited Upside**: Maximum profit when underlying goes to zero
- **Unlimited Downside**: Loss increases as price rises
- **Linear Payoff**: Inverse relationship with underlying

#### **Practical Example**
**Buy Nifty Futures at 18,000:**
- **If Nifty closes at 18,100**: Profit = (18,100 - 18,000) × 50 = ₹5,000
- **If Nifty closes at 17,900**: Loss = (17,900 - 18,000) × 50 = -₹5,000

---

### **5. FUTURES PRICING & COST OF CARRY**

#### **Theoretical Fair Value**
**Futures Price = Spot Price × e^(r×t)**
Where:
- r = Risk-free interest rate
- t = Time to expiry (in years)

#### **Cost of Carry Model**
**For Dividend-Paying Stocks:**
**Futures Price = (Spot Price - PV of Dividends) × e^(r×t)**

#### **Basis & Convergence**
- **Basis**: Futures Price - Spot Price
- **Contango**: Futures > Spot (normal market)
- **Backwardation**: Futures < Spot (stressed market)
- **Convergence**: Futures and spot prices converge at expiry

---

### **6. PRACTICAL TRADING STRATEGIES**

#### **Hedging Strategies**
**Long Stock + Short Futures:**
- **Purpose**: Protect against price decline
- **Example**: Own 1000 shares, sell 20 futures contracts (if 50 lot size)
- **Result**: Portfolio becomes market-neutral

**Short Stock + Long Futures:**
- **Purpose**: Protect against price rise in short position
- **Risk Management**: Limited upside exposure

#### **Speculation Strategies**
**Directional Trading:**
- **Bullish View**: Buy futures contracts
- **Bearish View**: Sell futures contracts
- **Leverage**: Amplifies both profits and losses

#### **Arbitrage Opportunities**
**Cash-Futures Arbitrage:**
- **When**: Futures significantly overpriced vs fair value
- **Action**: Buy cash, sell futures
- **Profit**: Capture the price differential

---

### **7. RISK MANAGEMENT IN FUTURES**

#### **Position Sizing**
**Risk per Trade**: Never risk more than 2% of capital
**Calculation**: Position size = (Risk amount) / (Stop loss in points)

#### **Stop Loss Strategies**
- **Percentage-based**: 2-3% from entry price
- **Technical Levels**: Support/resistance levels
- **Volatility-based**: Based on Average True Range (ATR)

#### **Common Mistakes**
1. **Over-leveraging**: Using maximum available leverage
2. **Ignoring M2M**: Not maintaining sufficient margin
3. **No Stop Loss**: Unlimited loss potential
4. **Emotional Trading**: Adding to losing positions

---

## 📊 **DERIVATIVES ECOSYSTEM**

### **8. MARKET PARTICIPANTS**

#### **Hedgers**
- **Purpose**: Risk reduction
- **Example**: Exporter hedging currency risk
- **Motivation**: Protect existing positions

#### **Speculators**
- **Purpose**: Profit from price movements
- **Example**: Trader betting on Nifty direction
- **Motivation**: Leverage to amplify returns

#### **Arbitrageurs**
- **Purpose**: Risk-free profits from price differentials
- **Example**: Cash-futures arbitrage
- **Motivation**: Exploit pricing inefficiencies

### **9. EXPIRY DAY DYNAMICS**

#### **Settlement Process**
- **Cash Settlement**: Based on final settlement price
- **Physical Delivery**: Actual asset transfer (commodities)
- **Final Settlement Price**: Average of last 30 minutes trading

#### **Expiry Day Effects**
- **Volatility Increase**: Higher than normal price swings
- **Volume Surge**: Increased trading activity
- **Pin Risk**: Prices tend to gravitate toward strike prices

---

## 💰 **BUSINESS & ENTREPRENEURSHIP APPLICATIONS**

### **10. CORPORATE HEDGING**

#### **Currency Risk Management**
**Export Business:**
- **Risk**: INR strengthening reduces rupee receipts
- **Hedge**: Sell USD futures or buy INR futures
- **Benefit**: Predictable cash flows

**Import Business:**
- **Risk**: INR weakening increases rupee outflow
- **Hedge**: Buy USD futures or sell INR futures
- **Benefit**: Cost certainty

#### **Commodity Price Risk**
**Manufacturing Companies:**
- **Input Cost Hedging**: Lock in raw material prices
- **Output Price Hedging**: Secure selling prices
- **Inventory Management**: Hedge stored commodity values

### **11. FINANCIAL PLANNING**

#### **Portfolio Management**
- **Tactical Asset Allocation**: Use index futures for quick exposure changes
- **Cost Efficiency**: Lower transaction costs vs cash market
- **Liquidity Management**: Maintain cash while having equity exposure

#### **Systematic Investment Plans (SIP)**
- **Rupee Cost Averaging**: Regular investment in index futures
- **Leverage Control**: Systematic approach to leveraged investing
- **Risk Management**: Predetermined exit strategies

---

## 🎯 **QUIZ SUCCESS STRATEGIES**

### **Key Concepts to Master**
1. **Leverage Calculation**: Contract value / Margin required
2. **M2M Process**: Daily profit/loss settlement
3. **Payoff Profiles**: Linear relationship with underlying
4. **Basis Behavior**: Convergence at expiry
5. **Risk Management**: Position sizing and stop losses

### **Important Formulas**
- **Futures Price**: Spot × e^(r×t)
- **Leverage Ratio**: Contract Value / Margin
- **P&L Calculation**: (Exit Price - Entry Price) × Lot Size
- **Basis**: Futures Price - Spot Price

### **Critical Numbers**
- **Nifty Lot Size**: 50 units
- **Bank Nifty Lot Size**: 25 units
- **Typical Margin**: 8-15% of contract value
- **Expiry Day**: Last Thursday of month
- **Trading Hours**: 9:15 AM - 3:30 PM

### **Risk Management Rules**
1. **Maximum Risk**: 2% of capital per trade
2. **Margin Buffer**: Maintain 1.5x required margin
3. **Stop Loss**: Always use protective stops
4. **Position Sizing**: Based on volatility and risk tolerance
5. **Diversification**: Don't put all eggs in one basket

### **Real-World Applications**
- **Business Hedging**: Currency and commodity risk management
- **Portfolio Management**: Tactical allocation and liquidity
- **Speculation**: Leveraged directional bets
- **Arbitrage**: Risk-free profit opportunities

**Remember**: Futures are powerful tools for both risk management and speculation. The key is understanding leverage - it amplifies both profits AND losses. Always trade with proper risk management and never risk more than you can afford to lose! 