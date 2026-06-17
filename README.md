# Data Jobs Dashboard with Power BI

![Data Jobs Dashboard Overview](images/Dashboard_Page1_Overview.png)

<!-- If you've published this to Power BI Service and have a public link, add it here:
> 📊 [View interactive dashboard here on the Power BI Service](YOUR_LINK_HERE) -->

## Introduction

This dashboard was built to solve a common problem for **job seekers, job transitioners, and career switchers**: information about the data job market is scattered across job boards and hard to compare. Using a real-world dataset of 2024 data science job postings (titles, salaries, locations, and platforms), this project brings everything into one interface to explore market trends and compensation.

## Dashboard File

You can find the file for the dashboard here: [`Data_Jobs_Dashboard.pbix`](Data_Jobs_Dashboard.pbix).
<!-- Confirm this matches your actual .pbix filename in the repo -->

## Skills Showcased

- **⚙️ Data Transformation (ETL) with Power Query:** Cleaned and shaped the raw job postings data, handled blanks, fixed data types, and created new columns for analysis.
- **🧮 DAX Measures:** Built measures for key KPIs including `Job Count`, `Median Yearly Salary`, and `Median Hourly Salary`.
- **📊 Core Charts:** Used line charts to track job trends over time, and bar charts to rank job titles by salary.
- **🔵 Scatter Plot:** Compared hourly vs. yearly salary across job titles to spot pay patterns.
- **📈 Sparklines:** Embedded job trend sparklines directly inside the stats table for a compact view of trends per role.
- **🗺️ Map Chart:** Visualized the global distribution of job postings on the drill-through page.
- **🎯 Gauge & Donut Charts:** Used gauge visuals for salary ranges and donut charts to show percentages for work-from-home, degree requirements, and health insurance availability.
- **⭐ Rating Visual:** Displayed an average job rating KPI using a star rating visual.
- **🔢 Cards & Tables:** Used cards for headline KPIs and a sortable table for detailed job stats.
- **🖱️ Interactive Reporting:**
  - **Slicer:** Filter the report by job title.
  - **Drill-Through:** Click a button to jump from the summary page to a detailed view for a specific job title.
  - **Navigation Button:** A back button to return from the drill-through page to the main dashboard.

---

## Dashboard Overview

*This report is split into two pages: a high-level summary and a detailed, job-specific drill-through view.*

### Page 1: High-Level Market View

![Data Jobs Dashboard Page 1](images/Dashboard_Page1_Overview.png)

This page is the mission control for the data job market. It shows headline KPIs (total job count, average job rating, median yearly and hourly salary), a trend line of job postings across 2024, a scatter plot comparing hourly vs. yearly pay by role, a bar chart ranking job titles by salary, and a detailed stats table with built-in trend sparklines.

### Page 2: Job Title Drill Through

![Data Jobs Dashboard Page 2](images/Dashboard_Page2_DrillThrough.png)

This is the deep-dive page. Clicking the **Drill Through to Job Title** button on Page 1 brings you here, filtered to a single job title (e.g. Senior Data Analyst). It shows yearly and hourly salary ranges via gauge charts, percentages for work-from-home availability, degree requirements, and health insurance via donut charts, a map of where these jobs are posted globally, and breakdowns of job platforms and schedule type.

---

## Acknowledgments

This project was built while following **Luke Barousse's free Data Analyst Bootcamp**. The dataset, project brief, and overall dashboard concept are based on his course material — I rebuilt and customized the dashboard myself as part of learning Power BI, including my own choices on chart types, layout, and styling. Credit to Luke for the structure and dataset that made this project possible.

## Conclusion

This dashboard shows how raw job posting data can be turned into a practical tool for career research — slicing, filtering, and drilling through to compare roles and make informed decisions about where to apply next.
