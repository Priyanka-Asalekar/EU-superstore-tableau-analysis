# 📊 EU Superstore Sales Analysis — Tableau Project

An interactive retail analytics project built in **Tableau Desktop** to explore sales performance, customer activity, order trends, and delivery performance using the EU Superstore dataset.

\---

## 📌 Project Overview

This project uses the **Orders** sheet from the EU Superstore Excel workbook, containing **10,000 order-line records and 20 fields**. The packaged Tableau workbook includes sales and order KPIs, customer analysis, delivery-time analysis, customer rankings, and a dynamic X–Y analysis view.

The aim is to make it easier to explore retail performance through interactive dashboards, filters, and parameters.

## 🎯 Project Objectives

* Track key metrics such as sales, profit, quantity, orders, customers, and average order value.
* Analyze customer purchase frequency and identify top customers by sales or order frequency.
* Compare sales, profit, and order activity over time.
* Explore product and sub-category performance.
* Review delivery time and order distribution by shipping mode.
* Use parameters to change the dimension and measure shown in the dynamic X–Y view.
* Filter and explore the dashboards interactively.

## 🗂 Dataset Description

**Source file:** `Sample - EU Superstore.xlsx`

The Excel workbook contains three sheets: `Orders`, `Returns`, and `People`. **The Tableau analysis described in this project uses the `Orders` sheet**, which contains 10,000 rows and 20 fields.

|Field|Description|
|-|-|
|`Row ID`|Row-level identifier|
|`Order ID`|Order identifier|
|`Order Date`|Date the order was placed|
|`Ship Date`|Date the order was shipped|
|`Ship Mode`|Shipping method|
|`Customer ID` / `Customer Name`|Customer identifiers and names|
|`Segment`|Customer segment|
|`City`, `State`, `Country`, `Region`|Geographic attributes|
|`Product ID` / `Product Name`|Product identifiers and names|
|`Category` / `Sub-Category`|Product classification|
|`Sales`|Sales amount|
|`Quantity`|Quantity ordered|
|`Discount`|Discount value|
|`Profit`|Profit amount|

## 🛠 Tools \& Tableau Features

* **Tableau Desktop** — worksheets and interactive dashboards
* **Microsoft Excel** — source dataset
* **Calculated fields** — KPI totals, average order value, and delivery days
* **Parameters** — dynamic X-axis dimension, Y-axis measure, and Top N selection
* **Filters and dashboard actions** — interactive data exploration
* **Packaged workbook (`.twbx`)** — Tableau workbook with an embedded data extract

## 🔄 Project Workflow

1. Connect Tableau to the EU Superstore Excel data.
2. Review the Orders fields and create calculated fields for key metrics.
3. Build KPI worksheets for sales, profit, quantity, orders, customers, average order value, and delivery days.
4. Create customer, product, sales-trend, and shipping-mode views.
5. Add parameters for dynamic dimension/measure selection and Top N customer analysis.
6. Combine worksheets into interactive dashboards and add filters/actions.
7. Review dashboard values and compare them with the source data.

## 📊 Key Metrics \& Findings

The following values are reported in the project presentation and dashboard:

|Metric|Reported value|
|-|-:|
|Total Sales|₹2,938,089.06|
|Total Profit|₹372,829.74|
|Total Quantity|37,773|
|Distinct Orders|4,596|
|Total Customers|795|
|Average Order Value|₹639.27|
|Average Order-to-Ship Time|4.01 days|

### Sales analysis

* **Technology** is the top sales category at approximately ₹1.11M.
* **Office Supplies** follows at approximately ₹1.05M.
* **Furniture** contributes approximately ₹0.78M.
* The **Central** region is shown as the highest-sales region at approximately ₹1.72M.

### Order and delivery patterns

* **Standard Class** has 2,857 distinct orders.
* **Second Class** has 1,014 distinct orders.
* **First Class** has 760 distinct orders.
* **Same Day** has 266 distinct orders.

### Customer analysis

* The dashboard includes top customers by sales and purchase frequency, with a configurable Top N parameter.
* The customer/order dashboard also includes customer details and KPI views for customers, orders, average order value, and delivery days.

## 🎛️ Dashboard Interactivity

The packaged workbook contains two dashboards:

* **Sales Analysis Dashboard** — sales, orders, profit, quantity, customers, sales by a selectable dimension, and product sales-versus-profit analysis.
* **Customer \& Order Analysis Dashboard** — customer and order KPIs, customer details, orders by ship mode, top customers by sales, and top customers by purchase frequency.

The workbook also includes filters for fields such as Region, Country, Year, and Segment, plus parameters for dynamic X-axis dimension, Y-axis measure, and Top N selection. Available controls may vary by dashboard.

## 📁 Repository Structure

```text
Tableau-EU-Superstore-Analysis/
├── README.md
├── Tableau Sample EU Superstore sales analysis.twbx
├── Sample-EU Superstore.xlsx
└── EU Superstore Tableau Project Presentation.pptx
```

## ▶️ How to Use the Project

1. Download or clone this repository.
2. Open the `.twbx` file using **Tableau Desktop**.
3. If Tableau prompts for a data connection, check that the packaged workbook's data extract is available or reconnect to `Sample - EU Superstore.xlsx`.
4. Open either dashboard and explore the filters and parameters.
5. Change the X-axis dimension, Y-axis measure, or Top N selection to explore different views.
6. Open the PowerPoint presentation for the project overview, objectives, dashboard previews, and key findings.



## 👩‍💻 Skills Demonstrated

* Tableau dashboard and worksheet development
* Calculated fields and KPI creation
* Parameter-driven analysis
* Top N customer analysis
* Sales and profit analysis
* Customer purchase-frequency analysis
* Order and delivery analysis
* Interactive filters and dashboard actions
* Communicating findings through a project presentation

## 👤 Author

**Priyanka Asalekar**  
**Project:** EU Superstore Sales Analysis  
**Tools:**·Tableau Desktop · Excel · Calculated Fields · Parameters

\---

⭐ This project demonstrates how Tableau can turn retail order data into interactive views for sales, customer, product, and delivery analysis.

