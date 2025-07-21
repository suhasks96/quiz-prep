# QUIZ PREP: Futures Trading & Derivatives
*Based on Module 4: Futures Trading*

## 🎯 **DERIVATIVES FUNDAMENTALS**

### **1. WHAT ARE DERIVATIVES?**

#### **Core Definition**
**Derivative**: Financial instrument that derives its value from an underlying asset
**Underlying Assets**: Stocks, indices, commodities, currencies, bonds
**Purpose**: Price discovery, risk management, speculation, arbitrage

#### **Derivative Instrument Classification**
**Exchange Traded**: Standardized contracts (Futures, Options)
**OTC (Over-the-Counter)**: Customized contracts (Forwards, Swaps)
**Linear**: Symmetrical P&L (Futures, Forwards)
**Non-Linear**: Asymmetrical P&L (Options)

---

## 🔄 **FUTURES vs FORWARDS: COMPREHENSIVE COMPARISON**

### **2. DETAILED STRUCTURAL COMPARISON**

#### **Fundamental Differences Matrix**

| **Parameter** | **FUTURES** | **FORWARDS** |
|---------------|-------------|--------------|
| **Trading Venue** | Exchange (NSE (National Stock Exchange), BSE (Bombay Stock Exchange)) | Over-the-Counter (OTC) |
| **Standardization** | Fully standardized | Completely customized |
| **Counterparty Risk** | Clearinghouse guarantee | Direct counterparty risk |
| **Margin System** | Daily margin requirements | No margin system |
| **Mark-to-Market** | Daily settlement | Settlement at maturity |
| **Liquidity** | High (secondary market) | Low (hold to maturity) |
| **Regulation** | SEBI regulated | Unregulated private agreement |
| **Contract Size** | Fixed lot sizes | Any size |
| **Delivery Date** | Standardized expiry | Any mutually agreed date |
| **Default Risk** | Minimal (exchange backed) | High (counterparty dependent) |

#### **Practical Example Comparison**
**Futures Contract**: Buy 1 lot Nifty futures (75 shares) expiring last Thursday of month
**Forward Contract**: Private agreement to buy 100 Reliance shares on specific date at agreed price

#### **Why Exchanges Prefer Futures**
**Risk Management**: Clearinghouse eliminates counterparty risk
**Liquidity**: Standardization enables active secondary market
**Price Discovery**: Transparent price formation
**Regulation**: SEBI oversight ensures investor protection
**Efficiency**: Lower transaction costs due to standardization

---

## 📊 **CASH vs DERIVATIVES MARKET COMPARISON**

### **3. MARKET STRUCTURE ANALYSIS**

#### **Complete Market Comparison Matrix**

| **Feature** | **CASH MARKET** | **DERIVATIVES MARKET** |
|-------------|-----------------|----------------------|
| **Settlement** | T+2 delivery | Cash settlement (mostly) |
| **Leverage** | None (100% payment) | High leverage (margin-based) |
| **Position Types** | Only long positions | Long and short positions |
| **Holding Period** | Unlimited | Limited (expiry-based) |
| **Physical Delivery** | Mandatory | Optional (mostly cash settled) |
| **Margin Requirements** | Full payment required | 10-20% margin sufficient |
| **Risk Profile** | Limited to investment | Unlimited loss potential |
| **Market Timing** | Not critical | Critical (time decay) |
| **Regulatory Framework** | SEBI equity regulations | SEBI derivative regulations |

#### **Capital Efficiency Comparison**
**Cash Market Example**: Buy ₹1,00,000 worth shares = ₹1,00,000 required
**Derivatives Example**: Buy ₹1,00,000 exposure = ₹15,000 margin required
**Leverage Ratio**: 6.67:1 in derivatives vs 1:1 in cash

#### **Risk-Return Profile**
**Cash Market**: Limited risk (maximum loss = investment), unlimited upside
**Derivatives**: Unlimited risk and return potential, amplified by leverage

---

## 🎯 **STOCK FUTURES vs INDEX FUTURES COMPARISON**

### **4. INDIVIDUAL vs INDEX FUTURES ANALYSIS**

#### **Comprehensive Feature Comparison**

