# sales-dashboard-sql-powerbi
Interactive Sales Dashboard built with SQL and Power BI to analyze revenue, customers, products, and sales trends for data-driven decision making.

# 📊 Sales Dashboard Project  

## 📝 Overview  
This project demonstrates an **end-to-end Business Intelligence (BI) workflow** using **SQL** and **Power BI**.  
The goal was to design an interactive **Sales Dashboard** that provides insights into revenue, sales performance, customer distribution, and product analysis.  

---

## ⚙️ Tools & Technologies Used  
- **SQL (MySQL Workbench)** → Data storage & extraction  
- **Power BI** → Data visualization & dashboarding  
- **Power Query** → Data cleaning & transformation  
- **DAX (Data Analysis Expressions)** → KPI calculations & advanced measures  

---

## 🔄 Project Workflow  

1. **Data Source & Import**  
   - Dataset provided in a `.sql` file.  
   - Imported into **MySQL Workbench** and explored data structure.  

2. **Database Connection**  
   - Connected **MySQL Server** to **Power BI** for live data access.  

3. **Data Cleaning & Transformation**  
   - Performed data wrangling in **Power Query**.  
   - Handled missing values, corrected data types, and applied proper formatting.  

4. **Data Modeling**  
   - Designed a **star schema** in Power BI for optimized performance.  
   - Defined relationships between fact and dimension tables.  

5. **DAX Measures**  
   - Built measures for KPIs such as:  
     - Total Revenue  
     - Total Sales Quantity  
     - Total Customers  
     - Total Products  
     - MoM % (Month-over-Month Growth)  
     - YoY % (Year-over-Year Growth)  

6. **Data Visualization**  
   - Created an interactive **Sales Dashboard** with:  
     - Revenue & Sales KPIs  
     - Zone-wise Sales & Revenue  
     - Product-wise Performance  
     - Customer Type Analysis (Brick & Mortar vs. E-Commerce)  
     - Top 10 Customers (by Revenue & Sales Quantity)  
     - Year & Month filters for dynamic analysis  

---

## 📊 Dashboard Preview  
![Sales Dashboard](sales.png)  

---

## 💡 Key Insights  
- **North Zone** generates the highest revenue contribution (~₹675M).  
- **Own Brand** products dominate both revenue and sales quantity.  
- **Brick & Mortar** customers contribute more revenue than E-Commerce.  
- Overall revenue shows strong **YoY growth (~46%)**.  

---

## 🚀 Outcomes  
- Demonstrated the ability to perform **end-to-end BI project development**.  
- Gained hands-on experience in **SQL, Power Query, DAX, and Power BI**.  
- Delivered a dashboard that can help stakeholders identify trends and make data-driven decisions.  
