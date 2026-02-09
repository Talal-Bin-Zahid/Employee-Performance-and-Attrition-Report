# Employee-Performance-and-Attrition-Report
<img width="962" height="537" alt="Employee Performance and Attrition Report" src="https://github.com/user-attachments/assets/df7b3a2c-525a-4267-a2a4-b5d136ae17d3" />

## 📌 Project Overview

The **Employee Performance and Attrition Report** is an interactive Power BI dashboard designed to analyze workforce composition, employee performance indicators, and attrition drivers. The report consolidates demographic, compensation, tenure, satisfaction, and work-life balance metrics into a single analytical view, enabling HR leaders and business stakeholders to identify high-risk attrition segments and support data-driven retention strategies.

The dashboard leverages **dynamic slicers, KPI cards, comparative charts, and relationship-based visuals** to provide both high-level insights and granular analysis across employee attributes.

---

## 🎯 Business Objective

* Measure overall employee attrition and workforce stability
* Identify demographic, departmental, and role-based attrition patterns
* Evaluate the impact of compensation, tenure, job satisfaction, and work-life balance on employee exits
* Enable interactive, self-service HR analytics through Power BI

---

## 📊 Key Performance Indicators (KPIs)

| KPI                          | Value          | Description                                            |
| ---------------------------- | -------------- | ------------------------------------------------------ |
| **Total Employees**          | **1,470**      | Total number of employees included in the analysis     |
| **Average Monthly Income**   | **$6.50K**     | Average monthly compensation across all employees      |
| **Average Years at Company** | **7.01 Years** | Mean employee tenure                                   |
| **Attrition Rate**           | **16.12%**     | Percentage of employees who have left the organization |

---

## 📈 Metrics & Numerical Measures

The dashboard incorporates the following calculated and aggregated metrics:

* **Attrition Count** (Yes / No)
* **Attrition Percentage**
* **Employee Count by Category**
* **Average Monthly Income**
* **Average Years at Company**
* **Job Satisfaction Distribution**
* **Work-Life Balance Score Distribution**
* **Education Level Distribution**
* **Gender-wise Attrition Share**
* **Department-wise Attrition Count**
* **Role-wise Attrition Patterns**

All KPIs and metrics are calculated using **DAX measures** to ensure accuracy and interactivity across slicers.

---

## 📊 Core Visualizations & Analytical Insights

### 1️⃣ Attrition by Education Level

* **Visualization:** Clustered Bar Chart
* **Metric:** Attrition Count (Yes / No)
* **Categories:** Education Levels 1–5
* **Purpose:** Identifies education tiers with disproportionately high turnover

---

### 2️⃣ Attrition by Gender

* **Visualization:** Donut Chart
* **Metrics:**

  * Male Attrition: **63.29%**
  * Female Attrition: **36.71%**
* **Purpose:** Highlights gender-based attrition distribution and workforce diversity patterns

---

### 3️⃣ Attrition by Department

* **Visualization:** Bar Chart
* **Departments Analyzed:**

  * Research & Development
  * Sales
  * Human Resources
* **Metrics:** Attrition Count (Yes / No)
* **Purpose:** Identifies departments with elevated attrition risk

---

### 4️⃣ Job Satisfaction vs. Attrition (Heatmap)

* **Visualization:** Matrix / Heatmap
* **Rows:** Job Roles
* **Columns:** Job Satisfaction Levels (1–4)
* **Metric:** Attrition Percentage
* **Purpose:** Examines how job satisfaction impacts attrition across different roles

---

### 5️⃣ Work-Life Balance vs. Attrition

* **Visualization:** Horizontal Bar Chart
* **Metric:** Attrition Count
* **Scale:** Work-Life Balance Ratings (1–4)
* **Purpose:** Demonstrates correlation between poor work-life balance and higher attrition

---

### 6️⃣ Monthly Income vs. Age

* **Visualization:** Scatter Plot
* **X-Axis:** Age
* **Y-Axis:** Monthly Income
* **Legend:** Attrition Status (Yes / No)
* **Purpose:** Identifies income and age clusters associated with higher attrition risk

---

## 🎛️ Interactive Filters & Parameters

The dashboard includes the following **dynamic slicers** for detailed segmentation:

* **Age Range** (18–60)
* **Marital Status**
* **Gender**
* **Department**

These parameters allow users to:

* Drill down into specific employee segments
* Compare attrition patterns across demographics
* Perform targeted workforce analysis

---

## 🔍 Key Analytical Findings

* Sales roles exhibit **higher attrition**, particularly among employees with **low job satisfaction**
* Employees reporting **poor work-life balance** show significantly increased turnover
* **Early-career employees** demonstrate higher attrition despite lower income levels
* Certain **education levels** experience disproportionate attrition
* Attrition patterns vary substantially across **job roles and departments**

---

## 🛠️ Technical Stack

* **Power BI Desktop** – Dashboard design and visualization
* **DAX (Data Analysis Expressions)** – KPI and metric calculations
* **Power Query** – Data cleaning, transformation, and modeling
* **Interactive Slicers & Filters** – Dynamic data exploration

---

## 🚀 Future Enhancements

* Predictive attrition modeling using machine learning
* Time-series attrition trend analysis
* Department-level drill-through pages
* Integration with employee engagement and survey data
* Advanced cohort and tenure-based analysis

---

