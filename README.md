# 💊 Pharmaceutical Sales Analytics | Power BI

## 📘 Overview
This project analyzes sales data from a global pharmaceutical manufacturing company to evaluate performance across **regions, distributors, products, and sales teams**. The objective is to transform raw distributor-level sales data into actionable insights using **Power BI** for business and sales decision-making.

---

## ✨ Key Features
⚡ Built using **Power BI Desktop**  
⚡ Data transformation and modeling with **Power Query Editor**  
⚡ Published via **Power BI Service** for web-based access (no login required)  
⚡ **Multi-page interactive dashboards** for detailed analysis and insights  

---

## 🌍 Business Context
The organization operates across multiple international markets and follows a **distributor-based sales model**. Rather than selling directly to customers, the company collaborates with regional distributors who periodically share sales data in CSV format.

This analysis focuses on improving visibility into **retail-level performance**, with one of the studied regions covering **Germany and Poland** as part of the broader global footprint.

---

## 🎯 Objectives
The analysis was designed to meet the needs of multiple stakeholders:

### 🧑‍💼 Executive Leadership
- High-level overview of overall sales performance  
- Trends by year and month  
- Identification of top drug classes, products, and customer cities  

### 📊 Sales Managers & Representatives
- Distributor-wise and product-wise sales analysis  
- Top-performing products, customers, and cities  
- Channel and sub-channel contribution insights  

### 🏷️ Head of Sales
- Sales performance by sales teams and managers  
- Product and product-class contribution by team  
- Flexible filtering by **year and month**  

---

## 📂 Dataset Description
The dataset is consolidated from multiple distributors and represents **wholesale-to-retail pharmaceutical sales data**.

| Field Name | Description |
|----------|-------------|
| `Distributor` | Name of the wholesaler |
| `Customer Name` | Name of the customer |
| `City` | Customer city |
| `Country` | Customer country |
| `Latitude` | Geographic latitude |
| `Longitude` | Geographic longitude |
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

## 🔍 Analysis Approach

### 🧪 Exploratory Data Analysis (EDA)
Initial data exploration was performed using **Python (Pandas)** to assess data quality and structure. This included:
- Checking for missing or inconsistent values  
- Identifying outliers and invalid entries (e.g., negative sales)  
- Classifying categorical and numerical variables  
- Reviewing value distributions and ranges  

---

### 🧹 Data Cleaning & Transformation
Data preparation was carried out using **Power Query Editor**, where:
- Column names were standardized  
- Appropriate data types were assigned  
- The dataset was validated for reporting readiness  

Only minimal corrections were required due to the overall cleanliness of the data.

---

### 🧩 Data Modeling
The flat dataset was redesigned into a **star schema**, separating **fact** and **dimension** tables. This structure improves performance and enables efficient slicing and drill-down analysis across multiple business dimensions.

---

## 📊 Dashboard Development
Three interactive report pages were developed in **Power BI Desktop**:

### 1️⃣ Executive Summary
- Overall sales KPIs and trends  
- Quick view of top-performing products and regions  

### 2️⃣ Distributor & Customer Analysis
- Sales contribution by distributors and customers  
- Drill-down to product-level performance  

### 3️⃣ Sales Team Performance
- Comparative analysis across sales teams and managers  
- Product and product-class contribution insights  

All dashboards include **interactive slicers** for filtering by **year and month**.

---

## 🚀 How to Access the Report

### 🌐 Web Access (Recommended)
The dashboard is published via **Power BI Service** and can be accessed through a read-only web link, providing full interactivity without requiring a Power BI login.

### 💻 Local Access
The `.pbix` file can be downloaded and opened in **Power BI Desktop**. It contains the complete transformed dataset and data model, allowing further customization or experimentation.

### 📂 Dataset Access
To download the dataset, **[click here](https://drive.google.com/file/d/1OlhJlkcGrPeVWjyLM7ya3UGMVZd_afM7/view?usp=sharing)**.


---
