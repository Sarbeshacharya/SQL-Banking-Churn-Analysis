BANKING CUSTOMER CHURN ANALYSIS PROJECT DOCUMENTATION

1. PROJECT TITLE

Banking Customer Churn Analysis using SQL and Excel Dashboard


2. PROJECT OBJECTIVE

The objective of this project is to analyze customer churn in a banking dataset using SQL and Microsoft Excel. The project focuses on identifying customer groups with higher churn risk, measuring financial exposure through CLV at Risk and Revenue at Risk, and providing business recommendations to improve customer retention.

This project combines SQL analysis, Excel data cleaning, pivot tables, pivot charts, slicers, KPI cards, RFM segmentation, risk scoring, CLV at Risk analysis, and an interactive Excel dashboard.


3. DATASET OVERVIEW

The dataset contains information about 10,000 bank customers. It includes demographic, financial, product usage, and churn-related information.

The target variable used in this project is Exited.

Exited = 1 means the customer churned.
Exited = 0 means the customer was retained.

Main fields used in the project include:

CustomerId
CreditScore
Geography
Gender
Age
Tenure
Balance
NumOfProducts
HasCrCard
IsActiveMember
EstimatedSalary
Exited


4. TOOLS USED

SQL:
Used for initial churn analysis, customer segmentation, cohort analysis, RFM logic, risk analysis, and business insight extraction.

Microsoft Excel:
Used for data cleaning, calculated columns, pivot tables, pivot charts, slicers, KPI cards, dashboard creation, and documentation.

Pivot Tables:
Used to summarize churn rate, customer count, CLV at Risk, and Revenue at Risk across different customer segments.

Pivot Charts:
Used to visualize churn patterns and financial risk.

Slicers:
Used to make the Excel dashboard interactive.

Excel Formulas:
Used to create calculated fields such as Churn Status, Age Group, Balance Tier, CLV Estimate, CLV at Risk, Revenue at Risk, Risk Score, and Risk Status.


5. DATA CLEANING AND PREPARATION

The raw banking churn dataset was loaded into Excel and transformed into a clean analysis-ready dataset.

The following cleaning and preparation steps were performed:

1. Raw data was loaded into Excel.
2. A clean data sheet was created for analysis.
3. Churn Status was created from the Exited column.
4. Age Group was created to group customers by age bands.
5. Balance Tier was created to classify customers based on account balance.
6. Tenure Cohort was created to group customers by relationship length.
7. Card Status was created from the HasCrCard column.
8. Active Status was created from the IsActiveMember column.
9. Revenue Value was calculated for customer-level revenue analysis.
10. CLV Estimate was calculated to estimate customer lifetime value.
11. CLV at Risk was created to measure CLV associated with churned customers.
12. Revenue at Risk was created to measure revenue associated with churned customers.
13. Risk Score was created using churn-related customer characteristics.
14. Risk Status was created to classify customers into Low, Medium, High, and Emergency risk groups.
15. RFM Segment was created to classify customers based on relationship, product usage, and monetary value.


6. KEY CALCULATED FIELDS

Churn Status:
Readable churn label created from the Exited column.

Age Group:
Customer age categories used to analyze churn by age segment.

Balance Tier:
Customer balance categories used to analyze financial risk by balance level.

Tenure Cohort:
Customer lifecycle group based on tenure with the bank.

Revenue Value:
Estimated revenue value used for business impact analysis.

Revenue at Risk:
Revenue value counted only for churned customers.

CLV Estimate:
Estimated Customer Lifetime Value.

CLV at Risk:
CLV estimate counted only for churned customers.

Risk Score:
Numeric score used to estimate customer churn risk.

Risk Status:
Risk category based on Risk Score, such as Low Risk, Medium Risk, High Risk, and Emergency.

RFM Segment:
Customer segment based on RFM-style logic using available customer relationship, product, and monetary fields.


7. ANALYSIS PERFORMED

The project includes the following analysis areas:

Geography Analysis:
Used to identify which countries have higher churn rates and higher CLV at Risk.

Gender Analysis:
Used to compare churn behavior between male and female customers.

Age Group Analysis:
Used to identify customer age groups with higher churn risk.

Product Analysis:
Used to analyze churn based on the number of bank products used by customers.

Credit Card Analysis:
Used to compare churn between customers with and without credit cards.

Engagement Analysis:
Used to analyze churn based on active or disengaged customer behavior.

Balance Tier Analysis:
Used to measure churn and CLV at Risk across different customer balance groups.

Tenure Cohort Analysis:
Used to analyze churn across customer lifecycle stages.

Risk Score Analysis:
Used to understand how churn rate changes with increasing risk scores.

Risk Status Analysis:
Used to group customers into business-friendly risk categories.

RFM Segment Analysis:
Used to identify valuable and at-risk customer segments.

