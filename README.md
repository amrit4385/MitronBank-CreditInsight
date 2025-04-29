# Mitron Bank Credit Card Analysis

## Overview

Mitron Bank, a well-established financial institution based in Hyderabad, aims to introduce a new line of credit cards to expand its offerings and improve customer engagement. To ensure a data-driven approach, AtliQ Data Services proposed an analytical study, but the bank’s **Strategy Director, Mr. Bashnir Rover**, requested a pilot project before proceeding further.  

This project analyzes **customer demographics, spending behaviors, income patterns, and financial trends** using a sample dataset of **4,000 customers** across five cities. The insights generated will help Mitron Bank tailor its credit card features to specific user segments, enhancing its success in the financial market.

## Contents

- [Live Dashboard](#live-dashboard)
- [Problem Statement](#problem-statement)
- [Project Objective](#project-objective)
- [Power BI Dashboard Sections](#power-bi-dashboard-sections)
- [Tools Used](#tools-used)
- [Dataset Overview](#dataset-overview)
- [Data Integrity](#data-integrity)
- [Data Model](#data-model)
- [Data Processing](#data-processing)
- [Key Insights](#key-insights)
- [Recommendations](#recommendations)
- [Conclusion](#conclusion)

---

## Live Dashboard

[Click here to view the live dashboard](https://app.powerbi.com/view?r=eyJrIjoiMTVkNTU2NjctNjM2ZC00NzEyLWFiYzItNzA3MzhiODNmODUzIiwidCI6ImM2ZTU0OWIzLTVmNDUtNDAzMi1hYWU5LWQ0MjQ0ZGM1YjJjNCJ9)

---

## Problem Statement

Mitron Bank is focused on understanding key trends that influence credit card usage. Specifically, the bank aims to analyze:

1. **Demographic Classification:** Identifying customer segments based on age, gender, occupation, and other key attributes.
2. **Spending Behavior:** Evaluating spending patterns across various categories, and analyzing correlations with demographics.
3. **High-Value Customer Segments:** Profiling customers most likely to use the credit card actively, based on their financial behaviors.
4. **Credit Card Feature Recommendations:** Suggesting valuable features backed by data insights and additional research to optimize credit card adoption.

---

## Project Objective

The objective of this analysis is to **leverage data-driven insights** to refine Mitron Bank’s credit card strategy. By evaluating customer behaviors, income trends, and spending habits, the project aims to recommend personalized credit card offerings that maximize user engagement and financial sustainability.

---

## Power BI Dashboard Sections

The analysis is structured into **five key dashboard pages**, each providing a unique perspective on customer financial habits:

1. **Demographic Overview** – Classifies customers based on age, gender, occupation, and city.
2. **Income Analysis** – Examines income distribution and utilization patterns.
3. **Spending Trends** – Identifies top spending categories and payment preferences.
4. **Additional Insights** – Highlights deeper trends and correlations within the dataset.
5. **Executive View** – Provides a high-level summary for decision-makers.

---

## Tools Used

- **Microsoft Excel** – Data Cleaning & Transformation
- **Power BI** – Data Analysis & Visualization

---

## Dataset Overview

The dataset consists of two key tables:

### **dim_customers**
Contains customer-related details, including:
- `customer_id`: Unique identifier for each customer.
- `gender`: Classification (Male/Female).
- `age_group`: Categorized age brackets.
- `city`: Residence location (Mumbai, Delhi-NCR, etc.).
- `occupation`: Employment type.
- `average_income`: Monthly earnings.

### **fact_spends**
Tracks spending patterns and payment preferences:
- `customer_id`: Links to customer data.
- `month`: Month-wise spending records.
- `category`: Expense type (Entertainment, Apparel, Electronics, etc.).
- `payment_type`: Payment mode (Credit Card, UPI, Debit Card, Net Banking).
- `spends`: Total amount spent.

---

## Data Integrity

### **Data Cleaning Steps**
- Duplicates were identified and removed.
- Formatting issues (e.g., *Delhi NCR* changed to *New Delhi*) were corrected.
- Missing values were validated to maintain dataset reliability.

---

## Data Model

Power BI was used to structure the data model, establishing relationships between customer attributes and transaction records to generate actionable insights.

---

## Data Processing

### **Transformations & Calculations**
- **Income Utilization Percentage** – Avg_spends vs. avg_income to assess likelihood of credit card usage.
- **Segmentation Analysis** – Identifying customer groups based on demographics and spending behavior.
- **Trend Observations** – Analyzing monthly spending cycles and payment preferences.

---

## Key Insights

- **Customer Distribution:** Largest age group is **25-35 years**, with **Mumbai** having the highest customer base.
- **Spending Trends:** Credit card usage dominates, accounting for **$216M** in transactions with a **17.45% utilization rate**.
- **Peak Spending Months:** **September** records the highest expenditure at **$116M**.
- **Income Utilization Rates:** Males have a **44.39% utilization**, higher than females at **39.92%**.

---

## Recommendations

- **Festive Offers:** Cashback and **No Cost EMI** promotions during **September & August** to maximize engagement.
- **Targeted Outreach:** Focus marketing efforts on **married males (25-34) in Mumbai’s IT sector**, as they have the highest repayment capability.
- **Spending Incentives:** Introduce **reward points** for top categories (**Bills & Groceries**) to encourage credit card adoption.
- **UPI Integration:** Embed credit card payment options within **UPI transactions**, promoting indirect usage.

---

## Conclusion

This pilot study equips Mitron Bank with key insights into customer behavior, enabling them to create personalized credit card offerings that drive engagement. By leveraging data analytics and financial segmentation, the recommendations present a strong foundation for a successful credit card rollout.

---
