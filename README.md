# 🏏 Where Are IPL Matches Won?  
## And How the Impact Player Rule Changed the Game

### 📌 Project Overview

The Indian Premier League (IPL) is one of the most data-rich cricket tournaments in the world. This project analyzes 18 seasons of IPL ball-by-ball data to answer a fundamental question:

👉 **Which phase of the match actually determines the winner?**  
👉 **And how has the Impact Player rule changed match dynamics?**

This project combines data engineering, analysis, and visualization to uncover hidden patterns in match-winning strategies.


### 🎯 Objectives

- Identify which match phase (Powerplay, Middle Overs, Death Overs) has the highest impact on winning
- Analyze how phase dominance translates into match outcomes
- Evaluate the effect of the Impact Player rule on scoring patterns and aggression
- Build an end-to-end analytics pipeline with visualization in Power BI


### 📊 Dataset

- IPL Ball-by-Ball Data (2007–2025)
- Match-level dataset
- Over 1000+ matches analyzed


### ⚙️ Methodology

#### 1. Data Cleaning & Validation
- Removed super overs and non-standard innings
- Handled missing values
- Validated dataset consistency before and after cleaning

#### 2. Feature Engineering
- Created match phases:
  - Powerplay (Overs 1–6)
  - Middle Overs (7–15)
  - Death Overs (16–20)
- Aggregated data at phase level:
  - Runs
  - Balls
  - Wickets

#### 3. Phase Impact Analysis
- Identified phase winners per match
- Compared phase winners with match winners
- Calculated win percentage per phase

#### 4. Match Outcome Analysis
- Evaluated how many phases a team needs to win
- Created phase dominance categories

#### 5. Impact Player Rule Analysis
- Compared pre vs post rule (2023+)
- Metrics analyzed:
  - Average runs per match
  - Wickets per match
  - Death over run rate
  - Frequency of 200+ scores

#### 6. Visualization
- Python (Matplotlib, Seaborn)
- Power BI Dashboard


### 📈 Key Insights

#### 🧠 1. Middle Overs Are the Most Important Phase
- ~70.5% win correlation
- Teams that dominate middle overs are significantly more likely to win

#### ⚡ 2. Death Overs Decide Under Pressure
- Highest wicket impact (~57%)
- Critical for finishing and defending totals

#### 🎯 3. Winning 2 Phases Is Enough
- Teams don’t need to dominate all phases
- Winning **2 out of 3 phases** is usually sufficient

#### 🚀 4. Impact Player Rule Increased Aggression
- Higher run rates in death overs
- Increased frequency of 200+ scores
- More aggressive and dynamic matches


### 📊 Dashboard (Power BI)

The dashboard highlights:
- Phase-wise win impact
- Wicket impact comparison
- Match outcome distribution
- Impact Player rule effects


### 🧰 Tools Used

- Python (Pandas, NumPy)
- Matplotlib & Seaborn
- Power BI
- Google Colab


### 🚀 Key Takeaway

IPL matches are not won in a single phase.

👉 **Middle overs build the advantage**  
👉 **Death overs decide the outcome**  

And with the Impact Player rule, the game is becoming more aggressive than ever.



### 🙌 Acknowledgment

This project was completed as part of the **ORU IPL Analytics Hackathon**.