| **Parameter** | **STOCK FUTURES** | **INDEX FUTURES** |
|---------------|-------------------|-------------------|
| **Underlying** | Individual stocks | Basket of stocks (index) |
| **Diversification** | Company-specific risk | Diversified portfolio risk |
| **Volatility** | Higher (single stock risk) | Lower (portfolio effect) |
| **Margin Requirements** | Higher margins | Lower margins |
| **Liquidity** | Varies by stock | Generally higher |
| **Corporate Actions** | Direct impact | Indirect impact |
| **News Sensitivity** | Company-specific news | Broader market news |
| **Lot Size** | Varies (₹5-15 lakhs) | Fixed (Nifty: 75, Bank Nifty: 25) |
| **Settlement** | Cash settled | Cash settled |

#### **Risk Profile Comparison**
**Stock Futures Risks**:
- Company-specific events (results, management changes)
- Sector-specific risks
- Lower liquidity in smaller stocks
- Higher volatility

**Index Futures Risks**:
- Systematic market risk only
- Economic and policy changes
- Currency fluctuations (for global exposure)
- Interest rate changes

#### **Why Index Futures Are Preferred for Beginners**
**Lower Risk**: Diversification reduces individual stock risk
**Better Liquidity**: Higher trading volumes
**Predictable Behavior**: Less prone to manipulation
**Economic Indicators**: Better reflection of overall economy
**Professional Usage**: Institutional preference makes it more efficient

---

## 💰 **MARGIN SYSTEM COMPARISON**

### **5. SPAN vs EXPOSURE MARGIN ANALYSIS**

#### **Margin Component Breakdown**

| **Margin Type** | **Purpose** | **Calculation** | **Typical Range** |
|-----------------|-------------|-----------------|-------------------|
| **SPAN (Standard Portfolio Analysis of Risk) Margin** | Mark-to-market losses | Risk array-based | 3-6% of contract value |
| **Exposure Margin** | Extreme price movements | Fixed percentage | 3-5% of contract value |
| **Premium Margin** | Option writing | Premium amount | 100% of premium |
| **Assignment Margin** | Option assignment | Based on underlying | Variable |

#### **SPAN (Standard Portfolio Analysis of Risk)**
**Methodology**: Evaluates portfolio risk across different market scenarios
**Scenarios**: 16 different price and volatility combinations
**Calculation**: Worst-case loss among all scenarios
**Benefits**: More accurate risk assessment than fixed percentage

#### **Margin Comparison by Instrument**

| **Instrument** | **SPAN (Standard Portfolio Analysis of Risk) Margin** | **Exposure Margin** | **Total Margin** |
|----------------|-----------------|-------------------|------------------|
| **Nifty Futures** | 3.5% | 3% | 6.5% |
| **Bank Nifty** | 4% | 4% | 8% |
| **Stock Futures** | 5-8% | 4-6% | 9-14% |
| **Currency Futures** | 1-2% | 2-3% | 3-5% |

---

## 📈 **P&L SCENARIOS COMPARISON**

### **6. LONG vs SHORT POSITION ANALYSIS**

#### **Futures Position Payoff Matrix**

| **Market Movement** | **LONG FUTURES** | **SHORT FUTURES** |
|-------------------|------------------|-------------------|
| **Price Increases** | Profit (unlimited) | Loss (unlimited) |
| **Price Decreases** | Loss (unlimited) | Profit (unlimited) |
| **No Change** | Small loss (charges) | Small loss (charges) |
| **Breakeven** | Entry price + costs | Entry price - costs |

#### **Detailed P&L Example**
**Nifty Futures at 18,000 (Lot size: 75)**
**Contract Value**: 18,000 × 75 = ₹13,50,000
**Margin Required**: ₹87,750 (6.5%)

**Long Position Scenarios**:
- Nifty at 18,300: Profit = 300 × 75 = ₹22,500
- Nifty at 17,700: Loss = 300 × 75 = ₹22,500
- Return on Margin = ₹22,500 ÷ ₹87,750 = 25.6%

**Short Position Scenarios** (opposite of long):
- Nifty at 18,300: Loss = ₹22,500
- Nifty at 17,700: Profit = ₹22,500

---

## 🔄 **HEDGING vs SPECULATION COMPARISON**

### **7. FUTURES USAGE STRATEGIES**

#### **Purpose-Based Classification**

| **Strategy** | **HEDGING** | **SPECULATION** |
|--------------|-------------|-----------------|
| **Objective** | Risk reduction | Profit generation |
| **Position** | Opposite to cash position | Directional bet |
| **Risk Tolerance** | Low | High |
| **Time Horizon** | Defensive, longer term | Aggressive, shorter term |
| **Capital Usage** | Portfolio protection | Capital appreciation |
| **Market View** | Risk-averse | Risk-seeking |

