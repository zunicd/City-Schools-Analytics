# City Schools Analytics

## Objective

The objective of this project is to perform data analytics for a fictional city's school district.

Based on every student's math and reading scores, as well as various information on the schools they attend, we will aggregate the data and showcase obvious trends in school performance.

The final report includes each of the following:

#### District Summary

* A high level snapshot (in table form) of the district's key metrics, including:
  * Total Schools
  * Total Students
  * Total Budget
  * Average Math Score
  * Average Reading Score
  * % Passing Math
  * % Passing Reading
  * Overall Passing Rate (Average of the above two)

#### School Summary

-  An overview table that summarizes key metrics about each school, including:
  - School Name
  - School Type
  - Total Students
  - Total School Budget
  - Per Student Budget
  - Average Math Score
  - Average Reading Score
  - % Passing Math
  - % Passing Reading
  - Overall Passing Rate (Average of the above two)

#### Top Performing Schools (By Passing Rate)

* A table that highlights the top 5 performing schools based on Overall Passing Rate and includes:
  * School Name
  * School Type
  * Total Students
  * Total School Budget
  * Per Student Budget
  * Average Math Score
  * Average Reading Score
  * % Passing Math
  * % Passing Reading
  * Overall Passing Rate (Average of the above two)

#### Bottom Performing Schools (By Passing Rate)

* A table that highlights the bottom 5 performing schools based on Overall Passing Rate and includes all of the same metrics as above.

#### Math Scores by Grade

* A table that lists the average Math Score for students of each grade level (9th, 10th, 11th, 12th) at each school.

#### Reading Scores by Grade

* A table that lists the average Reading Score for students of each grade level (9th, 10th, 11th, 12th) at each school.

#### Scores by School Spending

* A table that breaks down school performances based on average Spending Ranges (Per Student). 4 bins to group school spending are used and the table includes each of the following:
  * Average Math Score
  * Average Reading Score
  * % Passing Math
  * % Passing Reading
  * Overall Passing Rate (Average of the above two)

#### Scores by School Size

* The above breakdown is repeated, but this time schools are grouped based on a reasonable approximation of school size (Small, Medium, Large).

#### Scores by School Type

* The above breakdown is repeated, but this time schools are grouped based on school type (Charter vs. District).



## Tools / Techniques Used:

- Python
- Pandas
- Jupyter Notebook

 

## About Data

1. ***Resources/schools_complete.csv*** -  schools information

- **Number of records:**	15
- **Columns**:
  - School ID
  - school_name
  - type
  - size
  - budget



2. ***Resources/students_complete.csv*** -  students information

- **Number of records:**	39,170
- **Columns**:
  - Student ID
  - student_name
  - gender
  - grade
  - school_name
  - reading_score
  - math_score



.