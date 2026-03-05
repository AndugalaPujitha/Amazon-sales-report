# 📊 Amazon Sales Analysis Report

## 📌 Project Overview
This project provides an **in-depth analysis of Amazon sales data using Power BI**. The dataset contains order details, product categories, fulfillment types, shipping information, and financial insights. The goal of this project is to analyze sales trends, understand customer behavior, and identify business performance patterns.

---

## 💾 Dataset Information

- **Total Records:** 49 transactions  
- **Total Columns:** 20 attributes  

The dataset includes the following key information:

### Order Details
- Order ID
- Date
- Order Status (Shipped, Delivered, Cancelled)

### Fulfillment & Sales Channel
- Fulfillment Type (Amazon / Merchant)
- Sales Channel (Amazon.in)

### Shipping Details
- Service Level
- Ship City
- Ship State
- Ship Country

### Product Information
- SKU
- Category
- Size
- ASIN

### Courier & Financial Details
- Courier Status
- Quantity Sold
- Currency
- Sales Amount

---

## 📊 Insights & Visualizations

The dashboard built in **Power BI** provides the following insights:

### 1️⃣ Sales Performance
- Total sales and total quantity sold
- Average sales value
- Sales trends over time (weekly / monthly)

### 2️⃣ Product Insights
- Best-performing product categories
- Most popular product sizes
- Category-wise sales distribution

### 3️⃣ Geographical Insights
- Top cities and states contributing to sales
- Sales distribution by country
- Relationship between shipping location and courier status

### 4️⃣ Fulfillment Efficiency
- Percentage of orders successfully shipped
- Fulfillment comparison between **Amazon vs Merchant**
- Delivery performance analysis

### 5️⃣ Customer Type Insights
- Comparison between **B2B and B2C orders**
- Impact of customer type on overall revenue

### 6️⃣ Order Status Analysis
- Ratio of **shipped vs cancelled orders**
- Courier delivery performance

---

## 🔍 Data Quality Observations

During data analysis, the following issues were identified:

- Columns **`New`** and **`PendingS`** contain no values and may be removed.
- Column **`fulfilled-by`** contains many missing values (only about **30% populated**).
- Some fields require **data cleaning and preprocessing** before visualization.

---

## 🛠 Tools & Technologies

- **Power BI** – Data Visualization & Dashboard Creation
- **Microsoft Excel** – Data Processing and Cleaning
- **Data Transformation Techniques** – Handling missing values and improving data quality

---

## 📁 Project Structure

```
Amazon-sales-report-main
│
├── dataset/
│   └── amazon_sales_data.xlsx
│
├── dashboard/
│   └── Amazon_Sales_Dashboard.pbix
│
├── images/
│   └── dashboard_preview.png
│
└── README.md
```

---

## 📈 Key Outcome

This project helps in:

- Understanding **sales trends**
- Identifying **high-performing products**
- Evaluating **regional sales performance**
- Improving **fulfillment and delivery efficiency**
- Supporting **data-driven business decisions**

---

## 🚀 Future Improvements

- Add larger dataset for better analysis
- Implement **predictive sales forecasting**
- Integrate **machine learning for demand prediction**
- Build an **interactive web dashboard**

---