#### **Hedging Examples**
**Portfolio Hedge**: Own ₹50 lakh portfolio, sell 4 Nifty futures to hedge market risk
**Individual Stock Hedge**: Own 1000 Reliance shares, sell 1 Reliance futures
**Sector Hedge**: Own banking stocks, sell Bank Nifty futures

#### **Speculation Examples**
**Bullish View**: Buy Nifty futures expecting market rise
**Bearish View**: Sell Nifty futures expecting market fall
**Arbitrage**: Exploit price differences between cash and futures

---

## 💡 **POSITION SIZING IN FUTURES TRADING**

### **8. COMPREHENSIVE POSITION SIZING STRATEGIES**

#### **Position Sizing Methods for Futures**

| **METHOD** | **CALCULATION** | **RISK FOCUS** | **SUITABILITY** |
|------------|-----------------|----------------|-----------------|
| **Fixed Contract** | Same number of contracts | Simple approach | Beginners |
| **Fixed Capital** | Same rupee exposure | Capital consistency | Conservative traders |
| **Risk-Based** | Based on maximum loss tolerance | Risk management | Professional traders |
| **Volatility-Adjusted** | Inverse to volatility | Risk equalization | Advanced traders |

#### **Method 1: Fixed Contract Approach**
**Strategy**: Trade same number of contracts regardless of price
**Example**: Always trade 1 lot of Nifty futures
**Advantage**: Simple execution
**Disadvantage**: Risk varies with price levels

**Practical Example**:
- Nifty at 18,000: Risk = 18,000 × 75 = ₹13,50,000 exposure
- Nifty at 20,000: Risk = 20,000 × 75 = ₹15,00,000 exposure
- Risk Difference = ₹1,50,000 (11% higher risk)

#### **Method 2: Fixed Capital Approach**
**Strategy**: Maintain same rupee exposure across trades
**Calculation**: Number of Lots = Target Exposure ÷ Contract Value

**Detailed Example**:
**Target Exposure**: ₹10,00,000
**Nifty at 18,000**: Contract Value = 18,000 × 75 = ₹13,50,000
**Lots Required**: ₹10,00,000 ÷ ₹13,50,000 = 0.74 lots ≈ 1 lot
**Actual Exposure**: 1 × ₹13,50,000 = ₹13,50,000

**Nifty at 15,000**: Contract Value = 15,000 × 75 = ₹11,25,000
**Lots Required**: ₹10,00,000 ÷ ₹11,25,000 = 0.89 lots ≈ 1 lot
**Actual Exposure**: 1 × ₹11,25,000 = ₹11,25,000

#### **Method 3: Risk-Based Position Sizing**
**Strategy**: Size positions based on maximum acceptable loss
**Formula**: Position Size = Risk Amount ÷ (Stop Loss Distance × Lot Size)

**Comprehensive Example**:
**Trading Capital**: ₹10,00,000
**Risk per Trade**: 2% = ₹20,000
**Nifty Current Price**: 18,000
**Stop Loss Level**: 17,400 (600 points below)
**Lot Size**: 75

**Calculation**:
Position Size = ₹20,000 ÷ (600 × 75) = ₹20,000 ÷ ₹45,000 = 0.44 lots

**Practical Decision**: Trade 0 lots (risk too high) or accept higher risk with 1 lot

**Alternative with Smaller Stop**:
**Stop Loss Level**: 17,800 (200 points below)
Position Size = ₹20,000 ÷ (200 × 75) = ₹20,000 ÷ ₹15,000 = 1.33 lots ≈ 1 lot

#### **Method 4: Volatility-Adjusted Sizing**
**Strategy**: Reduce position size when volatility is high
**Formula**: Base Position Size × (Average Volatility ÷ Current Volatility)

**Practical Example**:
**Base Position**: 2 lots when volatility is normal
**Average VIX**: 20
**Current VIX**: 30 (high volatility)
**Adjusted Position**: 2 × (20 ÷ 30) = 1.33 lots ≈ 1 lot

**When VIX = 15** (low volatility):
**Adjusted Position**: 2 × (20 ÷ 15) = 2.67 lots ≈ 3 lots

---

## 📊 **PRACTICAL POSITION SIZING EXAMPLES**

### **9. REAL-WORLD SCENARIOS**

#### **Scenario 1: Conservative Trader**
**Profile**: ₹5,00,000 capital, 1% risk per trade, long-term view
**Risk per Trade**: ₹5,000
**Target**: Nifty long at 18,000, stop at 17,700

