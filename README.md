# Jegadeesh-et-Titman-Profitability-of-Momentum-Strategies

Project Overview
This project aims to test the profitability of the momentum strategy as described in the paper "Returns to Buying Winners and Selling Losers: Implications for Stock Market Efficiency" by Jegadeesh and Titman (Journal of Finance, 1993).

The paper investigates 16 different strategies, obtained by varying the formation and holding periods of the portfolios. The study also explores whether or not a one-week delay between the formation period and the investment period is applied. In this project, we focus on replicating one specific strategy:

Identification Phase:
Selecting stocks for "winner" and "loser" portfolios based on the observed returns over a 12-month period.
Investment Phase:
Investing in the selected portfolios over the following 6-month period.
Data
The data used for this project comes from the CRSP (Center for Research in Security Prices) database, containing historical stock data.
The dataset includes information on:
PERMNO: Unique identifier for each stock.
TRC: Total Return to Common, representing the monthly return for each stock.
Date: Observations over a period spanning multiple years.
Methodology
Step 1: Data Preparation
Data cleaning was performed to handle missing values and format the date fields correctly.
The dataset was filtered to focus on a relevant sample of stocks.
Step 2: Portfolio Formation
The stocks were sorted based on their 12-month cumulative returns.
The dataset was split into deciles (10 groups), with the top decile (Decile 9) identified as the "winner" portfolio and the bottom decile (Decile 0) as the "loser" portfolio.
Step 3: Investment Phase
The performance of the "winner" and "loser" portfolios was tracked over the subsequent 6-month period.
The returns were aggregated and compared to analyze the profitability of the momentum strategy.
Results
Winners Portfolio (Decile 9): Achieved a higher average return compared to the rest of the deciles.
Losers Portfolio (Decile 0): Underperformed relative to the "winners" portfolio, as expected based on the momentum hypothesis.
The momentum strategy demonstrated profitability, in line with the findings of Jegadeesh and Titman (1993).
Key Findings
The analysis suggests that stocks with strong past performance (winners) tend to continue outperforming, while stocks with poor past performance (losers) tend to underperform in the short-term future.
The momentum effect observed in this study aligns with the conclusions of the original research, highlighting potential inefficiencies in the stock market.
References
Jegadeesh, N., & Titman, S. (1993). Returns to Buying Winners and Selling Losers: Implications for Stock Market Efficiency. Journal of Finance.
License
This project is licensed under the MIT License - see the LICENSE file for details.
Contact
For questions or feedback, please reach out:

Your Name: eloi.martin@edu.devinci.fr
GitHub Profile: https://github.com/yourusername
