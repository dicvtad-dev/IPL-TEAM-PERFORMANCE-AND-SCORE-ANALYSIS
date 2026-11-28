# IPL Cricket Data Analysis | Power BI

## 1. Project Overview

This project focuses on analyzing Indian Premier League (IPL) cricket data using Microsoft Power BI. The objective is to develop an interactive report that provides insights into team performance, match outcomes, and individual batting and bowling statistics.

The report uses multiple related datasets to explore different aspects of IPL matches and player performances.

## 2. Project Objectives

- Analyze the performance of IPL teams.
- Examine individual match outcomes and results.
- Explore batting and bowling statistics.
- Understand team performance across matches.
- Present cricket data through interactive visualizations.
- Identify and address inconsistencies in the source datasets.

## 3. Dataset Information

The project uses the following datasets:

| Dataset | Description |
|---|---|
| Matches | Match details, teams, winners, results and match information. |
| Deliveries | Ball-by-ball information, including batting and bowling details. |
| Team Description | Information about IPL teams. |
| Players Information | Details about individual players. |
| Match Dates | Date-related information for IPL matches. |

## 4. Dashboard Overview

The Power BI report includes the following analysis sections:

### A. Team Analysis

Focuses on evaluating and comparing IPL team performance.

Analysis includes:
- Team-wise performance.
- Match results and outcomes.
- Comparison of team statistics.
- Performance-related insights.

### B. Match Analysis

Focuses on examining individual IPL matches and their outcomes.

Analysis includes:
- Match-related information.
- Match winners and results.
- Result margins.
- Match-level statistics.

### C. Batting & Bowling Analysis

Explores individual player performance using ball-by-ball delivery data.

Analysis includes:
- Individual batting statistics.
- Individual bowling statistics.
- Player performance comparisons.
- Relevant player-level metrics.

## 5. Data Cleaning & Preparation

Data preparation was an important part of this project.

The following activities were performed:

- Formatting and organizing columns and rows.
- Identifying inconsistencies in the source datasets.
- Correcting selected data entries using Excel formulas.
- Preparing additional fields for individual batter and bowler statistics.
- Reviewing data types and preparing tables for Power BI.
- Establishing relationships between tables for analysis.

### Data Issues Identified

During the project, several inconsistencies were identified:

**1. Batting Team & Bowling Team**

Some entries in the `Batting Team` and `Bowling Team` columns of the Deliveries table did not correspond correctly with the innings, toss winner, and toss decision information.

Excel formulas were created to correct the affected entries.

**2. Batter & Bowler Entries**

Some batter and bowler entries in the Deliveries table contained inconsistencies that could not be independently verified or fully corrected using the available source information.

These limitations were considered during the analysis.

**3. Match Results**

Some entries in the Matches table, particularly the Winner, Result, and Result Margin fields, required checking.

Excel formulas and score-based logic were used to verify and correct the identified errors where possible.

## 6. Tools & Technologies

- Microsoft Power BI Desktop
- Microsoft Excel
- Power Query
- DAX (Data Analysis Expressions)
- Data Cleaning & Transformation
- Data Modeling
- Data Visualization
- Calculated Measures and Columns

## 7. Project Workflow

1. Understanding the available IPL datasets.
2. Inspecting the structure and contents of each dataset.
3. Identifying data inconsistencies and formatting issues.
4. Cleaning and preparing data using Microsoft Excel.
5. Importing datasets into Power BI.
6. Establishing relationships between tables.
7. Creating calculated fields and DAX measures.
8. Developing Team Analysis and Match Analysis pages.
9. Analyzing batting, bowling, team, and match-related information.
10. Building interactive visualizations to present the findings.

## 8. Learning Outcomes

Through this project, I gained practical experience in:

- Working with multiple related datasets.
- Cleaning and validating structured data.
- Identifying data quality issues.
- Using Excel formulas to correct inconsistencies.
- Creating relationships between Power BI tables.
- Developing DAX measures for cricket statistics.
- Analyzing team and individual player performance.
- Building interactive Power BI reports.

## 9. Project Files

This repository contains:

- Power BI project file (`.pbix`).
- Dashboard screenshots.
- Project documentation.
- README file.

## 10. Acknowledgement

This project was completed as part of my hands-on Power BI learning and On-the-Job Training (OJT).

Special thanks to **Bright Computer Education** and **Kamlesh Vaghela** for their guidance and support.

## 11. Author

**Divyesh Tadvi**
