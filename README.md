

# AdventureWorks – Business Performance Analysis using Power BI

## 📌 Project Overview

This project focuses on analysing business performance using the AdventureWorks sample business dataset.

An interactive Power BI dashboard was developed to analyse sales performance, financial metrics, product profitability, customer activity, and budget achievement.

The objective is to transform raw business data into meaningful insights that support data-driven business decisions.

## 🎯 Project Objectives

* Analyse overall sales and revenue performance.
* Evaluate gross profit and profit margins.
* Identify top-performing products and categories.
* Understand regional sales performance.
* Monitor customer activity and product returns.
* Compare actual revenue against budget.
* Track business performance through interactive dashboards.

## 🛠️ Tools and Technologies

| Tool               | Purpose                              |
| ------------------ | ------------------------------------ |
| Microsoft Power BI | Dashboard development                |
| Power Query        | Data cleaning and transformation     |
| DAX                | Measures and calculated columns      |
| Data Modelling     | Establishing table relationships     |
| Data Visualisation | Interactive charts, KPIs and reports |

## 📂 Dataset Information

The project uses 11 original CSV files.

The three yearly sales files (2020, 2021 and 2022) were appended into one consolidated Sales Data table.

After appending, the data model contains nine main tables.

### Data Profile

| Metric                      |  Value |
| --------------------------- | -----: |
| Original CSV Files          |     11 |
| Tables After Appending      |      9 |
| Total Rows Before Cleaning  | 77,277 |
| Total Columns Across Tables |     49 |
| Sales Records               | 56,046 |
| Unique Sales Orders         | 25,164 |
| Unique Customers in Sales   | 17,416 |
| Customer Records            | 18,154 |
| Products                    |    293 |
| Product Subcategories       |     37 |
| Product Categories          |      4 |
| Territories                 |     10 |
| Return Records              |  1,809 |
| Discount Records            |     12 |
| Calendar Records            |    912 |

**Data Coverage:** January 2020 – June 2022.

*Note: The row count represents the original data profile before cleaning. Five error rows were removed from Customer Data during the cleaning process.*

## 🔄 Data Cleaning and Transformation

The following processes were performed using Power Query:

* Imported multiple CSV files.
* Appended the three yearly sales datasets.
* Reviewed column names and data types.
* Identified and handled data errors.
* Removed five error rows from Customer Data.
* Prepared tables for data modelling and analysis.

## 🧩 Data Modelling

The project uses a relational data model connecting sales information with customer, product, territory, and calendar tables.

Main relationships include:

* Customer Data → Sales Data
* Product Data → Sales Data
* Territory Data → Sales Data
* Calendar Data → Sales Data
* Product Categories → Product Subcategories
* Product Subcategories → Product Data

These relationships allow users to analyse sales from different business perspectives.

## 📐 DAX Measures

Some of the important DAX measures developed include:

* Total Revenue
* Net Revenue
* Total Product Cost
* Gross Profit
* Gross Profit Margin %
* Total Orders
* Total Quantity
* Unique Customers
* Total Discount
* Total Returned Quantity
* Return Rate %
* Previous Year Net Revenue
* Net Revenue YoY Change %
* Budget Variance
* Budget Achievement

## 📊 Dashboard Pages

### 1. Executive Overview

Provides a high-level summary of business performance through KPIs and revenue analysis.

Key metrics:

* Net Revenue
* Gross Profit
* Total Orders
* Return Rate

### 2. Sales Analytics

Focuses on sales performance, product categories, regional revenue, and top-performing products.

Key metrics:

* Total Revenue
* Total Quantity Sold
* Unique Customers
* Total Discount

### 3. Financial Analytics

Provides insights into business profitability and financial performance.

Key metrics:

* Total Revenue
* Total Product Cost
* Gross Profit
* Gross Profit Margin

### 4. Budget & Business Performance

Evaluates budget achievement and revenue performance.

Key metrics:

* Total Budget
* Actual Revenue
* Budget Variance
* Budget Achievement

## 💡 Key Business Insights

The dashboard provides insights into:

* Overall revenue and profitability.
* Product category and regional performance.
* Top-performing products.
* Monthly revenue trends.
* Gross profit and profit margins.
* Budget achievement and revenue shortfalls.
* Customer returns and discounts.

## 📁 Project Files

The repository includes:

* Power BI dashboard (.pbix)
* Dataset files (where redistribution is permitted)
* Dashboard screenshots
* Project presentation
* DAX documentation

## 🚀 How to Use This Project

1. Download or clone this repository.
2. Obtain the dataset files from the permitted source.
3. Open the Power BI `.pbix` file using Microsoft Power BI Desktop.
4. If necessary, update the data source paths.
5. Refresh the dataset.
6. Explore the four interactive dashboard pages.

## 📚 Learning Outcomes

This project helped me gain practical experience in:

* Power BI dashboard development.
* Power Query data transformation.
* DAX calculations.
* Relational data modelling.
* Business and financial analysis.
* Data storytelling and visualisation.

## 👩‍💻 Author

Created as a Data Analytics portfolio project.

**Tools:** Microsoft Power BI | Power Query | DAX

---

Thank you for exploring my project!

Feedback and suggestions are welcome.
