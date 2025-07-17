# OTT Dashboard - Power BI

## 📊 Overview

This Power BI dashboard provides a comprehensive view of key metrics for an Over-The-Top (OTT) streaming service. The dashboard is designed to help stakeholders monitor user behavior, track subscription trends, analyze content performance, and support data-driven decisions to improve user engagement and retention.

## 🎯 Objectives

- Visualize user acquisition and retention metrics.
- Analyze viewer engagement across different types of content.
- Track revenue from subscriptions and ads.
- Provide insights into platform performance over time.

## 🧩 Dashboard Sections

1. **Home Page / Executive Summary**
   - High-level KPIs: Total Users, Active Users, Churn Rate, Revenue
   - Filters: Date Range, Region, Platform (Mobile, Web, Smart TV)

2. **User Analytics**
   - New vs Returning Users
   - Session Duration & Frequency
   - Churn & Retention Analysis

3. **Content Performance**
   - Most Watched Content
   - Genre-wise Performance
   - Completion Rates

4. **Subscription Analytics**
   - Subscription Growth Over Time
   - Plan Type Analysis (Monthly, Yearly)
   - Cancellation Reasons & Trends

5. **Revenue & Monetization**
   - Monthly Recurring Revenue (MRR)
   - Ad Revenue vs Subscription Revenue
   - Average Revenue Per User (ARPU)

6. **Device & Platform Insights**
   - User Access by Device Type
   - Platform Usage Trends

## 📂 Data Sources

- **Primary Source**: SQL Server (OTT_App_DB)
- **Additional Sources**: Excel (Manual Upload for Ad Revenue)
- **Data Refresh Frequency**: Weekly (Every Sunday 2 AM)

## 🛠 Tools Used

- **Power BI Desktop**
- **Power Query**
- **DAX for calculated metrics**
- **Bookmarks & Drillthrough for UX enhancements**

## 🧑‍💼 Target Audience

- Product Management Team
- Marketing & Growth Team
- Business Intelligence Analysts
- Senior Management / CXOs

## ✅ KPIs Tracked

| KPI                      | Description |
|--------------------------|-------------|
| Total Users              | Total registered users on the platform |
| Active Users             | Users who logged in at least once during the selected period |
| Churn Rate               | % of users who canceled their subscription |
| Retention Rate           | % of users who continued subscription |
| Monthly Recurring Revenue (MRR) | Monthly subscription income |
| Average Session Time     | Avg. time spent per user session |
| Top Content              | Most-watched shows/movies |
| Completion Rate          | % of content watched to the end |
| Platform Distribution    | Usage by Web, Mobile, TV, etc. |

## 📌 Filters & Drilldowns

- **Filters**: Date Range, Region, Device Type, Subscription Plan
- **Drilldowns**: From hi
