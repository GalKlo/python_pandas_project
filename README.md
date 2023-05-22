# School Performance analysis

Script helps to analyze a district-wide standardized test results. 

Input: 
1. File with schools related information, including School name, type, size, budget. 
2. File with every student's information, including school, grade as well as math and reading scores.

With the use of Pandas DataFrames data from the input files was aggregated and manipulated to showcase obvious trends in school performance.

The results of the analysis returns:
- District summary:
    - Total number of unique schools
    - Total students
    - Total budget
    - Average math score
    - Average reading score
    - % passing math (the percentage of students who passed math)
    - % passing reading (the percentage of students who passed reading)
    - % overall passing (the percentage of students who passed math AND reading)

- School Summary:
    - School name
    - School type
    - Total students per school
    - Total school budget
    - Per student budget
    - Average math score per school
    - Average reading score per school
    - % passing math per school (the percentage of students who passed math)
    - % passing reading per school (the percentage of students who passed reading)
    - % overall passing per school (the percentage of students who passed math AND reading)

- 5 Highest-Performing Schools (by % Overall Passing)
- 5 Lowest-Performing Schools (by % Overall Passing)

- Math Scores by Grade
- Reading Scores by Grade

- Scores by School Spending
- Scores by School Size
- Scores by School Type
