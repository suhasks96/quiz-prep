# QUIZ PREP: Financial Markets Fundamentals
*Based on Module 1: Introduction to Stock Markets*

## 🎯 **THE NEED TO INVEST**

### **1. WHY INVEST?**

#### **The Power of Inflation**
- **Definition**: General increase in prices over time
- **Impact**: ₹100 today ≠ ₹100 in future purchasing power
- **Historical Rate**: India averages 6-7% annually
- **Reality Check**: Without investing, money loses value every year

#### **Investment vs Saving**
**Saving:**
- Money kept in banks/fixed deposits
- Safety but low returns (4-6%)
- **Real Return**: Often negative after inflation

**Investing:**
- Money deployed to generate higher returns
- Higher risk but potential for returns above inflation
- **Real Return**: Positive returns after adjusting for inflation

#### **Wealth Creation Example**
**Scenario**: ₹10,000 monthly for 20 years
**Saving Account @ 5%**: ₹39.8 Lakhs (vs ₹24L invested)
**Equity Investment @ 12%**: ₹89.9 Lakhs (vs ₹24L invested)
**Difference**: ₹50.1 Lakhs more through investing!

---

## 📈 **RETURN CALCULATIONS - MATHEMATICAL FORMULAS**

### **3. ABSOLUTE RETURN vs CAGR**

#### **Absolute Return Formula**
**Formula**: [Ending Period Value ÷ Starting Period Value - 1] × 100

**Example Calculation**:
```
Purchase Price: ₹3,030 (Infosys)
Selling Price: ₹3,550
Absolute Return = [3,550 ÷ 3,030 - 1] × 100
                = [1.1716 - 1] × 100
                = 0.1716 × 100 = 17.16%
```

#### **CAGR (Compound Annual Growth Rate) Formula**
**Formula**: {[Ending Value ÷ Starting Value]^(1/number of years) - 1} × 100

**Example Calculation**:
```
Purchase Price: ₹3,030 (Infosys)
Selling Price: ₹3,550 (after 2 years)
CAGR = {[3,550 ÷ 3,030]^(1/2) - 1} × 100
     = {[1.1716]^0.5 - 1} × 100
     = {1.082 - 1} × 100 = 8.2%
```

#### **When to Use Which Formula**
- **Absolute Return**: Use when holding period is 1 year or less
- **CAGR**: Use when holding period is more than 1 year
- **Annualized Return**: For periods less than 1 year, multiply by (12/months) or (365/days)

**Short-term Example**:
```
6-month return of 17.16%
Annualized Return = 17.16% × 2 = 34.32%
```

---

## 🏢 **MARKET INFRASTRUCTURE**

### **2. STOCK EXCHANGES COMPARISON**

#### **NSE vs BSE: Detailed Comparison**

