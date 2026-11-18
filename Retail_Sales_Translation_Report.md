### Retail Sales Performance Analysis Dashboard | Power BI

#### Project Overview

This project uses Power BI to analyze sales transaction data, focusing on sales performance, product categories, customer segmentation, promotional effectiveness, returns, shipping methods, and sales representative performance. The report uses KPI cards, line charts, doughnut charts, funnel charts, and matrices to help users quickly understand retail sales and explore related trends and patterns.



#### Project Objectives

Monitor overall sales performance and identify sales trends over time.

Analyze sales distribution across different product categories and sales channels.

Explore customer purchasing behaviour across different demographic segments.

Evaluate promotional effectiveness and the relationship between discounts and sales.

Analyze return transactions and shipping performance.

Compare sales performance across different sales representatives and stores.



#### Data Modeling

FactSales: Main sales transaction data, including order details, sales amount, quantity, profit, and transaction information.

DimChannel: Sales channel information and classification.

DimCustomer: Customer information and demographic attributes.

DimDate: Date attributes for time-based sales analysis.

DimPayment: Payment methods and payment-related information.

DimProduct: Product information and product categories.

DimPromotion: Promotion details and discount-related information.

DimSalesRep: Sales representative information.

DimShipping: Shipping methods and delivery-related information.



#### Dashboard Pages \& Analysis

Page 1 -- Retail Sales Overview -- Overall sales performance and key business indicators

Key visualizations:

KPI Cards: Key sales performance indicators.

Line Chart: Total sales trends over time.

Clustered Column Chart: Total sales across different product categories.

Donut Chart: Sales distribution across different sales channels.

The business is growing, with clear sales changes throughout the year. Most sales come from electronics channel. The next stage is improving weaker product groups, putting more money into online sales.



Page 2 -- Product \& Total Sales -- Product performance and sales contribution

Key visualizations:

Clustered Bar Chart: Top 10 product subcategories by total sales.

Treemap: Total profit by product category and subcategory.

Scatter Chart: Average unit price versus quantity by product category.

Matrix: Detailed product sales performance.

Interactive slicers for product analysis.

The profit margin for all product categories are about 20%. However, sales rely heavily on a few main products, mainly laptops and office furniture. Keeping these products strong and growing high-profit areas such as furniture and home appliances to increase both sales and profit.



Page 3 -- Customer Segmentation \& Sales Analysis -- Customer and purchasing behaviour

Key visualizations:

Donut Chart: Customer distribution by segment.

Column Chart: Sales by customer gender and segment.

Line Chart: Sales per customer across different age groups.

Decomposition Tree: Interactive analysis of customer segmentation and sales performance.

Most revenue comes from online sales as the main channel. Spending varies by age, with older customers spending the most. The next step include growing the customer base, attracting new customers, continuing to invest in online sales.



Page 4 -- Promotion Sales \& Discount -- Promotional effectiveness and discount analysis

Key visualizations:

Clustered Bar Chart: Promotion sales by promotion type.

Line and Column Combo Chart: Total sales by discount rate.

Donut Chart: Total orders by promotion status.

Matrix: Detailed promotion performance analysis.

Promotions work best during key seasonal events with moderate discounts. Excessive discounts reduce profits without generating enough extra sales. Focus on holidays and Black Friday, control discount levels, remove weak promo codes, and use natural demand to reduce reliance on discounts.



Page 5 -- Return \& Shipping Method -- Return transactions and delivery performance

Key visualizations:

Clustered Bar Chart: Return transactions by different return reasons.

Clustered Column Chart: Average shipping performance by delivery days.

Funnel Chart: Total orders across different order statuses.

Interactive slicers for return transaction and shipping method.

While most orders are completed successfully, approximately 17% are returned or cancelled. Next Stages are shortening standard delivery times, ensuring order accuracy and optimizing packaging, setting clear delivery expectations, reducing the number of returns, and identifying the reasons behind order cancellations.



Page 6 -- Total Sales \& Sales Representative -- Sales representative and store performance

Key visualizations:

Clustered Column Chart: Total sales by sales representative.

Scatter Chart: Total quantity and profit margin by store.

Matrix: Detailed sales representative performance.

Interactive slicer for sales representative.

The business is stable, with similar margins and order values across stores and sales representative. Growth depends on increasing sales in smaller stores and improving low-margin stores. The rest of representative should learn skills from the top representative like NYC-01 and LA-01.



#### Key Skills Demonstrated

Data Cleaning \& Transformation

Power Query (ETL)

DAX Measures \& Calculations

Data Modeling

Star Schema Design

Exploratory Data Analysis (EDA)

Customer Segmentation

Sales \& Promotion Analysis

Data Visualization

Business Intelligence



#### Final Conclusion

This retail business generates stable profits and exhibits a clear seasonal pattern, with sales peaking in the fourth quarter. Revenue is primarily driven by laptops and office furniture, with the largest share of sales coming through online channels. Purchases are typically made by individual consumers, and gender has minimal impact on sales figures. Heavy discounting erodes profit margins, while approximately 17% of orders are returned or cancelled due to delivery delays, shipping errors, or product damage. The NYC-01 and LA-01 locations are top performers. Moving forward, the business should focus on optimizing delivery processes, reducing return rates, managing discount levels, expanding the product range, and boosting sales at smaller retail locations.

