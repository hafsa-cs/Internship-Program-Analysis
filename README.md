# Internship Program Analysis Dashboard

**Created & Analyzed by Hafsa Asif**  
*Data Analyst*

---

# Project Overview

The **Internship Program Analysis Dashboard** is an interactive Power BI project developed to analyze internship performance and identify the key factors that contribute to successful internship completion.

The dashboard transforms raw internship data into meaningful insights by analyzing enrollment trends, completion rates, dropout rates, mentor interactions, attendance, internship duration, and departmental performance. The project enables stakeholders to monitor internship outcomes and make informed decisions to improve future internship programs.

---

# Project Objective

The primary objective of this project is to analyze internship completion rates and identify the factors influencing intern success.

This dashboard was developed to:

- Analyze internship enrollment, completion, and dropout statistics.
- Identify trends across departments, internship duration, universities, and mentor interactions.
- Measure internship performance using interactive Power BI visualizations.
- Help stakeholders understand the factors associated with successful internship completion.

---

# Dataset Overview

A realistic internship dataset containing **300 records** was created for this project.

The dataset includes the following fields:

| Column | Data Type | Description |
|--------|-----------|-------------|
| Intern_ID | Integer | Unique identifier for each intern |
| Intern_Name | Text | Name of the intern |
| Gender | Text | Gender of the intern |
| Age | Integer | Age of the intern |
| University | Text | University of the intern |
| CGPA | Decimal | Academic CGPA |
| Department | Text | Internship department |
| Enrollment_Date | Date | Internship enrollment date |
| Internship_Duration_Months | Integer | Internship duration in months |
| Mentor_Name | Text | Assigned mentor |
| Mentor_Interactions | Integer | Number of mentor meetings/interactions |
| Attendance_% | Percentage | Internship attendance |
| Project_Score | Percentage | Final project evaluation score |
| Completion_Status | Text | Completed, Dropped, or Ongoing |
| Dropout_Reason | Text | Reason for dropping out (if applicable) |

---

# Tools & Technologies

- Microsoft Power BI
- Microsoft Excel
- Data Modeling
- DAX Measures
- Data Visualization

---

# Dashboard Overview

The dashboard provides a comprehensive overview of internship performance through interactive visualizations and KPI cards.

## Key Performance Indicators (KPIs)

- Total Enrollments
- Completed Interns
- Dropped Interns
- Ongoing Interns
- Completion Rate
- Dropout Rate

---

# Dashboard Visualizations

## 1. Completed Interns by Department

Displays the number of interns who successfully completed the internship across different departments, allowing comparison of departmental performance.

---

## 2. Internship Status Distribution

A pie chart showing the distribution of interns based on their current status:

- Completed
- Dropped
- Ongoing

This visualization provides a quick overview of overall internship outcomes.

---

## 3. Completion by Internship Duration

Shows how internship duration impacts successful completion by comparing completed interns across different internship lengths.

---

## 4. Completed Interns by University

Compares internship completion among different universities to identify institutions contributing the highest number of successful interns.

---

## 5. Mentor Interaction vs Project Score

A scatter plot illustrating the relationship between mentor interactions and project performance.

This visualization helps identify whether increased mentor engagement contributes to better project outcomes.

---

## 6. Average Attendance by Completion Status

Compares average attendance among:

- Completed Interns
- Dropped Interns
- Ongoing Interns

This visualization highlights the relationship between attendance and internship success.

---

# Interactive Features

The dashboard includes interactive slicers for:

- Department
- University
- Gender
- Internship Duration
- Completion Status
- Mentor Name

Users can dynamically filter the dashboard to explore internship performance from different perspectives.

---

# Key Insights

Based on the dashboard analysis:

- **300** interns enrolled in the internship program.
- **213 interns (71%)** successfully completed the internship.
- **60 interns (20%)** dropped out.
- **27 interns (9%)** are currently ongoing.
- Cyber Security recorded the highest number of completed interns.
- Interns with higher mentor interactions generally achieved higher project scores.
- Completed interns maintained significantly higher attendance than dropped interns.
- Internship duration showed a noticeable impact on completion trends.

---

# Business Recommendations

Based on the analysis, the following recommendations can improve internship success:

- Increase mentor engagement through regular mentoring sessions.
- Monitor intern attendance to identify at-risk participants early.
- Review departments with lower completion rates and implement targeted support strategies.
- Provide additional guidance to interns during longer internship durations.
- Analyze dropout reasons to improve intern retention and program effectiveness.

---

# Dashboard Preview

![Internship Program Analysis Dashboard](Dashboard.png)

---

# Repository Structure

```text
Internship-Program-Analysis
│
├── Internship_Program_Analysis.pbix
├── Internship_Data.xlsx
├── Dashboard.png
├── README.md
├── LICENSE
└── .gitignore
```

---

# Project Learnings

This project strengthened my understanding of:

- Power BI Dashboard Development
- Data Cleaning & Preparation
- DAX Measures & KPI Calculations
- Interactive Dashboard Design
- Data Storytelling
- Business Insight Generation
- Visual Analytics

It also enhanced my ability to transform raw data into actionable insights that support business decision-making.

---

# Future Improvements

Potential enhancements for future versions include:

- Multi-page dashboard with detailed analysis
- Time-based enrollment trend analysis
- Predictive modeling for internship completion
- Drill-through pages for detailed intern information
- Automated data refresh using Power BI Service

---

# 👩‍💻 About Me

## Hafsa Asif

**BS Computer Science Student**  
**Data Analyst**

### Skills

- Power BI
- SQL
- Python
- Microsoft Excel
- Data Visualization
- Data Analysis

---

⭐ **If you found this project helpful, please consider giving it a star!**
