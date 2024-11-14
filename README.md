# Jegadeesh-et-Titman-Profitability-of-Momentum-Strategies

# 📈 Profitability of Momentum Strategies: Replication of Jegadeesh & Titman (1993)

## 📝 Project Overview
This project aims to test the profitability of the momentum strategy as described in the paper **"Returns to Buying Winners and Selling Losers: Implications for Stock Market Efficiency"** by Jegadeesh and Titman (Journal of Finance, 1993).

The study investigates 16 different strategies by varying the formation and holding periods of the portfolios. In this project, we focus on one specific strategy:
- **Formation Period**: 12 months
- **Investment Period**: 6 months

## 📊 Methodology
The project follows a three-step approach:

### 1. Identification Phase
- **Objective**: Select stocks for "winner" and "loser" portfolios based on their observed returns over a 12-month period.
- **Data Source**: The data used comes from the **CRSP** (Center for Research in Security Prices) database, including:
  - `PERMNO`: Unique identifier for each stock.
  - `TRC`: Total Return to Common, representing the monthly return.
  - `Date`: Observations over a period spanning multiple years.

### 2. Portfolio Formation
- Stocks were sorted based on their 12-month cumulative returns.
- The dataset was divided into deciles (10 groups):
  - **Decile 9**: "Winner" portfolio (top performers)
  - **Decile 0**: "Loser" portfolio (bottom performers)

### 3. Investment Phase
- The performance of the "winner" and "loser" portfolios was tracked over the subsequent 6-month period.
- Returns were aggregated and analyzed to evaluate the momentum strategy's profitability.

## 🏆 Results
- **Winners Portfolio (Decile 9)**: Achieved a higher average return compared to the rest of the deciles.
- **Losers Portfolio (Decile 0)**: Underperformed as expected based on the momentum hypothesis.
- The momentum strategy demonstrated profitability, consistent with the findings of Jegadeesh and Titman (1993).

## 🔑 Key Findings
- Stocks with strong past performance (winners) tend to continue outperforming in the short-term future.
- Stocks with poor past performance (losers) tend to underperform.
- This aligns with the original study's conclusion, suggesting potential inefficiencies in the stock market.



Your Name: eloi.martin@edu.devinci.fr
GitHub Profile: https://github.com/yourusername
