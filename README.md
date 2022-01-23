# School_District_Analysis

## Overview
The PyCity School District is measuring school budgets and priorities based on standardized test scores and current funding of the school. This project explores using Anaconda and Jupyter Notebook by analyzing school district data in Pandas and creating DataFrames to make strategic decisions.

## Results

* How is the district summary affected?
  * When comparing 'PyCitySchools.ipynb' to 'PyCitySchools_Challenge.ipynb', the district summary in the challenge uses a floating decimal for the outputs rather than integers. This allows for a more accurate data as we aren't rounding up to a whole number.
* How is the school summary affected?
  * By removing all Thomas High School 9th graders from the dataset, the % Overall Passing changes slightly from 90.95% to 90.63%. They still sit at the 2nd best school in the district, however removing the 9th grade class benefits the school by 0.32%.
* How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?
  * Replacing these scores helps the school slightly, meaning Thomas High School 9th graders, on average, performed lower than other schools in the district.
* How does replacing the ninth-grade scores affect the following:
  * Math and reading scores by grade
    * All Thomas High School 9th graders scores were set to 'NaN'.
  * Scores by school spending
    * Thomas High School stayed in the $630-644 spending range.
  * Scores by school size
    * Thomas High School falls within the average scores of the medium sized schools (1000-2000).
  * Scores by school type
    * Thomas High Schools falls within the average scores of the 'Charter' type schools.

## Summary
After replacing all 9th grade scores at Thomas High School with 'NaN', it can be concluded that the schools overall average test scores went up slightly. This brought them to sit at the average for their spending range, school size, and school type.
