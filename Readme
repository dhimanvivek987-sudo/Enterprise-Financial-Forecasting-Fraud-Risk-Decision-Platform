# Enterprise Financial Forecasting, Fraud & Risk Decision Platform

## 1. Scale of the Problem

This project analyzes risk across three distinct horizons using multiple datasets.

- **2,512 transactions** processed for fraud risk  
- **32,581 customers / loan applications** assessed for credit risk  
- **12 months** of forward-looking financial exposure forecasted using macroeconomic drivers  

These datasets represent three layers of enterprise risk:

- **Immediate risk** → transaction-level fraud losses  
- **Medium-term risk** → customer credit defaults  
- **Forward-looking risk** → balance sheet and credit exposure  

The leadership question is not whether risk exists.  
It is **how concentrated that risk is** and **where intervention produces the highest return**.

---

## 2. Fraud Risk — What the Numbers Say

### Findings

Out of **2,512 transactions**, approximately **3% (≈75 transactions)** were flagged as high risk.

These transactions consistently exhibit:

- Login attempts that are **2–3× higher** than normal transactions  
- Transaction durations that are **50–60% longer** than average  
- Abnormal timing, including **night and off-hour activity**  

When fraud risk was converted into **expected fraud loss**:

- The **top ~1% of transactions** account for a disproportionate share of expected loss  
- Several transactions show **expected fraud losses exceeding 1,000 units**  
- Multiple **low-value transactions carry higher expected loss** than higher-value but normal transactions  

### Business Interpretation

Fraud exposure is **not volume-driven**.  
It is **highly concentrated** and driven primarily by **behavior**, not transaction size.

When fraud teams investigate transactions:

- Randomly, or  
- Using simple amount thresholds  

most investigative effort is wasted and **high-loss cases are addressed too late**.

---

## 3. Fraud Recommendation (Quantified)

### Recommendation 1 — Re-rank Fraud Queues by Expected Loss

Instead of investigating all alerts equally:

- Focus on the **top ~3% of transactions**
- Prioritize the **top ~1% by expected fraud loss**

**Expected impact:**

- **60–70% reduction** in investigation workload  
- Faster containment of **highest-loss fraud events**  
- Lower operational cost **without increasing fraud leakage**

This is a **pure efficiency gain** with no material downside.

---

## 4. Credit Risk — What the Numbers Say

### Findings

From **32,581 loan applications**:

- **Overall default rate:** ~22%

Default rates by credit risk segment:

| Credit Risk Segment | Default Rate |
|--------------------|--------------|
| Low Risk           | ~5%          |
| Medium Risk        | ~14%         |
| High Risk          | ~63%         |

Model discrimination:

- **ROC-AUC ≈ 0.87**, stable across training and test sets  

This implies that a customer in the **high-risk segment is ~12× more likely to default** than a low-risk customer.

---

## 5. Credit Risk Recommendation (Quantified)

### Recommendation 2 — Tighten Exposure on High-Risk Segment

High-risk customers represent **~25% of the portfolio** but generate:

- **~60%+ of total defaults**

Actions leadership can take:

- Reduce credit limits  
- Increase risk-adjusted pricing (APR)  
- Apply stricter approval thresholds  

**Expected impact:**

- Material reduction in default losses  
- Improved risk-adjusted returns  
- Better capital efficiency  

---

## 6. Enterprise Risk (Fraud + Credit) — What Changed When Combined

### Findings

When **fraud exposure** was combined with **credit risk**, default separation improved further:

| Enterprise Risk Segment | Default Rate |
|------------------------|--------------|
| Low                    | ~5%          |
| Medium                 | ~18%         |
| High                   | ~68%         |

This separation is **stronger than credit risk alone**.

**Key observation:**

Customers who appeared acceptable based on credit metrics alone moved into the **high-risk segment** once fraud behavior was included.

This explains a large share of **unexpected losses** that traditional credit models miss.

---

## 7. Enterprise Risk Recommendation (Quantified)

### Recommendation 3 — Use Enterprise Risk for Portfolio Controls

The enterprise risk score identifies:

- A **~17% customer segment** with **~68% default probability**

Recommended actions:

- Apply enhanced monitoring  
- Trigger early interventions (verification, limits, collections)  
- Increase provisions for this cohort  

**Expected impact:**

- Earlier loss recognition  
- Reduced tail-risk events  
- Fewer “surprise” defaults  

---

## 8. Financial Forecasting — What the Numbers Say

### Forecast Scope

- **Target:** Bank Credit Outstanding  
- **Horizon:** 12 months  
- **Drivers:** Interest rates and consumer spending  

### Model Comparison

| Model              | Forecast Error (MAPE) |
|--------------------|-----------------------|
| ARIMAX             | ~0.7%                 |
| Time-aware XGBoost | ~2.5%                 |

ARIMAX error is approximately **3.5× lower** than the ML alternative.

In addition, ARIMAX provides **confidence intervals**, enabling planning across a realistic range of outcomes rather than relying on a single point estimate.

---

## 9. Forecasting Recommendation (Quantified)

### Recommendation 4 — Plan Using Forecast Ranges, Not Points

Using single-point forecasts hides uncertainty and creates false confidence.

Using forecast ranges enables:

- Downside planning  
- Capital buffer sizing  
- Stress scenario preparation  

**Expected impact:**

- Better liquidity planning  
- Fewer forecast surprises  
- Higher board-level confidence in financial projections  

---

## 10. What Leadership Should Do Differently Tomorrow

Based on the evidence from this analysis:

- **Stop treating fraud as a volume problem**  
  → It is a **loss concentration problem**

- **Stop evaluating credit risk in isolation**  
  → Behavioral fraud signals materially improve prediction  

- **Stop using single-number forecasts**  
  → Confidence bands matter more than marginal precision  

- **Adopt a single enterprise risk metric**  
  → Fragmented dashboards hide systemic risk  

---

## Final Note

This project demonstrates how combining **behavioral fraud signals**, **structural credit risk**, and **macroeconomic forecasting** produces a clearer, more actionable view of enterprise financial risk. The value lies not in model complexity, but in **where leadership focuses attention, capital, and intervention**.
