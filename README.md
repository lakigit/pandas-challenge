# pandas-challenge
Module Challenge week4
# Background of the Repository
In this assignment, help the school board and mayor make strategic decisions regarding future school budgets and priorities.
To analyse this result, I used the Python pandas notebook. 
This project used two CSV files, school_complete and student_complete. 
For the analysis, merged these two data sets on the school name. 
The first task is, to analyse the local government area summary. It includes the following. 
[Total number of unique schools
Total Students
Total budget
Average maths score
Average reading score
% passing maths (the percentage of students who passed maths)
% passing reading (the percentage of students who passed reading)
% overall passing (the percentage of students who passed maths AND reading)]
**Note**: **passing grade is 50 or higher**
And the second task is, to analyse the school summary. Here, Perform the necessary calculations and then create a DataFrame that summarises key metrics about each school. Include the following:
[School name
School type
Total Students
Total school budget
Per student budget
Average maths score
Average reading score
% passing maths (the percentage of students who passed maths)
% passing reading (the percentage of students who passed reading)
% overall passing (the percentage of students who passed maths AND reading)]
And also find Highest-Performing Schools (by % Overall Passing), Lowest-Performing Schools (by % Overall Passing), Maths Scores by Year, Reading Scores by Year, Scores by School Spending, Scores by School Size, Scores by School Type. 
				
As I was working on finding scores by school spending, I realized that I needed to convert the data type of "per student budget" from object type to float. This was necessary because I was using the binning method. Unfortunately, I encountered an error because the initial data type of "per student budget" was an object. To avoid this error, I used the method of converting the data type.

**Note: I have added the report for this project to the repository. It is written on a Word file and should be easily accessible for anyone who needs to review it.**
