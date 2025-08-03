# SuperStore_Sales_Dashboard
PowerBI Dashboard
Power BI project: a detailed sales forecast dashboard for a Superstore. This dashboard offers an in-depth look at sales trends over time and provides actionable insights for better decision-making.

The first page features:

Donut charts: Highlighting sales distribution across different categories.
Map visualization: Showing regional sales performance.
Slicers: Allowing dynamic data filtering for a more interactive experience.
Line and stacked charts: Presenting sales trends and comparisons over time.
On the second page, I focused on sales forecasting using historical sales data. This involved:

Sales Forecasting: Using a DAX function to predict future sales based on past performance.
DAX
SalesForecast = SUMMARIZE('Sheet1', Sheet1[Order Date], "Total Sales", SUM(Sheet1[Sales]))
Zoom slicer: Enhancing the ability to explore data in detail.
This project has been a fantastic opportunity to deepen my skills in data visualization and advanced Power BI functionalities. Special thanks to Rishbah for his guidance throughout this process.


