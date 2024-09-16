# pandas-challenge:
In this assignment we analyzed and manupuliate the Pandas Data Frame.  
Using Pandas and Jupyter Notebook, we created a report that includes the following data. 
School Performance Analysis Report
Overview
This report provides an analysis of school performance metrics based on data from various schools. The analysis is performed using Pandas and Jupyter Notebook. The report includes district-wide and individual school summaries, as well as insights into performance based on school spending, size, and type.

Instructions
1. District Summary
Created a DataFrame that summarizes the key metrics for the entire district:

Total number of unique schools
Total students
Total budget
Average math score
Average reading score
% passing math (percentage of students who passed math)
% passing reading (percentage of students who passed reading)
% overall passing (percentage of students who passed both math and reading)

2. School Summary
Generated a DataFrame that summarizes key metrics for each individual school:

School name
School type
Total students
Total school budget
Per student budget
Average math score
Average reading score
% passing math
% passing reading
% overall passing

3. Highest-Performing Schools
Identified the top 5 schools based on the percentage of overall passing. Saved these results in a DataFrame called top_schools.

4. Lowest-Performing Schools
Identified the bottom 5 schools based on the percentage of overall passing. Saved these results in a DataFrame called bottom_schools.

5. Math Scores by Grade
Created a DataFrame that lists the average math score for students in each grade level (9th, 10th, 11th, 12th) at each school.

6. Reading Scores by Grade
Created a DataFrame that lists the average reading score for students in each grade level (9th, 10th, 11th, 12th) at each school.

7. Scores by School Spending
Created four bins for school spending per student.
Used pd.cut to categorize schools based on these bins.
Calculated the mean scores per spending range and created a DataFrame called spending_summary with the following metrics:
Average math score
Average reading score
% passing math
% passing reading
% overall passing
8. Scores by School Size
Created three bins for school size.
Used pd.cut to categorize schools based on these bins.
Calculated the mean scores per size range and created a DataFrame called size_summary with the following metrics:
Average math score
Average reading score
% passing math
% passing reading
% overall passing
9. Scores by School Type
Created a DataFrame called type_summary that shows school performance based on the "School Type". Included metrics similar to those in size_summary.

Observations

Trend 1: Discuss a trend related to spending and performance (e.g., "Schools with higher spending per student tend to have higher average math scores.")
Trend 2: Discuss a trend related to school size or type (e.g., "Large schools generally show a lower percentage of overall passing compared to medium-sized schools.")