# Retail Customer Segmentation – EDA

Exploratory data analysis on a retail customer dataset (200 customers) to understand 
what drives monthly revenue and identify patterns for customer segmentation.

## Dataset
- 200 customers, 9 features: Age, Gender, CityTier, MonthlyIncome, TenureMonths, 
  VisitsPerMonth, AvgOrderValue, MonthlyRevenue

## Key Findings
- **Visit frequency drives revenue, not tenure or age.** VisitsPerMonth has a 
  strong correlation with MonthlyRevenue (r = 0.84), while TenureMonths (r = 0.29) 
  and Age (r = -0.02) show weak to no relationship.
- **CityTier 3 generates the highest average revenue** (₹9,013.82), ahead of 
  CityTier 1 (₹8,420.35) and CityTier 2 (₹7,717.74) — a slightly counterintuitive 
  result worth further investigation (e.g., product mix, competition levels).
- **Gender shows minimal difference in spend** — Female customers average 
  ₹8,579.97/month vs. Male at ₹8,110.24, a gap of about 5%.

## Tools Used
Python, Pandas, NumPy, Matplotlib, Seaborn (via Google Colab)

## Business Recommendation
Since visit frequency is the strongest revenue driver, loyalty and engagement 
programs should prioritize increasing visit frequency over long-term tenure-based 
rewards.

## Notebook
[Open in Colab](https://colab.research.google.com/drive/1mb0lik9l5ZIeKd4AR-zP1IPR3SINhzOV)
-
