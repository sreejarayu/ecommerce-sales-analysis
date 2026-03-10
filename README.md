# E-Commerce Sales Analysis Dashboard

## Project Overview

This project performs an end-to-end data analysis of an e-commerce retail dataset to uncover insights about sales performance, customer purchasing behavior, and product demand.

The analysis includes **data cleaning, exploratory data analysis (EDA), customer segmentation using RFM analysis, and an interactive Power BI dashboard** to visualize business insights.

The goal of this project is to demonstrate how data analytics can help businesses understand revenue trends, identify high-value customers, and improve decision-making.

---

## Tools & Technologies Used

* Python
* Pandas
* Jupyter Notebook
* SQL (for analytical queries)
* Power BI
* Data Visualization

---

## Project Workflow

1. Data Collection – Load the e-commerce transaction dataset.
2. Data Cleaning – Remove cancelled orders, handle missing values, and filter invalid transactions.
3. Feature Engineering – Create new features such as revenue, month, and time-based metrics.
4. Exploratory Data Analysis – Analyze product performance, customer behavior, and revenue patterns.
5. Customer Segmentation – Perform RFM analysis to categorize customers based on recency, frequency, and monetary value.
6. Dashboard Development – Build an interactive Power BI dashboard to visualize insights.

---

## Key Business Insights

* The dataset generated approximately **$8.83M in total revenue**.
* **United Kingdom contributes the majority of sales**, indicating a strong market presence in that region.
* Sales show clear **seasonal trends with peaks during the holiday season**, especially in November and December.
* A small number of **high-value customers contribute a significant portion of revenue**.
* Certain home décor products are consistently among the **top-selling items**.

---

## Dashboard Features

The Power BI dashboard includes:

* **KPI Cards**

  * Total Revenue
  * Total Orders
  * Total Customers
  * Average Order Value

* **Top 10 Best-Selling Products**

  * Displays products with the highest quantity sold.

* **Monthly Revenue Trend**

  * Visualizes seasonal sales patterns.

* **Top Customers by Revenue**

  * Identifies high-value customers.

* **Revenue by Country**

  * Displays geographic distribution of sales.

* **Interactive Filters**

  * Country
  * Product Description

---

## Dashboard Preview

![Dashboard](images/dashboard_preview.png)

---

## Project Structure

```
ecommerce-sales-analysis
│
├── data
│   cleaned_ecommerce_data.csv
│
├── notebook
│   ecommerce_analysis.ipynb
│
├── powerbi
│   ecommerce_sales_dashboard.pbix
│
├── images
│   dashboard_preview.png
│
└── README.md
```

---

## Author

Lucky

This project is part of my **Data Analytics Portfolio**, showcasing skills in data cleaning, analysis, and visualization using Python and Power BI.
