# School Performance analysis

## Description
Project presents a comprehensive examination of academic performance across 15 schools in a district, involving 39,170 students. 

Through a detailed analysis, it showcases key metrics such as average scores, passing rates, and overall performance, enabling insights into the factors influencing educational outcomes. The project covers diverse aspects, including school types, budget allocations, grade-wise performance, and the impact of school size. 

Utilizing Python Pandas, the analysis provides a valuable resource for stakeholders in the education sector to make informed decisions for enhancing educational strategies and resource allocation.

## Technologies Used
Python (Pandas)

## File Structure
### PyCitySchools
- 'analysis.ipynb': Jupyter Notebook with python script that uncovers trends in data. 
### Resources
    - 'schools_complete.csv': CSV file with schools related information, including School name, type, size, budget.  
    - 'students_complete.csv': CSV file with every student's information, including school, grade as well as math and reading scores.

## Data Analysis Overview

Data from the input files is aggregated and manipulated with the use of Pandas DataFrames to showcase obvious trends in school performance.

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


## Results

- Total budget spend for all the schools is at $24,649,428.
- Math score across the district on average is 79, and Reading Average score is slightly higher - 82.
- Passing rates across all the students:
	- About 75% of all students get 70 or higher in Math exam.
	- 87% pass Reading exam with the mark 70 or higher.
	- 65% of all students pass Math and Reading achieveing 70 in both Math and Reading.
### Summary by School:
- Top 3 **Highest-Performing Schools** - based on the Overall Passing persentage - are of **Charter** type with Overall Passing percentage higher than 90.59%:
	- Cabrera High School (No of students - 1858, budget per student - $582);	
	- Thomas High School (No of students - 1635, budget per student - $638);
	- Griffin High School (No of students - 1468, budget per student - $625);

- Top 3 **Bottom-Performing Schools** - based on the Overall Passing persentage - are of **District** type with Overall Passing percentage about 52-53%:
	- Rodriguez High School (No of students - 3999, budget per student - $637);
	- Figueroa High School (No of students - 2949, budget per student - $639);
	- Huang High School (No of students - 2917, budget per student - $655);

- Math and Reading Scores by Grade are on par within the same school across 4 different grades - from 9th to 12th. 
### Summary by School Size and Budget Size:
- Higher-Performing schools are typically smaller sized than the Bottom-Performing schools. Schools with number of students under 2000 people show better students' performance than schools with over 2000 students;

- Budget per Student is not necesserily higher in the schools that perform better than in schools with the lower academic results. 
In fact, average passing rate for both Math and Reading is the **highest** for the schools with the spending rate **under $585** per student (Overall passing % - 90,37%), and **lower** in the schools with the spending rate **between $645 and $680** per student (Overall passing % - 53,53%).
