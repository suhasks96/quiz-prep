# QUIZ PREP: Option Strategies & Advanced Trading
*Based on Module 6: Option Strategies*

## 🎯 **OPTION STRATEGIES OVERVIEW**

### **1. MINDSET FOR OPTION STRATEGIES**

#### **The Right Approach to Options Trading**
**Common Mistakes:**
- **Lottery Mentality**: Treating options as gambling
- **"Limited Risk, Unlimited Profit" Trap**: Theoretically correct but practically dangerous
- **Hit or Miss Trading**: No systematic approach
- **Reflexive Brain vs Reflective Brain**: Emotional vs analytical decisions

#### **Winning Addiction Psychology**
**Behavioral Finance Insight**: Anticipating wins is more exciting than actual winning
- **Reflexive Brain**: Feel and intuition-driven (dangerous for trading)
- **Reflective Brain**: Analysis and calculation-based (necessary for success)
- **Solution**: Develop systematic, strategy-based approach

#### **Professional Approach**
**Strategy-Based Trading:**
- **Clear Objectives**: Define profit targets and stop losses
- **Risk Management**: Position sizing and diversification
- **Systematic Selection**: Choose strategies based on market conditions
- **Greeks Management**: Understand and monitor Greeks exposure

### **2. PREREQUISITES FOR STRATEGY TRADING**

#### **Essential Knowledge Base**
**Options Fundamentals:**
- **Call and Put Options**: Complete understanding of payoffs
- **The Greeks**: Delta, Gamma, Theta, Vega, Rho
- **Volatility**: Historical vs Implied volatility
- **Time Decay**: Impact on option prices

**Technical Analysis:**
- **Support and Resistance**: Key price levels
- **Trend Analysis**: Market direction identification
- **Chart Patterns**: Reversal and continuation patterns
- **Volume Analysis**: Confirmation tool

**Market Conditions:**
- **Bullish Markets**: Rising price expectations
- **Bearish Markets**: Falling price expectations
- **Sideways Markets**: Range-bound price action
- **High/Low Volatility**: Strategy selection criteria

---

## 📈 **BULLISH STRATEGIES**

### **3. BULL CALL SPREAD**

#### **Strategy Construction**
**Setup:**
- **Buy Call**: Lower strike price (ITM or ATM)
- **Sell Call**: Higher strike price (OTM)
- **Same Expiry**: Both options expire same date
- **Net Premium**: Debit spread (pay net premium)

#### **Example**
**Market Setup**: Stock at ₹100, expect moderate rise to ₹110
**Strategy:**
- **Buy Call**: 100 strike at ₹8
- **Sell Call**: 110 strike at ₹3
- **Net Premium**: ₹8 - ₹3 = ₹5 (paid)
- **Maximum Profit**: (110 - 100) - 5 = ₹5
- **Maximum Loss**: ₹5 (net premium paid)
- **Breakeven**: 100 + 5 = ₹105

#### **Payoff Analysis**
**At Expiry:**
- **Stock ≤ 100**: Both options expire worthless, Loss = ₹5
- **Stock = 105**: Long call worth ₹5, short call worthless, Net = 0 (breakeven)
- **Stock = 110**: Long call worth ₹10, short call worthless, Profit = ₹5
- **Stock > 110**: Long call gains offset by short call losses, Profit = ₹5

#### **Strategy Characteristics**
**Advantages:**
- **Lower Cost**: Cheaper than buying call outright
- **Limited Risk**: Maximum loss = net premium paid
- **Probability**: Higher probability of profit than naked call

**Disadvantages:**
- **Limited Profit**: Capped at strike difference minus premium
- **Time Decay**: Theta negative for net position
- **Requires Direction**: Need upward movement for profit

### **4. BULL PUT SPREAD**

#### **Strategy Construction**
**Setup:**
- **Sell Put**: Higher strike price (ATM or slightly OTM)
- **Buy Put**: Lower strike price (OTM)
- **Same Expiry**: Both options expire same date
- **Net Premium**: Credit spread (receive net premium)

#### **Example**
**Market Setup**: Stock at ₹100, expect to stay above ₹95
**Strategy:**
- **Sell Put**: 100 strike at ₹6
- **Buy Put**: 95 strike at ₹2
- **Net Premium**: ₹6 - ₹2 = ₹4 (received)
- **Maximum Profit**: ₹4 (net premium received)
- **Maximum Loss**: (100 - 95) - 4 = ₹1
- **Breakeven**: 100 - 4 = ₹96

