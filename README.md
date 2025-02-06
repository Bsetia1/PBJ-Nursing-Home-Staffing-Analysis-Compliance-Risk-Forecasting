# PBJ-Nursing-Home-Staffing-Analysis-Compliance-Risk-Forecasting

# Project Overview
This project analyzes nursing home staffing trends, compliance with CMS regulations, workforce stability, and future staffing risks using Payroll-Based Journal (PBJ) staffing data and nursing home provider information. The objective is to provide data-driven insights into:

📉 Staffing compliance & violations
📊 Workforce stability & contract staffing utilization
📈 Trends in staffing deviations by facility size & state
🔮 Predictive modeling to forecast staffing shortages

# Datasets Used
1️⃣ PBJ Staffing Data (Payroll-Based Journal)
- Daily nurse staffing hours recorded for RNs, LPNs, and CNAs
- MDS census counts (number of residents per day)
- Used to analyze staffing compliance, workforce deviations, and contract staffing utilization
2️⃣ Provider Information Data
- Facility-level metadata: Provider name, state, ownership type
- Regulatory history: Fines paid, citations, penalties
- Used to link staffing trends with regulatory non-compliance and financial impact

# Analysis Conducted
1. CMS Compliance Analysis
✅ Objective: Identify facilities falling below CMS staffing requirements (3.48 Hours Per Resident Day - HPRD).
🔎 Findings:

Numerous facilities fall below the 3.48 HPRD threshold, increasing penalty risks.
The most severely non-compliant facilities are at risk of fines and citations.

2. Workforce Stability & Contract Utilization Analysis
✅ Objective: Identify facilities with extreme staffing fluctuations but low contract staffing usage (≤20%).
🔎 Findings:

Many unstable facilities are not leveraging contract staffing, leading to inefficiencies.
The top 10 most unstable facilities accounted for $22,292,277.82 (0.05%) in fines paid.
Underutilization of contract nurses presents a sales opportunity for staffing solutions.

3. Facility Size & State-Level Trends
✅ Objective: Analyze staffing compliance by facility size.
🔎 Findings:

Large facilities (>150 residents) have the highest violation rates (43%).
Medium-sized facilities (50-150 residents) show 41% violation rates.
Small facilities (<50 residents) have the lowest violation rates (28%), indicating more stable staffing.
4️⃣ Predictive Staffing Analysis (ARIMA Forecasting)
✅ Objective: Forecast future staffing trends & predict compliance risks.
🔎 Findings:

Forecasting models indicate continued seasonal staffing fluctuations.
Many facilities are projected to remain non-compliant, reinforcing the need for proactive staffing solutions.

# Key Business Recommendations
This analysis supports data-driven staffing strategies for nursing homes, focusing on cost reduction, workforce optimization, and compliance solutions.

**Recommendation 1:** Staffing Strategy for Top 10 High-Deviation Facilities
- Overstaffed facilities → Offer cost-saving contract models
- Understaffed facilities → Offer on-demand staffing to avoid compliance issues

**Recommendation 2:** Targeting High-Instability Facilities with Low Contract Utilization (<20%)
- Facilities with high staffing deviations & low contract utilization should adopt dynamic workforce solutions.
- The top 10 most unstable facilities paid $22.2M in fines, indicating a high-risk, high-need market.

**Recommendation 3:** Flagged Non-Compliant Facilities based on CMS Benchmarks
- Target high-risk, non-compliant facilities to help them avoid CMS penalties with flexible staffing models.

**Recommendation 4:** Facility-Specific Strategy Based on Size and Risk Forecasting
- Large facilities (>150 residents) need scalable solutions.
- Medium facilities (50-150 residents) need predictive staffing models.
- Small facilities with worsening trends require intervention before compliance risks increase.

# Technical Implementation
  Technologies Used
  - Data Analysis: Pandas, NumPy, Matplotlib, Seaborn
  - Forecasting: ARIMA time series modeling (Statsmodels, Pmdarima)
  - Data Visualization: Seaborn, Matplotlib, Plotly
  - SQL Queries: Analyzed facility staffing trends using structured queries

# How To Use:
1. Clone the repository:
   ```bash
   git clone https://github.com/Bsetia1/A-B-Testing-Marketing-Campaign.git
