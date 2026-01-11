# Executive Findings  
## Enterprise Financial Forecasting, Fraud & Risk Decision Platform

---

## Overview

This analysis integrates transaction-level fraud detection, customer-level credit risk modeling, and macroeconomic financial forecasting into a single enterprise decision framework.

The objective was to identify:
- Where financial risk is concentrated today
- Which signals materially improve risk prediction
- How financial exposure is likely to evolve over the next 12 months

---

## Scale of Analysis

- **2,512 transactions** analyzed for fraud risk  
- **32,581 customers / loan applications** assessed for credit risk  
- **12-month forward-looking forecast** of bank credit exposure  

These datasets span three risk horizons:
- Immediate (fraud losses)
- Medium-term (credit defaults)
- Forward-looking (balance sheet exposure)

---

## Fraud Risk — Key Findings

- Only **~3% of transactions** were flagged as high risk  
- High-risk transactions show:
  - Login attempts **2–3× higher** than normal
  - Transaction durations **50–60% longer**
  - Disproportionate off-hour activity  

When translated into **expected fraud loss**:
- The **top ~1% of transactions** account for a majority of expected loss
- Several transactions exceed **1,000 units** in expected loss
- Transaction amount alone is a poor fraud indicator

**Interpretation:**  
Fraud risk is **highly concentrated** and driven by behavioral anomalies, not volume.

---

## Credit Risk — Key Findings

- Overall default rate across portfolio: **~22%**
- Default rates by credit risk tier:
  - Low risk: **~5%**
  - Medium risk: **~14%**
  - High risk: **~63%**
- Credit risk model performance:
  - **ROC-AUC ≈ 0.87**, stable across training and test data

**Interpretation:**  
Credit risk is strongly predictable and concentrated within a minority of the portfolio.

---

## Enterprise Risk — Combined View

When fraud exposure was combined with credit risk:
- High enterprise risk customers defaulted at **~68%**
- This is materially higher than credit-only risk segmentation
- Several customers moved into high risk due to behavioral fraud signals

**Interpretation:**  
Fraud behavior adds meaningful predictive power beyond traditional credit metrics.

---

## Financial Forecasting — Key Findings

- Forecast target: **Bank Credit Outstanding**
- Horizon: **12 months**
- Models compared:
  - ARIMAX
  - Time-aware XGBoost

| Model              | Forecast Error (MAPE) |
|--------------------|-----------------------|
| ARIMAX             | ~0.7%                 |
| Time-aware XGBoost | ~2.5%                 |

ARIMAX error is approximately **3.5× lower** than the ML alternative and provides **confidence intervals** for scenario planning.

---

## Executive Implications

- Fraud losses should be prioritized by **expected financial impact**
- Credit risk decisions should incorporate **behavioral fraud exposure**
- Enterprise risk should be managed using a **single integrated metric**
- Financial planning should rely on **forecast ranges, not point estimates**

---

## Bottom Line

This project demonstrates that combining behavioral fraud signals, structural credit risk, and macroeconomic forecasting provides a clearer, more actionable view of enterprise financial risk than siloed analytics.

The value lies in **where leadership intervenes**, not in model complexity.