#### **Why Bull Put Spread?**
**Advantages Over Bull Call Spread:**
- **Credit Received**: Get paid to enter the trade
- **Time Decay**: Benefits from theta decay
- **Lower Volatility Impact**: Less vega risk
- **Margin Efficient**: Uses margin more efficiently

#### **Strike Selection Guidelines**
**Conservative Approach**: Sell put 5-10% below current price
**Aggressive Approach**: Sell put near current price
**Protection Level**: Buy put 10-15 points below short put

---

## 📉 **BEARISH STRATEGIES**

### **5. BEAR CALL SPREAD**

#### **Strategy Construction**
**Setup:**
- **Sell Call**: Lower strike price (ATM or slightly OTM)
- **Buy Call**: Higher strike price (OTM)
- **Same Expiry**: Both options expire same date
- **Net Premium**: Credit spread (receive net premium)

#### **Example**
**Market Setup**: Stock at ₹100, expect to stay below ₹105
**Strategy:**
- **Sell Call**: 100 strike at ₹5
- **Buy Call**: 105 strike at ₹2
- **Net Premium**: ₹5 - ₹2 = ₹3 (received)
- **Maximum Profit**: ₹3 (net premium received)
- **Maximum Loss**: (105 - 100) - 3 = ₹2
- **Breakeven**: 100 + 3 = ₹103

#### **Strategy Benefits**
- **Credit Strategy**: Receive money upfront
- **Time Decay**: Theta works in your favor
- **High Probability**: Profitable if stock stays below breakeven

### **6. BEAR PUT SPREAD**

#### **Strategy Construction**
**Setup:**
- **Buy Put**: Higher strike price (ATM or ITM)
- **Sell Put**: Lower strike price (OTM)
- **Same Expiry**: Both options expire same date
- **Net Premium**: Debit spread (pay net premium)

#### **Example**
**Market Setup**: Stock at ₹100, expect fall to ₹90
**Strategy:**
- **Buy Put**: 100 strike at ₹4
- **Sell Put**: 95 strike at ₹1
- **Net Premium**: ₹4 - ₹1 = ₹3 (paid)
- **Maximum Profit**: (100 - 95) - 3 = ₹2
- **Maximum Loss**: ₹3 (net premium paid)
- **Breakeven**: 100 - 3 = ₹97

#### **Bear Call vs Bear Put Spread**
**Choose Bear Call When:**
- **High Implied Volatility**: Options expensive, better to sell
- **Time Decay Advantage**: Want theta to work for you
- **Credit Preference**: Want to receive premium

**Choose Bear Put When:**
- **Strong Bearish View**: Expect significant downward move
- **Low Implied Volatility**: Options cheap, better to buy
- **Directional Play**: Want to benefit from large moves

---

## 🔄 **RATIO STRATEGIES**

### **7. CALL RATIO BACK SPREAD**

#### **Strategy Construction**
**Setup:**
- **Sell Call**: 1 ATM call
- **Buy Call**: 2 OTM calls (higher strikes)
- **Ratio**: 1:2 (can be adjusted)
- **Net Premium**: Usually credit or near zero cost

#### **Example**
**Market Setup**: Stock at ₹100, expect volatility expansion
**Strategy:**
- **Sell Call**: 1 × 100 strike at ₹5
- **Buy Call**: 2 × 110 strike at ₹2 each
- **Net Premium**: ₹5 - ₹4 = ₹1 (received)
- **Breakeven Points**: 99 (lower) and 121 (upper)

#### **Payoff Characteristics**
**Limited Loss Zone**: Between strike prices (100-110)
**Unlimited Profit**: Above upper breakeven (121+)
**Small Profit**: Below lower breakeven (below 99)

#### **When to Use**
- **Expecting Volatility**: Large moves in either direction
- **Range-bound Currently**: But anticipating breakout
- **Low Cost**: Can establish for credit or small debit

### **8. PUT RATIO BACK SPREAD**

#### **Strategy Construction**
**Setup:**
- **Sell Put**: 1 ATM put
- **Buy Put**: 2 OTM puts (lower strikes)
- **Ratio**: 1:2 (can be adjusted)
- **Net Premium**: Usually credit or near zero cost

