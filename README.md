Global-Superstore-Sales-Analysis-Power-BI-Dashboard
📌 Project Overview
This project analyzes the Global Superstore dataset using Power BI to uncover insights into sales, profit, customer behavior, product performance, and operational efficiency.

The dashboard is designed to:

Track key performance indicators (KPIs)

Highlight top products, customers, and regions

Identify discounting patterns and their impact on profit

Optimize shipping and order fulfillment performance

🗂 Dataset
Source: Global Superstore Dataset (Kaggle)

Records: ~51,000

Columns: ~23 (Orders, Customers, Products, Region, Profit, Sales, Discount, Shipping, etc.)

Time Period: 2011 – 2015

🔑 Key Features of the Dashboard
Page 1 – Executive Overview
KPIs: Total Sales, Total Profit, Profit Margin %, Avg Order Value, Total Orders

Sales & Profit trend over time

Sales by Region (map visualization)

Top 5 Products by Sales

<img width="1346" height="758" alt="image" src="https://github.com/user-attachments/assets/8232536f-b841-4016-acb1-d188e6974855" />


Page 2 – Product & Category Analysis
Sales by Category & Sub-Category

Scatter Chart: Profit vs Discount (Size = Sales)

Top 10 Products by Profit (with Sales & Margin)

<img width="1344" height="757" alt="image" src="https://github.com/user-attachments/assets/cbb1655b-260f-41ae-b773-49dc9dc67a2a" />

Page 3 – Customer & Geography Insights

Sales by Customer Segment

Top 10 Customers by Sales

Sales by State/Region (map/heatmap)

KPI Card: Unique Customers

<img width="1331" height="726" alt="image" src="https://github.com/user-attachments/assets/66b1ac09-0242-430b-9e5f-2f08a2c5c5fb" />

Page 4 – Shipping & Operations

Avg Delivery Days by Ship Mode

Scatter Chart: Shipping Cost vs Sales

Orders by Priority

KPI Card: Avg Shipping Cost

<img width="1342" height="731" alt="image" src="https://github.com/user-attachments/assets/a9b5248e-8be0-4ffe-b147-1e1efb4351dc" />

⚙️ Data Cleaning & Transformation
Removed Postal Code due to 80% missing + 20% error values

Standardized data types (Dates, Numeric fields, Text fields)

Created a DateTable for time intelligence (Year, Month, Quarter)

Built DAX measures for KPIs and comparisons (YTD, YoY, Profit Margin, etc.)

📈 Key Insights

Furniture generates high sales but lower profitability due to heavy discounting

Technology delivers the highest profit margins across categories

APAC & EMEA regions show consistent YoY growth

Critical Priority orders cost more to ship but contribute heavily to revenue

Discounts above 25% tend to reduce overall profit margins

🛠 Tools & Skills Used

Power BI – Data modeling, DAX, dashboard design

DAX – Calculated measures (YTD, YoY Growth, Rank, Profit Margin)

Data Cleaning – Power Query

Visualization – KPIs, Maps, Bar Charts, Scatter Plots, Treemaps


