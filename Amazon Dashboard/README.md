# 📊 Amazon Product Pricing & Rating Analysis – Power BI Dashboard

## 📌 Overview

This project presents an **interactive Power BI dashboard** designed to analyze **Amazon product data** with a focus on **pricing, discounts, ratings, and customer engagement**.

The dashboard helps uncover patterns in product distribution, customer satisfaction, and pricing strategies across different product categories, enabling **data-driven insights for e-commerce analysis**.

---

## 🎯 Objectives

* Analyze product distribution across Amazon categories
* Understand customer rating behavior
* Study the impact of pricing and discounts on customer engagement
* Provide an interactive dashboard for exploratory analysis

---

## 📂 Project Structure

```
Amazon Dashboard/
│
├── Dataset/
│   └── amazon.csv
│
├── Dashboard/
│   └── Amazon_Product_Pricing_&_Rating_Analysis.pbix
│
├── Images/
│   └── dashboard_preview.png
│
└── README.md
```

---

## 🧹 Data Preparation

Data cleaning and transformation were performed using **Power Query** in Power BI:

* Removed irrelevant and text-heavy columns (e.g., product descriptions, reviews)
* Converted price and discount fields into numeric formats
* Handled invalid or missing rating values by replacing errors with nulls
* Split category data into **Main Category** and **Subcategory**
* Ensured consistency and accuracy for analysis

No DAX was used — the focus was on **clean data modeling and built-in aggregations**.

---

## 📊 Dashboard Features

### 🔹 Key Performance Indicators (KPIs)

* **Average Product Rating**
* **Total Products Analyzed**
* **Average Discount Percentage**
* **Average Discounted Selling Price**

### 🔹 Visualizations

* **Bar Chart**: Product distribution by category
* **Column Chart**: Average rating by category
* **Scatter Plot**: Relationship between price, rating, and customer engagement

### 🔹 Interactivity

* Category and subcategory slicers
* Rating range filter
* Discount percentage filter

These slicers allow users to dynamically explore specific segments without modifying the dashboard structure.

---

## 📈 Key Insights

* Electronics and Home categories dominate Amazon’s product listings
* Average product ratings remain consistently high (around 4+) across categories
* Higher discounts do not necessarily result in higher ratings
* Customer engagement is strongest in **mid-priced products**, not premium ones

---

## 🛠️ Tools & Technologies

* **Power BI Desktop**
* **Power Query** for data cleaning and transformation
* CSV dataset

---

## ▶️ How to Use the Dashboard

1. Download the `.pbix` file from the Dashboard folder
2. Open it using **Power BI Desktop**
3. Interact with slicers to explore category-wise and price-based insights
4. Analyze trends using the provided visualizations

---

## 🚀 Future Enhancements

* Time-based analysis (price and rating trends over time)
* Sentiment analysis on customer reviews
* Seller-level performance metrics
* Advanced analytics using DAX

---

## 👩‍💻 Author

**Anjali Barge**

Final-Year B.E. Computer Engineering Student

Interested in Data Analytics, Power BI, AI/ML, and Business Intelligence

---

## ⭐ Acknowledgements

This project was created for learning and academic purposes to strengthen skills in **data analytics, visualization, and dashboard design**.
