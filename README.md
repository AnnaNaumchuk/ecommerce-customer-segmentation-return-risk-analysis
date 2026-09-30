# ecommerce-customer-segmentation-return-risk-analysis
End-to-end e-commerce analytics project focused on customer segmentation, profitability, return risk, and business performance.

E-Commerce Sales & Customer Analysis
Junior Data Analyst Portfolio Project
Tools: Python, Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn, Power BI

Power BI Report:  https://app.powerbi.com/links/07yNuYp0dv?ctid=6eaa7d22-d277-4af8-9353-6e757a699301&pbi_source=linkShare&bookmarkGuid=4647af53-541d-42bb-b500-a8dc02dec2cf

1. Project Overview
This project is an end-to-end e-commerce data analytics project focused on understanding sales performance, customer behavior, profitability, and product return risk.
The project combines Python-based data analysis and machine learning with an interactive Power BI dashboard to transform raw e-commerce data into meaningful business insights.
The analysis covers 34,500 orders and 7,903 customers and focuses on identifying high-value customers, customer segments, profitability issues, and factors related to product returns.

2. Business Objectives
The main objectives of the project were to:
Analyze overall sales and profitability performance.
Identify the most valuable customer segments.
Understand customer purchasing behavior.
Segment customers using RFM analysis and K-Means clustering.
Analyze product returns and their impact on revenue and profitability.
Identify loss-making orders and potential profit leakage.
Estimate return risk using a machine learning model.
Build an interactive Power BI dashboard for business reporting.

3. Data Analysis with Python
Python was used as the main tool for data preparation, exploratory data analysis, customer segmentation, and return risk analysis.
The workflow included:
Data loading and initial inspection.
Data quality and consistency checks.
Exploratory Data Analysis (EDA).
Sales and profitability analysis.
Customer-level aggregation.
RFM analysis.
Customer segmentation using K-Means clustering.
Return risk analysis using Random Forest.
Analysis of loss-making orders and profit leakage.
KPI calculation and validation for Power BI.
The main Python libraries used were:
Pandas — data manipulation and analysis
NumPy — numerical operations
Matplotlib — visualization
Seaborn — exploratory visualization
Scikit-learn — clustering and machine learning

4. Customer Segmentation
RFM analysis was used to evaluate customers based on:
Recency — how recently a customer made a purchase.
Frequency — how often a customer placed an order.
Monetary — how much revenue a customer generated.
K-Means clustering was then applied to identify groups of customers with similar purchasing behavior.
The resulting customer segments were used to understand differences in customer value and identify groups that may require different business strategies.
Customer Segmentation
[INSERT SCREENSHOT – RFM / K-Means analysis]

5. Return Risk Analysis
The project also included an analysis of customer order returns.
A Random Forest model was used to explore return risk based on available order and customer characteristics.
The analysis focused on identifying patterns associated with returned orders and understanding which factors may contribute to higher return risk.
Return analysis was also connected with profitability to identify potential financial impact from returned orders.
Return Risk Analysis
[INSERT SCREENSHOT – Random Forest / Return Risk analysis]

6. Profitability & Loss Analysis
Profitability was analyzed at the order level to identify orders that generated negative profit.
The analysis showed:
Total Revenue: approximately $5.87M
Total Profit: approximately $970K
Loss-making Orders: 6,104
Loss-making Order Rate: 17.69%
Returned Orders: 1,903
Return Rate: 5.52%
Returned Revenue: approximately $389K
These metrics were used to identify areas where returns, shipping costs, discounts, and other order characteristics may contribute to profit leakage.
Profitability Analysis
[INSERT SCREENSHOT – Profit / Loss analysis]

7. Power BI Dashboard
The results of the Python analysis were used to build an interactive Power BI dashboard.
The dashboard provides a business-oriented view of:
Sales performance
Revenue and profit
Customer segments
Customer value
Return rate
Returned revenue
Loss-making orders
Return risk



<img width="1363" height="768" alt="Снимок экрана 2026-09-30 200003" src="https://github.com/user-attachments/assets/36ae993b-1f04-4789-88ed-0fc35737625b" />
<img width="1738" height="991" alt="Снимок экрана 2026-09-30 195917" src="https://github.com/user-attachments/assets/854c750a-b3b2-4629-b554-b2965672fb78" />
<img width="1755" height="982" alt="Снимок экрана 2026-09-30 195925" src="https://github.com/user-attachments/assets/006a142e-9670-4a9d-99d1-546497447685" />


Regional and category performance
The dashboard is designed to allow users to explore the data through interactive filters and visualizations.
