# ADVENTURE-WORKS-ANALYSIS
### Objective:
To analyze and visualize Adventure Works’ business data, enabling stakeholders to understand sales performance, customer trends, product profitability, and regional growth.

### Key Areas of Analysis:
* Sales Performance: Tracks total sales, profit, and order volume across different time periods.
* Product Insights: Identifies top-selling products, product categories, and revenue contributions.
* Customer Demographics: Explores customer segmentation by region, age, gender, and purchase behavior.
* Geographical Analysis: Sales performance by country, region, or city.
* Time Trends: Monthly, quarterly, and yearly sales trends and seasonality patterns.
* Profitability: Margins across products and categories, contribution to total profit.
* Salesperson Performance: Individual contribution of sales representatives toward overall targets.

### Data Sources:
* Fact tables like Sales, Reseller Sales, and Internet Sales
* Dimension tables such as Customers, Products, Date, Geography, and Sales Territories

### Tools Used:
* Power BI Desktop: For data modeling, DAX calculations, and interactive dashboard creation.
* Power Query Editor: For data transformation and cleansing.

### 🧹 Data Cleaning (ETL Process):
1. Removed unnecessary columns – e.g., GUIDs, internal codes not needed for analysis.
2. Handled null values – filled or removed missing entries in fields like Customer, Sales, Product.
3. Data type corrections – ensured dates, numbers, and texts are in proper formats.
4. Standardized categories – fixed inconsistent naming (e.g., "Mountain Bike" vs "MTB").
5. Created calculated columns/measures – e.g., Profit = Sales - Cost.

### 🧩 Data Modeling:
1. Star Schema Design:
* Fact Table: Sales
* Dimension Tables: Customer, Product, Date, Geography, Employee
  
2. Relationships:
* One-to-many (e.g., one customer → many sales)
* Used surrogate keys (IDs) to link tables.
  
3. Hierarchies:
* Built for Date (Year > Quarter > Month), Product Category, etc.
  
4. Measures Created:
* Total Sales, Total Profit, Sales Growth %, Profit Margin, etc.

  ### 🔑 Key Highlights
* Total Revenue Generated: Significant revenue contribution from online sales vs. in-store.
* Top Performing Products: Mountain bikes and road bikes lead in sales volume and revenue.
* Sales by Region: The US and Canada are the most profitable regions.
* Customer Segmentation: Repeat customers contribute over 60% of sales.
* Order Trends: Peak orders in Q2 and Q4, indicating seasonal buying behavior.

### 📊 Top Insights
1.Top-Selling Categories:
* Bikes contribute ~70% of overall revenue.
* Clothing and accessories have higher volume but lower profit margins.

2. Sales by Channel:
* Online sales outperform physical stores in both quantity and revenue.

3. Geographic Trends:
* Highest sales in California, Washington, and Ontario.
* Opportunities to grow in underperforming regions like the East Coast and Europe.

4. Customer Behavior:
* Loyal customers have higher average order values.
* Promotions significantly impact buying decisions (especially in Q4).

5.Time-Based Trends:
* December sees the highest monthly sales.
* Sales drop in January and July, suggesting off-peak periods.

  ### 📌 Sales & Revenue Recommendations
1. Focus on High-Performing Products
Identify top-selling products by quantity and revenue. Promote these through bundled offers or extended availability.
2.Boost Low Revenue Categories
Analyze underperforming product categories and improve them through:
* Better marketing
* Product repositioning
* Discounts or phasing out
3. Seasonal Trend Optimization
Leverage time-based trends to launch promotions during high-sales periods (e.g., end-of-year, summer months).

### 🌍 Geography-Based Recommendations
1. Target High-Potential Regions
Expand in regions showing consistent growth in revenue and customer acquisition.

### 👥 Customer Behavior Recommendations
1. Loyalty & Retention Programs
Focus on customers with repeat purchases. Implement loyalty rewards or email campaigns to retain them.
2. Customer Segmentation Strategy
Segment customers by demographics or buying frequency. Tailor campaigns based on these segments.

📦 Inventory & Product Recommendations
1. Optimize Inventory Management
* Match inventory levels with product sales trends. Avoid overstocking low-demand items.
2. Introduce Popular Product Variants
* If certain products are trending, consider offering variations (colors, sizes, bundles).

