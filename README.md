📊 Amazon Sales Data Analysis using SQL

An end-to-end SQL portfolio project analyzing Amazon sales transactions to uncover insights on revenue, profitability, customer behavior, and product performance.

Prepared by: Ronnit Singh — BBA Graduate | Aspiring Data Analyst Tools: SQL (MySQL), MySQL Workbench

📘 Project Overview

This project analyzes Amazon sales data to understand sales trends, customer behavior, product performance, and profitability. The dataset covers transactional records from three Amazon branches during Q1 2019 (January–March).

The goal is to apply real-world SQL techniques — including aggregations, subqueries, CTEs, and window functions — to answer key business questions about revenue growth, customer preferences, and operational efficiency.

📂 Dataset Description
Detail	Value
Dataset Name	Amazon Sales Dataset
Time Period	January 2019 – March 2019
Total Records	1,000
Total Columns	20
Branches	A, B, C
Cities	Yangon, Mandalay, Naypyitaw

Key Attributes:

Sales: quantity, unit price, total sales, VAT, cost of goods sold (COGS)
Customer: customer type, gender
Product: product line
Transaction: date, time, payment method, rating

Additional time-based columns — time_of_day, day_name, and month_name — were engineered using SQL to support deeper trend analysis.

🛠️ SQL Techniques Used
Aggregate functions (SUM, COUNT, AVG, MAX)
Subqueries & correlated subqueries
Common Table Expressions (CTEs)
Window functions (RANK(), LAG(), PARTITION BY)
CASE statements for categorization
Date/time functions (HOUR(), FIELD())
❓ Business Questions Answered

The analysis is organized into six sections, covering 37 SQL queries in total:

Dataset Overview — transaction counts, customer distribution, product/customer/payment method diversity
Sales & Revenue Analysis — top-selling and top-revenue product lines, monthly trends, peak revenue hours, revenue contribution by branch, month-over-month growth
Cost, VAT & Profitability Analysis — COGS trends, VAT by product line/city/customer type, most profitable product lines, profit margins, branch efficiency
Product Performance Analysis — good vs. bad performing product lines, average ratings, top 3 product lines per branch
Customer Behavior & Segmentation — branch performance vs. average, gender-based product preferences, customer type analysis, rating-revenue relationship, basket size
Time-Based & Payment Analysis — sales by day/time, rating patterns by day and time per branch, most-used and highest-revenue payment methods
🔑 Key Findings

Sales & Revenue

🏆 Highest sales product line: Electronic Accessories (971 units sold)
💰 Highest revenue product line: Food and Beverages ($56,144.96)
📉 Lowest sales product line: Health and Beauty (854 units)
📉 Lowest revenue product line: Health and Beauty ($49,193.84)

Time & Location

📅 Highest revenue month: January ($116,292.11)
📅 Lowest revenue month: February ($97,219.58)
🏙️ Highest revenue branch/city: Naypyitaw (Branch C) ($110,568.86)
🏙️ Lowest revenue branch/city: Mandalay (Branch B) ($106,198.00)

Customer Insights

👥 Predominant gender: Female
👥 Predominant customer type: Member
💵 Highest revenue gender: Female ($167,883.26)
💵 Highest revenue customer type: Member ($164,223.81)
🛍️ Most popular product line (Male): Health and Beauty
🛍️ Most popular product line (Female): Fashion Accessories
📊 Member distribution: Male (240) | Female (261)
📦 Units sold: Male: 2,641 | Female: 2,869

🧠 Conclusion

This SQL-based analysis demonstrates how multiple factors — cost, customer behavior, timing, and product performance — combine to shape overall business performance, not just revenue alone. Sales performance varies significantly across product lines, branches, and time periods; some product lines drive higher profit despite lower volume, while customer ratings and purchase timing also influence revenue. Member customers and specific branches emerge as key contributors to overall performance.

This project reflects practical, business-oriented SQL skills suitable for entry-level Data Analyst roles.

   📬AUTHOR
"RONNIT SINGH"
