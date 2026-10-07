# 🧸 Toy Store Sales Analysis — Power BI Project

## 📌 Project Overview
This Power BI project provides an end-to-end sales performance and business intelligence analysis for a toy retail chain. The objective of this project is to model multi-table transactional data, calculate key performance indicators (KPIs) using custom DAX formulas, and design an interactive dashboard to empower business stakeholders to make data-driven decisions regarding inventory, sales performance, and profitability.

---

## 📂 Repository Structure

Toy-Store-Sales-Analysis/  
├── Data/&emsp;&emsp;# Dataset files  
│   ├── data_dictionary.csv  
│   ├── inventory.csv  
│   ├── products.csv  
│   ├── sales.csv  
│   └── stores.csv  
├── Documentation/&emsp;&emsp;# Project screenshots & visual assets  
│   ├── dashboard_overview (1).png  
│   ├── dashboard_overview (2).png  
│   └── data_model.png  
├── Measures/&emsp;&emsp;# Custom DAX calculations  
│   └── dax_measures.txt  
├── Toy-Store-Sales-Analysis.pbix&emsp;&emsp;# Main Power BI Desktop file  
├── .gitignor&emsp;&emsp;# Git configuration file  
└── README.md&emsp;&emsp;# Project documentation  

---

## 🛠️ Key Requirements & Features Implemented

1. **Data Modeling:** Established relationships between the `sales` fact table and dimension tables in a Star Schema format.
2. **DAX Measures & KPIs:** Created calculated measures for core metrics such as Total Sales, Total Profit, Profit Margin %, Units Sold, and store performance analysis.
3. **Interactive Dashboard Design:** Designed dynamic visual layouts with clear hierarchy, slicers/filters (by City, Product Category, and Date).
4. **User Navigation & Bookmarks:** Integrated navigation bookmarks to enhance user experience and seamlessly toggle between view levels.

---

## 📊 Data Model Schema
The dataset is structured as a **Star Schema** to ensure efficient query performance and streamlined aggregation:
* **Fact Table:** `sales`
* **Dimension Tables:** `products`, `stores`, `inventory`, `data_dictionary`, 'calendar(date table)'

![Data Model Schema](Documentation/data_model.png)

---

## 🖥️ Dashboard Overview

![Dashboard View 1](Documentation/dashboard_overview%20(1).png)
![Dashboard View 2](Documentation/dashboard_overview%20(2).png)

---

## 📐 Key DAX Measures
![Dax Measures](Measures/dax_measures.txt")

---

## 🚀 How to Run the Project

1. Clone or download this repository to your local machine:
   git clone https://github.com/YOUR_USERNAME/toy-store-sales-analysis.git
2. Open `Toy-Store-Sales-Analysis.pbix` in **Power BI Desktop**.
3. Explore the interactive visuals, filter panel, and bookmarks.