| **Parameter** | **NSE (National Stock Exchange)** | **BSE (Bombay Stock Exchange)** |
|---------------|-----------------------------------|----------------------------------|
| **Established** | 1992 | 1875 (World's oldest in Asia) |
| **Index** | Nifty 50 | Sensex 30 |
| **Trading System** | NEAT (National Exchange for Automated Trading) | BOLT (BSE OnLine Trading) |
| **Listed Companies** | ~1,800 companies | ~4,000+ companies |
| **Market Cap** | Higher | Lower |
| **Trading Volume** | Higher (preferred by traders) | Lower |
| **Derivatives** | More liquid F&O market | Less liquid F&O market |
| **Technology** | Screen-based from inception | Transitioned from floor to screen |

#### **Why NSE is More Popular for Trading**
- **Higher Liquidity**: Better bid-ask spreads
- **Lower Impact Cost**: Easier to execute large orders
- **Technology Leadership**: Superior trading infrastructure
- **Derivatives Market**: More active F&O trading

### **3. MAJOR INDICES COMPARISON**

#### **Nifty 50 vs Sensex 30: Key Differences**

| **Parameter** | **Nifty 50** | **Sensex 30** |
|---------------|--------------|----------------|
| **Full Name** | CNX Nifty (CRISIL-NSE Index) | S&P BSE Sensex |
| **Stocks Included** | 50 largest companies | 30 largest companies |
| **Managed By** | India Index Services & Products Ltd (IISL) | S&P Dow Jones Indices |
| **Base Year** | November 3, 1995 (Base: 1000) | 1978-79 (Base: 100) |
| **Calculation** | Free-float market capitalization | Free-float market capitalization |
| **Rebalancing** | Semi-annual | Periodic (as needed) |
| **Sectoral Coverage** | Better sector representation | Concentrated in few sectors |

#### **Index Construction Methodology**
**Common Method**: Free-float Market Capitalization Weighted
**Formula**: Market Cap = Outstanding Shares × Current Price
**Weight Assignment**: Higher market cap = Higher weight in index
**Example**: If ITC has 7.6% weight in Nifty, then 7.6% of Nifty's movement comes from ITC

#### **Free Float Market Capitalization Formula**
**Formula**: Free Float Market Cap = Total Outstanding Shares × Current Stock Price

**Example Calculation**:
```
Company ABC:
- Total Outstanding Shares = 100 shares
- Current Stock Price = ₹50
- Free Float Market Cap = 100 × 50 = ₹5,000
```

#### **Index Weight Calculation**
**Formula**: Stock Weight = (Stock's Market Cap ÷ Total Index Market Cap) × 100

**Example**:
```
ITC Market Cap = ₹3,00,000 Crores
Total Nifty Market Cap = ₹40,00,000 Crores
ITC Weight = (3,00,000 ÷ 40,00,000) × 100 = 7.5%
```

#### **Index Calculation Process**
1. **Calculate Market Cap**: For each stock (Shares × Price)
2. **Sum Total Market Cap**: Add all constituent stocks
3. **Apply Base Divisor**: Adjust for corporate actions
4. **Index Value**: (Current Market Cap ÷ Base Market Cap) × Base Index Value

#### **Index Movement Impact**
**Formula**: Index Change = Σ(Stock Weight × Stock Price Change %)

**Example**:
```
If ITC (7.6% weight) moves up 2%:
Impact on Nifty = 7.6% × 2% = 0.152% (or ~15 points if Nifty at 10,000)
```

#### **Index Maintenance**
- **Regular Review**: Semi-annual evaluation of constituents
- **Eligibility Criteria**: Market cap, liquidity, listing history
- **Replacement Rules**: Stocks dropping out replaced by eligible ones
- **Corporate Actions**: Adjust for splits, bonuses, mergers

---

## 📊 **TRADING MECHANISMS**

### **4. ORDER TYPES COMPARISON**

#### **Comprehensive Order Types Guide**

| **Order Type** | **Description** | **When to Use** | **Risk Level** |
|----------------|-----------------|-----------------|----------------|
| **Market Order** | Buy/sell at current market price | When quick execution needed | High (price uncertainty) |
| **Limit Order** | Buy/sell at specific price or better | When price control important | Low (may not execute) |
| **Stop Loss (SL)** | Triggered when price hits trigger | Risk management | Medium |
| **Stop Loss Market (SL-M)** | Market order after trigger hit | Quick exit after stop loss | High |

#### **Order Duration Options**
**Day Order**: Valid for current trading session only
**Good Till Cancelled (GTC)**: Valid until manually cancelled (max 365 days)
**Good Till Day (GTD)**: Valid until specified date
**Immediate or Cancel (IOC)**: Execute immediately or cancel
**Fill or Kill (FOK)**: Execute completely or cancel entirely

#### **Order Execution Priority**
1. **Price Priority**: Better price gets preference
2. **Time Priority**: Earlier orders get preference at same price
3. **Market Orders**: Get priority over limit orders
4. **Pro-rata Allocation**: When multiple orders at same price

### **5. SETTLEMENT MECHANISMS**

#### **T+2 Settlement Cycle (Detailed)**

| **Day** | **Activity** | **Details** |
|---------|--------------|-------------|
| **T (Trade Day)** | Order executed | Trade confirmation generated |
| **T+1** | Processing | Money collection, stock blocking |
| **T+2** | Settlement | Shares delivered, funds credited |

#### **Settlement Process Flow**
**For Buyers**:
1. **T Day**: Place buy order, order executed
2. **T+1**: Funds blocked from account
3. **T+2**: Shares credited to Demat account

**For Sellers**:
1. **T Day**: Place sell order, shares blocked
2. **T+1**: Shares debited from Demat
3. **T+2**: Sale proceeds credited to bank account

#### **Different Settlement Types**
**Cash Settlement**: Same day for government securities
**T+1 Settlement**: Commercial papers, certificates of deposit
**T+2 Settlement**: All equity and corporate bond trades
**T+3 Settlement**: Currency and commodity derivatives

---

## 📈 **MARKET PARTICIPANTS COMPARISON**

### **6. INVESTOR vs TRADER vs SPECULATOR**

#### **Detailed Comparison Matrix**

| **Aspect** | **Investor** | **Trader** | **Speculator** |
|------------|--------------|------------|----------------|
| **Time Horizon** | Long-term (years) | Short-term (days/weeks) | Very short (intraday) |
| **Analysis Method** | Fundamental analysis | Technical + some fundamental | Purely technical/momentum |
| **Risk Appetite** | Moderate to low | Moderate | High |
| **Capital Commitment** | High per position | Medium per position | Low per position |
| **Diversification** | Highly diversified | Moderately diversified | Concentrated positions |
| **Income Source** | Dividends + capital gains | Capital gains | Quick profits |
| **Market Dependency** | Partial (long-term view) | High (market timing) | Complete (price movements) |

#### **Investment Styles Comparison**
**Value Investing**:
- Buy undervalued stocks
- Focus on intrinsic value
- Long holding periods
- Lower risk profile

**Growth Investing**:
- Buy high-growth companies
- Focus on earnings growth
- Medium to long holding
- Higher risk for higher returns

**Income Investing**:
- Focu on dividend-paying stocks
- Regular income generation
- Stable, mature companies
- Lower volatility

**Momentum Investing**:
- Buy trending stocks
- Technical analysis driven
- Short to medium term
- High risk, high potential returns

---

## 💹 **MARKET STRUCTURE DETAILS**

### **7. MARKET SEGMENTS COMPARISON**

#### **Cash vs Derivatives Market**

| **Parameter** | **Cash Market** | **Derivatives Market** |
|---------------|-----------------|----------------------|
| **Delivery** | Actual shares exchanged | No physical delivery |
| **Margin** | Full payment required | Only margin required |
| **Leverage** | None (1:1) | High leverage available |
| **Settlement** | T+2 basis | Daily mark-to-market |
| **Risk** | Limited to investment | Unlimited loss possible |
| **Purpose** | Investment/delivery trading | Hedging/speculation |

#### **Primary vs Secondary Market**

| **Feature** | **Primary Market** | **Secondary Market** |
|-------------|-------------------|-------------------|
| **Nature** | New securities issued | Existing securities traded |
| **Participants** | Company and investors | Investors only |
| **Price Discovery** | Fixed by company/book building | Market forces |
| **Examples** | IPO, FPO, Rights Issue | NSE, BSE trading |
| **Purpose** | Capital raising | Liquidity provision |
| **Regulation** | SEBI IPO guidelines | Exchange rules |

---

## 🏦 **MARKET INTERMEDIARIES**

### **8. INTERMEDIARY ROLES COMPARISON**

#### **Financial Intermediaries Matrix**

| **Intermediary** | **Primary Role** | **Regulation** | **Client Interaction** |
|------------------|------------------|----------------|----------------------|
| **Stock Broker** | Trade execution | SEBI registered | Direct (individual investors) |
| **Merchant Banker** | IPO management | SEBI Category I | Indirect (through companies) |
| **Registrar** | Record maintenance | SEBI registered | Minimal (back-office) |
| **Depository** | Securities holding | SEBI Act 1992 | Through DPs only |
| **Custodian** | Institutional custody | SEBI registered | Institutional clients |

#### **Broker Types Comparison**
**Full-Service Brokers**:
- Research reports and advice
- Relationship management
- Higher brokerage charges
- Multiple investment products

**Discount Brokers**:
- Execution-only services
- Lower brokerage charges
- Self-service model
- Technology-focused

**Bank-Based Brokers**:
- Integrated banking services
- Higher charges but convenience
- Traditional client base
- Conservative approach

---

## 📊 **INDICES AND BENCHMARKING**

### **9. SECTORAL INDICES COMPARISON**

#### **Major Sectoral Indices**

| **Index** | **Sector Focus** | **No. of Stocks** | **Key Companies** |
|-----------|------------------|-------------------|-------------------|
| **Bank Nifty** | Banking | 12 | HDFC Bank, ICICI Bank, SBI |
| **Nifty IT** | Information Technology | 10 | TCS, Infosys, HCL Tech |
| **Nifty Auto** | Automobile | 15 | Maruti, Bajaj Auto, M&M |
| **Nifty Pharma** | Pharmaceuticals | 10 | Sun Pharma, Dr. Reddy's |
| **Nifty FMCG** | Consumer Goods | 15 | HUL, ITC, Nestle |

#### **Index Usage Applications**
**Information Purpose**: Market sentiment and economic indicator
**Benchmarking**: Compare portfolio performance vs market
**Trading Purpose**: Take broader market view through derivatives
**Portfolio Hedging**: Protect portfolio during adverse movements

---

## 🔢 **CALCULATIONS AND FORMULAS**

### **10. KEY FINANCIAL CALCULATIONS**

#### **Market Capitalization Calculations**
**Formula**: Market Cap = Outstanding Shares × Current Share Price
**Free-float Market Cap**: Tradeable shares × Current Price
**Example**: 
- Total shares: 100 crores
- Free-float: 40 crores (60% held by promoters)
- Price: ₹500
- Market Cap: 100 × ₹500 = ₹50,000 crores
- Free-float Market Cap: 40 × ₹500 = ₹20,000 crores

#### **Index Weightage Calculation**
**Formula**: Weight = (Stock's Free-float Market Cap ÷ Total Index Market Cap) × 100
**Example**: If Reliance has market cap of ₹10 lakh crores and total Nifty market cap is ₹100 lakh crores:
Weight = (₹10 ÷ ₹100) × 100 = 10%

#### **Brokerage Calculations**
**Equity Delivery**: Usually 0.5% or flat fee
**Equity Intraday**: Usually 0.25% or flat fee
**Example**: Buy ₹1,00,000 worth shares
- Delivery brokerage: ₹1,00,000 × 0.5% = ₹500
- Plus: STT, exchange charges, GST, SEBI charges

#### **Return Calculations**
**Absolute Return**: (Ending Value - Beginning Value) ÷ Beginning Value × 100
**Annualized Return**: ((Ending Value ÷ Beginning Value)^(1/years)) - 1 × 100
**Example**: Bought at ₹100, sold at ₹150 after 2 years
- Absolute: (150-100)/100 = 50%
- Annualized: (150/100)^(1/2) - 1 = 22.47%

---

## ✅ **ENHANCED QUIZ STRATEGIES**

### **11. COMPARISON-BASED EXAM QUESTIONS**

#### **Expected Question Types**
**Index Comparisons** (15%):
1. Nifty 50 vs Sensex 30 differences
2. Index construction methodology
3. Sectoral index compositions
4. Free-float vs full market cap

**Exchange Comparisons** (15%):
1. NSE vs BSE characteristics
2. Trading systems differences
3. Listing requirements comparison
4. Market share and volumes

**Order Types** (20%):
1. Market vs limit order scenarios
2. Stop-loss mechanism understanding
3. Order duration options
4. Execution priority rules

**Settlement Mechanisms** (15%):
1. T+2 settlement process
2. Corporate action impact
3. Dividend ex-date rules
4. Rights issue settlements

#### **Key Numbers for Exams**
- **Nifty Base**: 1000 (Nov 3, 1995)
- **Sensex Base**: 100 (1978-79)
- **Nifty Stocks**: 50 companies
- **Sensex Stocks**: 30 companies
- **NSE Established**: 1992
- **BSE Established**: 1875
- **Settlement Cycle**: T+2 days
- **Order Validity**: 365 days maximum

#### **Critical Concepts to Master**
**Free-float Methodology**: Understand how only tradeable shares count
**Weightage Impact**: Larger companies have more index influence
**Corporate Actions**: How splits, bonuses affect index calculations
**Base Year Adjustments**: Why indices need base year modifications
**Trading Hours**: 9:15 AM to 3:30 PM (with pre-open 9:00-9:15)
**Circuit Breakers**: 10%, 15%, 20% limits on individual stocks

---

**REMEMBER**: Indian stock markets follow free-float market capitalization methodology for index construction. NSE's Nifty 50 and BSE's Sensex 30 are the primary benchmarks. Settlement happens on T+2 basis for equity trades. Order types determine execution priority and price control. Understanding these comparisons is crucial for market operations and professional trading.

**EXAM FOCUS**: Master the differences between Nifty and Sensex, understand order types and their applications, know the T+2 settlement process, and be able to calculate market cap and index weights. Comparison questions are common in certification exams.

---
*Markets • Indices • Trading • Settlement*
*Know the Infrastructure, Master the Mechanisms* 