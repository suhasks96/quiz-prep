# QUIZ PREP: Advanced Option Strategies
*Based on Module 6: Option Strategies*

## 🎯 **ADVANCED OPTION STRATEGIES**

### **1. SPREAD STRATEGIES OVERVIEW**

#### **What are Spreads?**
- **Definition**: Simultaneous buying and selling of options of same type
- **Purpose**: Reduce risk, lower cost, create specific payoff profiles
- **Types**: Bull/Bear spreads, Time spreads, Volatility spreads
- **Advantage**: Limited risk and limited reward (vs naked positions)

#### **Spread Categories**
**Vertical Spreads:**
- **Same expiry**, different strikes
- **Examples**: Bull Call Spread, Bear Put Spread

**Horizontal Spreads:**
- **Same strike**, different expiries
- **Examples**: Calendar spreads

**Diagonal Spreads:**
- **Different strikes** AND different expiries

**💡 Quiz Tip**: Spreads trade risk/reward for probability of profit - more conservative than naked options!

---

### **2. BULL STRATEGIES**

#### **Bull Call Spread**
**Construction:**
- **Buy lower strike call** + **Sell higher strike call**
- **Same expiry date**
- **Net debit strategy** (pay to enter)

**Example:**
- **Nifty at 18,000**
- **Buy 18,000 Call at ₹200**
- **Sell 18,200 Call at ₹100**
- **Net Cost**: ₹200 - ₹100 = ₹100

**Payoff Profile:**
- **Maximum Profit**: (Higher Strike - Lower Strike) - Net Premium
- **Maximum Loss**: Net Premium Paid
- **Breakeven**: Lower Strike + Net Premium
- **Best Result**: Price at or above higher strike at expiry

**Bull Call Spread Analysis:**
```
Max Profit = (18,200 - 18,000) - 100 = ₹100
Max Loss = ₹100 (net premium)
Breakeven = 18,000 + 100 = 18,100
Risk-Reward Ratio = 1:1
```

#### **Bull Put Spread**
**Construction:**
- **Sell higher strike put** + **Buy lower strike put**
- **Same expiry date**
- **Net credit strategy** (receive premium)

**Example:**
- **Nifty at 18,000**
- **Sell 18,000 Put at ₹180**
- **Buy 17,800 Put at ₹80**
- **Net Credit**: ₹180 - ₹80 = ₹100

**Payoff Profile:**
- **Maximum Profit**: Net Premium Received
- **Maximum Loss**: (Higher Strike - Lower Strike) - Net Premium
- **Breakeven**: Higher Strike - Net Premium
- **Best Result**: Price at or above higher strike at expiry

**When to Use Bull Spreads:**
1. **Moderately bullish** outlook
2. **High volatility** environment (premium expensive)
3. **Want to reduce cost** vs buying naked calls
4. **Limited upside expected**

---

### **3. BEAR STRATEGIES**

#### **Bear Call Spread**
**Construction:**
- **Sell lower strike call** + **Buy higher strike call**
- **Same expiry date**
- **Net credit strategy** (receive premium)

**Example:**
- **Stock at ₹100**
- **Sell 100 Call at ₹4**
- **Buy 110 Call at ₹1**
- **Net Credit**: ₹4 - ₹1 = ₹3

**Payoff Profile:**
- **Maximum Profit**: Net Premium Received
- **Maximum Loss**: (Higher Strike - Lower Strike) - Net Premium
- **Breakeven**: Lower Strike + Net Premium
- **Best Result**: Price at or below lower strike at expiry

#### **Bear Put Spread**
**Construction:**
- **Buy higher strike put** + **Sell lower strike put**
- **Same expiry date**
- **Net debit strategy** (pay to enter)

**Example:**
- **Stock at ₹100**
- **Buy 100 Put at ₹3**
- **Sell 90 Put at ₹1**
- **Net Cost**: ₹3 - ₹1 = ₹2

**Payoff Profile:**
- **Maximum Profit**: (Higher Strike - Lower Strike) - Net Premium
- **Maximum Loss**: Net Premium Paid
- **Breakeven**: Higher Strike - Net Premium
- **Best Result**: Price at or below lower strike at expiry

---

### **4. VOLATILITY STRATEGIES**

