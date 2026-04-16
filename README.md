# 🛍️ Customer Shopping Behavior Analysis

## 📌 Project Overview

This project focuses on analyzing customer shopping behavior using transactional retail data to uncover meaningful insights that drive business decisions. The objective is to understand purchasing patterns, customer segments, and key factors influencing buying behavior.

The project simulates a real-world business scenario where a retail company aims to improve **sales, customer engagement, and long-term loyalty** through data-driven strategies .

---

## 🎯 Business Problem

A retail company observed changes in purchasing patterns across:

* Customer demographics
* Product categories
* Sales channels

The key question addressed:

> **How can the company leverage consumer shopping data to identify trends, improve customer engagement, and optimize marketing and product strategies?** 

---

## 📊 Dataset Summary

* **Total Records:** 3,900 transactions

* **Columns:** 18 features

* **Key Data Includes:**

  * Customer demographics (Age, Gender, Location, Subscription Status)
  * Purchase details (Category, Item, Amount, Season, Size, Color)
  * Behavioral data (Discounts, Reviews, Purchase Frequency, Shipping Type)

* **Data Issue:**

  * Missing values found in *Review Rating* column (handled during preprocessing) 

---

## ⚙️ Project Workflow

### 1️⃣ Data Preparation & Cleaning (Python 🐍)

* Data loading using **pandas**
* Handling missing values (median imputation by category)
* Feature engineering:

  * Age groups creation
  * Purchase frequency transformation
* Column standardization (snake_case)
* Data validation & consistency checks
* Data exported to SQL database for further analysis 

---

### 2️⃣ Data Analysis (SQL 🗄️)

Performed business-driven queries to extract insights:

* Revenue comparison by gender
* High-spending discount users
* Top-rated products
* Shipping type impact on spending
* Subscriber vs non-subscriber analysis
* Discount-dependent products
* Customer segmentation (New, Returning, Loyal)
* Revenue contribution by age group

📌 Example insight (from analysis):

* Loyal customers form the majority segment (~3116 users)
* Express shipping users spend slightly more than standard users
* Certain products heavily depend on discounts 

---

### 3️⃣ Data Visualization (Power BI 📈)

An interactive dashboard was built to visualize:

* Revenue trends
* Customer segments
* Category-wise sales
* Age-group analysis
* Subscription distribution

👉 The dashboard highlights:

* Total customers: ~3.9K
* Average purchase: ~$59.76
* Clear comparison across segments and categories 

---

## 📈 Key Insights

* **Young adults contribute the highest revenue**
* **Discounts significantly influence purchase decisions**
* **Subscribers do not necessarily spend more per purchase**
* **Top-rated products can be leveraged for marketing campaigns**
* **Repeat customers form a strong base for loyalty programs**

---

## 💡 Business Recommendations

* 🚀 Promote subscription benefits to increase retention
* 🎯 Target high-revenue age groups with personalized marketing
* 💰 Optimize discount strategies to balance profit margins
* 🛍️ Highlight top-rated & best-selling products
* 🤝 Implement loyalty programs for repeat customers 

---

## 🛠️ Tech Stack

* **Python (Pandas, NumPy)** – Data cleaning & EDA
* **SQL (PostgreSQL/MySQL)** – Data analysis
* **Power BI** – Dashboard & visualization

---

## 👨‍💻 Author

**Kuldeep Vishwakarma**
Aspiring Data Analyst | Python | SQL | Power BI | Excel

---

