# School_District_Analysis
Use Python and Pandas library to analyze school district data and trends in school performance

1	Create the district and school summary DataFrames.
2	Calculate the top 5 and bottom 5 performing schools.
3	Calculate the average math and reading score for students in each grade level at each school.
4	Calculate the school performance based on the spending per student.
6	Calculate the school performance based on the size of the school.
7	Calculate the school performance based on the type of school.

## Challenge Overview
Replace the reading and math scores for ninth graders at Thomas High School with NaN. 

## Challenge Summary
1	How is the district summary affected?
The Average math and reading scores are similar; the score becomes a bit lower from 79.0 to 78.8 for math and stays the same at 81.9 for reading. The percetages all go down for passing math from 75 to 74, passing reading from 86 to 85, and overall passing from 65 to 64.

2	How is the school summary affected
Thomas High school was originally placed at second based on % overall passing, but not even in top 5 anymore after changing. The average score stays the same at 83.4 from math, and increases from 83.8 to 83.9 for reading; however, percetages all go down from 93 to 67 for passing math, and 6 to 4 for passing reading, and 91 to 65 for overall passing.

3	How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance, relative to the other schools?
The ranking of Thomas High school dropped from 2nd to 8th amoung total 15 schools.

4	How does replacing the ninth-grade scores affect the Math and Reading Scores by Grade, Scores by School Spending, Scores by School Size, and Scores by School Type? 
  - by School Spending: The average math and reading stays the same for all school spendings, but % goes down particularly for the school Spending range $630 ~ 644 from 73 to 67 for passing math, and 63 to 56 for overall passing.
  - by School Size: The average math and reading stays the same for all school sizes, but % goes down particularly for the school size Medium (1000~2000) from 94 to 88 for passing math, and from 6 to 5 for passing reading, and from 91 to 85 for overall passing.
  - by School Type: The average math and reading stays the same for both school types, but % goes down particularly for the school type Charter from 94 to 90 for passing math, and from 90 to 87 for overall passing.
