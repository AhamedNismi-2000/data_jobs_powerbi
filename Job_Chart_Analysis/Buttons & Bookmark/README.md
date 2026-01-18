# 📊 Power BI Report – Job Posting Insights with Bookmarks & Buttons

## 📌 Project Overview
This Power BI project demonstrates the use of **Bookmarks and Buttons** to build an **interactive dashboard** using the `job_posting_fact` dataset.

The report focuses on **median salary analysis, degree requirements, and country-wise pay comparison** for the **Top 6 job roles**, while showcasing advanced **bookmark-driven navigation and filtering**.

---

## 📸 Dashboard Preview

<p align="center">
  <img src="images/overview.png" width="800" alt="Dashboard Overview">
</p>

<p align="center">
  <img src="images/fitler.png" width="800" alt="Bookmarks and Buttons Interaction">
</p>

---

## 🗂 Dataset
- **Table Used:** `job_posting_fact`
- **Key Fields:**
  - Job Title  
  - Median Yearly Salary  
  - Country  
  - Degree Requirement (Degree Mentioned / No Degree Mentioned)

---

## 📈 Visualizations

### 1️⃣ Median Yearly Salary by Job Title (Bar Chart)
- **X-axis:** Median Yearly Salary  
- **Y-axis:** Job Title  
- **Purpose:** Compare salary differences across job roles.

---

### 2️⃣ Median Salary for Jobs with *No Degree Mentioned* (Stacked Column Chart)
- **X-axis:** Job Title  
- **Y-axis:** Median Yearly Salary  
- **Purpose:** Analyze salary potential without formal degree requirements.

---

### 3️⃣ Top 4 Countries Paying Top 6 Jobs (Column Chart)
- **Countries:** US, UK, France, India  
- **X-axis:** Country  
- **Y-axis:** Median Yearly Salary  
- **Purpose:** Country-wise salary comparison for top roles.

---

### 4️⃣ Degree Requirement Distribution (100% Stacked Bar Chart)
- **X-axis:** Degree Requirement  
- **Y-axis:** Job Title  
- **Purpose:** Shows proportion of job postings with and without degree requirements.

---

## 🎛 Interactivity (Bookmarks & Buttons)

### 🔹 Job Title Slicer
- Filters **Top 6 job roles**
- Hidden by default
- Displayed using a **Bookmark Button**

### 🔘 Buttons Implemented
- **Filter Button:** Opens slicer using bookmarks  
- **Clear Filter Button:** Clears slicer selections  
- **Back Button:** Returns to default dashboard view  

All interactions are handled using **Power BI Bookmarks**, not visual-level filters.

---

## 🔁 Bookmark Workflow
| Bookmark | Function |
|--------|----------|
| Default View | Clean dashboard without slicers |
| Filter View | Displays job title slicer |
| Clear Filter | Resets slicer state |

---

## 🧭 How to Use
1. Start with the default dashboard  
2. Click **Filter** to open the slicer  
3. Select job roles from Top 6  
4. Observe updates across all visuals  
5. Use **Clear Filter** to reset  
6. Click **Back** to return  

---

## 🛠 Tools & Skills
- Power BI  
- Bookmarks & Buttons  
- Slicers & Cross-filtering  
- Data Visualization & Storytelling  

---

## 📎 Use Case
Ideal for:
- Power BI portfolio
- Dashboard UI/UX demonstration
- Academic or interview evaluation