CLV at Risk Analysis:
Used to measure the financial exposure created by churned customers.


8. DASHBOARD OVERVIEW

An interactive Excel dashboard was created to summarize the most important churn and financial risk insights.

The dashboard includes:

KPI cards
Slicers
Pivot charts
CLV at Risk charts
RFM segment chart
Business recommendation table

Dashboard KPI cards include:

Total Customers:
Shows the total number of customers in the dataset.

Churned Customers:
Shows the number of customers who exited.

Churn Rate:
Shows the overall percentage of churned customers.

CLV at Risk:
Shows the estimated customer lifetime value associated with churned customers.

Revenue at Risk:
Shows the estimated revenue value associated with churned customers.

Dashboard slicers include:

Geography
Gender
Age Group
Risk Status
NumOfProducts
Balance Tier
RFM Segment

These slicers allow users to interactively filter the dashboard and explore churn patterns across different customer segments.


9. MAIN DASHBOARD VISUALS

The final dashboard includes the following visuals:

1. Churn Rate by Geography
2. Customers and Churn Rate by Age Group
3. Churn Rate by Number of Products
4. Churn Rate by Engagement Status
5. Churn Rate by Tenure Cohort
6. CLV at Risk by Balance Tier
7. CLV at Risk by Risk Status
8. CLV at Risk by RFM Segment
9. CLV at Risk by Number of Products
10. Key Findings and Business Recommendations


10. KEY FINDINGS

The analysis produced the following key findings:

1. Germany has the highest churn rate compared to other geographies.
2. Older customer groups show higher churn tendency.
3. Product count has a strong relationship with churn behavior.
4. Disengaged or inactive customers are more likely to churn.
5. High-balance customers carry higher financial risk when they churn.
6. High Risk and Emergency Risk customers contribute significantly to CLV at Risk.
7. RFM segmentation helps identify valuable customer groups that require targeted retention.
8. CLV at Risk provides better business context than churn count alone because it shows the financial impact of churn.


11. BUSINESS RECOMMENDATIONS

Based on the analysis, the following business actions are recommended:

1. Launch geography-specific retention campaigns for high-churn regions.
2. Provide senior-friendly support, loyalty benefits, and personalized service for older customers.
3. Run reactivation campaigns for disengaged or inactive customers.
4. Prioritize high-balance and high-CLV customers for retention outreach.
5. Use product-based strategies to improve customer stickiness and reduce churn.
6. Focus retention budget on High Risk and Emergency Risk customers.
7. Use RFM segmentation to design targeted offers for different customer groups.
8. Monitor CLV at Risk regularly to prioritize customers with the highest financial impact.


12. PROJECT WORKFLOW

The project followed this workflow:

1. SQL analysis was performed to explore customer churn patterns.
2. Raw banking churn data was loaded into Excel.
3. Data was cleaned and transformed into an analysis-ready format.
4. Calculated columns were created for churn, risk, CLV, revenue, and segmentation.
5. Pivot tables were created for each analysis area.
6. Pivot charts were built to visualize churn patterns and financial risk.
7. CLV at Risk and Revenue at Risk were added to measure business impact.
8. RFM segmentation was added for advanced customer segmentation.
9. A dashboard source sheet was created for interactive dashboard pivots.
10. KPI cards were linked to pivot outputs.
11. Slicers were connected to dashboard pivots and KPI cards.
12. An interactive Excel dashboard was designed.
13. Key findings and business recommendations were summarized.


13. LIMITATIONS

This project uses a sample banking churn dataset. Some business values such as Revenue Value, CLV Estimate, Revenue at Risk, and CLV at Risk are estimated for analytical and portfolio demonstration purposes.

The dataset does not include:

Transaction history
Actual bank revenue records
Customer complaint history
Marketing campaign data
Customer service interaction records
Branch-level service data
Real customer contact history
Transaction dates

Because transaction-level dates are not available, the RFM segmentation uses available proxy variables such as Tenure, NumOfProducts, Balance, and EstimatedSalary.

Therefore, the results should be interpreted as an analytical simulation and portfolio project rather than a final production-level banking model.


14. CONCLUSION

This project demonstrates how SQL and Microsoft Excel can be used together to perform customer churn analysis for a banking business.

The final dashboard highlights customer churn patterns, CLV at Risk, Revenue at Risk, risk segmentation, RFM segmentation, and business recommendations for customer retention.

The project demonstrates skills in:

SQL analysis
Excel data cleaning
Pivot tables
Pivot charts
Interactive dashboard design
Slicer-based filtering
KPI card creation
CLV at Risk analysis
Revenue at Risk analysis
RFM segmentation
Risk scoring
Business recommendation writing

Overall, this project helps identify which customer groups are more likely to churn, which segments create the highest financial risk, and where the bank should prioritize retention efforts.
