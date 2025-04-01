# Pandas Challenge: PyCitySchools Analysis

## Overview

This project analyzes standardized testing data for a hypothetical school district to help inform strategic decision-making around budgets and academic priorities. Using Python and the Pandas library, the analysis explores student and school-level performance metrics, including average scores, pass rates, and the impact of variables like school type, size, and budget per student.

## Dataset

The data comes from two CSV files:

- `schools_complete.csv`: Information about each school, including name, type (District or Charter), budget, and size.
- `students_complete.csv`: Contains information for each student, including school attended, grade level, gender, and test scores in math and reading.

## Objectives

- Generate a **District Summary** of key metrics like average test scores and pass rates.
- Create a **School Summary** that breaks down performance by individual schools.
- Rank schools based on overall student performance.
- Analyze **grade-level** performance trends in math and reading.
- Explore the relationship between **spending per student** and test performance.
- Investigate how **school size** and **school type** correlate with academic outcomes.

## Key Findings

- **Charter schools** consistently outperformed district schools in both math and reading, with higher average scores and pass rates.
- Smaller schools (fewer than 1,000 students) performed better on average than larger schools.
- Spending more per student did **not** correlate with higher performance, suggesting more efficient use of funds might be more important than total expenditure.
- **9th graders** generally had the lowest average scores across subjects, while **10th and 11th graders** tended to perform better.
- The top five schools were all charter schools, reinforcing the trend of better performance among that school type.

## Technologies Used

- **Python**
- **Pandas**
- **Jupyter Notebook**


## How to Use

1. Clone the repository:

```
git clone https://github.com/fbarffmann/pandas-challenge.git
```

2. Open the Jupyter Notebook:

```
cd pandas-challenge/PyCitySchools
jupyter notebook PyCitySchools.ipynb
```

3. Run all cells to execute the analysis.

---

👨‍💻 Developed by Finn Brennan Arffmann  
📊 Learn more at [github.com/fbarffmann](https://github.com/fbarffmann)