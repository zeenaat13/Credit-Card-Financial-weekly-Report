# Credit Card Weekly Financial Report – Power BI Dashboard

## 📌 Project Overview
This project analyzes customer demographics and credit card transaction data to build two interactive Power BI dashboards:

- Customer Report Dashboard  
- Transaction Report Dashboard  

The dashboards provide insights into customer behavior, spending patterns, and weekly revenue trends using dynamic slicers and DAX measures.

---

## 📊 Dashboards

### 1. Customer Report
Key visuals:
- Total Customers KPI  
- Average Credit Limit  
- Average Satisfaction Score  
- Customers by Gender  
- Customer Age Distribution  
- Customers by Income Group  
- Geographic Distribution (Map)

Slicers:
- Gender  
- Age Group  
- Income Group  

Purpose:
To understand customer demographics, distribution, and ownership patterns.

---

### 2. Transaction Report
Key visuals:
- Total Revenue  
- Total Transactions  
- Current Week Revenue  
- Previous Week Revenue  
- Revenue by Spending Category  
- Weekly Revenue Trend  
- Credit Limit vs Utilization (Scatter Plot)

Slicers:
- Gender  
- Week Number  
- Expense Type  

Purpose:
To analyze spending behavior, revenue trends, and credit utilization.

---

## 🗂 Dataset

Two datasets were used:

### CreditCard Table
Contains transaction-level information such as revenue, credit limits, utilization ratio, expense type, and weekly metrics.

### Customer Table
Contains demographic data such as age, gender, income, job, location, and satisfaction score.

A one-to-many relationship was created using `Client_Num`.

---

## ⚙️ Data Modeling & DAX

Derived Columns:
- Age Group  
- Income Group  
- Numeric Week Number  

Measures:
- Total Revenue  
- Total Transactions  
- Current Week Revenue  
- Previous Week Revenue  

---

## 🔍 Key Insights

- Certain spending categories contribute significantly more to overall revenue.
- Weekly revenue shows noticeable fluctuations, indicating periods of higher activity.
- Higher credit limits do not always mean higher utilization.
- Income and age groups show different spending patterns.
- Car/house ownership correlates with higher average credit limits.

---

## ⚠ Challenges Faced

- Week values were stored as text and converted to numeric for trend analysis.
- Circular dependency errors during week sorting were resolved using a separate numeric week column.
- Scatter plot initially showed one point; fixed using legend disaggregation.
- Ensuring slicers interacted correctly with all visuals required configuration.

---

## ✅ Conclusion

This project demonstrates an end-to-end Power BI workflow:

- Data modeling  
- DAX calculations  
- Interactive dashboard design  
- Business insight generation  

---

## 🛠 Tools Used
- Power BI Desktop  
- DAX  
- GitHub  

---

## 👤 Author
Zeenaat Hussain
