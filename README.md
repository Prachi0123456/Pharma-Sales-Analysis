# 💊 Pharmaceutical Sales Analytics | SQL & Power BI

This project analyzes pharmaceutical sales data to evaluate performance across **regions, distributors, products, and sales teams**. SQL is used for data querying and KPI extraction, while Power BI is used to build interactive dashboards for business decision-making.

---

## 📌 Project Overview

The pharmaceutical company operates through a distributor-based sales model across multiple international markets. Sales data is shared in CSV format, enabling analysis at both distributor and retail levels.

The objective of this project is to perform **end-to-end sales analysis**—from data extraction and aggregation using SQL to visualization and insight delivery using Power BI.

---

## 🛠️ Tools Used

- **SQL Server** — For querying transactional data, aggregations, KPIs, and trend analysis  


- **Power BI Desktop** — For interactive dashboards and business reporting  
 

- **Power Query** — For data cleaning and transformation within Power BI  

- **Excel / CSV** — Raw distributor-level sales dataset  
  

---

## 📂 Dataset Description

The dataset contains wholesale-to-retail pharmaceutical sales transactions with the following attributes:

| Column Name | Description |
|------------|------------|
| `Distributor` | Name of the wholesaler |
| `Customer Name` | Name of the customer |
| `City` | Customer city |
| `Country` | Customer country |
| `Channel` | Buyer type (Hospital, Pharmacy) |
| `Sub-channel` | Buyer sector (Government, Private, etc.) |
| `Product Name` | Name of the drug |
| `Product Class` | Drug category (e.g., Antibiotics) |
| `Quantity` | Units sold |
| `Price` | Selling price |
| `Sales` | Total sales value |
| `Month` | Month of sale |
| `Year` | Year of sale |
| `Sales Rep` | Sales representative |
| `Manager` | Sales manager |
| `Sales Team` | Sales team identifier |

---

## ❓ Business Questions Answered Using SQL

### ✅ Basic Analysis
1. Total sales, quantity, and revenue trends  
2. Sales distribution by product class and channel  
3. Monthly and yearly sales summary  
4. Top-performing products by sales and quantity  
5. Customers with single vs repeat purchases  

### 🔁 Intermediate Analysis
1. Sales and revenue by region and distributor  
2. Product and product-class performance comparison  
3. Channel and sub-channel contribution analysis  
4. Profitability trends by product category  
5. Sales team contribution by region  

### 🔍 Advanced Analysis
1. Month-over-month growth using `LAG()`  
2. Top-performing products by region using `RANK()`  
3. Identification of low-performing products  
4. Sales trend analysis across time periods  
5. Sales team performance ranking and contribution analysis  

---

## 📊 Dashboards & Insights

Power BI dashboards were created to support different stakeholder needs:

- **Executive Summary** – High-level KPIs, trends, and top-performing products and regions  
- **Distributor & Customer Analysis** – Sales breakdown by distributors, customers, channels, and products  
- **Sales Team Performance** – Comparative analysis across sales teams, managers, and product classes  

All dashboards include **interactive slicers and drill-downs** for flexible analysis.

---

## 🚀 Outcome

This project demonstrates a complete **analytics workflow**, combining **SQL-based data extraction** with **Power BI visualization** to deliver actionable insights. It reflects practical, real-world business analytics focused on clarity, performance tracking, and decision support.
