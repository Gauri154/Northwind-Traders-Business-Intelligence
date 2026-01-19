# Northwind-Traders-Business-Intelligence
Engineered an end-to-end **BI framework** using Joins, CTEs and Window Functions to transform raw transactional data into actionable growth, retention, and operational metrics. This project simulates a real-world Business Analyst workflow, tracking MoM growth across 830+ orders, segmenting 90+ customers for churn risk, and automating margin protection for 75+ products.

**Business Pillars & Key Insights -**

**1. Growth & Financial Performance**
**Metric:** Month-over-Month (MoM) Revenue Growth.
**Logic:** Built dynamic CTEs to calculate monthly revenue and utilized LAG() functions to determine growth percentage trends.
**Value:** Provides leadership with a clear view of seasonal performance and cumulative revenue health (Running Totals).

**2. Customer Retention & Loyalty (Churn Analysis)**
**Metric:** Customer Re-order Frequency.
**Logic:** Developed DATEDIFF and LAG pipelines to identify the gap between orders for 90+ unique customers.
**Value:** Enables the marketing team to identify "at-risk" customers and trigger automated retention campaigns.

**3. Operational Efficiency & Margin Protection**
**Metric:** Shipper ROI & Discontinued Product Management.
**Logic:** Used subquery-driven audits to flag shipping costs above the company average and implemented UPDATE triggers to zero-out discounts on discontinued items.
**Value:** Minimizes logistical waste and prevents profit leakage on low-stock/retired inventory.

**4. Sales Attribution & Strategic Ranking**
**Metric:** Top Employee Category Performance.
**Logic:** Applied RANK() OVER and PARTITION BY across 5+ tables to attribute revenue to specific employees within each product category.
**Value:** Informs HR and Sales Managers on high-performing staff to optimize commission structures and training.

**Technical Stack & Skills**
**Tool:** MySQL Workbench.
**Advanced SQL:** CTEs, Window Functions (RANK, DENSE_RANK, SUM OVER), Navigation Functions (LAG), and Date/Time functions (DATEDIFF).
**Data Modeling:** Multi-table Relational Joins, Subqueries, and Complex Aggregations.

**How to Navigate this Repository**
The Core Logic: View the full analysis in Northwind_Business_Intelligence_Analysis.sql.