#### **Long Straddle**
**Construction:**
- **Buy call** + **Buy put** at same strike (usually ATM)
- **Same expiry date**
- **Neutral strategy** - profit from big moves either direction

**Example:**
- **Nifty at 18,000**
- **Buy 18,000 Call at ₹150**
- **Buy 18,000 Put at ₹150**
- **Total Cost**: ₹300

**Payoff Profile:**
- **Maximum Profit**: Unlimited on upside, limited to strike on downside
- **Maximum Loss**: Total premium paid
- **Breakeven Points**: Strike ± Total Premium (17,700 and 18,300)
- **Best Result**: Large price movement in either direction

**When to Use Long Straddle:**
1. **Expecting high volatility** (earnings, events)
2. **Uncertain about direction** but expecting big move
3. **Before earnings announcements**
4. **When IV is low** relative to expected actual volatility

#### **Short Straddle**
**Construction:**
- **Sell call** + **Sell put** at same strike
- **Same expiry date**
- **Neutral strategy** - profit from low volatility

**Payoff Profile:**
- **Maximum Profit**: Total premium received
- **Maximum Loss**: Unlimited
- **Breakeven Points**: Strike ± Total Premium
- **Best Result**: Price stays at strike at expiry

**Risk Warning**: **EXTREMELY RISKY** - unlimited loss potential both sides!

#### **Long Strangle**
**Construction:**
- **Buy OTM call** + **Buy OTM put**
- **Different strikes**, same expiry
- **Lower cost** alternative to straddle

**Example:**
- **Nifty at 18,000**
- **Buy 18,200 Call at ₹80**
- **Buy 17,800 Put at ₹80**
- **Total Cost**: ₹160

**Advantages over Straddle:**
- **Lower cost** (using OTM options)
- **Need bigger move** to be profitable
- **Lower maximum loss**

---

### **5. RATIO STRATEGIES**

#### **Call Ratio Back Spread**
**Construction:**
- **Sell lower strike calls** (fewer quantity)
- **Buy higher strike calls** (more quantity)
- **Usually 1:2 or 1:3 ratio**

**Example (1:2 Ratio):**
- **Sell 1 × 18,000 Call at ₹200**
- **Buy 2 × 18,200 Call at ₹100 each**
- **Net Cost**: 2×100 - 200 = ₹0 (or small credit)

**Characteristics:**
- **Unlimited upside** potential
- **Limited downside** risk
- **Profit from large upward moves**
- **Delta neutral** at initiation

#### **Put Ratio Back Spread**
**Construction:**
- **Sell higher strike puts** (fewer quantity)
- **Buy lower strike puts** (more quantity)
- **Usually 1:2 or 1:3 ratio**

**Characteristics:**
- **Profit from large downward moves**
- **Limited upside** risk
- **Unlimited downside** potential (if underlying goes to zero)

---

### **6. SYNTHETIC STRATEGIES**

#### **Synthetic Long Stock**
**Construction:**
- **Buy call** + **Sell put** (same strike & expiry)
- **Replicates** long stock position
- **Lower capital requirement**

**Example:**
- **Buy 100 Call at ₹3**
- **Sell 100 Put at ₹3**
- **Net Cost**: ₹0
- **Position**: Acts like owning stock at ₹100

#### **Synthetic Short Stock**
**Construction:**
- **Sell call** + **Buy put** (same strike & expiry)
- **Replicates** short stock position

#### **Covered Call Synthetic (Collar)**
**Construction:**
- **Long stock** + **Short call** + **Long put**
- **Protective strategy** with income generation
- **Limited upside and downside**

---

### **7. ARBITRAGE STRATEGIES**

#### **Put-Call Parity**
**Fundamental Relationship:**
```
Call Premium - Put Premium = Stock Price - Strike Price × e^(-r×t)
```

**Arbitrage Opportunities:**
- **When parity violated**, risk-free profit possible
- **Conversion**: Long stock + Short call + Long put
- **Reversal**: Short stock + Long call + Short put

#### **Box Spread**
**Construction:**
- **Bull call spread** + **Bear put spread** (same strikes)
- **Risk-free strategy** when properly priced
- **Locks in interest rate** differential

---

