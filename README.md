# Telecom-Customer-Churn-Analysis
Customer churn is a major challenge for telecom companies because losing subscribers directly impacts revenue. This project analyzes telecom customer data to identify churn patterns, evaluate revenue performance, and understand subscriber behavior. The dataset was cleaned using Excel Power Query before being analyzed in Power BI.
## Business Problem

The telecom company wants to understand:

- What is the current customer churn rate?
- Which customer segments are more likely to churn?
- Which networks generate the highest revenue?
- Which factors influence customer retention?
- How can the company improve customer retention and revenue?
  ---

## Project Objectives

The objectives of this project are to:

- Clean and transform messy telecom customer data using Excel Power Query.
- Analyze customer churn patterns.
- Evaluate revenue performance across different customer segments.
- Analyze subscriber demographics and behavior.
- Build an interactive Power BI dashboard.
- Generate actionable business recommendations based on the findings.

---

## Dataset Information
The dataset contains customer-level information from a telecommunications company.

### Number of Records
- XXXX Customers

### Number of Columns
- XX Variables

### Dataset Type
- Customer Subscription Data

---

## Data Dictionary
| Column | Description |
|---------|-------------|
| Customer_ID | Unique identifier for each customer |
| Name | Customer name |
| Gender | Customer gender |
| Age | Customer age |
| State | Customer location |
| Network | Telecom network provider |
| Join_Date | Customer registration date |
| Tenure_Months | Number of months with the company |
| Contract_Type | Customer subscription plan |
| Data_Usage_GB | Monthly data usage |
| Voice_Minutes | Monthly call minutes |
| SMS_Count | Number of SMS sent |
| Recharge_Amount | Amount recharged |
| Monthly_Revenue | Monthly revenue generated |
| Calculated_Total_Revenue | Monthly Revenue × Tenure Months |
| Complaints | Number of complaints made 
| Customer_Service_Calls | Number of support calls |
| Payment_Method | Customer payment method |
| Churn | Customer churn status (Yes/No) |

---

## Data Cleaning Process

The dataset contained several data quality issues that were resolved using Microsoft Excel Power Query.

The following cleaning steps were performed:

- Removed duplicate Customer_ID records.
- Corrected inconsistent text values.
- Removed leading and trailing spaces.
- Standardized gender values.
- Corrected data types.
- Cleaned invalid age values.
- Converted revenue fields to numeric values.
- Created a new **Calculated_Total_Revenue** column using:
- **Monthly_Revenue × Tenure_Months**

- Preserved missing Join_Date values as null.
- Verified the dataset for consistency before analysis.

---

## Tools Used

- Microsoft Excel
- Excel Power Query
- Microsoft Power BI
- GitHub
---

## Skills Demonstrated

- Data Cleaning
- Data Transformation
- Power Query
- Power BI
- Data Visualization
- Dashboard Design
- Data Analysis
- Business Intelligence
- Data Storytelling
---

## Analysis Questions

### Subscriber Analysis

- How many subscribers does the company have?
- Which network has the highest number of subscribers?
- Which state has the most subscribers?
- What is the gender distribution of customers?

### Revenue Analysis

- What is the total revenue?
- Which network generates the highest revenue?
- Which state generates the highest revenue?
- Which contract type contributes the most revenue?
- Who are the top revenue-generating customers?

### Churn Analysis
- What is the overall churn rate?
- Which network has the highest churn rate?
- Which contract type experiences the highest churn?
- Which payment method is associated with the highest churn?
- Does customer tenure influence churn?

---

## Dashboard

The Power BI report consists of three pages:

### Executive Overview
- Total Subscribers
- Total Revenue
- Active Customers
- Churn Rate
- Revenue by Network
  - Subscribers by State

### Churn Analysis
- Churn by Network
- Churn by Contract Type
- Churn by Age Group
- Churn by Payment Method
- Churn by Complaints

### Revenue & Customer Insights
- Revenue by State
- Revenue by Contract Type
- Top Customers
- Customer Demographics
- Data Usage Analysis
---

## Key Insights
