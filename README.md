# FiscalGuard: Sovereign Debt & Fiscal Resilience Analysis
**Predicting Africa's Fiscal Future using Data Science & Machine Learning**

## Project Overview
**FiscalGuard** is a comprehensive data science project designed to diagnose the root causes of sovereign debt crises in emerging African markets (with a focus on Nigeria, Egypt, and South Africa). 

Using a dataset of over **23,700 fiscal records**, this project moves beyond simple visualization to build an **Early Warning System (EWS)** for fiscal instability. It leverages diagnostic analytics to identify structural economic flaws—such as the "Growth Paradox" and "Efficiency Gaps"—and employs predictive modeling to forecast fiscal trajectories through 2030.

### 🎯 Key Objectives
* **Diagnose:** Uncover the mathematical drivers of budget deficits (e.g., the correlation between GDP Growth and Debt).
* **Predict:** Forecast future deficits under "Business as Usual" vs. "Reform" scenarios using Linear Regression.
* **Solve:** Propose a data-backed "Combined Strategy" (The 50/50 Rule) to reclaim fiscal space for the Sustainable Development Goals (SDGs).

---

## Tech Stack & Methodology
This project was built using Python and the following data science libraries:

* **Pandas:** For cleaning, standardizing, and aggregating 23,000+ rows of messy fiscal data (handling mixed currencies and units).
* **Seaborn & Matplotlib:** For exploratory data analysis (EDA) and generating publication-ready visualizations of economic trends.
* **Scikit-Learn:** For building the **Anomaly Detection** model (Z-Score) and **Linear Regression** forecasting models.
* **Numpy:** For high-performance numerical calculations in the simulation engine.

---

## Key Insights & Findings

### 1. The "Jaws of Deficit" (Structural Divergence)
Our analysis revealed a critical decoupling in Nigeria's economy:
* **Expenditure** has grown exponentially while **Revenue** has remained linear.
* This created a structural deficit that widens regardless of oil price shocks.
* *Insight:* The deficit is not cyclical; it is systemic.

### 2. The "Growth Paradox"
* **Correlation Analysis:** We found a strong **negative correlation (-0.91)** between GDP Growth and Fiscal Balance.
* *Meaning:* As the economy grows, the deficit gets *worse*. This proves a "Hollow Growth" model where economic expansion happens in untaxed sectors, costing the government more to govern than it generates in revenue.

### 3. The Efficiency Trap
* **Correlation:** A near-perfect **-0.99 correlation** between Expenditure and Deficit.
* *Meaning:* Zero efficiency leverage. Every unit of spending creates an equivalent unit of debt.

### 4. Crowding Out Human Capital
* **SDG Impact:** "State Security" has cannibalized "Human Security." Defence spending now nearly doubles Health spending, directly undermining SDG 3 (Health) and SDG 4 (Education).

---

## Predictive Modeling (The "Cone of Possibility")
We simulated Nigeria's fiscal path to 2030 under three scenarios:

1.  **🔴 Business as Usual (BAU):**
    * *Result:* Deficit widens to **~47 Trillion NGN** by 2030.
    * *Verdict:* Fiscal Collapse.

2.  **🟠 Revenue-Only / 🔵 Cuts-Only:**
    * *Result:* Single-sided reforms fail to close the gap significantly.

3.  **🟢 The FiscalGuard Strategy (Recommended):**
    * *Approach:* +50% Revenue Efficiency AND -50% Recurrent Expenditure Growth.
    * *Result:* Deficit reduces to **~32 Trillion NGN**.
    * *Impact:* **Cumulative Saving of 15 Trillion NGN** by 2030.

---

## 📂 Repository Structure
```bash
├── data/
│   └── 10Alytics_Fiscal_Data.csv    # Raw dataset (Cleaned version used in code)
├── notebooks/
│   └── FISCAL DATA ANALYSIS AND PREDICTON.ipynb   # Full analysis (Cleaning -> EDA -> ML)
├── visuals/
│   ├── nigeria_trends.png           # "Jaws of Deficit" Chart
│   ├── correlation_matrix.png       # Drivers of Instability Heatmap
│   ├── anomaly_detection.png        # AI Shock Detection Chart
│   └── forecast_2030.png            # The "Cone of Possibility" Prediction
├── README.md                        # Project Documentation
└── requirements.txt                 # Python dependencies