#### **Example**
**Market Setup**: Stock at ₹100, expect volatility with bearish bias
**Strategy:**
- **Sell Put**: 1 × 100 strike at ₹4
- **Buy Put**: 2 × 90 strike at ₹1.50 each
- **Net Premium**: ₹4 - ₹3 = ₹1 (received)

#### **Risk Profile**
**Advantages:**
- **Credit Strategy**: Receive premium upfront
- **Volatility Play**: Profits from large moves
- **Bearish Bias**: Benefits more from downward moves

**Disadvantages:**
- **Limited Loss Zone**: Loss in middle range
- **Complexity**: Harder to manage than simple strategies
- **Margin Requirements**: Higher margin for naked puts

---

## 🌀 **VOLATILITY STRATEGIES**

### **9. LONG STRADDLE**

#### **Strategy Construction**
**Setup:**
- **Buy Call**: ATM call option
- **Buy Put**: ATM put option (same strike)
- **Same Expiry**: Both options expire same date
- **Net Premium**: Debit (pay for both options)

#### **Example**
**Market Setup**: Stock at ₹100, expect big move but unsure of direction
**Strategy:**
- **Buy Call**: 100 strike at ₹5
- **Buy Put**: 100 strike at ₹5
- **Net Premium**: ₹10 (paid)
- **Breakeven Points**: 90 and 110
- **Profit**: Stock moves below 90 or above 110

#### **The Directional Dilemma**
**Problem**: Don't know if stock will go up or down
**Solution**: Straddle profits from movement in either direction
**Key Requirement**: Movement must be larger than premium paid

#### **Volatility Matters**
**High IV Environment**: Straddles expensive, consider selling
**Low IV Environment**: Straddles cheap, good buying opportunity
**IV Expansion**: Helps long straddle even without price movement
**IV Contraction**: Hurts long straddle even with price movement

#### **What Can Go Wrong?**
**Time Decay**: Theta is enemy #1 for straddle buyers
**Volatility Crush**: Post-event IV collapse
**Insufficient Movement**: Price moves but not enough to overcome premium
**Wrong Timing**: Buying straddle too close to expiry

### **10. SHORT STRADDLE**

#### **Strategy Construction**
**Setup:**
- **Sell Call**: ATM call option
- **Sell Put**: ATM put option (same strike)
- **Same Expiry**: Both options expire same date
- **Net Premium**: Credit (receive for both options)

#### **Example**
**Market Setup**: Stock at ₹100, expect low volatility/sideways movement
**Strategy:**
- **Sell Call**: 100 strike at ₹5
- **Sell Put**: 100 strike at ₹5
- **Net Premium**: ₹10 (received)
- **Profit Zone**: Stock stays between 90 and 110
- **Maximum Profit**: ₹10 (if stock stays at 100)

#### **Risk Management**
**Unlimited Risk**: Potential for large losses beyond breakevens
**Margin Requirements**: Substantial margin needed
**Early Management**: Close position at 25-50% profit
**Stop Loss**: Difficult to set, requires active monitoring

### **11. LONG STRANGLE**

#### **Strategy Construction**
**Setup:**
- **Buy Call**: OTM call option
- **Buy Put**: OTM put option
- **Same Expiry**: Both options expire same date
- **Lower Cost**: Cheaper than straddle

#### **Example**
**Market Setup**: Stock at ₹100, expect big move but want lower cost than straddle
**Strategy:**
- **Buy Call**: 105 strike at ₹3
- **Buy Put**: 95 strike at ₹3
- **Net Premium**: ₹6 (paid)
- **Breakeven Points**: 89 and 111
- **Lower Cost**: ₹6 vs ₹10 for straddle

#### **Strangle vs Straddle**
**Strangle Advantages:**
- **Lower Cost**: Cheaper premium
- **Wider Breakevens**: Need larger move to profit
- **Less Time Decay**: Lower theta exposure

**Straddle Advantages:**
- **Closer Breakevens**: Need smaller move to profit
- **Better Delta**: More sensitive to price moves

### **12. SHORT STRANGLE**

#### **Strategy Construction**
**Setup:**
- **Sell Call**: OTM call option
- **Sell Put**: OTM put option
- **Same Expiry**: Both options expire same date
- **Net Premium**: Credit (receive premium)

#### **Strategy Benefits**
**High Probability**: Wider profit zone than short straddle
**Time Decay**: Theta works strongly in your favor
**Credit Strategy**: Receive money upfront
**Range Trading**: Profit from sideways markets

---

