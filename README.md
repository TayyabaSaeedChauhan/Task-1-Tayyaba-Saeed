# 📊 E-Commerce Sales & Order Data Analytics — DECODE Lab Task 1

[![Data Analytics](https://img.shields.io/badge/Domain-Data%20Analytics-blue.svg)](https://github.com/)
[![Tool](https://img.shields.io/badge/Tool-Microsoft%20Excel-green.svg)](https://github.com/)
[![Internship](https://img.shields.io/badge/Program-DECODE%20Lab%20Internship-orange.svg)](https://github.com/)

## 📌 Project Overview
Welcome to my submission for **Task 1** of the **DECODE Lab Remote Data Analytics Internship Program**. This project demonstrates end-to-end e-commerce data auditing, dataset restructuring, and numerical verification on real-world transactional data.

The dataset features **1,200 transactional records** spanning from **January 2023 through April 2026**, capturing key performance indicators (KPIs) across sales channels, customer payment preferences, promotional campaign codes, and order fulfillment states.

---

## 🚀 Key Analytics & Project Highlights
* **Dataset Scale**: 1,200 transactional order records
* **Gross Revenue Audited**: $1,264,761.96
* **Key Product Categories**: Laptops, Desks, Monitors, Phones, Tablets, Chairs, Printers
* **Acquisition Channels Evaluated**: Instagram, Facebook, Google Search, Email Marketing, Direct Referrals
* **Payment Gateways Audited**: Credit Card, Debit Card, Online Transfer, Cash, Gift Cards

---

## 📂 Dataset Schema & Data Dictionary

| Field Name | Data Type | Description | Key Attributes / Categories |
| :--- | :--- | :--- | :--- |
| **OrderID** | String | Unique order identifier | `ORD200000` – `ORD201199` |
| **Date** | Date | Transaction timestamp | 2023-01-04 to 2026-04-17 |
| **CustomerID** | String | Customer account ID | Categorical identifier |
| **Product** | Text | Item purchased | *Monitor, Phone, Tablet, Chair, Printer, Laptop, Desk* |
| **Quantity** | Numeric | Units purchased per transaction | Range: 1 to 5+ |
| **UnitPrice** | Currency ($) | Price per single unit | Numeric decimal |
| **ShippingAddress**| Text | Delivery location address | Street Address |
| **PaymentMethod** | Categorical | Payment mode chosen | *Credit Card, Debit Card, Online, Cash, Gift Card* |
| **OrderStatus** | Categorical | Current fulfillment state | *Shipped, Delivered, Pending, Cancelled, Returned* |
| **TrackingNumber** | String | Shipping tracking number | Unique string |
| **ItemsInCart** | Numeric | Total items present in cart | Shopping cart volume |
| **CouponCode** | Categorical | Applied discount code | *SAVE10, FREESHIP, WINTER15, etc.* |
| **ReferralSource** | Categorical | Marketing acquisition channel | *Instagram, Facebook, Google, Email, Referral* |
| **Total Price** | Currency ($) | Calculated order line total | $\text{Quantity} \times \text{UnitPrice}$ |

---

## 🛠️ Data Cleaning & Integrity Workflow
To ensure accurate downstream business reporting and dashboard visualization, the following data engineering steps were performed:

1. **Schema Validation & Structural Audit**:
   * Isolated transactional records from summary calculation rows to prevent double-counting in aggregations.
   * Verified total gross revenue across 1,200 transactions ($1,264,761.96).

2. **Null Value & Data Type Normalization**:
   * Standardized datetime fields to ISO formatting.
   * Addressed structural null values in non-mandatory promotional fields (`CouponCode`).

3. **Formula & Arithmetic Integrity**:
   * Cross-verified line-item totals using validation logic:
     $$\text{Total Price} = \text{Quantity} \times \text{UnitPrice}$$

---

## 🔧 Tools & Tech Stack
* **Microsoft Excel**: Data Audit, Data Quality Checks, Conditional Formatting, Aggregations
* **Git & GitHub**: Version Control & Project Documentation

---

## 👩‍💻 Author
**Tayyaba Saeed**  
*Data Analytics Intern — DECODE Lab*  
https://github.com/TayyabaSaeedChauhan
<br>
https://www.linkedin.com/in/tayyabasaeedchauhan/

---
*Keywords: Data Analytics, E-Commerce Analytics, DECODE Lab, Data Cleaning, Data Integrity, Microsoft Excel, Data Validation, Exploratory Data Analysis (EDA), Sales Reporting.*
