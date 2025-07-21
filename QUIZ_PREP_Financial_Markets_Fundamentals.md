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
- **CAGR (Compound Annual Growth Rate)**: Use when holding period is more than 1 year
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

#### **Why NSE (National Stock Exchange) is More Popular for Trading**
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
| **Examples** | IPO (Initial Public Offering), FPO (Follow-on Public Offering), Rights Issue | NSE (National Stock Exchange), BSE (Bombay Stock Exchange) trading |
| **Purpose** | Capital raising | Liquidity provision |
| **Regulation** | SEBI (Securities and Exchange Board of India) IPO (Initial Public Offering) guidelines | Exchange rules |

---

## 🏦 **MARKET INTERMEDIARIES**

### **8. INTERMEDIARY ROLES COMPARISON**

#### **Financial Intermediaries Matrix**

| **Intermediary** | **Primary Role** | **Regulation** | **Client Interaction** |
|------------------|------------------|----------------|----------------------|
| **Stock Broker** | Trade execution | SEBI (Securities and Exchange Board of India) registered | Direct (individual investors) |
| **Merchant Banker** | IPO (Initial Public Offering) management | SEBI (Securities and Exchange Board of India) Category I | Indirect (through companies) |
| **Registrar** | Record maintenance | SEBI (Securities and Exchange Board of India) registered | Minimal (back-office) |
| **Depository** | Securities holding | SEBI (Securities and Exchange Board of India) Act 1992 | Through DPs (Depository Participants) only |
| **Custodian** | Institutional custody | SEBI (Securities and Exchange Board of India) registered | Institutional clients |

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
- Plus: STT (Securities Transaction Tax), exchange charges, GST (Goods and Services Tax), SEBI (Securities and Exchange Board of India) charges

#### **Return Calculations**
**Absolute Return**: (Ending Value - Beginning Value) ÷ Beginning Value × 100
**Annualized Return**: ((Ending Value ÷ Beginning Value)^(1/years)) - 1 × 100
**Example**: Bought at ₹100, sold at ₹150 after 2 years
- Absolute: (150-100)/100 = 50%
- Annualized: (150/100)^(1/2) - 1 = 22.47%

---

**Financial markets fundamentals provide the essential foundation for understanding capital markets structure, return calculations, index construction, and trading mechanisms - core knowledge that underpins all advanced financial concepts.**

---

## 🔧 **MARKET MICROSTRUCTURE & MECHANICS**

### **12. ORDER BOOK DYNAMICS & MARKET DEPTH**

#### **Understanding the Order Book**
**Order Book**: Real-time display of buy and sell orders at different price levels
**Market Depth**: Shows liquidity available at each price level
**Bid-Ask Spread**: Difference between highest bid and lowest ask price
**Price Priority**: Orders executed based on price-time priority

#### **Order Book Structure Analysis**

| **PARAMETER** | **BID SIDE (BUYERS)** | **ASK SIDE (SELLERS)** |
|---------------|----------------------|----------------------|
| **Price Movement** | Decreasing as you go down | Increasing as you go down |
| **Quantity Display** | Total quantity at each level | Total quantity at each level |
| **Color Coding** | Usually blue/green | Usually red/orange |
| **Market Impact** | Shows buying interest | Shows selling pressure |

#### **Market Depth Example**
```
ASK (SELLERS)               BID (BUYERS)
Price    Qty                Price    Qty
₹102.75  500   ←           ₹102.50  1000
₹102.50  800                ₹102.25  1500
₹102.25  1200              ₹102.00  2000
₹102.00  1500              ₹101.75  800

Bid-Ask Spread = ₹102.75 - ₹102.50 = ₹0.25
```

#### **Liquidity Assessment**
**Tight Spread**: High liquidity, easy to trade
**Wide Spread**: Low liquidity, higher impact cost
**Deep Book**: Large quantities at each level
**Thin Book**: Small quantities, price sensitive

### **13. COMPREHENSIVE ORDER TYPES GUIDE**

#### **Basic Order Types (Every Trader Must Know)**

| **ORDER TYPE** | **EXECUTION** | **BEST USE CASE** | **RISK LEVEL** |
|----------------|---------------|-------------------|----------------|
| **Market Order** | Immediate at best available price | Quick execution needed | High (price risk) |
| **Limit Order** | At specified price or better | Price control important | Low (execution risk) |
| **Stop Loss (SL)** | Becomes market order when triggered | Risk management | Medium |
| **Stop Loss Limit (SL-L)** | Becomes limit order when triggered | Controlled exit | Medium |

#### **Advanced Order Types (Professional Trading)**

| **ORDER TYPE** | **MECHANISM** | **PROFESSIONAL USE** |
|----------------|---------------|---------------------|
| **Immediate or Cancel (IOC)** | Execute immediately, cancel rest | Large order management |
| **Fill or Kill (FOK)** | Execute completely or cancel | All-or-nothing trades |
| **Iceberg Orders** | Show only small portion | Hide large positions |
| **Bracket Orders** | Auto target + stop loss | Complete trade management |
| **Cover Orders** | Mandatory stop loss with market order | Intraday risk control |

