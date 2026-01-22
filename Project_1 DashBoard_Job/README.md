# 📊 Power BI Job Dashboard – Interactive Job Market Analysis

## 📌 Project Overview
This **Job Dashboard** is an interactive Power BI report designed to analyze multiple aspects of the job market in a single view.  
It enables users to explore **salary metrics, job demand, job quality, and work conditions** using cards, charts, slicers, and drill-through functionality.

The dashboard is built with a **user-centric design**, making it easy to filter, drill down, and navigate between insights.

---

## 🧭 Dashboard Structure

### 🟦 Summary Cards
The dashboard includes **four KPI cards** that provide quick insights:

- **Median Yearly Salary**
- **Median Hourly Salary**
- **Job Star Rating**  
  - Calculated based on salary and job-related factors
- **Total Job Count**

These cards give an instant overview of the job market status.

---

### 🎛️ Filters & Navigation

#### 🔹 Job Title Slicer
- Allows users to **filter the entire dashboard by job title**
- Updates all visuals dynamically based on selection

#### 🔹 Drill-Down / Drill-Through Button
- Enables users to **drill through** using a selected job title or value
- Navigates to a detailed analysis page for deeper insights

---

## 📈 Visualizations – Home Page

### 🔹 Line Chart
- **X-axis:** Job Posted Date  
- **Y-axis:** Job Count  
- Shows job posting trends over time

---

### 🔹 Scatter Plot
- Displays **Median Hourly Salary vs Median Yearly Salary**
- Each data point is **labeled by Job Title**
- Helps identify high-paying roles and salary distribution

---

### 🔹 Bar Chart (Job Demand)
- **X-axis:** Job Count  
- **Y-axis:** Job Title  
- Highlights demand across different job roles

---

### 🔹 Matrix Visual
Includes:
- **Job Title**
- **Median Hourly Salary**
- **Median Yearly Salary**
- **Job Count**
- **Sparkline** for trend visualization

This provides a detailed, comparative view of job performance.

---

## 🖼️ Dashboard Screenshot (Home Page)
![Job Dashboard Home Page](images/job_dashboard_home.png)

> 📌 Replace the image name with your actual screenshot uploaded inside the `images/` folder.

---

## 🔍 Drill-Through Page – Detailed Job Analysis

### 🏠 Navigation
- **Home Icon Button** to return to the main dashboard

---

### 📌 Selected Job Context
- Displays the **Job Title selected** from the home page
- Ensures context-aware analysis

---

### 📊 Detailed Visuals

#### 🔹 Gauge Cards
- **Median Hourly Salary**
- **Median Yearly Salary**
- Helps visualize salary position against defined ranges

---

#### 🔹 Pie Charts
- **Work From Home Availability**
- **Employees With / Without Insurance**
- **Jobs With Degree Requirement**

Used to analyze job benefits and requirements.

---

#### 🔹 Map Visual
- Shows **Job Posting Countries**
- Helps identify geographical demand

---

#### 🔹 Bar Chart (Job Source)
- **X-axis:** Job Count  
- **Y-axis:** Job Posting Source (via where the job is posted)

---

#### 🔹 Tree Map
- Represents **Job Schedule Type**
- Visualizes distribution across full-time, part-time, contract, etc.

---

## 🖼️ Dashboard Screenshot (Drill-Through Page)
![Job Dashboard Drill-Through Page](images/job_dashboard_detail.png)

> 📌 Replace the image name with your actual drill-through page screenshot.

---

## 🛠️ Tools & Technologies
- **Power BI Desktop**
- **DAX Measures**
- Cards, Line, Bar, Scatter, Pie, Gauge, Map & Tree Map Visuals
- Slicers, Drill-Through & Navigation Buttons

---

## 🎯 Key Features
- Fully interactive job title filtering
- Drill-through analysis for detailed exploration
- Clear navigation using buttons and icons
- Combination of summary KPIs and detailed visuals

---

## 📂 Repository Structure
- `README.md` – Project documentation  
- `images/` – Dashboard screenshots  
- Power BI report file (`.pbix`)

---

## ✅ How to Use
1. Open the Power BI report file in **Power BI Desktop**.
2. Use the **Job Title slicer** to filter the dashboard.
3. Review key metrics using the **summary cards**.
4. Click the **drill-through button** to navigate to the detailed view.
5. Use the **home icon** to return to the main dashboard.

---

## 📬 Author
**Nismi**