**Calculation**:
- Stop Loss Distance: 300 points
- Loss per Lot: 300 × 75 = ₹22,500
- Position Size: ₹5,000 ÷ ₹22,500 = 0.22 lots
- **Decision**: No trade (position too small) or accept higher risk

**Alternative Approach**: Use Bank Nifty with smaller lot size
**Bank Nifty at 42,000, Stop at 41,500** (500 points)
- Loss per Lot: 500 × 25 = ₹12,500
- Position Size: ₹5,000 ÷ ₹12,500 = 0.4 lots
- **Decision**: Still too small, consider options or cash market

#### **Scenario 2: Aggressive Trader**
**Profile**: ₹20,00,000 capital, 3% risk per trade, active trading
**Risk per Trade**: ₹60,000
**Target**: Nifty short at 19,000, stop at 19,400

**Calculation**:
- Stop Loss Distance: 400 points  
- Loss per Lot: 400 × 75 = ₹30,000
- Position Size: ₹60,000 ÷ ₹30,000 = 2 lots
- **Margin Required**: 2 × ₹1,23,500 = ₹2,47,000
- **Margin Utilization**: ₹2,47,000 ÷ ₹20,00,000 = 12.4%

**Risk Management Check**:
- **Maximum Loss**: ₹60,000 (3% of capital) ✓
- **Margin Comfort**: 12.4% utilization allows for mark-to-market ✓
- **Position Manageable**: 2 lots easy to monitor ✓

#### **Scenario 3: Hedging Example**
**Profile**: Equity portfolio worth ₹1,00,00,000, hedge 50%
**Hedge Value**: ₹50,00,000
**Nifty Level**: 20,000
**Contract Value**: 20,000 × 75 = ₹15,00,000

**Hedge Calculation**:
- Futures Required: ₹50,00,000 ÷ ₹15,00,000 = 3.33 lots
- **Hedge Decision**: Sell 3 lots of Nifty futures
- **Hedge Coverage**: 3 × ₹15,00,000 = ₹45,00,000 (90% hedge)
- **Margin Required**: 3 × ₹97,500 = ₹2,92,500

---

## 📈 **EXPIRY AND SETTLEMENT COMPARISON**

### **10. CONTRACT MONTH ANALYSIS**

#### **Near vs Far Month Contracts**

| **Contract** | **NEAR MONTH** | **MID MONTH** | **FAR MONTH** |
|--------------|----------------|---------------|---------------|
| **Liquidity** | Highest | Medium | Lowest |
| **Volumes** | 70-80% of total | 15-20% | 5-10% |
| **Bid-Ask Spread** | Tightest | Moderate | Widest |
| **Time Decay** | Most sensitive | Moderate | Least sensitive |
| **Preferred By** | Day traders | Position traders | Hedgers |

#### **Rollover Strategy Comparison**
**Automatic Rollover**: System automatically moves to next month
**Manual Rollover**: Trader decides timing and month
**Selective Rollover**: Based on market conditions and strategy

#### **Settlement Methods**
**Cash Settlement**: Most index and stock futures (no physical delivery)
**Physical Settlement**: Some commodity and currency futures
**Mark-to-Market**: Daily adjustment of P&L

---

## 🔢 **FUTURES PRICING COMPARISON**

### **11. FAIR VALUE vs MARKET PRICE**

#### **Theoretical vs Actual Pricing**

| **Component** | **IMPACT ON FUTURES PRICE** | **DIRECTION** |
|---------------|----------------------------|---------------|
| **Spot Price ↑** | Futures price increases | Positive |
| **Interest Rate ↑** | Futures price increases | Positive |
| **Dividend ↑** | Futures price decreases | Negative |
| **Time to Expiry ↑** | Futures price increases | Positive |

#### **Spot-Future Parity Formula**
**Theoretical Futures Price** = Spot Price × e^((r-d) × t)
**Where**:
- r = Risk-free interest rate
- d = Dividend yield
- t = Time to expiry

#### **Basis Analysis**
**Basis** = Futures Price - Spot Price
**Contango**: Futures > Spot (normal market)
**Backwardation**: Futures < Spot (stressed market)

---

**Futures trading provides powerful derivative instruments for hedging, speculation, and arbitrage, utilizing leverage and standardized contracts while requiring sophisticated understanding of margin systems and risk management.**

---

*Leverage • Hedging • Speculation • Settlement*
*Master the Mechanics, Manage the Risk* 

#### **Futures Trading Abbreviations - Comprehensive Definitions**

**F&O (Futures and Options)**: Derivative instruments traded on exchanges that derive their value from underlying assets like stocks, indices, commodities, or currencies.

