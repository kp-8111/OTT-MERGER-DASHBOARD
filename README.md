# 📺 OTT Merger Dashboard – Analyzing Jotstar & Liocinema Integration

## 🚀 Project Overview
The OTT Merger Dashboard is a Power BI-based analytics solution that provides insights into the merger of Jotstar & Liocinema, two major streaming platforms. The dashboard helps stakeholders understand user engagement, content performance, subscription behavior, and revenue trends to guide post-merger strategic decisions.

This project was developed as part of Codebasics Resume Project Challenge #14.

---

## 📊 Problem Statement
With the recent merger of Jotstar & Liocinema, it is essential to evaluate:
- ✅ How has content consumption changed post-merger?
- ✅ Which content types (Movies, Series, etc.) and genres drive the most engagement?
- ✅ Are users from both platforms engaging with the merged content?
- ✅ How do subscription trends compare before and after the merger?
- ✅ What factors influence user retention, upgrades, and downgrades?

This dashboard consolidates data from multiple sources, processes key business metrics, and presents actionable insights.

---

## 🎯 Project Objectives
The goal of this project is to:
- 🔹 Analyze streaming trends and content consumption behavior
- 🔹 Identify user engagement patterns and inactivity risks
- 🔹 Understand subscription revenue, upgrade, and downgrade trends
- 🔹 Optimize pricing strategies based on data-driven insights
- 🔹 Provide an interactive dashboard to assist in business decisions

---

## ⚒️ Tools & Technologies Used
- ✅ Power BI – Dashboard creation & data visualization
- ✅ SQL – Data transformation, cleaning, and querying
- ✅ Excel – Data aggregation & preprocessing

---

## 📂 Dataset & Data Model
The project uses merged datasets from Jotstar & Liocinema, including:

### 1️⃣ Merged_Contents Table (Content Library)
- `content_id` – Unique identifier for each content item
- `content_type` – Movie, Series, etc.
- `language` – Available languages (Hindi, English, etc.)
- `genre` – Action, Drama, Comedy, etc.
- `run_time` – Total duration (in minutes)

### 2️⃣ Merged_Subscribers Table (User Data)
- `user_id` – Unique identifier for each subscriber
- `age_group` – 18-24, 25-34, etc.
- `city_tier` – Tier 1, Tier 2, Tier 3
- `subscription_date` – Date of first subscription
- `subscription_plan` – Free, Basic, Premium, VIP
- `last_active_date` – Last interaction date (to track inactivity)
- `plan_change_date` – Date of last plan upgrade/downgrade

### 3️⃣ Merged_Content_Consumption Table (Watch Time & Engagement)
- `user_id` – Linked to subscribers
- `device_type` – Mobile, TV, Tablet
- `total_watch_time (mins)` – Total viewing duration

#### 🔗 Relationships:
- ✔ `content_id` (in Merged_Content_Consumption) → `content_id` (in Merged_Contents)
- ✔ `user_id` (in Merged_Content_Consumption) → `user_id` (in Merged_Subscribers)

**Data Model Diagram:**
![Data Model](https://github.com/kp-8111/OTT-MERGER-DASHBOARD/blob/main/Data%20Model.png)

---

## 📊 Dashboard Highlights

### 📌 1. Total Users & Growth Trends
- ✅ Tracks user acquisition and churn trends
- ✅ Compares pre-merger and post-merger user activity

### 📌 2. User Demographics
- ✅ Analyzes user base by age group, city tier, and subscription plan
- ✅ Provides insights into regional engagement patterns

### 📌 3. Paid User & Revenue Analysis
- ✅ Examines subscription revenue across different plans
- ✅ Tracks upgrade/downgrade trends

### 📌 4. Watch Time Analysis
- ✅ Identifies top-performing content types, genres, and languages
- ✅ Analyzes watch time by device type

### 📌 5. Inactivity Correlation
- ✅ Investigates relationship between low engagement and inactivity
- ✅ Helps predict at-risk users for re-engagement

### 📌 6. Upgrade & Downgrade Trends
- ✅ Shows how users transition between plans
- ✅ Helps optimize pricing strategies

### 📌 7. Content Library Insights
- ✅ Compares Jotstar vs. Liocinema content diversity
- ✅ Evaluates which genres drive the most engagement

---

## 🔗 Project Links
- 📊 Live Dashboard: [Live Dashboard](https://project.novypro.com/yn9QQn)
- 🖥️ Project Presentation: [LinkedIn Post](https://www.linkedin.com/posts/kp8111_codebasics-codebasicsresumeprojectchallenge-activity-7305526862317826048-rigU?utm_source=share&utm_medium=member_desktop&rcm=ACoAADBUMiIBbw-0vbmKJ3oXG_HRfnHXMUiO2fc)


---

🔹 This README provides everything someone needs—from understanding the project goals to using the dashboard. Let me know if you want any refinements! 🚀
