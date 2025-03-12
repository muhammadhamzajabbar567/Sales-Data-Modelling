# 📊 Sales Data Modelling

This repository contains a **Sales and Budget Data Model** for business intelligence and analytics. It includes **fact tables** for **sales transactions** and **budgeting**, along with **dimension tables** to support efficient reporting.

---

## 🚀 Overview
The **Sales Data Modelling** project is designed to structure and analyze sales data efficiently. It follows a **fact-based schema** with two key fact tables (**Sales & Budget**) and multiple dimension tables.

This model enables:  
✅ **Sales Performance Analysis**  
✅ **Forecasting & Trend Analysis**  
✅ **Budget vs. Actual Comparisons**  

---

## 📂 Files & Structure
📌 **SALES (FACT TABLE).png** - Visualization of the **Sales Fact Table**  
📌 **FACTBUDGET (FACT TABLE).png** - Visualization of the **Budget Fact Table**  
📌 **SALES DATA MODEELLING.png** - Complete **Data Model** showing relationships  
📌 **FactBudget.csv** - Budgeted sales data in CSV format  
📌 **Sales.zip** - Compressed file containing sales-related data  
📌 **SALES DATA MODEELLING.pbix** - **Power BI** report file  

---

## 🛠 Data Model Relationships
The schema follows a **star schema** with the following relationships:

### **1️⃣ Sales Fact Table**
🔹 Linked to **Product, Customer, Store, Salesperson, and Date Dimensions**  
🔹 Contains **Quantity Sold, Revenue, Discount, and Profit**  

### **2️⃣ Budget Fact Table**
🔹 Linked to the **same dimensions** to enable **Actual vs. Budget analysis**  

### **3️⃣ Dimension Tables**
🔸 **Product Dimension**: Links via `Product ID`  
🔸 **Customer Dimension**: Links via `Customer ID`  
🔸 **Date Dimension**: Links via `Order Date` & `Ship Date`  
🔸 **Store Dimension**: Links via `Store ID`  
🔸 **Salesperson Dimension**: Links via `Salesperson ID`  

---

## 📊 Key Features
✔ **Actual vs. Budgeted Sales Comparison**  
✔ **Sales Trends Analysis (Time-based, Product-based, Region-based)**  
✔ **Profitability & Discount Analysis**  
✔ **Customer & Salesperson Performance Tracking**  
✔ **Optimized for Power BI & Data Warehousing**  

---

## 📌 Data Model Structure

### **🔹 Sales Fact Table**
![Sales Fact Table](https://raw.githubusercontent.com/muhammadhamzajabbar567/Sales-Data-Modelling/main/SALES%20(FACT%20TABLE).png)

### **🔹 Budget Fact Table**
![Budget Fact Table](https://raw.githubusercontent.com/muhammadhamzajabbar567/Sales-Data-Modelling/main/FACTBUDGET%20(FACT%20TABLE).png)

### **🔹 Sales Data Modelling**
![Sales Data Modelling](https://raw.githubusercontent.com/muhammadhamzajabbar567/Sales-Data-Modelling/main/SALES%20DATA%20MODEELLING.png)

---

## ⚙️ Technologies Used
- **SQL (Microsoft SQL Server, PostgreSQL, MySQL)** – Data storage & management  
- **Power BI / Tableau** – Data visualization & reporting  
- **ETL Pipelines** – Data extraction, transformation, and loading  

---

## 🚀 How to Use
### **1️⃣ Clone the repository**
```sh
git clone https://github.com/muhammadhamzajabbar567/Sales-Data-Modelling.git


---

### **✅ Enhancements in This README**  
- 📌 **Well-structured sections** for clarity.  
- 🎨 **Icons & emojis** for better readability.  
- 🔗 **Clickable links** for direct navigation.  
- 🖥 **Formatted code blocks** for commands.  

This **README** makes your **GitHub repository professional & easy to understand**. 🚀 Let me know if you need any further refinements! 😊