**M2M (Mark to Market)**: Daily settlement process in futures where profits and losses are calculated based on closing prices and credited/debited to trading accounts.

**SPAN (Standard Portfolio Analysis of Risk)**: A margin calculation system that determines the minimum margin requirement based on portfolio risk across different scenarios.

**OI (Open Interest)**: The total number of outstanding futures contracts that have not been settled, indicating market interest and liquidity in specific contracts.

**COD (Cash on Delivery)**: Settlement method where physical delivery of the underlying commodity occurs against cash payment on the maturity date.

**MTM (Mark to Market)**: The process of valuing positions at current market prices to determine unrealized gains or losses for margin purposes.

**CVaR (Conditional Value at Risk)**: A risk measure that calculates the expected loss beyond the VaR threshold, used for extreme risk scenarios.

**NRML (Normal)**: An order type in futures trading that allows positions to be carried forward to the next trading day with appropriate margins.

**MIS (Margin Intraday Square-off)**: An order type that provides leverage for intraday trading but requires positions to be squared off before market close.

**CNC (Cash and Carry)**: A product type for delivery-based equity trading where investors take actual delivery of shares purchased. 

---

## 📊 **CONSOLIDATED FORMULA TABLE**

### **FUTURES TRADING - ALL FORMULAS REFERENCE**

| **FORMULA NAME** | **MATHEMATICAL EXPRESSION** | **DESCRIPTION** |
|------------------|----------------------------|-----------------|
| **Contract Value** | `Futures Price × Lot Size` | Total value of futures contract |
| **Leverage Ratio** | `Contract Value ÷ Margin Required` | Leverage provided by futures |
| **Margin Requirement** | `Contract Value × Margin %` | Capital needed for futures position |
| **P&L per Point** | `Lot Size × 1 point` | Profit/loss for 1 point movement |
| **Total P&L** | `(Exit Price - Entry Price) × Lot Size` | Total profit/loss on position |
| **Return on Margin** | `P&L ÷ Margin Used × 100` | Return percentage on margin capital |
| **Theoretical Futures Price** | `Spot Price × e^((r-d) × t)` | Fair value based on cost of carry |
| **Simple Futures Price** | `Spot Price × [1 + (r-d) × (t/365)]` | Simplified fair value calculation |
| **Basis** | `Futures Price - Spot Price` | Price difference between futures and spot |
| **Basis Convergence** | `Basis approaches zero as expiry nears` | Basis reduction over time |
| **Position Size (Risk-based)** | `Risk Amount ÷ (Stop Distance × Lot Size)` | Risk-controlled position sizing |
| **Position Size (Fixed Capital)** | `Target Exposure ÷ Contract Value` | Capital-based position sizing |
| **Position Size (Volatility-adjusted)** | `Base Size × (Normal Vol ÷ Current Vol)` | Volatility-based position sizing |
| **Calendar Spread P&L** | `(New Spread - Old Spread) × Lot Size` | Profit/loss on spread trades |
| **Arbitrage Profit** | `(Market Price - Fair Value) × Lot Size` | Risk-free profit opportunity |
| **Hedge Ratio** | `Portfolio Value ÷ Contract Value` | Number of contracts for hedge |
| **Maximum Drawdown** | `(Peak Value - Trough Value) ÷ Peak Value × 100` | Worst-case loss percentage |

#### **Key Variables Reference:**
- **r**: Risk-free interest rate (annual)
- **d**: Dividend yield (annual)
- **t**: Time to expiry (in years)
- **e**: Mathematical constant (≈2.718)
- **Stop Distance**: Difference between entry and stop-loss price
- **Normal Vol**: Historical average volatility
- **Current Vol**: Present volatility level

#### **Important Calculations:**
- **Margin %**: Typically 6-14% for equity futures
- **Lot Size**: Varies by underlying (Nifty: 75, Bank Nifty: 25)
- **Basis Pattern**: Positive (contango) vs Negative (backwardation)
- **Risk per Trade**: Generally 2-5% of total capital

#### **Calendar Spread Example:**
- **Long Calendar**: Buy far month, sell near month
- **Short Calendar**: Sell far month, buy near month
- **Profit Factors**: Time decay and volatility changes

#### **Position Sizing Guidelines:**
- **Conservative**: 1-2% risk per trade
- **Moderate**: 2-3% risk per trade  
- **Aggressive**: 3-5% risk per trade (maximum recommended)

---

*Use this formula table for quick reference during futures trading and risk management* 