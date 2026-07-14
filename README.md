# 📊 E-Commerce Sales Dashboard using Power BI

## 📌 Project Overview

This project is an interactive **E-Commerce Sales Dashboard** developed using **Microsoft Power BI**. It provides valuable insights into sales performance, customer behavior, product categories, payment methods, and monthly profit trends, helping businesses make data-driven decisions.

The dashboard allows users to analyze key business metrics through interactive visualizations and filters.


## 🎯 Objectives

- Analyze overall sales performance.
- Monitor profit and quantity sold.
- Identify top-performing states and customers.
- Understand category and payment mode distribution.
- Track monthly profit trends.
- Provide interactive filtering using slicers.


## 🛠️ Tools & Technologies

- Microsoft Power BI Desktop
- Power Query
- DAX (Data Analysis Expressions)
- CSV Dataset



## 📂 Dataset

The project uses two CSV files:

- **Orders.csv**
- **Details.csv**

These datasets contain order details, customer information, product categories, payment modes, sales amount, profit, and quantity.



## 📋 Data Preparation

The dataset was cleaned using **Power Query** by:

- Importing CSV files
- Checking data types
- Removing duplicate records
- Validating missing values
- Creating relationships between tables




## 📈 DAX Measures Created

```DAX
Total Sales = SUM(Details[Amount])

Total Profit = SUM(Details[Profit])

Total Quantity = SUM(Details[Quantity])

Total Orders = COUNTROWS(Orders)

Average Order Value =
DIVIDE([Total Sales],[Total Orders])




## 📊 Dashboard Features

### KPI Cards

- Total Sales
- Total Quantity
- Total Profit
- Average Order Value
- Total Orders

### Visualizations

- Sales by State
- Sales by Customer
- Profit by Month
- Sales by Payment Mode
- Profit by Category
- Top Sub-Categories

### Interactive Filters

- Quarter
- State



## 📌 Key Insights

- Maharashtra generated the highest sales.
- Clothing category contributed the highest sales.
- COD was the most preferred payment mode.
- Monthly profit varied throughout the year.
- Top customers contributed significantly to overall revenue.



## 📷 Dashboard

The dashboard includes:

- Interactive KPI Cards
- Donut Charts
- Bar Charts
- Column Charts
- Slicers
- Dynamic Filtering


## ▶️ How to Use

1. Clone the repository.
2. Open the `.pbix` file using Microsoft Power BI Desktop.
3. Refresh the dataset if required.
4. Interact with slicers and charts to explore insights.


## 📚 Skills Demonstrated

- Data Cleaning
- Data Modeling
- Power Query
- DAX
- Data Visualization
- Dashboard Design
- Business Intelligence
- Interactive Reporting



## 🎯 Future Enhancements

- Year-over-Year Sales Analysis
- Profit Margin Analysis
- Customer Segmentation
- Forecasting
- Geographic Map Visualization




## ⭐ If you found this project useful, consider giving it a Star!
