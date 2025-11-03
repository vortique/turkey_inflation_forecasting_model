# 🇹🇷 Turkey Inflation Trend Forecasting (2015–2025)

This project analyzes and forecasts the inflation rate (TÜFE) in Turkey using time series trend modeling.  
The main goal is not just to predict numbers, but to **understand how inflation dynamics evolve over time** and **how statistical models can detect turning points** in an unstable economy.

---

## 📊 Project Overview

The dataset covers the period **from January 2015 to November 2025**.  
While early years (2015–2019) were relatively stable, the model captures how inflation **started rising around early 2023** and has continued to accelerate since then.

The project uses **trend decomposition** and **forecasting models** to analyze the underlying patterns in Turkey’s inflation data.

---

## 🧠 Objectives

- Analyze historical inflation (TÜFE) data from 2015–2025  
- Extract **trend**, **seasonal**, and **residual** components  
- Forecast the future inflation trend for the next 1–2 years  
- Compare the model’s predictions to **real-world inflation data**  
- Discuss economic interpretation of trend changes

---

## 📈 Model Summary

The model was trained on **10 years of monthly inflation data**.  
Trend decomposition showed that:
- From **2015 to late 2022**, actual inflation and the model’s trend line were significantly different (indicating a stable and predictable economy).
- After **early 2023**, the actual inflation curve started converging with the model’s trend — a sign of **systemic inflation acceleration**.
- Eventually, both lines intersected, meaning the economy was no longer returning to the old trend but **adopting a new high-inflation equilibrium**.

---

## 🔮 Forecast Results

The forecast suggests the following pattern for upcoming years:

- 📅 **2025–2026:** Continued increase in inflation  
- 🕒 **Mid-2026:** Slight slowdown in the rate of increase (temporary stabilization)  
- 🚀 **Late 2027:** Another sharp surge in inflation levels  

While this is **not a literal economic prediction**, it reflects the **pattern recognition** ability of the model based on the data it has seen.

---

## 📉 Interpretation

Interestingly, when inflation began to rise sharply in real life,  
the model’s predicted trend line **moved closer to the actual data**, showing that statistical forecasting can adapt faster when the system becomes more volatile.

This demonstrates:
- Models trained on **stable periods** may underperform during economic shifts  
- But as volatility increases, **the model’s error margin decreases**, since the direction becomes more predictable (always upward)

---

## References
- Turkish Statistical Institute (TÜİK) — [https://data.tuik.gov.tr](https://data.tuik.gov.tr)
- Central Bank of the Republic of Turkey (TCMB) — [https://www.tcmb.gov.tr](https://www.tcmb.gov.tr)
- Prophet Documentation — [https://facebook.github.io/prophet/docs](https://facebook.github.io/prophet/docs)

---

## 🧑‍💻 Author

[Me!](https://github.com/vortique)

---

> ⚠️ Disclaimer:
> This project is for educational purposes only.
> The forecasts shown here are not investment or policy advice — they represent a machine learning perspective on Turkey’s inflation trend.

