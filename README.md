# 📊 Data Jobs Market Analysis in Excel

## Overview

This project analyzes over **32,000 job postings** from the data industry using Microsoft Excel. The workbook leverages **Power Query**, **Power Pivot**, and **DAX** to transform raw job posting data into an interactive analytical report.

The analysis explores salary trends, hiring demand, required skills, and compensation differences across job titles and countries through PivotTables, PivotCharts, and interactive slicers.

---

## Project Preview

### Skill Job Analysis

![Skill Job Analysis](images/skill-job-analysis.png)

### Salary vs Skills

![Salary vs Skills](images/salary-vs-skills.png)

### Salary Analysis

![Salary Analysis](images/salary-analysis.png)

### Skill Salary Analysis

![Skill Salary Analysis](images/skill-salary-analysis.png)

---

## Business Questions

This workbook answers questions such as:

- Which skills are most frequently requested for data-related jobs?
- Does requiring more technical skills correlate with higher salaries?
- How do median salaries vary across different job titles?
- Are salaries higher in the United States compared to other countries?
- Which technical skills are associated with the highest median salaries?

---

## Workbook Pages

### 📈 Skill Job Analysis

Analyzes the most requested technical skills across data-related job titles.

**Features**

- Top skills by demand
- Skill likelihood (% of job postings)
- Interactive filtering by Job Title and Country

---

### 💰 Salary vs Skills

Examines the relationship between median salary and the average number of skills requested for each job title.

**Features**

- Scatter plot with trendline
- Median salary comparison
- Average skills required per role
- Country slicer

---

### 🌎 Salary Analysis

Compares compensation across different job titles.

**Features**

- Overall median salary
- US median salary
- Non-US median salary
- Country filtering

---

### 📊 Skill Salary Analysis

Compares the demand for technical skills against their associated median salaries.

**Features**

- Median salary by skill
- Skill likelihood (%)
- Interactive filters by Job Title and Country

---

## Tools & Technologies

- Microsoft Excel
- Power Query
- Power Pivot
- DAX
- Excel Data Model
- Pivot Tables
- Pivot Charts
- Slicers

---

## Data Preparation

Power Query was used to clean and transform the raw dataset before loading it into the Excel Data Model.

Data preparation included:

- Cleaning raw data
- Removing unnecessary columns
- Correcting data types
- Standardizing values
- Preparing tables for analysis

---

## Data Modeling

Power Pivot was used to build a relational data model connecting the job postings and skills tables, enabling efficient analysis and DAX calculations.

---

## DAX Measures

The workbook includes several custom DAX measures to support the analysis.

| Measure | Description |
|----------|-------------|
| **Job Count** | Counts the total number of job postings. |
| **Median Salary** | Calculates the overall median salary. |
| **Median Salary US** | Calculates the median salary for US job postings. |
| **Median Salary Non-US** | Calculates the median salary for non-US job postings. |
| **Skill Count** | Counts how many times each skill appears in job postings. |
| **Skills Per Job** | Calculates the average number of skills required for each job title. |
| **Median Salary - Skills** | Calculates the median salary associated with each technical skill. |
| **Skill Likelihood** | Calculates the percentage of job postings requesting each skill. |

---

## Key Insights

- SQL and Python are the most frequently requested technical skills.
- Higher-paying roles generally require a greater number of technical skills.
- US-based positions typically offer higher median salaries than positions in other countries.
- Skills such as Spark, AWS, and Java are associated with some of the highest median salaries.

---

## Skills Demonstrated

- Data Cleaning
- Data Transformation
- Power Query
- Power Pivot
- DAX
- Excel Data Model
- Data Modeling
- Pivot Tables
- Pivot Charts
- Interactive Reporting
- Data Visualization
- Business Intelligence
- Data Analysis

---

## Author

**Daniel Betancourt**

Electronic Engineer | Data Analyst

- **GitHub:** https://github.com/danielbm98
- **LinkedIn:** https://www.linkedin.com/in/danielbetancourtmontoya/
