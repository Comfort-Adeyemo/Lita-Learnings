# Sales Insight: Uncovering Key Trends and Revenue Drivers
Welcome to Sales Insight, a comprehensive sales analysis project aimed at helping businesses make data-driven decisions to boost revenue, enhance customer retention, and optimize marketing strategies. This project dives deep into sales performance across different product lines, regions, and customer segments, leveraging powerful data analysis techniques to extract actionable insights. 

In this project, we'll:
- Analyze Sales Trends over time to identify seasonality, high-performing months, and growth patterns.
- Segment Customers by purchase behavior and regions, highlighting profitable and underperforming markets.
 - Product Performance: Discover top products and uncover hidden trends in customer preferences.
- Revenue Insights: Break down revenue by product category, region, and customer type to pinpoint areas for growth.

## Data Sources [Download Here](https://www.microsoft.com)
The Sales Insight project pulls data from several key sources essential for a comprehensive view of sales performance. Our primary data includes transactional records capturing OrderID, CustomerID, Product, Region, Order Date, Quantity, Unit Price, Total Sales, and Month. Additionally, we have customer demographics and subscription data, which includes CustomerID, CustomerName, Region, Subscription Type, Subscription Start, Subscription End, Canceled Status, and Revenue. By integrating these sources, the analysis captures both sales trends and customer behaviors, enabling us to drill down into regional and product-based performance, retention patterns, and customer segmentation.

## Tools Used 
This analysis leverages a powerful set of tools—Excel, SQL, and Power BI—to efficiently handle data processing, analysis, and visualization. Excel is used for quick data cleaning, preliminary analyses, and pivot tables that provide a snapshot of sales trends and customer behaviors. SQL allows us to run complex queries to aggregate and filter large datasets, performing deeper analysis on factors like regional sales breakdown, product performance, and customer segmentation. Finally, Power BI brings the analysis to life with dynamic dashboards, enabling stakeholders to interact with visuals and uncover key insights in real time. Together, these tools provide a streamlined approach for data-driven decision-making.

Data Analysis
'''SQL
SELECT * FROM SALES DATA
WHERE CONDITION = TRUE
'''

## Data Visualisation

