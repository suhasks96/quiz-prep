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
| **Trading Venue** | Exchange (NSE, BSE) | Over-the-Counter (OTC) |
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
| **SPAN Margin** | Mark-to-market losses | Risk array-based | 3-6% of contract value |
| **Exposure Margin** | Extreme price movements | Fixed percentage | 3-5% of contract value |
| **Premium Margin** | Option writing | Premium amount | 100% of premium |
| **Assignment Margin** | Option assignment | Based on underlying | Variable |

#### **SPAN (Standard Portfolio Analysis of Risk)**
**Methodology**: Evaluates portfolio risk across different market scenarios
**Scenarios**: 16 different price and volatility combinations
**Calculation**: Worst-case loss among all scenarios
**Benefits**: More accurate risk assessment than fixed percentage

#### **Margin Comparison by Instrument**

| **Instrument** | **SPAN Margin** | **Exposure Margin** | **Total Margin** |
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

## 📊 **EXPIRY AND SETTLEMENT COMPARISON**

### **8. CONTRACT MONTH ANALYSIS**

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

### **9. FAIR VALUE vs MARKET PRICE**

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

## ✅ **ENHANCED QUIZ STRATEGIES**

### **10. COMPARISON-BASED EXAM QUESTIONS**

#### **Expected Question Types**
**Futures vs Forwards** (25%):
1. Structural differences and advantages
2. Risk management features
3. Regulatory framework differences
4. Market accessibility and liquidity

**Cash vs Derivatives** (25%):
1. Leverage and margin comparisons
2. Settlement mechanism differences
3. Risk-return profiles
4. Capital efficiency analysis

**Stock vs Index Futures** (20%):
1. Risk diversification benefits
2. Margin requirement differences
3. Liquidity and volume comparisons
4. Corporate action impacts

**Position Analysis** (20%):
1. Long vs short position payoffs
2. Hedging vs speculation strategies
3. Margin requirement calculations
4. P&L scenario analysis

#### **Critical Numbers for Exams**
- **Nifty Lot Size**: 75 shares
- **Bank Nifty Lot Size**: 25 shares
- **Typical Margin**: 6-14% of contract value
- **Settlement**: T+1 for F&O
- **Expiry**: Last Thursday of month
- **Trading Hours**: 9:15 AM to 3:30 PM
- **Maximum Contracts**: 3 months at any time

#### **Formula Quick Reference**
- **Contract Value** = Price × Lot Size
- **Margin Requirement** = Contract Value × Margin %
- **P&L** = (Exit Price - Entry Price) × Lot Size
- **Return on Margin** = P&L ÷ Margin Used × 100

---

## 🏆 **ADVANCED COMPARISON CONCEPTS**

### **11. INTERNATIONAL vs DOMESTIC MARKETS**

#### **Global Futures Market Comparison**

| **Exchange** | **PRODUCTS** | **CHARACTERISTICS** |
|--------------|--------------|-------------------|
| **CME (US)** | S&P 500, Currency | High liquidity, 24-hour trading |
| **EUREX (Europe)** | DAX, BUND | Electronic trading pioneer |
| **NSE (India)** | Nifty, Bank Nifty | Emerging market leader |
| **SGX (Singapore)** | Nifty (overseas) | Arbitrage opportunities |

#### **Why Futures Markets Exist**
**Price Discovery**: Efficient price formation through continuous trading
**Risk Management**: Transfer risk from hedgers to speculators
**Leverage**: Capital efficiency for market participants
**Arbitrage**: Eliminate price inefficiencies between markets

---

**REMEMBER**: Futures are standardized, exchange-traded contracts with daily mark-to-market settlement. They provide leverage, enable short selling, and facilitate both hedging and speculation. Understanding the differences between futures and forwards, cash and derivatives markets, and various contract types is essential for derivatives trading.

**EXAM FOCUS**: Master the structural differences between futures and forwards, understand margin calculations and P&L scenarios, know the advantages of index over stock futures, and be able to analyze hedging vs speculation strategies. Comparative analysis is fundamental to futures market understanding.

---
*Leverage • Hedging • Speculation • Settlement*
*Master the Mechanics, Manage the Risk* 