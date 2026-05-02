# 📊 Customer Behavior Analytics (SQL + Python + Power BI)

## 🔍 Project Overview

This project focuses on analyzing customer shopping behavior using an end-to-end data analytics pipeline.
It covers data cleaning, database integration, analysis, and visualization.

The goal is to extract meaningful insights from raw customer data and present them using interactive dashboards.

---

## ⚙️ Tech Stack

* **Python** (Pandas, Matplotlib)
* **MySQL** (Database & Querying)
* **Power BI** (Data Visualization)
* **SQLAlchemy / PyMySQL** (Database Connection)

---

## 🔄 Workflow (ETL Pipeline)

1. **Data Collection**

   * Dataset loaded from CSV file

2. **Data Cleaning (Python)**

   * Handled missing values
   * Standardized column names
   * Created new features (age_group, purchase_frequency_days)

3. **Data Storage (MySQL)**

   * Created structured tables
   * Inserted cleaned data into database

4. **Data Retrieval (SQL → Python)**

   * Used SQL queries to fetch and aggregate data
   * Loaded data into Pandas DataFrame

5. **Data Analysis**

   * Category-wise sales analysis
   * Customer segmentation by age group
   * Purchase behavior insights

6. **Visualization (Power BI)**

   * Interactive dashboard creation
   * KPI tracking and trend analysis

---

## 📈 Key Insights

* 📌 **Top Selling Category:** Clothing
* 📌 **Most Active Age Group:** Adult
* 📌 **High Frequency Buyers:** Weekly & Bi-Weekly customers
* 📌 **Customer Retention:** Subscription users show higher purchase frequency

---

## 📊 Dashboard Preview

![Dashboard Preview](images/dashboard_preview.png)

---

## 📁 Project Structure

```
customer-analytics-project/
│
├── DATA_SET/customer_shopping_behavior.csv
├── EXCEL/
├── POWER BI/
├── PYTHON USING PANDAS AND NUMPY DATA ANALYSIS/Customer_Shopping_Behavior_Analysis.ipynb 
├── SQL/customer_behavior_sql_queries.sql
└── README.md

```

---

## 🚀 How to Run the Project

1. Clone the repository:

```
git clone <your-repo-link>
```

2. Install dependencies:

```
pip install -r requirements.txt
```

3. Run Python scripts:

```
python python/01_data_cleaning.py
python python/02_mysql_connection.py
python python/03_data_insert.py
python python/04_analysis.py
```

4. Open Power BI file:

* Navigate to `powerbi/` folder
* Open `.pbix` file

---

## 🧠 Learning Outcomes

* Built an end-to-end data analytics pipeline
* Integrated Python with MySQL
* Performed real-world data cleaning and transformation
* Created business insights using SQL and visualization tools

---

## 🔮 Future Improvements

* Implement Machine Learning models for prediction
* Automate ETL pipeline
* Deploy dashboard for real-time analytics

---

## 🙌 Author

**Vinayak Nimonkar**
Aspiring Data Analyst | Python | SQL | Power BI

---