### **8. STRATEGY SELECTION GUIDE**

#### **Market Outlook Based Selection**

**Strongly Bullish:**
- **Long calls** (high reward, high risk)
- **Bull call spreads** (moderate reward, limited risk)

**Moderately Bullish:**
- **Bull put spreads** (income generation)
- **Covered calls** (if holding stock)

**Neutral:**
- **Short straddles/strangles** (high risk, consistent income)
- **Iron condors** (limited risk-reward)

**Moderately Bearish:**
- **Bear call spreads** (income generation)
- **Bear put spreads** (limited risk-reward)

**Strongly Bearish:**
- **Long puts** (high reward, high risk)
- **Bear put spreads** (moderate reward, limited risk)

**High Volatility Expected:**
- **Long straddles** (earnings plays)
- **Long strangles** (lower cost alternative)

**Low Volatility Expected:**
- **Short straddles** (very high risk)
- **Iron butterflies** (limited risk-reward)

#### **Risk Tolerance Based Selection**

**Conservative Traders:**
- **Spreads** over naked options
- **Limited risk strategies**
- **Avoid short straddles/strangles**

**Aggressive Traders:**
- **Naked option buying**
- **Ratio spreads**
- **Volatility strategies**

---

## 💰 **BUSINESS & ENTREPRENEURSHIP APPLICATIONS**

### **9. CORPORATE FINANCE APPLICATIONS**

#### **Merger & Acquisition Strategies**
**Risk Arbitrage:**
- **Long target company stock**
- **Short acquirer stock** (if stock deal)
- **Hedge with options** to limit downside

#### **Earnings Strategies**
**Pre-Earnings:**
- **Long straddles** - expect volatility
- **Call/put spreads** - directional bias with limited risk

**Post-Earnings:**
- **Short straddles** - volatility crush
- **Calendar spreads** - time decay benefit

#### **Portfolio Hedging**
**Large Portfolio Protection:**
- **Index put options** - portfolio insurance
- **Collar strategies** - cost-effective protection
- **Bear put spreads** - cheaper alternative to long puts

### **10. WEALTH MANAGEMENT APPLICATIONS**

#### **Income Generation**
**Conservative Strategies:**
- **Covered calls** on dividend stocks
- **Cash-secured puts** on quality stocks
- **Short put spreads** in bull markets

#### **Speculation with Limited Risk**
**Defined Risk Trades:**
- **Bull/bear spreads** instead of naked options
- **Long straddles** for event-driven trades
- **Ratio spreads** for experienced traders

---

## 🎯 **QUIZ SUCCESS STRATEGIES**

### **Key Strategy Classifications**
1. **Debit Spreads**: Pay to enter, limited loss
2. **Credit Spreads**: Receive premium, limited gain
3. **Volatility Plays**: Straddles, strangles
4. **Ratio Strategies**: Unequal quantities
5. **Synthetic Positions**: Replicate other instruments

### **Important Risk-Reward Profiles**
- **Bull Call Spread**: Limited risk, limited reward, bullish
- **Bear Put Spread**: Limited risk, limited reward, bearish  
- **Long Straddle**: Limited risk, unlimited reward, volatility
- **Short Straddle**: Unlimited risk, limited reward, low volatility
- **Call Ratio Back Spread**: Limited risk, unlimited reward, very bullish

### **Critical Decision Factors**
1. **Market Outlook**: Direction and magnitude
2. **Volatility Expectation**: High or low
3. **Time Horizon**: Days to expiry
4. **Risk Tolerance**: Conservative vs aggressive
5. **Capital Requirement**: Available funds

### **Common Strategy Mistakes**
1. **Using wrong strategy** for market outlook
2. **Ignoring volatility** impact
3. **Poor strike selection**
4. **Not having exit plan**
5. **Over-complicating** simple trades

### **Greeks Impact on Strategies**
- **Delta**: Directional exposure
- **Gamma**: Acceleration risk
- **Theta**: Time decay impact
- **Vega**: Volatility sensitivity

**Remember**: Advanced strategies are tools to fine-tune risk-reward profiles. Master the basics first, then progress to complex strategies. Always understand maximum loss before entering any trade. The key is matching strategy to market outlook, volatility expectation, and risk tolerance! 