# economic-growth-peru-var-analysis
Econometric analysis of Peru’s GDP growth using VAR model, IRF, and Granger causality

# Impact of External Factors on Peru’s Economic Growth (1994–2019)

## Overview
This project analyzes the impact of external economic factors on Peru’s GDP growth using a Vector Autoregression (VAR) model. The objective is to evaluate how global economic conditions influence domestic economic performance.

## Data
The analysis is based on quarterly data (1994–2019) from:
- Peru GDP growth rate
- China & United States GDP growth rates
- Metal price index
- Volatility Index (VIX)

Sources: BCRP, IMF, OECD, FRED

## Methodology
- Stationarity tests: Augmented Dickey-Fuller (ADF) and Phillips-Perron (PP)
- VAR model estimation (optimal lag selection based on AIC, SC, HQ)
- Model diagnostics:
  - Autocorrelation test (LM)
  - Heteroskedasticity test (White)
  - Normality test (Jarque-Bera)
- Impulse Response Function (IRF)
- Variance Decomposition
- Granger Causality Test

A stable VAR(1) model was estimated after validating all assumptions.

## Key Findings
- External factors explain approximately 45% of Peru’s GDP growth variability
- China & US economic growth are the most influential factors (~24%)
- Metal prices significantly impact economic growth (~19%)
- VIX does not show a statistically significant effect
- Positive external shocks generate a delayed but persistent increase in Peru’s GDP growth

## Tools Used
- EViews
- Excel

## Files Included
- [report.pdf](https://github.com/user-attachments/files/26720755/report.pdf): Summary of methodology and key results 
- Impulse response graphs:
<img width="570" height="248" alt="image" src="https://github.com/user-attachments/assets/e37e2d16-d1de-47ea-a673-03004534cdc1" />
<img width="570" height="241" alt="image" src="https://github.com/user-attachments/assets/bb8c9b51-e2dd-4fb7-92b6-61f73d795f8e" />
<img width="570" height="241" alt="image" src="https://github.com/user-attachments/assets/f054849c-8923-46e3-92c0-dd56b8565b53" />

- Variance decomposition results:
<img width="451" height="319" alt="image" src="https://github.com/user-attachments/assets/d4c8d72a-2ba7-433c-aa4b-1370b9abea9f" />

## Author
Solanssch Cristina Rodriguez Hidalgo  
Economist | Data Analyst