## 📊 **SYNTHETIC STRATEGIES & ARBITRAGE**

### **13. SYNTHETIC LONG STOCK**

#### **Strategy Construction**
**Setup:**
- **Buy Call**: ATM call
- **Sell Put**: ATM put (same strike)
- **Result**: Mimics long stock position

#### **Synthetic vs Actual Stock**
**Advantages:**
- **Lower Capital**: Requires less margin than buying stock
- **Flexibility**: Can adjust strikes and expiries
- **Leverage**: Control more shares with less capital

**Disadvantages:**
- **Time Decay**: Options have expiry
- **Complexity**: More moving parts than stock
- **Dividend Risk**: No dividend rights

### **14. ARBITRAGE OPPORTUNITIES**

#### **Put-Call Parity Arbitrage**
**Principle**: C - P = S - K × e^(-r×T)
**Opportunity**: When market prices deviate from theoretical relationship
**Execution**: 
- If calls overpriced relative to puts: Sell calls, buy puts
- If puts overpriced relative to calls: Sell puts, buy calls

#### **Box Spread Arbitrage**
**Construction**: Long call spread + Short put spread (same strikes)
**Opportunity**: When box trades away from risk-free rate
**Risk-Free Profit**: Theoretical arbitrage with no market risk

---

## 📈 **ADVANCED CONCEPTS**

### **15. MAX PAIN THEORY**

#### **Concept Explanation**
**Max Pain**: Price level where maximum number of options expire worthless
**Theory**: Market tends to move toward max pain by expiry
**Calculation**: Sum of value lost by all option holders at each price level

#### **Max Pain Calculation Process**
1. **List all strikes**: For both calls and puts
2. **Calculate losses**: At each price level for option holders
3. **Sum total losses**: Across all strikes and option types
4. **Find maximum**: Price level with highest total losses

#### **Practical Application**
**Market Maker Influence**: Market makers benefit from options expiring worthless
**Expiry Week**: Theory most relevant in final days before expiry
**Support/Resistance**: Max pain can act as magnet for prices
**Limitations**: Theory doesn't account for fundamental factors

### **16. PUT-CALL RATIO (PCR)**

#### **Definition & Calculation**
**PCR**: Put volume (or OI) ÷ Call volume (or OI)
**Interpretation**:
- **PCR > 1**: More puts than calls (bearish sentiment)
- **PCR < 1**: More calls than puts (bullish sentiment)
- **PCR around 1**: Balanced sentiment

#### **Types of PCR**
**Volume PCR**: Based on daily trading volumes
**Open Interest PCR**: Based on outstanding positions
**Strike-wise PCR**: PCR at specific strike levels
**Time-series PCR**: PCR trends over time

#### **Using PCR for Trading**
**Contrarian Indicator**: Extremely high PCR can be bullish signal
**Sentiment Gauge**: Overall market sentiment measurement
**Support/Resistance**: High OI strikes act as support/resistance
**Strategy Selection**: High PCR suggests volatility strategies

---

## 🎯 **STRATEGY SELECTION FRAMEWORK**

### **17. MARKET CONDITION MAPPING**

#### **Bullish Markets**
**Mild Bullish**: Bull call spread, Bull put spread
**Strong Bullish**: Long calls, Call ratio back spread
**Volatile Bullish**: Long call, Long straddle

#### **Bearish Markets**
**Mild Bearish**: Bear call spread, Bear put spread
**Strong Bearish**: Long puts, Put ratio back spread
**Volatile Bearish**: Long put, Long straddle

#### **Sideways Markets**
**Low Volatility**: Short straddle, Short strangle
**High Volatility**: Iron condor, Iron butterfly
**Range-bound**: Covered calls, Cash-secured puts

### **18. VOLATILITY-BASED SELECTION**

#### **High IV Environment**
**Strategies to Consider**: Short straddle, Short strangle, Credit spreads
**Avoid**: Buying expensive options
**Focus**: Selling premium and time decay

#### **Low IV Environment**
**Strategies to Consider**: Long straddle, Long strangle, Debit spreads
**Avoid**: Selling cheap options
**Focus**: Buying cheap volatility

#### **IV Rank Guidelines**
**IV Rank > 50**: Consider selling strategies
**IV Rank < 30**: Consider buying strategies
**IV Rank 30-50**: Neutral strategies or spreads

---

## 🛡️ **RISK MANAGEMENT**

