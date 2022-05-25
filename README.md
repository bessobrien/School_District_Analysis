# School District Analysis

## Overview

The purpose of this analysis was to go through school district information for the year, and provide several snapshots and overviews showing the following:

1. High-level snapshot of the district's key metrics.
2. Overview of key metrics for each school.
3. Tables showing:
- Top 5 and bottom 5 performing schools, based on overall passing rate
- The average math score received by students in each grade level at each school
- The average reading score received by students in each grade level at each school
- School performance based on the budget per student
- School performance based on the school size 
- School performance based on the type of school

We utilized Jupyter Notebook to write the script.

Once we finished the initial analysis, we were informed that there were signs of academic dishonesty for a specific grade and school (Thomas High School, 9th grade). We then had to refactor the script to reflect updated results that replaced all grades for Thomas High School - 9th grade to NaN.

## Resources

- Python 3.9.12
- VS Code 1.67.2
- Jupyter Notebook
- [students_complete.csv](https://github.com/bessobrien/School_District_Analysis/blob/main/Resources/students_complete.csv)
- [schools_complete.csv](https://github.com/bessobrien/School_District_Analysis/blob/main/Resources/schools_complete.csv)

**Original script:** [PyCitySchools.ipynb](https://github.com/bessobrien/School_District_Analysis/blob/main/PyCitySchools.ipynb)

## Results
After we replaced the the grades of the 9th Grade at Thomas High School with "NaN", our overall results changed across the board.

### District Summary
Our original district summary: ![District Summary 1](https://github.com/bessobrien/School_District_Analysis/blob/main/Resources/District%20Summary%201.png)

Our new district summary: ![District Summary 2](https://github.com/bessobrien/School_District_Analysis/blob/main/Resources/District%20Summary%202.png)

There was no change in our overall district summary.

### School Summary

Our original school summary: ![School Summary 1](https://github.com/bessobrien/School_District_Analysis/blob/main/Resources/School%20Summary%201.png)

Our new school summary: ![School Summary 2](https://github.com/bessobrien/School_District_Analysis/blob/main/Resources/School%20Summary%202.png)

We can see that the only school changed after the analysis is Thomas High School.

### Performance Relative to Other Schools

Original performance by Thomas High School: ![Thomas Original](https://github.com/bessobrien/School_District_Analysis/blob/main/Resources/Thomas%20Old%20Grades%201.png)

New performance by Thomas High School: ![Thomas Updated](https://github.com/bessobrien/School_District_Analysis/blob/main/Resources/Thomas%20New%20Grades%202.png)

We can see that that after the change in analysis, average scores went up, as well as percent passing math, reading, and overall.

### Score Performance

Here are some snapshots of the results *after* the analysis adjustment:

1. Math and reading scores by grade: ![Math and Reading Scores](https://github.com/bessobrien/School_District_Analysis/blob/main/Resources/Math%20Scores%20by%20Grade%202.png) 
2. Scores by school spending: ![Scores by School Spending](https://github.com/bessobrien/School_District_Analysis/blob/main/Resources/Scores%20by%20School%20Spending%202.png)
3. Score by school size: ![Score by school size](https://github.com/bessobrien/School_District_Analysis/blob/main/Resources/Scores%20by%20School%20Size%202.png)
4. Score by school type: ![Score by school type](https://github.com/bessobrien/School_District_Analysis/blob/main/Resources/Scores%20by%20School%20Type%202.png)
5. Top 5 Schools: ![Top 5 Schools](https://github.com/bessobrien/School_District_Analysis/blob/main/Resources/Top%205%20Schools%202.png)
6. Bottom 5 Schools: ![Bottom 5 Schools](https://github.com/bessobrien/School_District_Analysis/blob/main/Resources/Bottom%205%20Schools%202.png)


## Summary

Overall, it was important to know, recognize, and clean our data in response to the discovery that academic dishonesty was found in one of the schools. By replacing all grades for 9th grade at Thomas High School to NaN, we found the top four changes in our data results:

1. For Thomas High School, average reading score went up, while average math score went down.
2. Thomas High School Overall % Passing rate went down.
3.
4.

Good data drives good decisions,which drives good success!
