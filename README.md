# 🛒 E-commerce Sales Analysis – SQL | Power BI | Python | Excel  

![Status](https://img.shields.io/badge/Project-Completed-brightgreen?style=flat-square)  
![Python](https://img.shields.io/badge/Python-3.x-blue?style=flat-square&logo=python)  
![SQL](https://img.shields.io/badge/SQL-MySQL-orange?style=flat-square&logo=mysql)  
![Power BI](https://img.shields.io/badge/PowerBI-Dashboard-yellow?style=flat-square&logo=powerbi)  
![Excel](https://img.shields.io/badge/Excel-Analysis-green?style=flat-square&logo=microsoft-excel)  

---
## 📊 Visual Highlights  

### 1️⃣ Sales Performance Over Time  
![Sales Trend](images/sales_trend.png)  <!-- Add a png of sales performance over time from powerbi -->

### 2️⃣ Top Product Categories  
![Top Categories](images/top_categories.png)  <!-- Add a png of top product category from powerbi --> 

### 3️⃣ Customer Segmentation (Pareto Analysis)  
![Pareto Analysis](images/pareto.png)  <!-- Add a png of Customer Segmentation from powerbi -->

### 4️⃣ Interactive Dashboard Demo  
![Dashboard Demo](images/dashboard_demo.gif)  <!-- Add a png of Interactive Dashboard Demo from powerbi -->

---

## 📖 Project Overview  
This project analyzes one year of Brazilian e-commerce sales data from the **Olist dataset** to uncover key trends, customer behaviors, and product performance.  

The goal is to simulate a real-world analytics workflow where raw transactional data is transformed into **actionable business insights** using **data cleaning, SQL querying, Python analysis, and Power BI dashboarding**.  

---

## 🎯 Business Problems  
Olist, a Brazilian e-commerce platform, wants to:  
1. Understand overall sales performance and seasonal patterns  
2. Identify profitable products and top customers  
3. Improve marketing targeting and inventory planning  
4. Build an interactive dashboard for continuous monitoring  

---

## 📊 Objectives  
- Track **monthly and weekly revenue trends**  
- Identify **top-selling products** and categories  
- Calculate **profit margins** per product/category  
- Segment customers by **region and purchase frequency**  
- Perform **Pareto analysis (80/20 rule)** to identify high-value customers  
- Visualize insights in an **interactive Power BI dashboard**  

---

## 🧰 Tools & Technologies  
- **SQL** → Data cleaning, joins, and aggregations  
- **Python (Pandas, Matplotlib, Seaborn)** → Data wrangling, EDA, and visualization  
- **Power BI** → Interactive dashboards with slicers, KPIs, and drilldowns  
- **Excel** → Quick pivot table checks and data validation  
- **GitHub** → Version control and portfolio hosting  

---

## 📂 Dataset  
- **Source:** [Olist Brazilian E-Commerce Dataset – Kaggle](https://www.kaggle.com/datasets/olistbr/brazilian-ecommerce)  
- **Files Used:**  
  - `olist_orders_dataset.csv` – Order details and status  
  - `olist_customers_dataset.csv` – Customer IDs and location  
  - `olist_order_items_dataset.csv` – Products and prices  
  - `olist_products_dataset.csv` – Product category metadata  
  - `olist_order_payments_dataset.csv` – Payment details  
  - `product_category_name_translation.csv` – Category translations (Portuguese → English)  
  - `olist_geolocation_dataset.csv` – Geographical locations  
  - `olist_orders_review_dataset.csv` – Customer reviews  
  - `olist_sellers_dataset.csv` – Seller information  

---

## 📂 Project Structure  
```plaintext
Ecommerce-Sales-Analysis/
├── data/                  # All datasets
│   ├── raw/               # Original data from Kaggle
│   ├── cleaned/           # Processed datasets (via Python scripts)
├── scripts_python/jupyter_notebook_scripts
# Python scripts for cleaning + EDA
  ├── data_import.py          # Import & save raw → processed CSVs
  ├── data_cleaning.py        # Clean each dataset (duplicates, strip, casing)
  ├── data_transformation.py  # Transform/join data for analysis 
  ├── main.py                 # Run everything together
        
├── sql/                   # SQL scripts (validation + joins)
├── dashboards/            # Power BI dashboards
├── images/                # Screenshots (charts, dashboards)
├── insights.md            # Key findings & recommendations
├── README.md              # Project documentation
└── requirements.txt       # Python dependencies








