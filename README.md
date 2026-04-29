# Credit Card Weekly Financial Report – Power BI Dashboard

## 📌 Project Overview
This project focuses on analyzing credit card customer data and transaction behavior to derive meaningful business insights. The goal was to build an interactive Power BI dashboard that helps understand customer demographics, spending patterns, and weekly revenue trends.

The project consists of two dashboards:

- Customer Report Dashboard
- Transaction Report Dashboard

Through this project, I aimed to simulate a real-world business scenario where data is transformed into actionable insights using Power BI.
---
## 🎯Project Objectives
The main objectives of this project were:

To analyze customer demographics such as age, income, education, and occupation
To identify spending patterns across different categories
To track weekly revenue trends and transaction performance
To understand credit utilization behavior
To create an interactive dashboard for better decision-making

## 🛠️ Tools & Technologies Used
- **Power BI Desktop** – Data visualization and dashboard creation
- **Power Query** – Data cleaning and transformation
- **DAX (Data Analysis Expressions)** – Creating calculated columns and measures
- **GitHub**– Project documentation and version control 

## 🗂 Dataset

Two datasets were used:

### CreditCard Table
This table contains transaction-level data, including:

Total transaction amount and volume
Credit limit and utilization ratio
Expense type (Bills, Fuel, Travel, etc.)
Weekly data (Week Number, Week Start Date)
Interest earned and delinquent accounts

### Customer Table
This table contains customer demographic details such as:

Age, Gender, and Marital Status
Income and Job type
Education level
Location (State, Zipcode)
Customer satisfaction score

Both tables were connected using Client_Num, forming a customer-level data model.

---
## 🔗 Data Modeling & Transformations
During the data preparation phase:

Created a one-to-one relationship between the Customer and CreditCard tables
Built calculated columns such as:
Age Group
Income Group
Numeric Week Number (for proper sorting)
Handled data type issues (e.g., converting week values from text to numeric)
Ensured all columns had 100% valid values with no errors or nulls

## 📊 Dashboards

### 1. Customer Report
<img width="1182" height="671" alt="CreditCard Customer Report" src="Dashboard Screenshot/Creditcard Customer report.png" />


Key visuals:
- Customers by State
- Customers by Marital Status  
- Customers by Age Group
- Customers by Education Level
- Customers by Gender    
- Customers by Income Group  
- Customers by Occupation

KPI:
- Total Customers
- Average Income
- Average Customer Age
- Average Credit Limit
- Average Satisfaction Score

Slicers:
- Gender  
- Age Group  
- Income Group  

Purpose:
To understand who the customers are and how they are distributed across different segments.

---
<img width="1202" height="685" alt="CreditCard Transaction Report" src="Dashboard Screenshot/Creditcard Transaction Report.png" />

### 2. Transaction Report
Key visuals:
- Revenue by Spending Category  
- Weekly Revenue Trend
- Revenue by Education Level
- Revenue by Occupation
- Revenue by Card Category
- Revenue by Use Method 
- Credit Limit vs Utilization (Scatter Plot)

KPI:
- Total Revenue  
- Total Transactions  
- Current Week Revenue  
- Previous Week Revenue
- Interest Earned
- Average utilization
  
Slicers:
- Gender  
- Week Number  
- Expense Type  

Purpose:
To analyze how customers spend and how revenue changes over time.

---



## 🔍 Key Insights

- Spending is highest in categories like Bills and Fuel
- Revenue shows fluctuations across different weeks
- Higher credit limits do not always mean higher utilization.
- Income and age groups show different spending patterns.
- Educated and working professionals contribute significantly to revenue.
- Customer demographics strongly influence spending behavior.
- Car/house ownership correlates with higher average credit limits.

---

## ⚠ Challenges Faced

- Week values were stored as text, causing sorting issues, and converted to numeric for trend analysis.
- Circular dependency errors during week sorting were resolved using a separate numeric week column.
- Scatter plot initially showed one point; fixed using legend disaggregation.
- Ensuring slicers interacted correctly with all visuals required configuration.

---
## 📌 Recommendations & Improvements
- Focus more on high-revenue categories like Bills and Fuel by giving offers and rewards
- Target high-value customers (educated and working professionals) with personalized services
-Encourage customers with high credit limits to use more through discounts and EMI options
-Improve weekly revenue by running regular offers and campaigns
-Create different strategies for different income and age groups

---
## ✅ Conclusion

This project demonstrates an end-to-end Power BI workflow:

- Data cleaning and transformation
- Data modeling 
- DAX calculations  
- Interactive dashboard design  
- Business insight generation  

---



## 👤 Author
Zeenaat Hussain
