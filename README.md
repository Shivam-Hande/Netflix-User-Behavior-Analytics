# Netflix User Behavior Analytics

## 📊 Overview

Netflix User Behavior Analytics is a data analytics project built using **SQL and Microsoft Excel** to analyze user engagement, subscription behavior, viewing patterns, content preferences, and monthly activity.

The project demonstrates an end-to-end analytics workflow:

**Raw Data → SQL Data Cleaning → Exploratory Analysis → Business Analysis → Excel Dashboard → Insights**

The goal is to transform raw user-level data into meaningful insights that can support decisions around customer engagement, subscriptions, content strategy, and user retention.

---

## 🎯 Business Problem

A streaming platform generates large amounts of user activity data, but raw data alone does not provide clear business insights.

The key business questions addressed in this project include:

- Which countries have the highest number of users?
- Which subscription types are most popular?
- Which content genres receive the highest engagement?
- How does watch time vary across different user segments?
- How does user activity change over time?
- Which subscription groups show stronger engagement?
- Which customer segments could be targeted for improved retention?
- What patterns can help improve content and subscription strategies?

---

## 🛠️ Tools & Technologies

- **SQL** — Data cleaning, transformation, aggregation, and business analysis
- **Microsoft Excel** — Data analysis, Pivot Tables, charts, slicers, and dashboard development
- **CSV** — Source dataset

---

## 🔄 Project Workflow

### 1. Data Preparation

The raw dataset was examined for:

- Missing values
- Duplicate records
- Data consistency
- Invalid or inconsistent values
- Data types
- Key analytical fields

SQL was used to prepare the dataset for analysis.

### 2. SQL Analysis

SQL queries were developed to perform:

- Data quality checks
- Aggregations
- User segmentation
- Subscription analysis
- Country-level analysis
- Genre analysis
- Engagement analysis
- Monthly activity analysis
- Business-focused analysis

### 3. Excel Analysis

The processed data was analyzed using:

- Pivot Tables
- Pivot Charts
- Slicers
- KPI summaries
- Interactive visualizations
- Dashboard components

### 4. Business Insights

The final analysis converts the results into actionable insights related to:

- Customer engagement
- Subscription behavior
- Content preferences
- User activity
- Retention opportunities

---

## 📁 Repository Structure

```text
Netflix-User-Behavior-Analytics
│
├── SQL
│   ├── 01_Data_Cleaning.sql
│   ├── 02_Exploratory_Analysis.sql
│   └── 03_Business_Analysis.sql
│
├── Excel
│   └── Netflix_User_Analytics.xlsx
│
├── Dataset
│   └── netflix_users.csv
│
├── Screenshots
│   └── dashboard.png
│
└── README.md