### Monthly Sales Performance and Movement Summary
![Screenshot 2024-11-06 234030](https://github.com/user-attachments/assets/5f9a0a6e-ec3d-4ef1-8681-27ef2e47feb4)

This report presents a high-level overview of monthly sales performance, highlighting total sales and month-over-month percentage changes. Key insights are as follows:

Strong Growth Periods: Significant growth was observed in February (+120.00%), June (+138.10%), and October (+285.71%). These months saw substantial increases in sales compared to the preceding month, indicating periods of high demand or successful sales initiatives.

Declines in Sales: Notable drops occurred in March (-80.45%), April (-55.81%), August (-26.13%), September (-82.93%), and December (-52.38%). These declines suggest potential seasonal effects, reduced demand, or other factors impacting sales performance.

Stable Months: Months such as July (+11.00%) showed modest growth, indicating more stable performance.

The total sales for the year amount to 10,587,500. This analysis provides insights into peak sales periods and potential areas for improvement, which are crucial for strategic planning and resource allocation.

### Sales Analysis by Region and Product
![Screenshot 2024-11-06 234526](https://github.com/user-attachments/assets/0877c53f-47e3-414d-8c2f-fb2f56897eea)

This table provides a detailed breakdown of total sales across different products and regions (East, North, South, and West), along with an overall Grand Total of 10,587,500. Here’s a closer analysis of the performance across each product and region:

Regional Sales Insights:
South is the top-performing region with a total sales value of 4,675,000, indicating a high concentration of demand in this area.
East follows with 2,450,000 in sales, making it the second most profitable region.
North has 1,950,000 in sales, showing moderate demand across products.
West has the lowest sales total at 1,512,500, suggesting an opportunity for growth or increased marketing focus in this region.

Product Sales Insights:
Shoes lead in sales with a total of 3,087,500, driven largely by high sales in the South (2,750,000). This product shows strong demand and could be a focal point for future sales strategies.
Shirt sales total 2,450,000, with balanced performance across East and North, each contributing 1,200,000+.
Hat follows with 1,587,500, with strong sales in East (537,500) and West (875,000).
Gloves achieved 1,500,000 in sales, mostly concentrated in the South (1,250,000), indicating a regional preference for this product.
Jacket sales totaled 1,050,000, evenly split between East and North, suggesting consistent demand across these regions.
Socks have the lowest total sales at 912,500, primarily sold in the South and West.

Key Takeaways:
South Region Dominance: The South leads in sales across multiple products, especially Shoes and Gloves, showing strong customer interest in these items.
Product-Specific Demand: Shoes and Shirts are the highest-revenue products, particularly in the South and East regions, highlighting opportunities to focus inventory and marketing efforts on these products in high-demand regions.

Growth Potential: The West region has lower sales across most products, suggesting potential for strategic growth initiatives, such as targeted marketing or promotions.
This analysis helps identify high-performing regions and products, guiding inventory planning, regional marketing strategies, and product-specific investments.

### Product Sales Summary
![Screenshot 2024-11-06 234556](https://github.com/user-attachments/assets/4bb6abab-982d-44a1-96cb-f9fe8d7d690c)

The sales data reveals the performance of various products, with a Grand Total of 10,587,500 in sales. Key insights include:

Shoes lead in total sales, contributing 3,087,500, making them the top-selling product.
Shirts follow closely with 2,450,000 in sales, showing high customer demand.
Hats and Gloves also perform well, generating 1,587,500 and 1,500,000 respectively.
Jackets account for 1,050,000, indicating moderate sales.
Socks have the lowest total sales at 912,500, suggesting lower demand relative to other products.
This summary highlights Shoes and Shirts as the highest revenue-generating products, with potential for focused marketing to maintain or increase their strong sales.

### Sales Summary by Region
![Screenshot 2024-11-06 234632](https://github.com/user-attachments/assets/1bb82e7d-8e65-4420-a89f-551d9d68985b)

The sales performance across regions reveals the following key insights:

The East region generated a total of $2.45 million in sales, with an average unit price of $287,500 and a quantity sold of 102,500 units. The North region followed with $1.95 million in total sales, boasting a higher average unit price of $425,000, but a lower quantity sold of 62,500 units. The South region led in total sales, reaching $4.68 million, with the highest average unit price of $475,000 and a substantial quantity of 122,500 units sold. Finally, the West region contributed $1.51 million in sales, with an average unit price of $275,000 and 57,500 units sold.

In total, across all regions, the company achieved $10.59 million in sales, with an overall average unit price of $1.46 million and a combined quantity of 345,000 units sold. This summary highlights the varying sales dynamics and pricing strategies across different regions.

### Regional Sales Summary
![Screenshot 2024-11-06 233306](https://github.com/user-attachments/assets/57257066-e960-47b8-a117-36f72cbbe2d5)

The "Regional Amount" chart provides a clear visualization of sales distribution across four key regions, with each segment representing the proportion of total sales attributed to each area. The South region leads significantly, accounting for the largest share at 4,675,000, suggesting a strong sales presence or high demand in this area. The East region follows with 2,450,000, indicating solid performance, though notably lower than the South. North and West contribute 1,950,000 and 1,512,500 respectively, with the West region generating the smallest share of total sales.

This insight is crucial for decision-makers aiming to target high-performing regions or explore growth strategies for underperforming areas.

### Average Sales Per Product Analysis
![Screenshot 2024-11-06 233931](https://github.com/user-attachments/assets/1184510e-e6e2-4365-a5fe-dc618038760f)

The "Average Sales per Product" charts, both line and bar formats, illustrate the trends in average sales amount and unit quantity across various product categories. The Amount (in blue) reflects the revenue per product, while Unit (in red) shows the average number of items sold per transaction.

Key observations include:
High initial sales amount for certain products, such as Shoes, which see a steep drop-off in average sales amount in subsequent categories.
Amount fluctuations across different product categories, with a noticeable dip in some product groups, followed by a gradual recovery towards the end of the series.
Unit sales remain relatively stable, showing only minor variations across products, suggesting that while revenue fluctuates, the quantity sold remains consistent.
This analysis provides a dynamic view into product performance, revealing which items drive higher revenue versus stable unit sales. Such insights are essential for pricing strategies, inventory planning, and understanding product-specific demand patterns.

