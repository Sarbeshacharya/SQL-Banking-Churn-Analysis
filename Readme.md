# Banking Customer Churn Analysis & Retention Strategy  
**End-to-End SQL Analytics Project**

![SQL](https://img.shields.io/badge/SQL-MySQL-blue?style=for-the-badge&logo=mysql)
![Status](https://img.shields.io/badge/Status-Complete-success?style=for-the-badge)
![Analysis](https://img.shields.io/badge/Customers-10000-orange?style=for-the-badge)

> I analyzed 10,000 bank customers and found something that challenges everything banks believe about customer loyalty. 

---

**Project Duration:** December 2025 – April 2026  
**Dataset:** 10,000 bank customers (Kaggle – Bank Churn Modelling)  
**Tools:** MySQL 8.0  
**My Role:** Aspiring Banking Data Analyst (BSc IT 4th Semester)

---

### Executive Summary

I performed a full end-to-end analysis on 10,000 bank customers to uncover why customers churn, quantify financial loss, and recommended practical retention strategies.  

Using advanced SQL (CTEs, Window Functions, RFM, Cohort Analysis, CLV Modelling, Risk Scoring), I identified actionable insights that can help reduce churn from **20.37% to below 15%**.

**Key Business Impact**  
- Churned customers: **2,037** (20.37%)  
- Annual revenue at risk: **$3.71 Million**  
- CLV lost to churn: **$47.5 Million** (23.37% of total portfolio)  
- Highest risk segments: Germany + customers aged 41+

---

### Key Insights & Findings

**1. Germany Crisis (Highest Priority)**  
Germany churn rate: **32.44%** — nearly double France (16.15%) and Spain (16.67%).

**2. Age Paradox**  
Customers aged 41+ represent only 37% of the base but **70% of all churn**.  
Age 51-60 churn rate: **56.21%**.

**3. Product Complexity Paradox**  
- 1 product → 27.71% churn  
- 2 products → **7.58% churn** (sweet spot)  
- 3 products → 82.71% churn  
- 4 products → **100% churn**

**4. Inactive Member Crisis**  
Inactive members (48.5% of base) churn at **26.85%** vs 14.27% for active members.

**5. Cohort Analysis (Favourite Query)**  
Tenure-based lifecycle analysis showed:  
- 0–2 years: 21.15% churn  
- 6–8 years: **18.87% churn** (sweet spot – most loyal)  
- 9+ years: 21.30% churn (churn rises again)

**6. RFM Segmentation (Favourite Query)**  
Built RFM model (Recency = Tenure, Frequency = NumOfProducts, Monetary = Balance + Salary) and created clear business segments (High-Value Loyal, At-Risk High-Balance, Young Digital, Senior Low-Activity).

**7. CLV & Cross-Sell Opportunity**  
Calculated Customer Lifetime Value and identified high-balance, low-product customers as prime cross-sell targets.

---

### Financial Impact Summary

- Total Deposits Lost: $185.7M  
- Revenue at Risk: $206.7M  
- Expected Annual Loss: $3.71M  
- CLV at Risk: $47.5M

---

### Top Recommended Actions (With Estimated ROI)

1. **Germany Rescue Program** → Investment $600K | ROI ~13:1  
2. **Senior Engagement Initiative (Age 51-60)** → Investment $350K | ROI ~15:1  
3. **Cross-Sell Optimization (1→2 products)** → Investment $500K | ROI ~30:1  
4. Loyalty programs for 6-8 year “sweet spot” cohort  
5. Targeted reactivation campaigns for inactive high-value customers

---

### Technical Skills Demonstrated
- Advanced SQL: CTEs, Window Functions (NTILE, RANK), CASE, Subqueries  
- Analytics: RFM, Cohort Analysis, Risk Scoring, CLV Modelling  
- Business Thinking: Revenue impact, customer segmentation, ROI-based recommendations

### Project Structure
- Section 1: Foundation & Data Quality  
- Section 2: Pattern Finding  
- Section 3: Business Insights & Risk Scoring  
- Section 4: RFM & Customer Segmentation  
- Section 5: Advanced Analytics (Cohort, CLV, Cross-Sell)

**Total Queries:** 22+ | **Total Insights:** 50+

### Deliverables
- Complete SQL script with full documentation  
- Excel dashboard with interactive visualisations (coming soon)  
- Actionable recommendations with ROI projections

### Learning Outcomes
This was my first major project. I learned how to go from raw data → business insights → clear recommendations. I now understand that the best analytics challenge assumptions (like the “more products = more loyalty” myth).

**Special Thanks**  
To **Luke Barousse** and **Alex The Analyst** — your tutorials made this possible.

---

**Connect with me**  
Actively looking for **Junior Data Analyst / MIS / Banking Analytics** roles in Nepal.

Email: sarbeshacharya45@gmail.com  
LinkedIn: https://www.linkedin.com/in/sarbesh-acharya-93a3251b4  
GitHub: github.com/Sarbeshacharya

---

**Tags:** #BankingAnalytics #CustomerChurn #SQL #RFM #CohortAnalysis #CLV #DataAnalysis #Fintech #Excel
