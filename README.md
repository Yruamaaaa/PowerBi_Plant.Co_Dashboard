# Power BI Dashboard Project: Plant Co. Sales Performance
The goal of this Power BI dashboard project is to analyze and visualize sales performance of Plant Co., a company operating in the plant and gardening products sector. The dashboard provides a comprehensive and interactive view of the company’s key performance indicators, sales trends, country-level performance, and profitability insights.

Key Visualizations and Insights:
Sales YTD vs PYTD by Country: A treemap highlights the 10 lowest-performing countries in terms of year-over-year sales difference. China shows the largest decline (–$691.73K), followed by Sweden and the United States.

Waterfall Chart: This visual shows the monthly variation in YTD vs PYTD sales across different countries and product types. It helps identify which months contributed most to the decline or improvement.

Monthly Sales Breakdown: A column and line chart displays monthly YTD sales per product type (Indoor, Outdoor, Landscape), compared to the PYTD values. This helps in monitoring seasonal trends and comparing against last year’s performance.

Profitability Segmentation: A scatter plot shows the distribution of accounts based on GP% and total YTD sales, allowing segmentation of high-revenue vs high-margin accounts.

Data Sources:
Two datasets were used for this project:

Plant Fact Table: Contains transactional sales data including Product_id, Sales_USD, Quantity, Price_USD, COGS_USD, Date_Time, and Account_id. This data enabled the calculation of revenue, unit economics, and gross profit.

Account Table: Provides account-level details such as country_code, Account_name, latitude, longitude, and full address details. This was used to map performance geographically and to enrich the data model with regional insights.

 

Power BI's modeling and DAX capabilities were used to calculate YTD and PYTD measures, GP% (Gross Profit = Sales – COGS), and to compare sales performance across dimensions like country, time, and product category. Filters and slicers allow dynamic exploration of the data.

This dashboard helps stakeholders quickly identify underperforming markets, analyze the impact of time and product type on sales, and segment customers by profitability to drive strategic business decisions.

Visualisation :

![image](https://github.com/user-attachments/assets/21c091d3-b5b1-4160-b675-b99acaa391c9)

