# 📦 Sales Performance & Segmentation Dashboard – Tableau + SQL Project

## 📊 Overview  
This project combines **SQL-based data analysis** with **Tableau dashboards** to deliver a comprehensive view of sales performance and customer behavior. It includes product-level revenue breakdowns, regional sales trends, deal size analysis, and RFM-based customer segmentation — providing valuable insights to boost sales strategies and customer retention.

---

## 🎯 Project Objective  
To analyze sales trends, understand customer value, and build segmentation models using RFM logic — enabling smarter targeting, sales forecasting, and business growth planning.

---

## 🔍 SQL-Driven Analysis  
The backend logic of the project is powered by SQL (`RFM_Segmentation_Sales.sql`), which prepares data for Tableau by:

- Performing **RFM segmentation** based on:
  - **Recency** (last purchase date)
  - **Frequency** (number of transactions)
  - **Monetary** (total amount spent)
- Assigning customer labels:
  - `loyal`, `active`, `new customers`, `slipping away`, `lost customers`, `potential churners`
- Aggregating sales by:
  - Year, product line, deal size, country, order status
- Optimizing data structure for visualization and dashboard filters

---

## 📊 Dashboard Features  

![Dashboard Screenshot – Sales Overview](sc1.JPG)  


![Dashboard Screenshot – Customer Distribution](sc2.JPG)


### 1. 💰 Revenue Breakdown  
- **Product Line Performance** – Classic Cars and Vintage Cars lead in revenue  
- **Revenue by Status** – Majority comes from shipped orders  
- **Country-wise Revenue** – USA, France, and UK are top-performing markets

### 2. 📦 Sales Distribution  
- **Deal Size** – Medium-sized deals dominate overall performance  
- **Yearly & Monthly Trends** – Revenue patterns from 2003 to 2005, highlighting Q4 peaks  
- **Sales Volume Histogram** – Distribution of order quantities

### 3. 🧍 Customer Insights  
- **RFM Segmentation** displayed visually in Tableau  
- **Top Customers by Country**  
- **Quantity Distribution** grouped by bins (low to bulk orders)

---

## 📈 Key Insights  

- 🏆 **Classic Cars** are consistently the top-selling product line  
- 🌍 **USA, France, and UK** drive the majority of global revenue  
- 📦 **Medium-sized deals** contribute the most to total sales  
- 📅 **November** is the most profitable month across all years  
- 📊 **RFM analysis** identifies loyal vs. at-risk customers for personalized marketing

---

## 📌 Recommendations  

1. **Target Loyal Customers**  
   Reinforce retention with loyalty rewards and exclusive offers.

2. **Revive At-Risk Segments**  
   Engage `slipping away` and `lost` customers with reactivation campaigns.

3. **Optimize Stock for Medium Deals**  
   Align product availability to meet the most active deal size segment.

4. **Boost Seasonal Sales**  
   Launch high-impact campaigns in November based on past performance.

5. **Focus on Top Geographies**  
   Localize marketing for high-revenue regions like the US and France.

---

## ✅ Conclusion  
This project demonstrates proficiency in both:

- ✅ SQL data wrangling and business segmentation  
- ✅ Tableau visualization and dashboard storytelling  
- ✅ End-to-end pipeline from raw data to executive-ready insights  
- ✅ Real-world business application: performance monitoring and CRM targeting

---

## 🛠️ Tools Used  
- **SQL Server / MySQL** – Data aggregation, transformation, and segmentation  
- **Tableau Desktop** – Dashboard design and interactive filtering  
- **Jupyter Notebook (optional)** – For supplementary EDA or automation  
- **Dataset** – `sales_data_sample`

---

## 📎 Files Included

```markdown
- `Sales Dashboard.twbx` – Tableau workbook with all visualizations  
- `RFM_Segmentation_Sales.sql` – SQL queries for RFM segmentation and sales aggregation  
- `sc1.JPG` – Screenshot: Revenue breakdown by product, country, and year  
- `sc2.JPG` – Screenshot: Customer segmentation and distribution analysis  
