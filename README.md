# Seasonal Agriculture Performance Analysis

**VOIS AICTE Batch 1, 2026-2027 — Major Data Analytics Project**

## Overview
This project analyzes farm-level agricultural data to investigate how performance
varies across seasons (Kharif, Rabi, Zaid) in terms of yield, production, resource
usage, and profitability. The analysis covers data cleaning, univariate, bivariate
and multivariate exploration, correlation analysis, and statistical testing
(Kruskal-Wallis) to confirm which seasonal differences are genuinely significant.

## Domain
Agriculture

## Tools Used
- Python
- Pandas, NumPy
- Matplotlib, Seaborn
- SciPy (statistical testing)
- Jupyter Notebook / Google Colab

## Files
- `Seasonal_Agriculture_Performance_Analysis.ipynb` — full analysis notebook
- `seasonal_agriculture_performance_dataset.csv` — dataset used

## Key Findings
- Kharif consistently outperforms other seasons on yield, profit, and water efficiency.
- Zaid is the only season with a negative average profit, and has the highest share
  of loss-making farms.
- Seasonal differences across yield, production, profit, water efficiency, and
  disease/pest risk are all statistically significant (Kruskal-Wallis, p < 0.001).
- Farming inputs (fertilizer, N/P/K, pesticide, seed quality) show almost no
  correlation with yield in this dataset.
- Profitability by crop is highly season-dependent — the same crop can swing from
  strongly profitable to loss-making depending on the season it is grown in.

## Note
This is a Data Analytics project. No Machine Learning or dashboard development
was required or performed.
