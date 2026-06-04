# Nutrition Tracking System

An advanced data analytics and visualization project designed to monitor, track, and evaluate nutritional outcomes and implementation metrics under the POSHAN Abhiyaan initiative. This repository contains the data processing pipelines, visualization scripts, and the final executive monitoring report.

## 📌 Project Overview
This project transforms raw tracking data into actionable insights for healthcare and administrative stakeholders. By leveraging structured data modeling and robust visualization, the system tracks key performance indicators (KPIs) related to maternal and child nutrition, institutional delivery rates, and regional performance.

### Key Deliverables
* **Executive Summary Report:** A high-quality analytical document detailing core findings and strategic recommendations.
* **Data Pipelines:** Automated data cleaning and transformation scripts for consistent reporting.

---

## 🛠️ Tech Stack & Architecture

### Tools & Languages
* **Data Processing:** Python (`pandas`, `numpy`)
* **Visualization:** `matplotlib`, `seaborn`


### Data Modeling (Star Schema)
To ensure optimal performance and scalable reporting, the analytical environment is structured using a **Star Schema**:
* **Fact Table:** Stores core transactional metrics (e.g., monthly tracking logs, nutritional measurements, distribution records).
* **Dimension Tables:** Contains contextual attributes including:
  * `Dim_Demographics` (Age groups, target demographics)
  * `Dim_Geography` (State, District, Block-level metadata)
  * `Dim_Time` (Standardized calendar and fiscal periods)

---

## 📊 Key Insights Captured
* **Target vs. Achievement:** Tracking actual metrics against national nutritional goals.
* **Regional Disparities:** Identifying high-performing vs. critical-priority districts to optimize resource distribution.
* **Trend Analysis:** Monitoring month-over-month progress in institutional deliveries and supplemental nutrition intake.
