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
'''sql
select * from Sales data
where Conditions = TRUE
'''

## Data Visualisation

### Monthly Sales Performance and Movement Summary
![Screenshot 2024-11-06 234030](https://github.com/user-attachments/assets/5f9a0a6e-ec3d-4ef1-8681-27ef2e47feb4)

This report presents a high-level overview of monthly sales performance, highlighting total sales and month-over-month percentage changes. Key insights are as follows:

Strong Growth Periods: Significant growth was observed in February (+120.00%), June (+138.10%), and October (+285.71%). These months saw substantial increases in sales compared to the preceding month, indicating periods of high demand or successful sales initiatives.

Declines in Sales: Notable drops occurred in March (-80.45%), April (-55.81%), August (-26.13%), September (-82.93%), and December (-52.38%). These declines suggest potential seasonal effects, reduced demand, or other factors impacting sales performance.

Stable Months: Months such as July (+11.00%) showed modest growth, indicating more stable performance.

The total sales for the year amount to 10,587,500. This analysis provides insights into peak sales periods and potential areas for improvement, which are crucial for strategic planning and resource allocation.
![Screenshot 2024-11-06 234526](https://github.com/user-attachments/assets/0877c53f-47e3-414d-8c2f-fb2f56897eea)

![Screenshot 2024-11-06 234556](https://github.com/user-attachments/assets/4bb6abab-982d-44a1-96cb-f9fe8d7d690c)

![Screenshot 2024-11-06 234632](https://github.com/user-attachments/assets/1bb82e7d-8e65-4420-a89f-551d9d68985b)

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
