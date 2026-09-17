# 📊 Loan Application Analysis Dashboard

An interactive Power BI dashboard designed to analyze loan applications, customer characteristics, loan performance, payment behavior, and default patterns.

---

## 📌 Project Overview

This project transforms raw banking loan data into an interactive business intelligence dashboard using Power BI.

The dashboard provides a consolidated view of loan applications and enables users to explore application trends, customer demographics, loan types, payment status, and default behavior through interactive visualizations and filters.

---

## 🎯 Business Objectives

- Analyze overall loan application performance
- Monitor approved, rejected, and pending applications
- Compare applications across different loan types
- Analyze customer demographics and employment characteristics
- Examine the relationship between income, credit score, and loan amount
- Analyze payment and default behavior
- Track loan application trends over time
- Provide customer-level loan details using drill-through analysis

---

## 🛠️ Tools & Technologies

- **Power BI Desktop**
- **Power Query**
- **DAX**
- **Data Modeling**
- **Microsoft Excel**

---

## 📂 Dataset

The dataset contains banking and loan application information including:

- Customer ID
- Application Date
- Age
- Gender
- Employment Type
- Annual Income
- Credit Score
- Loan Type
- Loan Amount
- Interest Rate
- Loan Term
- Application Status
- Region
- Branch
- Existing Loans
- Monthly EMI
- Default Status
- Payment Status

The dataset was prepared and transformed using Power Query before building the dashboard.

---

# 📊 Dashboard Pages

## 1️⃣ Executive Overview

Provides a high-level summary of the loan portfolio using KPI cards and interactive filters.

### Key KPIs

- Total Applications
- Approved Loans
- Rejected Loans
- Pending Loans
- Average Credit Score
- Approval Rate
- Pending Rate
- Total Loan Amount
- Average Loan Amount

### Interactive Filters

- Loan Type
- Region
- Date

---

## 2️⃣ Loan Analysis

Analyzes loan application patterns across different loan types and statuses.

### Visualizations

- Total Applications by Loan Type
- Loan Applications by Status
- Loan Applications Trend
- Total Loan Amount by Loan Type

---

## 3️⃣ Customer Analysis

Provides insights into customer demographics and financial characteristics.

### Visualizations

- Loan Applications by Employment Type
- Income vs Loan Amount
- Loan Applications by Age Group
- Credit Score vs Annual Income
- Loan Applications by Gender

This page helps analyze customer segments and borrowing patterns.

---

## 4️⃣ Loan Performance Analysis

Focuses on loan repayment and risk-related performance.

### Visualizations

- Applications by Payment Status
- Total Loan Amount by Payment Status
- Average Interest Rate by Loan Type
- Applications by Default Status

This page helps evaluate payment behavior and potential credit risk.

---

## 5️⃣ Customer Loan Details

A detailed customer-level drill-through page.

Users can select a customer and drill through to view detailed loan information.

### Details Available

- Customer ID
- Age
- Employment Type
- Loan Amount
- Loan Type
- Interest Rate
- Credit Score
- Application Date
- Application Status
- Payment Status
- Default Status

A **Back button** is provided to return to the previous analysis page.

---

# ⚙️ Power BI Features Used

### Data Preparation

- Power Query
- Data Cleaning
- Duplicate handling
- Missing-value handling
- Data-type validation
- Data standardization

### Data Modeling

- Fact and Dimension tables
- Relationships
- Date Dimension
- Customer Dimension
- Loan Type Dimension
- Star Schema

### DAX

- Calculated Measures
- KPI Measures
- Approval Rate
- Pending Rate
- Total Loan Amount
- Average Loan Amount
- Average Credit Score

### Time Intelligence

- MTD — Month-to-Date
- QTD — Quarter-to-Date
- YTD — Year-to-Date
- LY — Last Year

### Interactive Features

- Slicers
- Cross-filtering
- Page Navigation
- Drill-through
- Back Navigation
- Interactive Visualizations

---

# 💡 Key Insights

The dashboard enables users to identify:

- Loan types with the highest application volumes
- Loan types contributing the highest loan amounts
- Application trends over time
- Relationships between income and loan amount
- Relationships between credit score and income
- Application distribution across employment types
- Application distribution across age groups and gender
- Payment behavior across loan applications
- Default patterns and associated loan exposure
- Customer-level loan information for detailed analysis

---

# 📁 Project Structure

```text
Loan_Application_Analysis_Dashboard/
│
├── README.md
│
├── Power BI/
│   └── Loan_Application_Analysis_Dashboard.pbix
│
├── Dataset/
│   └── Banking_Loan_Analytics_Practice.xlsx
│
├── Dashboard PDF/
│   └── Loan_Application_Analysis_Dashboard.pdf
│
└── Screenshots/
    ├── 01_Executive_Overview.png
    ├── 02_Loan_Analysis.png
    ├── 03_Customer_Analysis.png
    ├── 04_Loan_Performance.png
    └── 05_Customer_Loan_Details.png

## Dashboard Pages

### 1. Executive Overview
- Total Applications
- Approved Loans
- Rejected Loans
- Pending Loans
- Approval Rate
- Pending Rate
- Total Loan Amount
- Average Loan Amount
- Loan Type, Region and Date filters

### 2. Loan Analysis
- Applications by Loan Type
- Applications by Status
- Loan Application Trend
- Total Loan Amount by Loan Type
- Region, Loan Type and Date filters

### 3. Customer Analysis
- Applications by Employment Type
- Income vs Loan Amount
- Applications by Age Group
- Credit Score vs Annual Income
- Applications by Gender

### 4. Loan Performance Analysis
- Applications by Payment Status
- Total Loan Amount by Payment Status
- Average Interest Rate by Loan Type
- Applications by Default Status
- Region, Loan Type and Date filters

### 5. Customer Loan Details
- Customer-level loan details
- Customer ID selection
- Loan amount and loan type
- Interest rate and credit score
- Application date and status
- Drill-through functionality for customer-level analysis

## Key Features

- Interactive Power BI dashboard
- Page navigation using buttons
- Interactive slicers and filters
- Drill-through analysis using Customer ID
- Date-based filtering
- Data modeling and relationships
- DAX measures and calculations
- Business-focused visualizations

## Key Insights

- Personal Loan has the highest number of applications.
- Home Loans contribute the highest total loan amount.
- The overall approval rate is approximately 65%.
- Most applications are paid on time.
- Default cases represent a small proportion of total applications.
- Customer income and loan amount show a positive relationship.
- The 45–54 age group has the highest number of applications.

## Tools & Technologies

- Power BI Desktop
- Power Query
- DAX
- Data Modeling
- Excel / CSV

## Conclusion

This project demonstrates an end-to-end Power BI workflow, from data preparation and modeling to interactive dashboard development and business insights. It focuses on analyzing loan applications, customer characteristics, loan performance and default patterns to support data-driven decision-making.
