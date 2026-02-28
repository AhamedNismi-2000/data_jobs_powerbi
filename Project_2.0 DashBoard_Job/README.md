# 📊 Power BI Job Dashboard – Interactive Job Market Analysis

## 📌 Project Overview
This **Job Dashboard** is an interactive Power BI report designed to analyze multiple dimensions of the job market.  
It combines **cleaned data, calculated measures, and interactive visuals** to help users understand salary trends, job demand, benefits, and job distribution across locations.

The dashboard is optimized for **easy interaction, drill-through analysis, and decision-making**.

---

## 🧹 Data Preparation (Power Query)
Before visualization, the dataset was cleaned and transformed using **Power Query**, including:

- Removal of unnecessary and duplicate columns
- Handling missing and null values
- Standardizing job titles and categorical fields
- Data type corrections for salary and date fields
- Preparing fact tables for accurate aggregation

This ensures **reliable and consistent analysis** across all visuals.

---

## 📐 Measures & Calculations
Several DAX measures were created to support the dashboard, including:

- **Median Yearly Salary**
- **Median Hourly Salary**
- **Job Count**
- **Job Star Rating**
  - Calculated based on salary-related metrics
- Aggregated values used across cards, charts, and drill-through pages

---

## 🧭 Dashboard Structure

### 🟦 KPI Summary Cards
The home page includes **four KPI cards**:

- Median Yearly Salary  
- Median Hourly Salary  
- Job Star Rating  
- Total Job Count  

These provide a quick overview of the job market.

---

### 🎛️ Filters & Navigation
- **Job Title Slicer**  
  Allows users to filter the entire dashboard by selected job title.

- **Drill-Through Button**  
  Enables navigation to a detailed page based on the selected job title or visual value.

---

## 📈 Visualizations – Home Page

- **Line Chart**  
  - X-axis: Job Posted Date  
  - Y-axis: Job Count  

- **Scatter Plot**  
  - Median Hourly Salary vs Median Yearly Salary  
  - Labeled by Job Title  

- **Bar Chart**  
  - X-axis: Job Count  
  - Y-axis: Job Title  

- **Matrix Visual**  
  - Job Title  
  - Median Hourly Salary  
  - Median Yearly Salary  
  - Job Count  
  - Sparkline for trend visualization  

---

## 🖼️ Dashboard Screenshot – Home Page
<p align="center">
  <img src="/images/job_dashboard_home.png" width="1200" alt="Job Dashboard Home Page">
</p>

---

## 🔍 Drill-Through Page – Detailed Analysis

### 🧭 Navigation
- **Home Icon Button** to return to the main dashboard

### 📌 Context Awareness
- Displays the **Job Title selected** from the home page

### 📊 Detailed Visuals
- **Gauge Cards**
  - Median Hourly Salary
  - Median Yearly Salary

- **Pie Charts**
  - Work From Home availability
  - Insurance availability
  - Degree requirement

- **Map Visual**
  - Job posting distribution by country

- **Bar Chart**
  - X-axis: Job Count
  - Y-axis: Job posting source

- **Tree Map**
  - Job schedule type distribution

---

## 🖼️ Dashboard Screenshot – Drill-Through Page
<p align="center">
  <img src="/images/job_dashboard_detail.png" width="1200" alt="Job Dashboard Drill-Through Page">
</p>

---

## 🛠️ Tools & Technologies
- Power BI Desktop
- Power Query (ETL & Data Cleaning)
- DAX Measures
- Cards, Line, Bar, Scatter, Matrix, Gauge, Pie, Map & Tree Map visuals
- Slicers, Drill-Through & Navigation Buttons

---

## 🎯 Key Features
- Cleaned and transformed data for accuracy
- Median-based salary analysis
- Interactive filtering by job title
- Drill-through navigation for detailed insights
- User-friendly and intuitive dashboard design

---

## 📂 Repository Structure
- `README.md` – Project documentation  
- `images/` – Dashboard screenshots  
- Power BI report file (`.pbix`)

---

## ✅ How to Use
1. Open the `.pbix` file in **Power BI Desktop**.
2. Use the **Job Title slicer** to filter data.
3. Review KPIs and charts on the home page.
4. Click the **drill-through button** for detailed analysis.
5. Use the **home icon** to return to the main dashboard.