#### **Order Duration Options**
**Day Orders**: Valid only for current session
**Good Till Cancelled (GTC)**: Valid until manually cancelled (max 365 days)
**Good Till Date (GTD)**: Valid until specified date
**After Market Orders (AMO)**: Placed after market hours for next session

#### **Order Execution Priority Rules**
1. **Price Priority**: Better price gets executed first
2. **Time Priority**: Earlier timestamp at same price
3. **Size Priority**: Larger orders may get preference (varies by exchange)
4. **Order Type Priority**: Market orders before limit orders

### **14. CIRCUIT BREAKERS & MARKET HALTS**

#### **Individual Stock Circuit Breakers**

| **PRICE BAND** | **MOST STOCKS** | **SPECIAL CASES** | **DAILY LIMIT** |
|----------------|-----------------|-------------------|-----------------|
| **Upper Circuit** | +20% from previous close | +5% for volatile stocks | Trading halted |
| **Lower Circuit** | -20% from previous close | -5% for volatile stocks | Trading halted |
| **No Limit** | Index stocks in derivatives | F&O stocks | No daily limit |

#### **Market-Wide Circuit Breakers**

| **INDEX FALL** | **TIME OF TRIGGER** | **MARKET HALT DURATION** |
|----------------|---------------------|-------------------------|
| **10%** | Before 1:00 PM | 1 hour |
| **10%** | Between 1:00-2:30 PM | 30 minutes |
| **10%** | After 2:30 PM | No halt |
| **15%** | Before 1:00 PM | 2 hours |
| **15%** | After 1:00 PM | Remainder of day |
| **20%** | Any time | Remainder of day |

#### **Purpose of Circuit Breakers**
**Risk Management**: Prevent panic selling/buying
**Price Discovery**: Allow time for information absorption
**System Protection**: Prevent technical glitches impact
**Investor Protection**: Cool-off period for decisions

### **15. MARKET SESSIONS & TIMING STRUCTURE**

#### **Complete Market Schedule**

| **SESSION** | **TIMING** | **ACTIVITY** | **ORDER TYPES ALLOWED** |
|-------------|------------|--------------|------------------------|
| **Pre-Open** | 9:00-9:15 AM | Order collection, no trades | Limit orders only |
| **Normal Trading** | 9:15 AM-3:30 PM | Regular trading | All order types |
| **Closing Session** | 3:30-4:00 PM | Closing price determination | Limited participation |
| **After Market** | 4:00-9:00 AM (next day) | AMO (After Market Orders) placement | AMO only |

#### **Pre-Open Session Breakdown**
**9:00-9:08 AM**: Order entry, modification, cancellation allowed
**9:08-9:12 AM**: Order entry allowed, no modification/cancellation
**9:12-9:15 AM**: Buffer period, random closure for opening price

#### **Market Holidays & Impact**
**National Holidays**: Market closed, no trading
**Special Sessions**: Settlement activities continue
**Trading Calendar**: Published annually by exchanges
**Global Impact**: International market movements during closure

### **16. ROLE OF MARKET MAKERS & LIQUIDITY**

#### **Market Maker Functions**
**Liquidity Provision**: Continuous buy/sell quotes
**Spread Management**: Maintain tight bid-ask spreads
**Price Stability**: Absorb temporary imbalances
**Market Efficiency**: Reduce impact costs for traders

#### **Liquidity Metrics**
**Bid-Ask Spread**: Tighter spread = better liquidity
**Market Depth**: Volume available at each price level
**Turnover Ratio**: Trading volume / market cap
**Impact Cost**: Price movement for standard trade size

#### **High Frequency Trading (HFT - High Frequency Trading) Impact**
**Advantages**: Improved liquidity, tighter spreads
**Concerns**: Market volatility, unfair advantages
**Regulation**: SEBI guidelines for algo trading
**Technology**: Co-location services, ultra-low latency

---

## 📊 **MARKET STRUCTURE COMPARISON**

### **17. SPOT vs DERIVATIVES MARKET INTERACTION**

#### **Market Integration Analysis**

| **ASPECT** | **SPOT MARKET** | **DERIVATIVES MARKET** | **INTERACTION** |
|------------|-----------------|----------------------|-----------------|
| **Price Discovery** | Current fair value | Future expectations | Arbitrage opportunities |
| **Volume Impact** | Direct price movement | Leveraged impact | Cross-market effects |
| **Volatility** | Natural volatility | Amplified volatility | Spillover effects |
| **Liquidity** | Fundamental liquidity | Derived liquidity | Mutual dependence |

#### **Arbitrage Mechanisms**
**Cash-Futures Arbitrage**: Price differences between spot and futures
**Calendar Arbitrage**: Different expiry month price differences
**Strike Arbitrage**: Options pricing inconsistencies
**Index Arbitrage**: Index vs constituent stocks pricing 

