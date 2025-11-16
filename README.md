# **Customer-Behavior-Analysis-Project**

---

**📌 Overview**  
This project analyzes customer shopping behavior using a dataset of **3,900 transactions**.  
The goal is to understand **customer demographics**, **spending patterns**, **product preferences**, and **subscription behavior**.  
The project includes **Python EDA**, **data cleaning**, **SQL analysis (MySQL)**, a **Power BI dashboard**, and a **final report**.

---

**📂 Dataset**

**Total Rows:** 3,900  
**Total Columns:** 18  

**Includes:**  
- Customer details (age, gender, subscription status)  
- Purchase details (amount, category, item purchased)  
- Shopping patterns (discount, promo code, frequency, review rating)  
- Shipping information  

---

**🛠 Tools Used**  
- Python (pandas)  
- MySQL for SQL queries  
- Power BI for dashboard creation  
- Excel for initial checks  
- Jupyter Notebook for analysis  

---

**📁 Project Files**

| File Name | Description |
|-----------|-------------|
| Customer Behavior Dashboard.pbix | Power BI dashboard |
| customer_behavior_dataset.csv | Dataset used |
| customer_behavior_analysis.sql | SQL queries used |
| Customer_Behavior_Analysis-checkpoint.ipynb | Python EDA + cleaning notebook |
| Customer Behavior Analysis Report.pdf | Final report |
| Customer Behavior.xlsx | Excel data review |
| README.md | Project documentation |
| Customer Behavior Dashboard.png | Dashboard Screenshot |

---

**📂 Folder Structure**


---

**🔎 Steps Performed**

**1. Load Dataset (Python)**  
- Imported data using pandas  
- Reviewed structure with `.info()` and `.describe()`  

**2. Data Cleaning**  
- Handled missing values (review ratings)  
- Standardized column names  
- Removed duplicates  
- Feature Engineering:  
  - `age_group`  
  - `purchase_frequency_days`  

**3. Exploratory Data Analysis (EDA)**  
- Distribution analysis (age, rating, purchase amount)  
- Category performance  
- Revenue & sales analysis  
- Outlier detection  

**4. SQL Analysis (MySQL)**  
Business Questions Answered:  
- Revenue by gender  
- Top 5 products by average rating  
- Shipping type comparison  
- Subscriber vs non-subscriber spending  
- Discount-driven products  
- Customer segmentation  
- Revenue by age group  
- Top products per category  

**5. Power BI Dashboard**  
Dashboard includes:  
- Total customers  
- Avg purchase amount  
- Avg rating  
- Revenue by category  
- Age group-wise sales  
- Subscription breakdown  
- Filters for gender, category, shipping type  

**6. Report Creation**  
Created a report summarizing:  
- Insights  
- SQL findings  
- Dashboard visuals  
- Business recommendations  

---

**📸 Dashboard Preview**

![Customer Behavior Dashboard](Customer%20Behavior%20Dashboard.png)

---


