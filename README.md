Note: This is an independent portfolio/practice project inspired by modern fintech dashboard design patterns. It is not affiliated with or endorsed by Niyo. All transaction data used in this project is synthetic/sample data created for analytics and visualization purposes.


Finance Transactions Analytics Dashboard (Power BI)

Project Overview:

An end-to-end Power BI analytics dashboard built to analyze 50,000 banking transactions across 3,983 customers and 7,987 accounts between January 2023 and April 2026.
The project was designed to simulate how a finance operations or payments analytics team would monitor:
Transaction performance and revenue trends.
Fraud and high-risk activity.
Transaction-level operational analysis.
Customer purchase frequency and retention behavior.
The dashboard combines financial analytics, fraud monitoring, customer behavior analysis, and operational reporting into a single connected reporting solution powered by advanced DAX calculations and a star-schema data model.

Business Problem
Finance and payment platforms process thousands of transactions daily across multiple customer segments, payment channels, and merchant categories.
Business stakeholders need centralized visibility into three key areas:
1. Business Performance
Are transaction volumes and revenue growing?
Which channels and customer segments contribute most?
2. Fraud & Risk Monitoring
Where is fraud concentrated?
Which payment channels and merchant categories carry the highest risk?
3. Customer Retention & Purchase Frequency
Are customers transacting repeatedly?
Which customers are becoming inactive over time?

The dashboard follows a star-schema architecture with:

Transaction Fact Table,
Customer Dimension,
Calendar Table,

The model supports:
Time-intelligence analysis,
Customer segmentation,
Fraud monitoring,
Dynamic KPI reporting,
Purchase-frequency analytics.

A Dynamic Metric Field Parameter was implemented to allow users to switch KPI visuals between different business metrics without duplicating charts or measures, improving scalability and report usability.

Dashboard Pages
1. Executive Overview
The executive summary page provides a high-level view of transaction performance and revenue trends.
Features
KPI Cards with YoY comparisons
Monthly transaction trends
Customer segment analysis
Transaction status breakdown
Geographic transaction analysis
Transaction-type performance
Dynamic KPI switching using field parameters
Key KPIs
Total Transaction Amount
Total Transactions
Average Transaction Value
Total Fees
Total Tax

2. Transactions Analysis
A detailed operational page designed for transaction-level investigation and drill-down analysis.
Features
Fully sortable transaction table
Transaction filtering by status, segment, and type
Drill-through analysis
Transaction cohort investigation
Dynamic KPI re-contextualization based on filters
This page simulates how operations analysts investigate transaction anomalies and customer activity.

3. Fraud & Risk Monitoring
A risk analytics page focused on fraud concentration and high-risk transaction behavior.
Features
Fraud transaction monitoring
Fraud amount analysis
Fraud trends over time
Channel-level fraud analysis
Merchant-category fraud analysis
State-wise fraud concentration
Key Findings
ATM and POS channels showed the highest fraud concentration
Rent, Utilities, and Insurance categories carried elevated fraud rates
Fraud spikes became visible through time-series analysis

4. Customer Purchase Frequency & Retention
A customer-behavior analytics page built around recency and frequency analysis.
Features
Repeat customer analysis
Purchase frequency segmentation
Average days between purchases
Customer recency monitoring
Frequency vs recency scatter analysis
Frequent shopper segmentation
Business Value

The page helps identify:
High-frequency customers
Customers becoming inactive
Retention opportunities
Re-engagement targets
Advanced DAX Measures

Key Insights
The platform processed over ₹45.5 Crore (~$5.4M) in transaction value.
Approximately 89.4% of transactions succeeded successfully.
Overall fraud rate remained low at 1.26%.
Nearly 99.7% of customers were repeat customers.
Around 90% of customers qualified as frequent shoppers with 5+ transactions.
Repeat customers transacted approximately every 123 days on average.
Maharashtra, Karnataka, and Gujarat led in both transaction volume and fraud amount.

The recency-frequency analysis helped surface previously active customers who had become inactive — enabling potential retention and re-engagement strategies.

Business Recommendations
Strengthen fraud controls for ATM and POS channels.
Monitor merchant categories with elevated fraud rates.
Launch re-engagement campaigns for inactive high-frequency customers.
Prioritize loyalty programs for repeat customers.
Improve transaction success rates in high-risk payment categories.

Dashboard Screenshots
Executive Overview
<img width="1392" height="747" alt="image" src="https://github.com/user-attachments/assets/4820068d-873a-49f9-a108-d7b9cccebad3" />

Transactions Analysis
<img width="1377" height="740" alt="image" src="https://github.com/user-attachments/assets/6c01e5c3-65e9-49f7-af96-3cf16b9e2aec" />

Fraud & Risk Dashboard
<img width="1320" height="747" alt="image" src="https://github.com/user-attachments/assets/8e88944b-6fe2-4ffe-a2ca-cabbb30fd639" />

Customer Purchase Frequency Dashboard
<img width="1331" height="742" alt="image" src="https://github.com/user-attachments/assets/47c05b1b-e873-47bd-a91d-81e5c9b45cc9" />