#### **Additional Financial Market Abbreviations**
**DPs (Depository Participants)**: Entities facilitating demat services
**DP (Depository Participant)**: Individual demat account service provider
**KYC (Know Your Customer)**: Identity verification requirement
**PAN (Permanent Account Number)**: Tax identification number
**UCC (Unique Client Code)**: Client identification in trading system
**MTF (Margin Trading Facility)**: Leveraged equity trading
**SLB (Securities Lending and Borrowing)**: Stock lending mechanism 

#### **Financial Markets Abbreviations - Comprehensive Definitions**

**ETF (Exchange Traded Fund)**: A marketable security that tracks an index, commodity, bonds, or basket of assets. Trades like individual stocks on exchanges while providing diversification of an index fund.

**IPO (Initial Public Offering)**: The process by which a private company first offers shares to the public, transforming from private to public company status and raising capital from public investors.

**FPO (Follow-on Public Offering)**: Additional share issuance by an already public company to raise more capital, diluting existing shareholding but providing growth funds.

**NSE (National Stock Exchange)**: India's leading stock exchange established in 1992, known for electronic trading, higher liquidity, and the benchmark Nifty 50 index.

**BSE (Bombay Stock Exchange)**: Asia's oldest stock exchange (1875), home to the Sensex index and over 4,000 listed companies, though with lower trading volumes than NSE.

**SEBI (Securities and Exchange Board of India)**: The securities market regulator that protects investor interests, develops the securities market, and regulates market intermediaries.

**AMO (After Market Orders)**: Orders placed outside regular trading hours (typically 4:00 PM to 9:00 AM) that are queued for execution when the market opens.

**IOC (Immediate or Cancel)**: An order type that executes immediately for whatever quantity is available and cancels the remaining unfilled portion.

**FOK (Fill or Kill)**: An order that must be executed completely and immediately, or it gets cancelled entirely - no partial fills allowed.

**DPs (Depository Participants)**: SEBI-registered intermediaries that provide demat account services, acting as agents of depositories (NSDL/CDSL) for investors.

**KYC (Know Your Customer)**: Mandatory identity verification process required by SEBI for all financial transactions, involving document submission and verification.

**PAN (Permanent Account Number)**: A 10-digit unique alphanumeric identity issued by Income Tax Department, mandatory for financial transactions above specified limits.

**UCC (Unique Client Code)**: A unique identifier assigned to each client by brokers for tracking and managing their trading activities across all segments.

**MTF (Margin Trading Facility)**: A facility that allows investors to buy shares by paying only a portion of the trade value, with the broker funding the balance against collateral.

**SLB (Securities Lending and Borrowing)**: A mechanism where investors can lend their shares to earn additional income or borrow shares for short selling. 

---

## 📊 **CONSOLIDATED FORMULA TABLE**

### **FINANCIAL MARKETS FUNDAMENTALS - ALL FORMULAS REFERENCE**

| **FORMULA NAME** | **MATHEMATICAL EXPRESSION** | **DESCRIPTION** |
|------------------|----------------------------|-----------------|
| **Absolute Return** | `[(Ending Value ÷ Starting Value) - 1] × 100` | Total percentage return over investment period |
| **CAGR (Compound Annual Growth Rate)** | `{[Ending Value ÷ Starting Value]^(1/years) - 1} × 100` | Annualized return for periods > 1 year |
| **Annualized Return (Short-term)** | `Return × (365/days)` or `Return × (12/months)` | Annualizing returns for periods < 1 year |
| **Market Capitalization** | `Outstanding Shares × Current Share Price` | Total company value in market |
| **Free-float Market Cap** | `Free-float Shares × Current Price` | Market cap of tradeable shares only |
| **Index Weight** | `(Stock's Market Cap ÷ Total Index Market Cap) × 100` | Stock's contribution to index movement |
| **Index Movement Impact** | `Stock Weight × Stock Price Change %` | How individual stock affects index |
| **Index Value Calculation** | `(Current Market Cap ÷ Base Market Cap) × Base Index Value` | Current index level calculation |
| **Contract Value (Futures)** | `Price × Lot Size` | Total value of futures contract |
| **Margin Requirement** | `Contract Value × Margin %` | Capital needed for futures position |
| **P&L (Futures)** | `(Exit Price - Entry Price) × Lot Size` | Profit/loss on futures trade |
| **Return on Margin** | `P&L ÷ Margin Used × 100` | Return percentage on margin capital |
| **Position Size (Risk-Based)** | `Risk Amount ÷ (Stop Distance × Lot Size)` | Number of contracts based on risk limit |
| **Hedge Ratio** | `Portfolio Value ÷ Contract Value` | Number of contracts needed for hedge |
| **Brokerage Cost** | `Trade Value × Brokerage Rate` | Transaction cost calculation |

#### **Key Variables Reference:**
- **CAGR**: Use when holding period > 1 year
- **Index Weight**: Higher market cap = higher index influence
- **Margin %**: Typically 6-14% for equity derivatives
- **Stop Distance**: Difference between entry and stop-loss price
- **Risk Amount**: Maximum acceptable loss per trade (typically 2-5% of capital)

---

*Use this formula table for quick reference during analysis and exams* 