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

We can see the data before and after in the images below

![Capture3.PNG](/Resources/Capture3.PNG)


![Capture4.PNG](/Resources/Capture4.PNG)

### Top 5 Schools

After replacing the math and reading scores of ninth graders at Thomas High School with NaN and performing the analysis based on the new student count that excludes the ninth grade students of Thomas High School, we can see that Thomas High School's position has been dropped from the second place and replaced by Griffin High School.

You can see prior to the adjustments Thomas heald the 2nd place position...
![Capture6.PNG](/Resources/Capture6.PNG)

Though once correction where made in our investigation we see Griffin move to that position.

![Capture5.PNG](/Resources/Capture5.PNG)

### Bottom 5 Schools

Replacing the ninth graders scores at Thomas High School did not have any effect on the 5 lowest performing schools.

### Math & Reading Scored By Grade

The per_school_summary_original_df dataframe analyzes the data after we have replaced the ninth grade math and reading scores with Nan but have not replaced the school summary dataframe with new passing percentages for 10th to 12th graders for Thomas High School as instructed in steps 5 to 12. In this case,

* math by grade score shows NaN for Thomas High School 9th graders.

![Capture7.PNG](/Resources/Capture7.PNG)

* Reading by grade also shows NaN for Thomas High School 9th graders.

![Capture8.PNG](/Resources/Capture8.PNG)

### Scores By School Spending

The spending randge for the schools budget(per student) were affected 

* % Passing Math reduced from 73% to 67%
* % Passing Reading reduced from 84% to 77%
* % Overall Passing reduced from 63% to 56% 

Before
![Capture10.PNG](/Resources/Capture10.PNG)

After 
![Capture10.PNG](/Resources/Capture10.PNG)

### Scores By School Size

In terms of school size, there were no changes in scores for small and large schools.Only the scores for medium schools have been affected.

* % Passing Math reduced from 94% to 88%
* % Passing Reading reduced from 97% to 91%
* % Overall Passing reduced from 91% to 85%

![Capture11.PNG](/Resources/Capture11.PNG)
![Capture12.PNG](/Resources/Capture12.PNG)

### Schools By Type

It would seem that only the Charter school leve has been affected while the District level remains unchanged.

* Passing Math reduced from 94% to 90%
* Passing reading reduced from 97% to 93%
* Overall Passing reduced from 90% to 87%

![Capture13.PNG](/Resources/Capture13.PNG)

## Summary

We can now conclude that with Thomas Highschool the performance of grades other than the 9th grade class remained consistent when we analyzed the data, we see a drop in the High schools overall performance in reference to other schools once we started to exclude the data of the 9th grade students. Factoring in our new formating we saw a performance drop in Charter schools overall.
In the end we were able to see the affect that just one grade level had on the data for the type of school as well as the size of the school. 
