# GTA Online Player Analysis

## 🎮 Project Overview
Analysis of 9,476 GTA Online players over 3 months to understand the relationship between player engagement and monetization behavior.

**Datathon:** Rockstar Games Datathon Fall 2025

## 📊 Key Findings

### 1. Engagement Drives Revenue - But It's Not Linear
- **Correlation:** Weak positive relationship (r=0.237) between playtime and spending
- **Spending Gap:** High-engagement players (top 25%) spend **5.9x more** than casual players
  - Top quartile: 6.9M GTA$ average
  - Bottom quartile: 1.2M GTA$ average

### 2. The 2.7% That Matter
- Only **2.7% of players** purchase premium currency
- These payers maintain nearly equal balances:
  - Earned currency: 576K GTA$
  - Paid currency: 688K GTA$
- **Insight:** Payers aren't avoiding gameplay - they actively earn currency too

### 3. The Engagement Paradox ⚠️
- **Counter-intuitive finding:** Payers play LESS than non-payers
  - Payers: 13.0 hours average
  - Non-payers: 17.9 hours average
- **Implication:** Big spenders are efficiency-focused, not super-fans

## 💡 Strategic Insights

**The Bottom Line:** GTA Online's biggest spenders aren't necessarily the most engaged players - they're strategic players who value their time. Understanding this distinction is key to growing the 2.7% conversion rate while maintaining engaging experiences.

**Recommendations:**
1. **Target "Efficient Achievers"** - Design time-saving purchases, not just cosmetics
2. **Conversion Opportunity** - 97.3% of players don't pay yet; top engaged non-payers represent untapped revenue
3. **Dual Economy Validation** - Payers use both currencies, confirming the two-currency system works
4. **Retention ≠ Monetization** - Build separate strategies for engagement and conversion

## 📁 Dataset

**Sample Size:** 9,476 players | **Time Period:** 3 months

### Files Analyzed:
- `player_statistics.csv` - Player engagement metrics (246,137 rows)
- `item_spend.csv` - Purchase transactions (155,750 rows)
- `player_activity.csv` - Activity participation data (not included in repo due to size)

### Data Fields:
- Player demographics (platform, account_id)
- Engagement metrics (playtime, days played, character rank)
- Currency balances (earned vs paid)
- Item purchases (type, category, amount spent)

## 🛠️ Tech Stack
- **Python** - Core analysis
- **Pandas** - Data manipulation
- **NumPy** - Numerical computations
- **Matplotlib & Seaborn** - Visualizations
- **Scipy** - Statistical analysis

## 🚀 How to Run

### Prerequisites
```bash
pip install pandas numpy matplotlib seaborn scipy jupyter
```

## Copyright
© [2025] [Colin J. Emmanuel]. All rights reserved.
This code is shared for portfolio and reference purposes only.
This project was completed as part of the Rockstar Games Datathon Fall 2025.