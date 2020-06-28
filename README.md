# school_district_analysis

### Project Overview
A local school board tasked us with creating a summary of their school district using DataFrames. Thomas High School had the highest percentage of students passing reading. After removing the ninth graders scores that percentage dropped drastically compared to the other charter schools. However, after the removal of their grades Thomas High Schools percentages of students passing reading and math dropped to levels comparable to the district schools analyzed. 

### Resources 
data source: schools_complete.csv, students_complete.csv

software: jupyter notebook, python, visual studio code 

### District Summary Changes
	 overall passing % decreased from 65% to 64%
	 passing reading % decreased from 86% to 85%
	 passing math % decreased from 75% to 74%
	 average reading score remained the same
	 average math score decreased from 79% to 78.9%
### School Summary Changes
	 overall passing % decreased from 90% to 65%
	 passing reading % decreased from 97.6% to 69.6%
	 passing math % decreased from 93.2% to 66.9%
	 average reading % remained basically the same. It increased from 83.84% to 83.89%
	 average math % remained basically the same. It decreased from 83.41% to 83.35%

### Math and Reading Scores by Grade

    these scores remained unaffected because the ninth grade values were replaced with nan. The averages for the other grades remained unchanged. 

### Scores by School Spending

    Thomas High School is in the $630-644 bin. So the scores in this bin range have been affected. 
    Overall passing percentage dropped from 63% to 56%. 
    Percentage of students passing reading dropped from 84% to 77%. 
    Percentage of students passing math dropped from 73% to 67%
    average reading and math scores remained the same

### Scores by School Size

    Thomas High School is in the medium(1000-2000) bin for school size so this bin was affected. 
    Overall passing decreased by 6%
    passing reading decreased by 6%
    passing math decreased by 6%
    average reading and math scores remained the same 

### Scores by School Type

    Thomas High School is a charter school, so the charter school statistics moved with the removal of the ninth grader math and reading scores. 
    overall passing % decreased from 65% to 64%
    passing reading % decreased from 86% to 85%
    passing math % decreased from 75% to 74%
    average reading score remained the same
    average math score decreased 79% to 78.9%
