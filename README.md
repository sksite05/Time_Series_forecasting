# Critical Mineral Import Forecasting & Risk Analysis (India)

## Project Summary

This project analyzes India’s **import dependency and future supply risk** for three critical minerals — **Lithium, Copper, and Graphite** — using historical EXIM trade data and time-series forecasting. These minerals are central to India’s energy transition, electric mobility, and industrial growth, yet remain highly import-dependent.

The study integrates **trade analytics, forecasting, dependency metrics, supplier concentration analysis, and statistical validation** to provide a structured, data-driven assessment of mineral supply vulnerability.  
Developed as part of a **Critical Mineral Forecasting Hackathon**.

---

## Key Questions Addressed

- How dependent is India on imports for critical minerals?
- How will import demand evolve over the next **12 and 36 months**?
- Which minerals face the **highest supply risk**?
- Are trade patterns statistically different across minerals?
- What strategic actions can reduce long-term vulnerability?

---

## Data & Tools

### Data Sources
- **DGCI&S Foreign Trade Data Dissemination Portal** (monthly EXIM data, 2018–2024)
- **TRADESTAT** (Ministry of Commerce & Industry)
- **Indian Minerals Yearbook (IBM)** – contextual reference

### Tools & Methods
- Python (Pandas, NumPy, Matplotlib, Statsmodels)
- Time-series forecasting: Naive, ARIMA, SARIMA
- Model evaluation: MAPE, MAE, RMSE
- Statistical validation: One-way ANOVA

---

## Methodology Overview

1. Exploratory analysis of historical import trends  
2. Trend and seasonality decomposition  
3. Model selection and forecasting (12M & 36M horizons)  
4. Import dependency and trade balance analysis  
5. Country concentration (supplier risk) assessment  
6. Integrated risk matrix construction  
7. Statistical validation using ANOVA  

---

## Key Insights

### Lithium
- Near-total import dependency  
- Highly concentrated supplier base  
- Strong, predictable growth in future imports  
- **Highest supply risk**

### Graphite
- Persistently high import dependency  
- Concentrated sourcing  
- Moderate but sustained demand growth  
- **High supply risk**

### Copper
- Rising import dependency  
- High volatility and forecast uncertainty  
- Relatively diversified sourcing  
- **Medium-to-high supply risk**

ANOVA results confirm that import behavior differs significantly across minerals, justifying **mineral-specific strategies**.

---

---

## Outcomes

- Forecasted import demand for critical minerals (12M & 36M)
- Quantified import dependency and supplier concentration risk
- Ranked minerals using an integrated risk matrix
- Delivered actionable policy and strategy insights

---

## Future Scope

- Integration of domestic production and recycling data  
- Inclusion of exogenous variables (prices, policy, global demand)  
- State-level extraction and value-chain mapping  
- Interactive decision-support dashboard  

---

