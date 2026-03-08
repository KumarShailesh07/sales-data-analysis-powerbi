# Sales Data Analysis Dashboard — Power BI

A comprehensive end-to-end Sales Analytics Dashboard built in Power BI, transforming raw transactional data into actionable business intelligence across 5 interactive report pages.

---

## Screenshots

<img width="717" height="398" alt="Sales Data Analysis Dashboard" src="https://github.com/user-attachments/assets/2b99d239-20c6-4cdc-bcf8-d276c648803c" />
<img width="715" height="380" alt="Sales Data Analysis Dashboard 2" src="https://github.com/user-attachments/assets/7c1f372a-6bdb-41c9-91c0-7ee0e2638db4" />
<img width="718" height="401" alt="Sales Data Analysis Dashboard 3" src="https://github.com/user-attachments/assets/e1939bb2-c106-4923-8629-083bd5188546" />
<img width="701" height="395" alt="Sales Data Analysis Dashboard 4" src="https://github.com/user-attachments/assets/3b006d1b-34a7-4e8a-ba03-d2cdd99987c3" />
<img width="717" height="403" alt="Sales Data Analysis Dashboard 5" src="https://github.com/user-attachments/assets/c3ec90d5-5cfd-4d8a-a05c-6322f5e4cda6" />

---

## Project Overview

This project analyzes sales data from 2020 to 2024 for an Indian retail business. The dashboard provides insights into sales trends, product performance, promotional effectiveness, geographic distribution, and period-over-period comparisons.

---

## Dashboard Pages

### Page 1 — Overview Dashboard
- Total Orders KPI (3,510 orders)
- Sales Trend by Period (2020–2024)
- Geographic Sales Distribution across major Indian cities
- Average Discount by Promotion Category
- Profit vs. Net Sales scatter plot

### Page 2 — Product Performance
- Top 5 and Bottom 5 Products by Sales, Quantity, and Profit
- Side-by-side bar charts for easy comparison

### Page 3 — Period-over-Period Comparison
- Dual date range slicers for custom time period selection
- Clustered bar charts comparing Total Sales, Profit, and Quantity Sold

### Page 4 — Individual Period Analysis
- Two independent date range filters
- Separate KPI bars for each period with color-coded visuals

### Page 5 — Raw Data Explorer
- Interactive table with 5 slicers (Product, Date, Promotion, Customer, Product Name)
- Full transactional drill-down view

---

## Key Insights

- Sales peaked in 2023 at ₹32M, followed by a sharp decline in 2024
- Apple iPhone 14 is the top product with ₹21.4M in sales and ₹2.14M in profit
- Colgate Toothpaste is the lowest performer at ₹0.02M in sales
- Weekend Flash Sale drives the highest average discounts (₹23K)
- Overall profit margin is ~10% (₹12.2M profit on ₹122M total sales)
- Electronics consistently dominate top performers across all metrics

---

## Tools & Technologies

| Tool | Usage |
|------|-------|
| Power BI Desktop | Dashboard development |
| DAX | Calculated measures and KPIs |
| Power Query | Data transformation and cleaning |
| Bing Maps Visual | Geographic sales distribution |
| Data Modeling | Table relationships and schema design |

---

## Dataset Details

| Field | Description |
|-------|-------------|
| CustomerID | Unique customer identifier |
| Order ID | Unique order identifier |
| Product ID | Product reference code |
| PromotionID | Linked promotion (if applicable) |
| Date | Transaction date |
| Discount | Discount amount applied |
| Discount Percentage | Discount as a percentage |
| Net Sales | Sales after discount |
| Price Per Unit | Unit selling price |
| Profit | Profit earned per transaction |
| Total Sales | Gross sales value |
| Units Sold | Quantity sold |

---

## DAX Measures Used

- Total Sales = SUM(Sales[Total Sales])
- Total Profit = SUM(Sales[Profit])
- Total Quantity Sold = SUM(Sales[Units Sold])
- Net Sales = SUM(Sales[Net Sales])
- Average Discount = AVERAGE(Sales[Discount])
- Profit Margin % = DIVIDE([Total Profit], [Total Sales])

---

## How to Use

1. Clone or download this repository
2. Open the `Sales_Data_Analysis.pbix` file in Power BI Desktop
3. Navigate through the 5 report pages using the tabs at the bottom
4. Use the slicers and date filters to explore specific time periods, products, customers, or promotions

---

## Project Structure

```
sales-data-analysis-powerbi/
│
├── Sales_Data_Analysis.pbix
├── Sales_Data_Analysis_Dashboard.png
├── Sales_Data_Analysis_Dashboard_2.png
├── Sales_Data_Analysis_Dashboard_3.png
├── Sales_Data_Analysis_Dashboard_4.png
├── Sales_Data_Analysis_Dashboard_5.png
└── README.md
```

---

## Author

Feel free to connect with me on [LinkedIn](#) or raise an issue if you have any questions or suggestions!

---

## License

This project is open source and available under the [MIT License](LICENSE).
