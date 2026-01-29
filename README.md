# 🛒 Customer Shopping Behavior Analysis

![Python](https://img.shields.io/badge/Python-3.9%2B-blue)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-15%2B-336791)
![PowerBI](https://img.shields.io/badge/Power_BI-2024-yellow)
![License](https://img.shields.io/badge/License-MIT-green)

## 📊 Project Overview
This project analyzes customer shopping behavior using transactional data from **3,900 purchases** across various product categories. The goal is to uncover insights into spending patterns, customer segments, product preferences, and subscription behavior to guide strategic business decisions.

## 📁 Dataset Summary
- **Rows:** 3,900 | **Columns:** 18
- **Key Features:** Customer demographics, purchase details, shopping behavior metrics
- **Missing Data:** 37 values in Review Rating column (handled via imputation)

## 🔧 Tech Stack
- **Python** (Pandas, NumPy) – Data cleaning & EDA
- **PostgreSQL** – Business intelligence & querying
- **Power BI** – Interactive dashboard & visualization

## 📈 Analysis Workflow

### 1. Data Preparation & Cleaning (Python)
- Loaded dataset, checked structure, and handled missing values
- Standardized column names to snake_case
- Feature engineering: age groups, purchase frequency days
- Data consistency checks and redundant column removal
- PostgreSQL integration for SQL analysis

### 2. Business Analysis (SQL)
10 key business questions were answered through SQL queries:

| # | Question |
|---|----------|
| 1 | Revenue by gender |
| 2 | High-spending discount users |
| 3 | Top 5 products by rating |
| 4 | Shipping type comparison |
| 5 | Subscribers vs. non-subscribers |
| 6 | Discount-dependent products |
| 7 | Customer segmentation (New, Returning, Loyal) |
| 8 | Top 3 products per category |
| 9 | Repeat buyers & subscription correlation |
|10 | Revenue by age group |

### 3. Interactive Dashboard (Power BI)
Built an intuitive Power BI dashboard for visual exploration of:
- Revenue trends by demographics
- Product performance
- Customer segmentation
- Subscription insights

## 📋 Key Insights
- **Female customers** generated higher revenue than male customers
- **Express shipping** users spent slightly more on average
- **Subscribers** had slightly lower average spend but valuable lifetime value
- **Age group 31–45** contributed most revenue
- **Hats, Sneakers, Coats** were most discount-dependent products
- **Loyal customers** represent ~80% of the customer base

## 🚀 Business Recommendations
1. **Boost Subscriptions** – Promote exclusive benefits for subscribers
2. **Loyalty Programs** – Reward repeat buyers to move them into "Loyal" segment
3. **Review Discount Policy** – Balance sales boosts with margin control
4. **Product Positioning** – Highlight top-rated and best-selling products
5. **Targeted Marketing** – Focus on high-revenue age groups and express shipping users

## 📁 Repository Structure
