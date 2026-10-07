# OperationsPerformanceDashboardAnalytics

Cascade Supply Co. — Operations Performance Dashboard
Project Overview
Cascade Supply Co. is a fictional regional distributor that needed a clearer way to monitor sales, customer, and fulfillment performance. The source data contained more than 10,000 order-line records covering customer activity, products, sales channels, delivery performance, cancellations, and returns.
The goal of this project was to transform the raw operational data into an interactive Tableau dashboard that helps management identify trends, investigate operational issues, and make more informed decisions.
Business Questions
The dashboard was designed to answer questions such as:
- How are revenue and order volume changing over time?
- Which customers, regions, product categories, and sales channels drive the most revenue?
- Are important customer accounts showing signs of decline?
- Which regions have fulfillment or delivery performance issues?
- Are cancellation rates stable or are there periods of unusual activity?
- Which product categories have the highest return rates?
- What are the most common reasons for product returns?
Tools Used
- Excel — data audit and source validation
- Tableau Public — data visualization, calculated fields, filters, dashboard actions, and interactive analysis
Data Preparation & Validation
Before building the dashboards, the source data was audited for:
- Row and column counts
- Date ranges
- Duplicate records
- Missing values
- Category consistency
- Numeric validity
- Revenue calculation accuracy
- Order-level vs. product-line-level grain
One important modeling consideration was that a single order could contain multiple product-line records. Order-level KPIs therefore use distinct counts of Order_ID, while return metrics are calculated at the product-line level.
Key KPIs
- Total Revenue
- Total Orders
- Average Order Value
- Total Units Sold
- On-Time Delivery %
- Average Order-to-Delivery Time
- Average Shipping Time
- Cancellation Rate
- Return Rate
Dashboard Pages
1. Executive Overview
Provides a high-level view of company performance, including revenue, order volume, average order value, on-time delivery, cancellation rate, regional performance, and product-category revenue.
2. Sales & Customer Analysis
Focuses on customer concentration, customer revenue trends, segment performance, sales-channel trends, and top-performing products.
3. Operations & Fulfillment
Monitors delivery reliability, fulfillment speed, shipping-method performance, cancellation trends, regional service levels, product returns, and return reasons.
Key Findings
1. Northstar Health Systems retention risk
   Northstar was the highest-revenue customer over the reporting period, but purchasing activity declined sharply after March 2026.
2. Northeast regional revenue acceleration
   The Northeast became the highest-revenue region during each of the most recent three months, indicating a meaningful recent growth trend.
3. South-region fulfillment gap
   The South had the weakest on-time delivery performance, falling to approximately 76.7% in 2026 while also handling the highest order volume.
4. Shift toward online purchasing
   Online sales increased materially as a share of both revenue and order volume, indicating a change in customer purchasing behavior.
5. Spring 2026 cancellation spike
   Cancellation rates rose sharply in April and May 2026, with the South region experiencing the largest increase before returning closer to normal levels.
6. Technology return risk
   Technology products had the highest return rate, while damage in transit was the largest single return reason across the business.
Business Value
This project demonstrates an end-to-end analytics workflow: auditing source data, defining business KPIs, creating calculated fields, designing interactive dashboards, investigating trends, and translating findings into management recommendations.
The approach is applicable to businesses that rely on spreadsheets or transaction exports but need clearer visibility into performance, customer behavior, and operational issues.
Deliverables
- Interactive Tableau dashboard
- Executive Overview dashboard
- Sales & Customer Analysis dashboard
- Operations & Fulfillment dashboard
- Business Insights report
- Project Summary
- Source and working Excel files
Data Note
All company names, customers, transactions, and operational data used in this project are fictional and were created specifically for portfolio demonstration purposes.
