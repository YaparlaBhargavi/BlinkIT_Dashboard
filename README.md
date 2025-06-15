# 🛒 Blinkit Interactive Power BI Dashboard

Welcome to the **Blinkit Sales Performance Dashboard** — a project built to demonstrate how business intelligence tools like **Power BI** can help companies like Blinkit (India’s Last Minute App) visualize and understand their data for better decision-making.

---

## 📘 Project Overview

This Power BI dashboard provides a **360° view of sales performance**, item distribution, customer ratings, and outlet details across multiple dimensions such as:

- **Outlet Location (Tier 1, 2, 3)**
- **Outlet Type and Size**
- **Item Type and Fat Content**
- **Customer Feedback (Ratings)**

The dashboard enables users (analysts, managers, decision-makers) to filter data dynamically and derive **actionable insights** to improve supply chain, marketing strategy, or product mix.

---

## 🎯 Use Case Scenarios

| Scenario | Business Question |
|----------|-------------------|
| Sales by Location | Which tier cities generate the most revenue? |
| Outlet Type Analysis | Which outlet type (e.g., Supermarket Type2) performs best? |
| Product Mix | What item types contribute most to sales? |
| Health Preferences | Are low-fat products popular among customers? |
| Ratings Insight | How do ratings vary across outlet types and item categories? |

---

## 📌 Problem Statement

Blinkit wants to understand how different outlets and items perform across India to make data-driven decisions. This includes:

- Monitoring sales across **regions and outlet types**
- Identifying **top-selling item categories**
- Understanding **customer preferences** through ratings
- Analyzing **outlet growth** over time
- Exploring how **fat content** impacts sales

As a **fresher in data analytics**, this project provided me with hands-on experience in **turning raw data into insights using Power BI**.

---

## 🧪 Dataset Summary

- **Variables Used**:
  - `Item Type`, `Outlet Type`, `Fat Content`, `Outlet Size`
  - `Sales`, `Rating`, `Establishment Year`
- **Metric Calculations**:
  - `Total Sales`, `Average Sales`, `Total Items`, `Average Rating`

---

## 🛠️ Step-by-Step Workflow

### 🔹 1. Data Cleaning
- Removed nulls and inconsistent values
- Formatted categories (e.g., Fat Content to: LF, Low Fat, Regular)

### 🔹 2. Data Modeling
- Created relationships between tables (if needed)
- Defined hierarchies for filtering

### 🔹 3. DAX Measures
```DAX
Total Sales = SUM(Sales)
Average Sales = AVERAGE(Sales)
Average Rating = AVERAGE(Rating)
No. of Items = COUNT(Item_ID)
## 🔹 4. Dashboard Design

The dashboard was designed with simplicity and insight in mind. It includes the following visual components:

- **KPI Cards** at the top displaying:
  - Total Sales
  - Average Sales
  - Number of Items
  - Average Customer Rating

- **Line Chart** to show the outlet growth over the years.

- **Donut Chart** to compare different outlet sizes visually.

- **Bar Charts** to illustrate sales by item type and fat content breakdown.

- **Stacked Bar Chart** showing how fat content types are distributed across different outlet locations.

- **Matrix Table** for detailed comparison of sales, ratings, and visibility across outlet types.

---

## 🔹 5. Interactivity

To make the dashboard user-friendly and flexible for analysis, the following **slicers** (filters) were added:

- **Outlet Location Type** (Tier 1, Tier 2, Tier 3)
- **Outlet Size** (Small, Medium, High)
- **Item Type** (e.g., Fruits, Snacks, Household)

These slicers allow users to interact with and explore specific segments of the data in real time.

---

## 📊 Dashboard Components Explained

| Component               | Description                                                                 |
|-------------------------|-----------------------------------------------------------------------------|
| 💰 **Total Sales**      | Shows the overall sales performance across all outlets.                    |
| ⭐ **Avg Rating**        | Reflects the average customer satisfaction score.                          |
| 🏬 **Outlet Growth**     | Displays the number of stores established over the years.                   |
| 🧁 **Fat Content Chart** | Breaks down sales by fat content (Low Fat, Regular, LF, etc.).             |
| 🧺 **Item Type Sales**   | Highlights top-selling product categories like Fruits, Snacks, etc.        |
| 🌐 **Outlet Location**   | Compares outlet sales across Tier 1, 2, and 3 city types.                   |
| 📊 **Matrix Table**      | Summarizes sales, item count, and average rating by outlet type.           |

---

## 🔍 Insights from the Dashboard

Here are some of the key insights derived from the dashboard:

- **Tier 3 outlets** contribute the highest amount to total sales.
- **Supermarket Type2** outlets are the best-performing outlet type.
- Items like **fruits, snacks, and household goods** generate the most revenue.
- **Low Fat** and **Regular** fat content items sell better than LF-labeled products.
- The **average customer rating** remains stable at around **3.9**, indicating moderate customer satisfaction.

---

## 🧑‍🎓 What I Learned as a Fresher

This project helped me grow both technically and analytically. Key skills and learnings include:

| Skill                 | Description                                                                 |
|------------------------|-----------------------------------------------------------------------------|
| **Power BI**           | Learned how to import data, clean it, and create interactive dashboards.    |
| **DAX**                | Practiced writing calculated measures for totals, averages, and counts.     |
| **Data Analysis**      | Gained insights by exploring trends and comparing data categories.          |
| **Storytelling**       | Designed visuals to tell a meaningful business story from raw data.         |
| **Visualization Design** | Built a clean and color-coded dashboard using best practices in UX/UI.     |

---

## 🧗 Challenges I Faced

As a fresher, I encountered several challenges and overcame them through learning and practice:

| Challenge                 | Solution                                                                 |
|---------------------------|--------------------------------------------------------------------------|
| Writing custom **DAX**    | Referred to Power BI community resources and Microsoft Docs.             |
| Balancing dashboard layout | Followed Power BI UI/UX best practices for clean design.                |
| Slicer filter conflicts   | Used visual-level filters and selection syncing to avoid overlaps.       |
| Performance optimization  | Reduced unnecessary visuals and minimized heavy calculations.            |

---
