# 🛒 E-commerce Sales Analysis – SQL | Power BI | Python | Excel  

![Status](https://img.shields.io/badge/Status-In%20Progress-yellow?style=flat-square)  
![Python](https://img.shields.io/badge/Python-3.x-blue?style=flat-square&logo=python)  
![SQL](https://img.shields.io/badge/SQL-MySQL-orange?style=flat-square&logo=mysql)  
![Power BI](https://img.shields.io/badge/PowerBI-Dashboard-yellow?style=flat-square&logo=powerbi)  
![Excel](https://img.shields.io/badge/Excel-Analysis-green?style=flat-square&logo=microsoft-excel)  

---

## 📊 Visual Highlights  

### 1️⃣ Sales Performance Over Time  
![Sales Trend](images/sales_trend.png)  

### 2️⃣ Top Product Categories  
![Top Categories](images/top_categories.png)  

### 3️⃣ Customer Segmentation (Pareto Analysis)  
![Pareto Analysis](images/pareto.png)  

### 4️⃣ Interactive Dashboard Demo  
![Dashboard Demo](images/dashboard_demo.gif)  

---

## 📖 Project Overview  
This project analyzes **Brazilian e-commerce sales data (Olist dataset)** to uncover **customer behavior, product performance, and sales trends**.  

The workflow follows a **real-world analytics pipeline**:  
- Importing **raw transactional data**  
- Performing **data cleaning & transformation**  
- Querying with **SQL** for KPI validation  
- Running **EDA in Python**  
- Designing an **interactive Power BI dashboard**  

---

## 🎯 Business Problems  
Olist, a Brazilian marketplace, wants to:  
1. Track **sales performance & seasonality**  
2. Identify **profitable product categories and top customers**  
3. Improve **marketing & customer retention**  
4. Monitor KPIs with an **interactive dashboard**  

---

## 📊 Objectives  
- Analyze **monthly & weekly revenue trends**  
- Identify **top-selling products & categories**  
- Calculate **profit margins** by category  
- Segment customers by **region & purchase frequency**  
- Perform **Pareto (80/20) analysis**  
- Build a **dashboard for decision-making**  

---

## 🧰 Tools & Technologies  
- **SQL** → Data validation, joins, aggregations  
- **Python (Pandas, Matplotlib, Seaborn)** → Data wrangling, EDA, visualization  
- **Power BI** → Interactive dashboards with KPIs & slicers  
- **Excel** → Pivot tables for quick checks  
- **GitHub** → Version control & portfolio hosting  

---

## 📂 Dataset  
**Source:** [Olist Brazilian E-Commerce Dataset – Kaggle](https://www.kaggle.com/datasets/olistbr/brazilian-ecommerce)  

**Files Used:**  
- `olist_orders_dataset.csv` – Orders & status  
- `olist_customers_dataset.csv` – Customer IDs & location  
- `olist_order_items_dataset.csv` – Products & pricing  
- `olist_products_dataset.csv` – Product category metadata  
- `olist_order_payments_dataset.csv` – Payments & installments  
- `olist_orders_review_dataset.csv` – Customer reviews  
- `olist_sellers_dataset.csv` – Seller info  
- `olist_geolocation_dataset.csv` – Geographical mapping  
- `product_category_name_translation.csv` – Category translations  

---

## 📂 Project Structure  
```plaintext
Ecommerce-Sales-Analysis/
│
├── data/                         # All datasets
│   ├── raw/                      # Original Kaggle data
│   ├── cleaned/                  # Cleaned datasets
│
├── scripts_python/               # Python scripts
│   ├── data_import.py            # Load raw CSV files
│   ├── data_cleaning.py          # Handle duplicates, missing values
│   ├── data_transformation.py    # Transform & merge datasets
│   ├── eda_analysis.ipynb        # Exploratory Data Analysis
│
├── sql/                          # SQL scripts
│   ├── schema.sql                # Schema creation
│   ├── queries_analysis.sql      # KPI queries
│
├── dashboards/                   # Power BI / Excel dashboards
│   ├── ecommerce_dashboard.pbix  # Power BI dashboard
│   ├── dashboard_screenshots/    # PNG snapshots
│
├── images/                       # Charts & visuals
│   ├── charts/                   # Python EDA charts
│   ├── dashboards/               # Power BI screenshots
│
├── insights.md                   # Insights (to be added later)
├── README.md                     # Documentation
└── requirements.txt              # Python dependencies
```
## ⚙️ How to Run  

Follow these steps to set up and run the project on your local machine:  

### 1️⃣ Clone the Repository  
```bash
git clone https://github.com/your-username/Ecommerce-Sales-Analysis.git
cd Ecommerce-Sales-Analysis
# Windows
python -m venv venv
venv\Scripts\activate

# Mac/Linux
python3 -m venv venv
source venv/bin/activate
pip install -r requirements.txt
python scripts_python/data_cleaning.py
python scripts_python/data_transformation.py
jupyter notebook scripts_python/eda_analysis.ipynb
dashboards/ecommerce_dashboard.pbix
```
#requirement files
```
# Core Python libraries
pandas
numpy

# Visualization
matplotlib
seaborn

# Jupyter Notebook
notebook
jupyterlab

# SQL connection (MySQL / PostgreSQL)
mysql-connector-python
SQLAlchemy
psycopg2-binary

# Data transformation / cleaning helpers
openpyxl
xlrd

# Power BI is external (install separately)

