<img width="992" height="565" alt="Screenshot 2026-04-29 103840" src="https://github.com/user-attachments/assets/dabffc03-10a4-4a73-bba5-8bab2865c344" />


# Student Performance Dashboard (Power BI)

## Overview

This project is an interactive Student Performance Dashboard built using Power BI. It provides insights into student attendance, academic performance, and behavioral patterns.

The dashboard helps in analyzing how different factors like attendance, behavior, and exam types impact student scores.

---

## Objectives

* Monitor student attendance and absenteeism
* Analyze average scores across subjects
* Track student behavior patterns
* Compare performance based on exam types
* Identify trends across gender and class

---

## Tools and Technologies

* Power BI Desktop
* Power Query for data cleaning
* DAX for calculations and KPIs

---

## Dataset Information

The project uses the following datasets:

### Students

* StudentID
* Name
* Gender
* Class
* Section

### Scores

* StudentID
* Subject
* Score
* ExamType
* Performance Category

### Attendance

* StudentID
* Date
* Status (Present/Absent)

### Behavior

* StudentID
* BehaviorType
* Date
* Notes

---

## Data Model

* Central table: Students
* Related tables:

  * Scores
  * Attendance
  * Behavior

Relationships:

* One-to-many from Students to other tables using StudentID
* Proper star schema design for optimized performance

---

## Key KPIs

* Total Students: 1K
* Total Present Count: 90K
* Total Absent Count: 10K
* Attendance Percentage: 90.05%
* Average Score: 49.87

---

## Dashboard Features

### 1. KPI Cards

* Student count
* Present and absent count
* Attendance percentage
* Average score

### 2. Average Score by Subject

* Line chart showing performance across:

  * Math
  * Science
  * English
  * History
  * Geography

### 3. Behavior Analysis

* Bar chart: Count of Behavior Type
* Donut chart: Behavior distribution

  * Disruptive
  * Late
  * Helpful
  * Participative
  * Absent without reason

### 4. Attendance Analysis

* Bar chart showing absent count by gender
* Helps compare male vs female attendance

### 5. Filters (Slicers)

* Class
* Exam Type:

  * Final Exam
  * Mid Term
  * Unit Test
* Subject

### 6. Student Performance Table

* Detailed table with:

  * Subject-wise marks
  * Total score
* Individual student performance tracking

---

## Key Insights

* Attendance rate is above 90%, indicating good student presence
* Average score is around 50, showing scope for improvement
* Disruptive and late behaviors are slightly higher compared to others
* Some subjects show lower average scores, indicating weak areas
* Gender-based absence difference is visible

---

## How to Use

1. Open the `.pbix` file in Power BI Desktop
2. Use slicers to filter by class, subject, or exam type
3. Explore different visuals for insights
4. Analyze individual student performance using the table

---

## Conclusion

This dashboard provides a complete analysis of student performance by combining academic, attendance, and behavioral data. It helps educators make informed decisions to improve student outcomes.

---

## Author

Yagna Patel
