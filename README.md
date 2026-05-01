# SaaS Revenue and Customer Analytics Dashboard

This project is an end-to-end data analytics solution built using ERPNext, Excel, and Power BI. It focuses on analyzing subscription-based business metrics such as revenue growth, customer behavior, and churn.

---

## Project Overview

The goal of this project is to simulate a SaaS business environment by generating transactional data in ERPNext and analyzing it in Power BI to derive meaningful business insights.

---

## Live Dashboard

View the interactive Power BI dashboard here:  
https://app.powerbi.com/view?r=eyJrIjoiNjNiOWZiMzgtODg2MS00OTVlLWEyZDYtOGI4M2Q5ZTZmZDY1IiwidCI6Ijk0OTAwMzkzLWI5ZmYtNDIzNS1iMDgzLTcwZmJjZTIzNzdkYSJ9&pageName=82100ec6a6aa113ee650

---

## Tools and Technologies

- ERPNext (data generation and invoicing)
- Microsoft Excel (data extraction and cleaning)
- Power BI (data modeling and dashboarding)
- DAX (calculated measures and KPIs)

---

## Workflow

### 1. Data Generation (ERPNext)
- Created customer records
- Defined subscription plans:
  - Basic Plan
  - Premium Plan
  - Pro Plan
- Generated sales invoices across multiple months
- Exported data to Excel

### 2. Data Preparation
- Cleaned and structured dataset in Excel
- Created a Month column
- Ensured consistent formatting for analysis

### 3. Data Modeling (Power BI)
- Imported dataset into Power BI
- Created relationships and calculated columns
- Built measures for key KPIs

---

## Key Metrics

- Monthly Recurring Revenue (MRR)
- Active Customers
- Churn Customers
- Average Revenue Per User (ARPU)
- MRR Growth Percentage

---

## Churn Definition

A customer is considered churned if:
- The customer made a purchase in previous months
- But did not make a purchase in the latest month

Customers with activity in the latest month are considered active.

---

## Dashboard Structure

### Page 1: Overview
- KPI cards for MRR, ARPU, Active Customers, Churn Customers
- MRR trend over time
- Revenue distribution by subscription plan
- Customer revenue contribution analysis

Key insight:
Revenue shows steady growth over time, with the Pro Plan contributing the largest share.

---

### Page 2: Customer Analysis
- Detailed customer subscription history
- Churn status per customer
- Top customers by revenue
- Customer activity trend over time

Key insight:
High-value customers show consistent engagement, while churn is concentrated in lower-tier plans.

---

## Dataset Description

The dataset includes:
- Customer ID
- Customer Name
- Month
- Plan Type
- Revenue

---

## Key Insights

- MRR increased steadily across the observed months
- Pro Plan contributes the highest revenue
- Customer churn is limited but present in lower-value segments
- A small group of customers contributes a large portion of revenue

---

## Files Included

- Power BI file (.pbix)
- Dashboard export (PDF)


---

## Learnings

- Practical implementation of SaaS metrics
- Churn analysis using DAX
- Dashboard design and storytelling
- Integration of ERP-generated data with BI tools

---

---

## Author

Vinit Solanki  
Data Analyst | SQL | Power BI | Python
