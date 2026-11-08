# Credit Score & Financial Risk Analysis using Power BI

## 1. Project Overview

This project focuses on analyzing customer financial data from the USA to understand credit behaviour, payment patterns, creditworthiness, loan distribution, and customer lifetime value (LTV).

The objective is to transform raw financial data into meaningful business insights through data cleaning, transformation, analysis, and interactive Power BI dashboards.

The project is based on a real-world business scenario where financial data is received from multiple survey teams. The goal is to streamline data processing, minimize manual errors, reduce operational costs, and provide timely insights to management.

## 2. Business Problem

The organization receives approximately 25 financial data files daily from survey teams across different locations.

The existing workflow involves:
- Downloading multiple files from emails.
- Combining individual files into one consolidated dataset.
- Cleaning and transforming raw financial data.
- Preparing and updating dashboards.
- Sharing analytical reports with management and the US government.

### Key Challenges

- Time-consuming manual data processing.
- Data inconsistencies and manipulation errors.
- Additional operational expenses of $12,000 per month.
- Increased employee workload.
- Delays in delivering business insights.

## 3. Project Objectives

- Streamline financial data processing.
- Analyze customer creditworthiness and financial behaviour.
- Identify potential loan customers.
- Understand age-wise credit score distribution.
- Analyze payment behaviour across credit mix categories.
- Evaluate customer Lifetime Value (LTV).
- Identify popular loan categories.
- Provide data-driven recommendations for financial product promotions.

## 4. Tools & Technologies

- Microsoft Power BI
- Power Query – Data cleaning and transformation
- DAX – Calculated measures and business KPIs
- Data Visualization – Interactive dashboards and analytical reporting

## 5. Key Business Requirements & Analysis

### A. Financial KPI Analysis
- Average Annual Income
- Average Monthly Balance
- Average Payment Delay
- Average Credit Utilization

### B. Age & Credit Limit Analysis
Investigate the relationship between customer age and changes in credit limits to identify age-related financial patterns.

### C. Customer Age Distribution
Create an age distribution visualization to understand the demographic composition of the customer base.

### D. Age Group & Credit Score Analysis

Customer age groups are categorized as:

| Age Range | Category |
|---|---|
| 14–19 | Teen |
| 19–25 | Young Adult |
| 25–35 | Old Adult |
| 35–45 | Old1 |
| Above 45 | Old2 |

Analyze the number of customers across different age groups and credit score categories.

### E. Credit Mix & Payment Behaviour
Analyze payment behaviour frequency across different credit mix categories to understand customer repayment patterns.

### F. Potential Loan Customer Identification
Identify customer age groups that can be targeted for loan-related financial products.

### G. Advanced Customer Segmentation
Further filter potential customer age groups based on an average number of credit inquiries greater than 7.5.

### H. Lifetime Value (LTV) Analysis

Calculate LTV for each customer age group using the following business formula:

LTV = (0.3 × Average Annual Income) − (0.15 × Average Payment Delay) + (0.4 × Average Credit Score) + (0.075 × Average Amount Invested) + (0.075 × Average Monthly Balance)

#### Promotional Strategy Based on LTV

| LTV Score | Promotional Offer |
|---|---|
| Above 80,000 | 30% off online purchases + Home loan at 4% interest |
| 60,000–80,000 | 15% off online purchases + ₹10,000 gift hampers |
| 50,000–60,000 | Any loan at 5% interest |

### I. Loan & Credit Card Analysis
- Calculate average loans held by customers across age groups.
- Calculate average credit cards held by customers across age groups.
- Identify age-wise credit ownership patterns.

### J. Loan Distribution Analysis
Visualize the count of different loan types to identify the most popular loan categories and support future promotional decisions.

## 6. Dashboard & Visualization

The Power BI dashboard is designed to provide:
- Financial KPI monitoring.
- Customer demographic analysis.
- Credit score distribution.
- Credit mix and payment behaviour analysis.
- Potential loan customer identification.
- LTV-based customer segmentation.
- Loan and credit card analysis.
- Loan distribution insights.

## 7. Business Impact

The project aims to support business decisions by:

- Reducing manual data processing.
- Improving data accuracy and consistency.
- Identifying potential loan customers.
- Supporting targeted financial promotions.
- Understanding customer credit behaviour.
- Improving financial reporting and decision-making.

## 8. Conclusion

This project demonstrates how financial data analytics and Power BI can be used to transform raw customer data into actionable business insights.

By combining customer segmentation, credit risk analysis, payment behaviour, and LTV analysis, the organization can make more informed decisions regarding customer targeting, financial products, and promotional strategies.

---

**Tools:** Microsoft Power BI | Power Query | DAX

**Project Type:** Financial Data Analysis | Credit Risk Analysis | Customer Segmentation