### **19. POSITION MANAGEMENT**

#### **Entry Rules**
**Strategy Selection**: Based on market outlook and volatility
**Position Sizing**: Risk appropriate amount per trade
**Time Selection**: Adequate time for thesis to play out
**Strike Selection**: Probability-based strike selection

#### **Exit Rules**
**Profit Targets**: 25-50% of maximum profit for credit strategies
**Loss Limits**: 2-3x credit received for credit strategies
**Time-based Exits**: Close before final week for complex strategies
**Adjustment Triggers**: Delta, gamma, or volatility thresholds

#### **Adjustment Techniques**
**Rolling**: Move strikes or expiry dates
**Delta Hedging**: Add/remove delta exposure
**Volatility Hedging**: Adjust vega exposure
**Partial Closing**: Close portion of position

### **20. COMMON MISTAKES TO AVOID**

#### **Strategic Mistakes**
**Over-complexity**: Using complex strategies when simple ones work
**Wrong Volatility**: Buying high IV or selling low IV
**Inadequate Time**: Too close to expiry for thesis
**Wrong Market View**: Strategy doesn't match outlook

#### **Execution Mistakes**
**Poor Timing**: Entering at wrong market conditions
**No Exit Plan**: Not defining profit/loss targets
**Position Sizing**: Risking too much on single strategy
**Ignoring Greeks**: Not understanding risk exposures

#### **Psychological Mistakes**
**Hope Trading**: Holding losers too long
**Greed**: Not taking profits when available
**FOMO**: Chasing strategies that have moved
**Overconfidence**: Increasing size after wins

---

## 🎯 **QUIZ SUCCESS STRATEGIES**

### **Key Strategy Concepts to Master**
1. **Spread Strategies**: Bull/Bear call/put spreads
2. **Volatility Strategies**: Straddles and strangles
3. **Ratio Strategies**: Back spreads and front spreads
4. **Synthetic Positions**: Replicating stock with options
5. **Greeks Impact**: How Greeks affect each strategy
6. **Strategy Selection**: Market condition-based selection
7. **Risk Management**: Entry, exit, and adjustment rules
8. **Max Pain & PCR**: Market sentiment indicators

### **Important Strategy Formulas**
- **Spread Maximum Profit**: Strike Difference - Net Premium Paid
- **Spread Maximum Loss**: Net Premium Paid (for debit spreads)
- **Breakeven Points**: Strike ± Net Premium
- **Straddle Breakevens**: Strike ± Total Premium Paid
- **Max Pain**: Price with maximum option value destruction

### **Key Strategy Numbers**
- **Spread Ratio**: Usually 1:1 for basic spreads
- **Ratio Back Spread**: 1:2 or 1:3 typical ratios
- **PCR Levels**: >1.2 bearish, <0.8 bullish
- **IV Rank**: >50 consider selling, <30 consider buying
- **Profit Target**: 25-50% for credit strategies

### **Common Quiz Topics**
**Strategy Construction:**
- How to build each strategy
- Required positions and ratios
- Net credit or debit calculations

**Payoff Analysis:**
- Maximum profit and loss
- Breakeven calculations
- Profit zones identification

**Greeks Impact:**
- How time decay affects strategies
- Delta exposure in spreads
- Volatility impact on strategies

**Strategy Selection:**
- When to use each strategy
- Market condition requirements
- Volatility environment considerations

**Risk Management:**
- Position sizing guidelines
- Exit strategy planning
- Adjustment techniques

### **Quiz Tips**
- **Master Basic Spreads**: Foundation for complex strategies
- **Understand Payoff Diagrams**: Visual representation crucial
- **Know Strategy Greeks**: How each Greek affects strategies
- **Practice Calculations**: Breakeven and profit/loss math
- **Strategy Selection Logic**: Match strategy to market view

### **Strategy Quick Reference**
**Bullish**: Bull call spread, Bull put spread, Long call
**Bearish**: Bear call spread, Bear put spread, Long put
**Neutral**: Short straddle, Short strangle, Iron condor
**Volatile**: Long straddle, Long strangle, Ratio back spreads
**High IV**: Credit strategies (short premium)
**Low IV**: Debit strategies (long premium)

**Remember**: Option strategies are tools to express market views while managing risk. The key to success is matching the right strategy to market conditions, understanding the risk-reward profile, and having clear entry/exit rules. Always consider the Greeks impact and manage positions actively rather than holding to expiry! 