# ⚡ Power Outage Dashboard – Tier-2 Indian Cities

An end-to-end **data analysis and visualization project** that explores the impact of power outages across power plants in Tier-2 Indian cities. This dashboard helps identify the **most affected states**, **worst-performing plants**, and **root causes** behind frequent power failures, using real-world operational downtime data.

---

## 📊 Project Purpose

The goal of this project is to:
- Analyze power outage patterns across plants and states.
- Identify critical downtime events and operational inefficiencies.
- Provide an **interactive tool** for stakeholders to explore KPIs, root causes, and high-risk areas.
- Showcase the integration of **Python for data preparation** and **Power BI for business intelligence reporting**.

---

## 📁 Dataset Information

- **Source:** Provided for educational purposes (anonymized and transformed).
- **Format:** Excel `.xlsx` file
- **Scope:** Outage records from multiple power plants across Tier-2 Indian states
- **Key Fields:**
  - `PLANT`, `UNIT`, `STATE`
  - `REASON`, `TOTAL_DOWNTIME`
  - `YEAR`, `MONTH`, etc.


---

## 🛠 Tools & Technologies Used

| Tool | Purpose |
|------|---------|
| **Python (Pandas, Matplotlib)** | Data cleaning, wrangling, and EDA |
| **Power BI** | Interactive dashboard, visuals, slicers |
| **DAX** | Custom measures, KPIs, dynamic titles |
| **Excel** | Raw data format |

---

## 🚀 Dashboard Features

- 🔹 **Page 1 – Overview**
  - KPIs: Total Downtime, Affected States, Plants, Outages
  - Bar Chart: States with highest outages
  - Map: Geographic distribution of power failures

- 🔹 **Page 2 – Plant Performance**
  - Table: Downtime by plant
  - Donut: Downtime by unit
  - Scatter & bar: Downtime vs outage count

- 🔹 **Page 3 – Executive Summary**
  - Decomposition Tree: Root cause analysis by state → plant → reason
  - Table: Top 20 critical power failures
  - Cards: Worst performing plant, most common reason

---

## 📸 Sample Dashboard Screenshots

![Alt text](https://github.com/gaurav-verma11/Power-Outage-Analysis-Dashboard-Tier-2-Indian-Cities/blob/main/page1.png)

---

## 📂 Folder Structure

