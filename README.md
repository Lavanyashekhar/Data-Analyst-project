# RetailMart India – Sales Analytics Dashboard
## 📊 Project Overview

This project is a Power BI Sales Analytics Dashboard created for RetailMart India Pvt. Ltd., a mid-sized electronics and home appliances retail company operating across four regions of India.
The dashboard helps management understand revenue, profit, sales targets, product performance, regional performance, and salesperson performance.
## 🎯 Business Problem
RetailMart was tracking sales using monthly Excel files, making it difficult to quickly analyse business performance.
This Power BI dashboard provides insights into:
- Monthly revenue trends
- Product and category performance
- Regional sales performance
- Actual sales compared with targets
- Salesperson performance
- Profit and profit margin
- Customer and transaction information
## 📁 Dataset

**Dataset:** CS1_RetailMart_Sales

**Records:** 2,000 rows

### Main Columns

- Transaction ID
- Date
- Product Name
- Category
- Region
- City
- Sales Amount
- Target Sales
- Cost Amount
- Profit
- Quantity
- Payment Method
- Salesperson
- Customer ID
- Discount %

## 🧹 Data Cleaning

The data was cleaned using Power Query.

The cleaning process included:

- Correcting data types
- Handling null values in Sales Amount
- Handling null values in Discount %
- Standardising inconsistent product names
- Removing extra spaces
- Removing completely empty rows where applicable
- Converting the Date column to Date format

## 🧮 DAX Measures

The dashboard uses DAX measures including:

- Total Revenue
- Total Cost
- Total Profit
- Profit Margin %
- Achievement Rate %
- Total Transactions
- Unique Customers
- Average Order Value
- Total Units Sold

A calculated column was also created:

- Sales Level – High / Medium / Low
## 📈 Dashboard Pages

### Page 1 – Sales Overview

The dashboard includes:

- Total Revenue KPI
- Total Profit KPI
- Profit Margin % KPI
- Achievement Rate % KPI
- Total Transactions KPI
- Monthly Revenue Trend
- Revenue by Product
- Region: Actual vs Target
- Revenue by Category
- Salesperson Performance
- Region Slicer
- Month Slicer

### Page 2 – Region Details

The drill-through page provides:

- Total Revenue
- Profit Margin %
- Unique Customers
- Sales by Product
- Monthly Revenue Trend
- Transaction Details

The Region Details page allows users to analyse a selected region in more detail.

## 🛠️ Tools & Technologies

- Power BI Desktop
- Power Query
- DAX
- Microsoft Excel

## 📂 Project Files

- `Case_1_Sales_Analytics_Dashboard.pbix` – Power BI report
- `Case_1_Sales_Analytics_Dashboard.pdf` – PDF export of the dashboard

## 💡 Key Skills Demonstrated

- Data Import
- Data Cleaning
- Power Query
- Data Modelling
- DAX
- KPI Development
- Data Visualisation
- Slicers
- Conditional Formatting
- Drill-through
- Dashboard Design

## 👩‍💻 Author

**Lavanya A.**

GitHub: [Lavanyashekhar](https://github.com/Lavanyashekhar)
