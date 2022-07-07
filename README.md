# School_District Analysis
## 1.Overview of School District Analysis
The purpose of this analysis was to clean a large csv data file with over 39k lines of data and to give details on school performance throughout this district on a macro level and to break down different variables to deep dive potential causes for varying performance. Variables include: school size, school type, school spending, and by grade level. 

The other variable tested through this analysis was to test the impact if a top performing school (Thomas High School) had a whole class' test scores changed to NaN, how would it impact the schools performance vs. district performance.


## Results: 
 Using bulleted lists and images of DataFrames as support, address the following questions.

How is the district summary affected?
There was little impact on the district summary by replacing the 9th graders scores with NaN.  The largest impact was the % passing reading which dropped .3% from 86% to 85.7%.  There were only 461 students impacted by this change which accounts for ~1.2% of the entire population which the change was not as impactful.

Original District Summary
![image](https://user-images.githubusercontent.com/107078763/177802891-76f5f8a5-194a-4df3-b665-10e39f3fdd4f.png)

Updated District Summary
![image](https://user-images.githubusercontent.com/107078763/177803301-72cd185b-d4f8-4487-84e1-3931557c7c74.png)

How is the school summary affected?
Origianl Top School Summary
![image](https://user-images.githubusercontent.com/107078763/177804782-334af187-ca66-4619-a619-d599c86b8a1b.png)

Updated Top School Summary
![image](https://user-images.githubusercontent.com/107078763/177805037-862e73b5-8142-4aa3-aae2-8571b0d6e28f.png)


How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?
How does replacing the ninth-grade scores affect the following:
Math and reading scores by grade
Scores by school spending
Scores by school size
Scores by school type

## Summary: Summarize four changes in the updated school district analysis after reading and math scores for the ninth grade at Thomas High School have been replaced with NaNs.
