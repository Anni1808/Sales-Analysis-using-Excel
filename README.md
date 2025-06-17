# Sales-Analysis-using-Excel

### 🔍 Project Overview

This project demonstrates the power of **Advanced Excel** in solving a real-world business problem — understanding and analyzing the performance of sales across different segments, categories, regions, and customer types using **interactive dashboards**.

The dataset used is the popular **Sample Superstore** dataset, which simulates real-world retail data including orders, profits, shipping, and customer information.

---

## ✅ Goals of the Project

* Clean and transform messy retail data
* Use **Power Query** for data preparation
* Analyze performance using **PivotTables**
* Create **interactive dashboards** with **slicers**
* Apply formulas like `SUMIFS`, `AVERAGEIFS`, and `COUNTIFS`
* Enable user-driven dynamic reporting

---

## 🛠 Tools & Features Used

| Feature/Tool                     | Usage                                                  |
| -------------------------------- | ------------------------------------------------------ |
| **Power Query**                  | To import, clean, and transform raw data               |
| **PivotTables & PivotCharts**    | For dynamic analysis (sales, profit, orders)           |
| **Slicers**                      | To add interactivity for Region, Segment, Category     |
| **Data Validation** *(optional)* | To add dropdown-based filters                          |
| **Formulas**                     | `SUMIFS`, `AVERAGEIFS`, `COUNTIFS`, `UNIQUE`, `FILTER` |
| **Dashboard Sheet**              | Final report with interactive visuals                  |

---

## 📌 Step-by-Step Breakdown

### 🔹 **Step 1: Data Cleaning with Power Query**

* Imported the CSV file using **Get Data → From CSV**.
* Opened **Power Query Editor**:

  * Checked for missing values.
  * Ensured `Order Date` and `Ship Date` were recognized as **Date type**.
  * Removed unnecessary columns.
* Loaded the cleaned data into Excel.

### 🔹 **Step 2: Data Exploration**

* Explored key metrics like:

  * Total Sales
  * Total Profit
  * Order Volume
* Understood column definitions (e.g., **Sales** is revenue; **Profit Margin** is calculated from Profit/Sales).

### 🔹 **Step 3: PivotTables and Charts**

* Created PivotTables to summarize:

  * Sales and profit by Region, Category, Sub-Category
  * Time-based analysis using `Order Date` (grouped by Year/Month)
* Built visualizations:

  * Bar charts, Line charts, Pie charts
  * Converted y-axis to "K" format (thousands) for readability

### 🔹 **Step 4: Interactive Filters with Slicers**

* Inserted **Slicers** for:

  * Region
  * Segment
  * Category
  * Year
* Linked slicers to multiple PivotTables using **PivotTable Connections**.

Optional:

* Also built drop-down filters with **Data Validation + UNIQUE + FILTER** to demonstrate formula-driven interactivity.

---

## 🚧 Issues Faced and Resolved

| Issue                                     | Solution                                                             |
| ----------------------------------------- | -------------------------------------------------------------------- |
| Changing column type to Date gave errors  | Ensured all date values were valid in Power Query before converting  |
| Power Query `Fill Down/Up` was confusing  | Understood that it fills missing values **downwards** from above     |
| Wanted unique items in drop-down lists    | Used `=UNIQUE()` and created **Named Ranges**                        |
| “Group” option was disabled in PivotTable | Found that **multiple PivotTables selected** disables group function |
| Formatting y-axis in charts (e.g., 10K)   | Used **Custom Number Format** in chart settings (`#,##0,"K"`)        |
| Dashboard layout was messy initially      | Organized layout: slicers on left, charts center, KPIs on top-right  |

---

## 🧠 Key Learnings

* Learned real-world application of **Excel for business intelligence**
* Understood how to **clean data like a pro** using Power Query
* Built a fully interactive, visually clean **Excel dashboard**
* Developed logic for dynamic metrics using `SUMIFS`, `AVERAGEIFS`, `COUNTIFS`

---


## 💼 Real-World Use Case

This dashboard is ideal for:

* Retail business performance monitoring
* Product/Segment/Region-wise profitability analysis
* Quick sales insights for executives or sales managers

