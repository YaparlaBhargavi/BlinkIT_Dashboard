# 🛒 Blinkit Power BI Dashboard – Interactive Sales Insights

This project is an interactive and visually-rich dashboard developed using Microsoft Power BI to analyze sales and performance data for Blinkit, a leading online grocery delivery platform. It helps the business understand key performance indicators such as sales volume, outlet performance, customer ratings, item categories, and fat content distribution.

As a fresher, this was my hands-on project to explore real-world data analysis, build meaningful dashboards, and tell data stories effectively using Power BI. The result is a complete solution to support Blinkit's business insights using an easy-to-navigate interface.

---

## 📌 Problem Statement

Blinkit needs a better understanding of its operational data to optimize product offerings, improve customer satisfaction, and scale outlet performance. Specifically, the company wanted to answer questions such as:

- Which outlet types perform best in terms of sales?
- What kinds of food items generate the most revenue?
- How does fat content influence sales?
- Which locations (Tier 1, 2, or 3) are driving business growth?
- What do customer ratings tell us about overall satisfaction?

The challenge was to create a single dashboard that could dynamically address all of these questions through visual exploration.

---

## 🧪 Dataset Summary

The dataset consists of retail and sales data with columns like:
- **Item Type**
- **Item Fat Content**
- **Outlet Size**
- **Outlet Type**
- **Outlet Location Type (Tier 1/2/3)**
- **Sales**
- **Rating**
- **Outlet Establishment Year**

From this raw data, I created key DAX measures:
- **Total Sales** = `SUM(Sales)`
- **Average Sales** = `AVERAGE(Sales)`
- **Average Rating** = `AVERAGE(Rating)`
- **Number of Items** = `COUNT(Item_ID)`

---

## 🛠️ Steps Followed

1. **Data Cleaning**: 
   - Removed duplicates and null values.
   - Standardized inconsistent fat content entries like "LF" and "low fat".
   - Verified numeric data types for aggregation.

2. **Data Modeling**: 
   - Built proper relationships and applied star schema design principles.
   - Ensured compatibility for slicers and interactive filtering.

3. **DAX Calculations**:
   - Developed essential metrics to power the dashboard cards and charts.

4. **Dashboard Design**:
   - Arranged visuals logically for business users.
   - Used KPI cards, line charts, donut charts, bar graphs, stacked visuals, and a matrix table.

5. **Interactivity**:
   - Added slicers for Outlet Size, Outlet Location Type (Tier), and Item Type.
   - Enabled sync across visuals to ensure consistent filtering experience.

---

## 📊 Dashboard Components

| Component             | Description                                                                 |
|-----------------------|-----------------------------------------------------------------------------|
| 💰 **Total Sales**     | Overall revenue generated from all items and outlets.                       |
| ⭐ **Avg Rating**       | Average customer satisfaction based on product experience.                  |
| 🏬 **Outlet Growth**    | Number of outlets opened across different years.                            |
| 🧁 **Fat Content Chart**| Shows consumer preference for fat content (Low Fat, Regular, etc.).         |
| 🧺 **Item Type Sales**  | Highlights top-performing item categories like Snacks, Fruits, Household.   |
| 🌐 **Outlet Location**  | Compares business performance across Tier 1, 2, and 3 cities.               |
| 📊 **Matrix Table**     | Summarizes outlet-wise sales, item count, and average rating.               |

---

## 🔍 Key Insights

- **Tier 3 outlets** drive the highest total sales, indicating strong demand in emerging cities.
- **Supermarket Type2** is the best-performing outlet category.
- **Fruits, Snacks, and Household goods** are the top-selling item types.
- Products labeled **Low Fat** and **Regular** are more popular than other fat content types.
- The **average rating** across all outlets is approximately **3.9**, suggesting moderate customer satisfaction.

---

## 🔧 Dashboard Design Highlights

- **KPI Cards** at the top to show vital metrics quickly (Sales, Items, Rating).
- **Line Chart** visualizing outlet growth over time.
- **Donut Chart** comparing outlet sizes.
- **Bar Charts** analyzing item categories and fat content preferences.
- **Stacked Chart** illustrating fat content across outlet tiers.
- **Matrix Table** for detailed multi-metric outlet performance view.
- **Slicers** for interactive filtering by outlet location, size, and item type.

---

## 🧑‍🎓 What I Learned as a Fresher

As a beginner in data analytics, this project was a turning point in my learning journey. Here’s what I gained:

| Skill               | Description                                                                 |
|---------------------|-----------------------------------------------------------------------------|
| **Power BI**         | Learned how to import, transform, model, and visualize data.                |
| **DAX**              | Gained experience in writing formulas for aggregation and logic.            |
| **Data Analysis**    | Identified patterns and correlations from business data.                    |
| **Dashboard Design** | Practiced designing clean, business-focused layouts using color & clarity.  |
| **Storytelling**     | Learned how to translate raw numbers into actionable insights.              |

---

## 🧗 Challenges Faced

| Challenge              | Solution                                                                 |
|------------------------|--------------------------------------------------------------------------|
| Writing custom DAX     | Practiced using Microsoft Docs and Power BI community examples.          |
| Layout balancing       | Applied Power BI UX/UI principles to design visual hierarchy.            |
| Slicer conflicts       | Solved by using visual-level and synced slicers across pages.            |
| Performance issues     | Minimized visuals and used optimized measures to improve responsiveness. |

---

 # Report Snapshot (Power BI DESKTOP)

 
![Dashboard_upload](![Screenshot 2025-06-15 191103](https://github.com/user-attachments/assets/bae84c41-919b-4908-825d-294813585f00)
)

