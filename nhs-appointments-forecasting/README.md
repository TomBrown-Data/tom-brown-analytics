# NHS GP Appointments: Demand, Missed Appointments & Forecasting

**Tools:** Python (pandas, matplotlib, statsmodels)  
**Focus:** Time series analysis · Service utilisation · Operational insights

---

## Problem

The NHS faces increasing pressure to expand capacity while operating under tight budget constraints. A key question is whether demand genuinely exceeds capacity, or whether existing resources could be used more efficiently.

This project analyses NHS GP appointment data to:
- understand utilisation trends over time,
- quantify the scale and impact of missed appointments (DNAs),
- and assess whether future demand risks exceeding current capacity.

---

## Data

The analysis uses NHS appointment records covering appointment volume, status, service setting, and appointment mode. Supplementary data includes limited appointment duration information and external contextual data from social media (Twitter/X).

**Limitations**
- Appointment duration data is incomplete across the full timeline.
- Capacity benchmarks are treated as reference estimates rather than fixed limits.
- Social data is used as contextual insight rather than causal evidence.

---

## Approach

1. Cleaned and aggregated appointment data to monthly level.
2. Analysed long-term trends, COVID disruption, and seasonal demand patterns.
3. Quantified missed appointments and compared attendance by appointment mode.
4. Built a SARIMAX time-series model to forecast short-term future demand.
5. Translated findings into operational recommendations.

---

## Key Insights

- Appointment demand rebounded strongly post-COVID and exceeds pre-pandemic levels, with clear winter seasonality.
- Missed appointments persist at ~4–5%, exceeding 1.5 million missed GP appointments in peak months.
- Remote appointments show slightly lower no-show rates than face-to-face consultations.
- Forecasting indicates that upcoming winter demand may approach effective capacity without intervention.

---

## Recommendations

1. Reduce DNAs via reminders and frictionless rescheduling.
2. Plan surge capacity ahead of predictable winter demand peaks.
3. Expand remote-first pathways where clinically appropriate.
4. Use public sentiment as a supplementary early-warning context signal.

---

## Why This Project Matters

This analysis demonstrates the ability to combine exploratory analysis, forecasting, and stakeholder-focused interpretation to inform public-sector decision-making.

Rather than assuming capacity expansion is the only solution, it highlights how efficiency gains — particularly reducing DNAs — can unlock significant value.

---

## Files

- `notebook.ipynb` – full reproducible analysis
