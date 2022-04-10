# PyCitySchool Challenge
## Overview of Project
The school board has notified Maria and her supervisor that the students_complete.csv file shows evidence of academic dishonesty; specifically, reading and math grades for Thomas High School ninth graders appear to have been altered. Although the school board does not know the full extent of the academic dishonesty, they want to uphold state-testing standards and have turned to Maria for help. She has asked you to replace the math and reading scores for Thomas High School with NaNs while keeping the rest of the data intact. Once you’ve replaced the math and reading scores, Maria would like you to repeat the school district analysis that you did in this module and write up a report to describe how these changes affected the overall analysis.

## Results
### District Summary

After replacing the math and reading scores for Thomas high School ninth graders with NaN we did not see much of a change at the district level. 
* Total students and total budget remains the same
* Average math score has changed from 79 to 78.9
* Average reading score has remained the same
* Passing Math has reduced from 75% to 74.8%
* Passing Reading has reduced from 86% to 85.7%
* Overall Passing has reduced from 65% to 64.9%

![Capture1.PNG](/Resources/Capture1.PNG)
![Capture2.PNG](/Resources/Capture2.PNG)

### School Summary

The school summary shows the performance of each school by the total students,total budget, per student budget, average math score, average reading score, percent passing math, percent passing reading and percent overall passing. We have calculated the percent passing math, reading, and overall passing for the schools with the new total student count that would exclude the Thomas high School ninth grade class.

* The total new student count was 38,709
* The % Passing Math column values have changed from 93.27% to 66.91% for Thomas High School
* The % Passing Reading column values have changed from 97.31% to 69.66% for Thomas High School
* The % Overall Passing column values have changed from 90.95% to 65.08% for Thomas High School

From this data we can see that we do have a significant drop in the performance of Thomas High School compared to the other schools.

