# Problem Statement

The U.S. Department of Education wants to promote preparation for global competitiveness and intends to announce a new grant program. <br>The hypothesis is that additional funding to the states will increase the states' SAT participation and SAT scores. This project examines the relationship between per pupil funding, the SAT participation and SAT scores for the years 2018 and 2019, with a recommendation on how to best distribute the additional funding.

# Executive Summary

Examine and analyze relationship between the scores, fundings and participation rate using datasets from 2018 and 2019

### Content:

- 2018 SAT Data Import, Cleaning and Sorting
- 2019 SAT Data Import, Cleaning and Sorting
- 2018 & 2019 Funding Data Import and Cleaning
- Exploratory Data Analysis
- Data Visualization
- Descriptive and Inferential statistics
- Conclusions and Recommendations

<ins>Data
* [`act_2018.csv`](./data/act_2018.csv): 2018 ACT Scores by State
* [`act_2019.csv`](./data/act_2019.csv): 2019 ACT Scores by State
* [`total_spending_per_student_by_state_2018_2019.csv`](./source/total_spending_per_student_by_state_2018_2019.csv): 2018 & 2019 Funding per Student by State

# Data Dictionary

|Feature|Type|Dataset|<p align='left'>Description|
|---|---|---|---|
|state|object|all_dfs|<p align='left'>State in the US and District of Columbia| 
|participation_2018|float64|all_dfs|<p align='left'>The SAT participation rate in 2018 (units percent to two decimals places 0.06 means 6%)|
|ebrw_2018|int64|all_dfs|<p align='left'>The SAT average score of the Evidence-Based Reading and Writing section in 2018 (out of 800)|
|math_2018|int64|all_dfs|<p align='left'>The SAT average score of the Mathematics section in 2018 (out of 800)|
|total_2018|int64|all_dfs|<p align='left'>The average of the total SAT score in 2018 (out of 1600)|
|participation_2019|float64|all_dfs|<p align='left'>The SAT participation rate in 2019 (units percent to two decimals places 0.06 means 6%)|
|ebrw_2019|int64|all_dfs|<p align='left'>The SAT average score of the Evidence-Based Reading and Writing section in 2019 (out of 800)|
|math_2019|int64|all_dfs|<p align='left'>The SAT average score of the Mathematics section in 2019 (out of 800)|
|total_2019|int64|all_dfs|<p align='left'>The average of the total SAT score in 2019 (out of 1600)|
|code|object|all_dfs|<p align='left'>The list of US state code|
|funding_2018|float64|all_dfs|<p align='left'>The average funding per student by state|
|funding_2019|float64|all_dfs|<p align='left'>The average funding per student by state|
|score_var|int64|all_dfs|<p align='left'>The SAT average score variance from year 2018 to 2019 per student by state|
|fund_var|float64|all_dfs|<p align='left'>The SAT average fund variance from year 2018 to 2019 per student by state|

# Analysis and Conclusion

1. Positive correlation between funding and SAT participation rate.
2. Weak correlation observed between funding and SAT total average scores.
3. Total funding increased from 2018 to 2019, however, slightly lower grades obtained.

# Recommendations

1. More funds can be allocated to states which have the most improvement in the total average scores as a form of incentive as these states show potential or seem to display effective educational systems.
2. As more funds are allocated in these selected states, participation rates will increase. This will encourage less wealthy students to participate as well.
3. Propose to provide additional funding to the States with low participation rate, with improving SAT scores. Such as Utah, Hawaii, South Dakota, Nevada, and Nebraska. 
4. This can help to improve participation rates and total average SAT scores.

### Given Sources:

* [SAT](https://collegereadiness.collegeboard.org/sat)
* [ACT](https://www.act.org/content/act/en.html)

### Additional Sources

* [2018 Funding](https://www.census.gov/data/tables/2018/econ/school-finances/secondary-education-finance.html)
* [2019 Funding](https://www.census.gov/data/tables/2019/econ/school-finances/secondary-education-finance.html)
* [Rich students get better SAT scores](https://www.cnbc.com/2019/10/03/rich-students-get-better-sat-scores-heres-why.html)
