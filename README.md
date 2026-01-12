# Attendance & Work Preference Analysis – Power BI Project

## Project Overview

This project analyzes employee attendance and work preferences using **Power BI** and **DAX**.
The objective is to identify patterns in work preferences, calculate sick leave percentages, and provide actionable insights for better workforce planning.

The project demonstrates **data gathering, transformation, and visualization skills**, allowing organizations to track attendance, understand employee work behavior, and plan effectively.

---

## Tools & Technologies

* **Power BI** – Dashboard creation, data modeling, and visualization
* **Power Query** – Data cleaning, transformation, and combining multiple sheets
* **DAX** – Measures, matrices, and key metrics calculation
* **Excel** – Source data across multiple sheets

---

## Dataset Description

The dataset contains employee attendance data spread across multiple Excel sheets (one sheet per month).
For example, the April 2022 sheet includes:

* Employee Code
* Name
* Daily attendance status (e.g., Present, Sick Leave, Work from Home, Holiday)

Other months follow the same structure. Data was consolidated into a **single table** for analysis.

---

## Data Gathering & Transformation

* Multiple monthly sheets were combined using **Power Query** to create a unified dataset.
* Null, blank, and inconsistent values were cleaned.
* Dates and attendance values were standardized for easier analysis.
  
Attendance data was originally stored across multiple monthly Excel sheets, each following a similar structure.
To ensure scalability and consistency, a template-based transformation approach was implemented using Power Query.

Created a standardized template query for one month (April)

Converted the template into a custom Power Query function

Applied the function dynamically to all monthly sheets

Automatically expanded and combined data into a single consolidated table

This approach eliminated manual repetition, ensured uniform transformations across months, and made the solution easy to maintain and extend for future data. See screenshot below for functions used for transformations
<img width="1918" height="1006" alt="image" src="https://github.com/user-attachments/assets/dd8162d7-28ab-4a55-90f8-eb18aaa14d98" />


---

## Key Analysis

1. **Work Preferences**

   * Analyzed employee choices for Work from Home (WFH), Office, or Hybrid.
   * Explored reasons behind WFH adoption to guide policy decisions.

2. **Sick Leave Analysis**

   * Calculated sick leave percentage for employees to inform better planning.
   * Measures created in DAX allowed tracking monthly sick leave trends.

3. **Matrix & KPI Creation**

   * Built matrices in Power BI to summarize attendance by employee and day.
   * Created KPIs to track overall attendance, sick leave %, and work preference counts.

---

## Dashboard Features

* Monthly attendance summary
* Work preference distribution (Office, WFH, Hybrid)
* Sick leave percentage by month
* Employee-wise attendance matrix
* Interactive slicers for month, department, and employee

---

## Dashboard Preview
<img width="1301" height="690" alt="image" src="https://github.com/user-attachments/assets/7958f7a5-7492-4643-953a-c90500dce9c9" />


---

## Key Learnings

* Consolidating multiple Excel sheets for unified analysis using Power Query
* Calculating key metrics and KPIs with DAX
* Building interactive dashboards for workforce planning
* Deriving actionable insights from attendance and work preference data


