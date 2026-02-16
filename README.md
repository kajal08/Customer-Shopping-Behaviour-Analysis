# 🛍 Customer Shopping Behaviour Analysis  
### End-to-End Retail Data Analytics Project (Python + SQL + Power BI)

---

## 📌 Executive Summary

This project presents a complete end-to-end retail analytics workflow, transforming raw transactional data into actionable business insights using:

- **Python** for Data Cleaning & Transformation  
- **SQL** for Business Querying & Analysis  
- **Power BI** for Executive Dashboard Visualization  

The objective was to simulate a real-world retail analytics scenario where business stakeholders require insights into customer behaviour, product performance, and revenue trends to improve strategic decision-making.

---

## 🎯 Business Objective

Retail companies face challenges in understanding:

- Which customers generate the highest revenue?
- Do discounts actually increase spending?
- Which product categories drive maximum profitability?
- How do subscription customers behave differently?
- What are the spending patterns across demographics?

This project answers these questions through structured data analysis and visualization.

---

## 📂 Dataset Overview

- **Source**: Customer transactional dataset (CSV format)
- **Granularity**: Transaction-level data
- **Key Dimensions**:
  - Customer Demographics (Age, Gender, Location)
  - Product Details (Item, Category)
  - Transaction Metrics (Purchase Amount, Discount Applied)
  - Behavioral Attributes (Subscription Status, Frequency of Purchases)
  - Review Ratings

---

## 🛠 Tech Stack

| Layer | Tools Used |
|-------|------------|
| Data Cleaning | Python (Pandas, NumPy) |
| Data Analysis | SQL (SQL Server / SSMS) |
| Visualization | Power BI |
| Data Source | CSV |

---

# 🔄 Project Workflow

---

## 1️⃣ Data Cleaning & Transformation (Python)

Performed detailed preprocessing in Jupyter Notebook:

- Checked and handled missing values
- Removed duplicates
- Standardized categorical variables
- Converted appropriate data types
- Generated summary statistics
- Conducted Exploratory Data Analysis (EDA)
- Performed Featured Engineering for downstream SQL analysis

📌 Focus: Ensuring data quality and analytical readiness.

<img width="1267" height="620" alt="image" src="https://github.com/user-attachments/assets/093a4b3d-5caf-4030-9f76-7628a8733c1d" />
<img width="1266" height="619" alt="image" src="https://github.com/user-attachments/assets/5401b190-dc28-4356-91e7-ded03ad3f98e" />
<img width="1268" height="610" alt="image" src="https://github.com/user-attachments/assets/39dc59c0-def5-45e4-92fe-2e9acc3db1e1" />
<img width="1292" height="594" alt="image" src="https://github.com/user-attachments/assets/2a5cedbe-9499-42a4-a8b5-46fc60e8d88b" />

---

## 2️⃣ Business Analysis Using SQL

Advanced SQL queries were used to extract decision-oriented insights.

### Key Analytical Questions Solved:

✔ Customers who used discounts but still spent above average  
✔ Top 5 highest-rated products  
✔ Revenue contribution by category  
✔ Average purchase amount by gender  
✔ Subscription vs non-subscription behaviour comparison  
✔ High-value customer identification  
✔ Purchase frequency analysis  

### SQL Concepts Applied:

- Aggregate Functions (SUM, AVG, COUNT)
- GROUP BY & HAVING
- Subqueries
- Filtering conditions
- TOP clause
- Conditional logic

📌 Focus: Translating business questions into structured database queries.

Some queries -

<img width="1091" height="585" alt="image" src="https://github.com/user-attachments/assets/58cef71c-beaf-4824-a239-39b8936de2b2" />
<img width="1094" height="586" alt="image" src="https://github.com/user-attachments/assets/e744b439-053d-4c1e-afbe-80ddc2248dad" />


---

## 3️⃣ Interactive Dashboard Development (Power BI)

An executive-level dashboard was built to present insights visually.

### Dashboard Components:

- 📊 Total Revenue KPI
- 💰 Average Purchase Value
- 👥 Customer Segmentation (Gender & Subscription)
- 📦 Category-wise Revenue Distribution
- 🎯 Discount Impact Analysis
- ⭐ Top Rated Products
- 🔄 Interactive slicers (Category, Gender, Location, Subscription)

📌 Focus: Business storytelling through interactive visual analytics.

<img width="914" height="504" alt="image" src="https://github.com/user-attachments/assets/4b303e46-42fb-4b62-8380-d4fb417fda56" />

---

# 📊 Key Business Insights

# 📊 Key Business Insights

- The dataset contains **3,900 transactions**, generating a total revenue of **$233,081**, with an average purchase value of **$59.76 per transaction**.
- Customers who applied discounts had an average purchase value of **$59.28**, while non-discount customers averaged **$60.13**, indicating that discounts did not significantly increase transaction size.
- Subscription customers recorded an average purchase value of **$59.49**, compared to **$59.86** for non-subscribers, showing minimal variation in spending behaviour between the two groups.
- Revenue analysis by category revealed that certain categories contributed a significantly higher share of total revenue, indicating revenue concentration within specific product segments.
- The top 5 highest-rated products achieved strong average ratings (close to 5.0), highlighting high customer satisfaction and potential repeat purchase drivers.
- With an overall average purchase value close to $60, the dataset reflects mid-range retail transaction behaviour with consistent spending patterns across customer segments.

---

# 📈 Business Impact Simulation

If implemented in a real retail environment, these insights could:

- Improve discount strategy targeting
- Optimize inventory planning
- Enhance customer segmentation strategies
- Support loyalty program evaluation
- Increase overall revenue efficiency

---

# 🧠 Skills Demonstrated

✔ Data Cleaning & Wrangling  
✔ SQL Query Optimization  
✔ Business Problem Solving  
✔ KPI Development  
✔ Dashboard Design Principles  
✔ Analytical Thinking  
✔ Data Storytelling  

---

# 📌 Conclusion

This project demonstrates the ability to execute a full analytics lifecycle:

**Raw Data → Cleaned Data → SQL Insights → Business Dashboard → Strategic Interpretation**

It reflects real-world data analyst responsibilities in consulting, retail analytics, and business intelligence roles.
