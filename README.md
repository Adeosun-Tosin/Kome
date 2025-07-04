### 📊 KMS SQL Case Study – Business Intelligence Analysis (2009–2012)


#### 📁 Project Overview


This repository contains an SQL-based case study analyzing historical sales data from Kultra Mega Stores (KMS), a company headquartered in Lagos, Nigeria, specializing in office supplies and furniture. The focus of this analysis is on the Abuja division, using order records from 2009 to 2012.

You have been engaged as a Business Intelligence Analyst to identify trends, evaluate customer segments, and provide actionable recommendations to management.




### 🏢 Company Background
Kultra Mega Stores (KMS) serves a wide customer base across Lagos, including:

Individual Consumers

Small Businesses (Retail)

Large Corporates (Wholesale)

This analysis helps the Abuja Business Manager understand regional performance, customer behavior, product profitability, and logistical cost efficiency.

###  ⚙️ Tools & Technologies
Database: Microsoft SQL Server

Language: T-SQL

IDE: SQL Server Management Studio (SSMS)

Dataset: Cleaned and imported from Excel (KMS Sql Case Study cleanEST)

Time Frame: 2009 – 2012

🔍 Case Scenario I: Operational & Regional Insights
1. Which product category had the highest sales?
Used GROUP BY and SUM(Sales) to identify top-performing product categories.

Finding: The category with the highest sales can guide promotional and inventory strategies.

2. Top 3 and Bottom 3 Regions by Sales
Ranked regions by total sales.

Finding: Reveals underserved markets and top-performing areas.

3. Total Sales of Appliances in Ontario
Filtered dataset to category = 'Appliances' and region = 'Ontario'.

Purpose: Helps understand category-level demand by geography.

4. Recommendations for Bottom 10 Customers
Identified least valuable customers based on sales.

Analyzed their spending behavior by product category.

### ✅ Recommendation to Management:
Upselling & Cross-Selling: Promote bundles or premium products.

Targeted Promotions: Offer personalized deals.

Account Management: Personal outreach to build loyalty.

Customer Segmentation: Create a “low-tier” customer group for experimentation.

5. Which shipping method incurred the most cost?
Summed Shipping_Cost by Ship_Mode.

Finding: Helps evaluate cost-effectiveness of logistics partners.

✨ Case Scenario II: Customer & Profitability Insights
6. Most Valuable Customers and Their Purchases
Top 10 customers by total sales.

Analyzed their top purchased products.

Insight: Helps tailor loyalty programs and retention strategies.

7. Top Small Business Customer by Sales
Filtered by Customer_Segment = 'Small Business'.

Aggregated total sales to rank.

8. Corporate Customer with the Most Orders (2009–2012)
Used COUNT(*) to track order frequency.

Helps identify long-term B2B engagement.

9. Most Profitable Consumer Customer
[To Be Analyzed] – Use SUM(Profit) filtered by Customer_Segment = 'Consumer'.

10. Customer Returns & Their Segments
[To Be Analyzed] – Requires Return_Flag or similar column (if available).

11. Is Shipping Cost Aligned With Order Priority?
Compare Shipping_Cost against Order_Priority and Ship_Mode.

Example Insight: If low-priority orders use Express Air, cost-saving opportunities exist.


### 📈 Summary of Key Insights
Top Category: [Insert result from your query]

Highest Sales Region: [Insert result]

Most Expensive Shipping Mode: [Insert result]

Top Customer Segment: Small Business showed strong engagement.

High Shipping Cost Use: Needs alignment with priority.

### 📌 Recommendations
Logistics Optimization: Reevaluate shipping methods vs. order urgency.

Customer Engagement: Re-engage bottom 10 customers with offers.

Focus on High-Margin Products: Target categories with best profit-to-sales ratios.

Segment-Based Strategy: Differentiate marketing by customer type (Consumer, Corporate, SMB).

Expand High-Performing Regions: Consider scaling operations in top 3 sales regions.

📂 Repository Structure
pgsql
Copy
Edit
📁 /KMS-SQL-Case-Study/
├── 📄 kms_project.sql              -- SQL schema & all queries
├── 📄 KMS Sql Case Study cleanEST.xlsx -- Cleaned source data (imported into SQL)
├── 📄 README.md                   -- Project documentation
