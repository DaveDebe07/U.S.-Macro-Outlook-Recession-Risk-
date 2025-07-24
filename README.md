# 🇺🇸 U.S. Macro Outlook & Recession Risk  
### A Quantitative Analysis (2000–2025)

This repository contains the full quantitative research behind the report *“U.S. Macro Outlook & Recession Risk: Quantitative Analysis on Historical Data (2000–2025)”*, exploring the predictive power of the 10Y–2Y yield curve, macroeconomic dynamics, and strategy backtests.

---

## 🧠 Executive Summary

- The 10Y–2Y yield curve has inverted ahead of every U.S. recession in the past 50 years.  
- Our logistic model (AUC Score = **0.744**) uses spread, rates, and unemployment to estimate 12-month recession probabilities.  
- A VAR model investigates impulse responses between GDP, CPI, Fed Funds, and unemployment.  
- A macro-based strategy using the yield spread underperforms SP500 in bull markets but offers downside protection.

---

## 📁 Contents

- `report.pdf` → Full written report in professional format  
- `code/` → Python source code & notebooks  
- `data/` → Cleaned datasets and sources  
- `figures/` → All plots and visuals  
- `slides/` → Instagram carousel ready for sharing  

---

## 📊 Key Metrics

| Metric              | Value       |
|---------------------|-------------|
| AUC (Logit Model)   | **0.744**   |
| Sharpe SP500        | 0.38        |
| Sharpe Strategy     | 0.26        |
| CAGR SP500          | 5.99%       |
| CAGR Strategy       | 3.82%       |
| Explained Variance (PCA) | [0.48, 0.40, 0.06] |

---

## 📚 Data Sources

- U.S. Treasury Yields (FRED: GS10, GS2)  
- Inflation CPI, Core CPI (FRED: CPIAUCSL, CPILFESL)  
- Fed Funds Rate (FRED: FEDFUNDS)  
- Unemployment Rate (FRED: UNRATE)  
- Recession Flags (FRED: USREC)  
- GDP Real (FRED: GDPC1)  
- Employment (FRED: MANEMP)  
- SP500 Prices (Yahoo Finance or Bloomberg, monthly close)
