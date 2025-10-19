# 📦 Profitability Optimization through Data-Driven Category Analysis

## 📊 Project Overview

This project focuses on **profitability analysis** across key product categories for **Daraz Pakistan**.  
The goal was to identify **loss-making segments**, understand the root causes behind negative margins, and drive **data-backed corrective actions** to improve profitability.

The analysis leveraged **SQL automation** to aggregate transaction-level, commission, and exchange rate data into a unified, actionable dataset.  
It served as the backend query for a **profitability monitoring dashboard**, enabling real-time tracking of category and seller-level performance.

---

## 🧩 Problem Statement

During campaign and regular operations, several product categories consistently showed **negative or declining profitability**.  
Initial investigations suggested that:
- **Shipping recovery was negative**, meaning shipping costs were higher than the revenue collected from customers.
- **Incorrect product weight configurations** by sellers led to **underestimated shipping charges**, causing the platform to absorb excess shipping costs.
- **Category-level profitability** was hard to measure due to data spread across multiple systems (orders, finance, FX rates).

The challenge was to **combine multiple data sources**, calculate true profitability per SKU/category, and identify where operational or seller-level adjustments were needed.

---

## 🧠 Approach

- Designed and implemented a **comprehensive SQL pipeline** integrating:
  - **Order data** from the transaction core dataset  
  - **Commission details** from the financial transaction system  
  - **FX rates** for currency normalization across ventures  
- Computed key profitability metrics including:
  - **Net Merchandise Value (NMV)**  
  - **GMV in USD**  
  - **Seller and platform commissions**  
  - **Category-wise profitability indicators**
- Filtered and segmented data by **venture, category, and month** for time-based performance tracking.
- Automated the query to refresh data regularly, feeding insights into a **profitability dashboard** used by business and category teams.

---

## 📈 Key Insights

- Identified **categories with negative profitability** caused by incorrect weight configurations and shipping cost mismatches.  
- Found that **seller-declared product weights** were significantly lower than actuals, inflating shipping losses.  
- Highlighted **imbalances between shipping revenue and cost**, prompting corrective actions.
- After communicating with sellers and adjusting weights and pricing structures, **category profitability improved significantly**.

---

## ⚙️ Tools & Technologies

- **SQL (Databricks / HiveQL)** – for data extraction, transformation, and metric computation  
- **Power BI** – to visualize profitability by category, seller, and month  
- **Excel / Python (optional)** – for validation and trend analysis  
- **ETL Scheduling** – to automate data refresh and dashboard updates  

---

## 🚀 Business Impact

- Improved **visibility into profitability drivers** at the SKU and category levels  
- **Reduced negative shipping recovery** through targeted interventions  
- Strengthened **seller compliance** on product weight accuracy  
- Enabled **data-driven pricing and shipping strategy decisions**  
- Streamlined profitability tracking through **automated SQL pipelines**

---

## 🔒 Confidentiality Note

Due to company data protection policies, raw data, exact profitability figures, and internal metrics are not disclosed.  
This repository focuses on the **data engineering and analytical approach** behind profitability optimization.

---

## 👤 Author

**Noor Wali**  
Growth Analyst – Daraz  
[LinkedIn](https://www.linkedin.com/in/your-link) | [GitHub](https://github.com/noorw8354)

---

### 🔖 Tags
#Daraz #SQL #ProfitabilityAnalysis #DataAnalytics #EcommerceInsights #Automation  
#CategoryPerformance #ShippingRecovery #PowerBI #DataDrivenDecisions #OperationalEfficiency
