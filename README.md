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

How is the school summary affected? Thomas High School's performance relative to other schools?
The school summary for Thomas High School was slightly worse than when the 9th graders scores were untouched. Overall passing % dropped from 90.95% to 90.63% but Thomas High School was still the 2nd best performing school based on % Overall passing in the district.  The 9th grade class at Thomas High School accounts for ~28% of student population so the impact is felt more at a school summary level.  The minor drops average scores, % passing, and overall passing indicates the the 9th grade class is a top performing class in the school but the performance of the 10th through 12th graders is consistent across the school which is why the school is still ranked #2 in the district.

Origianl Top School Summary
![image](https://user-images.githubusercontent.com/107078763/177804782-334af187-ca66-4619-a619-d599c86b8a1b.png)

Updated Top School Summary
![image](https://user-images.githubusercontent.com/107078763/177805037-862e73b5-8142-4aa3-aae2-8571b0d6e28f.png)


How does replacing the ninth-grade scores affect the following:
Math and reading scores by grade
Original Average Math by Grade

![image](https://user-images.githubusercontent.com/107078763/177808232-f7594a77-8ca5-47ed-b698-8d722698c43c.png)

Updated Average Math by Grade

![image](https://user-images.githubusercontent.com/107078763/177808528-78eca2d0-bad3-44b0-8933-414bf0f13a37.png)


Original Average Reading by Grade


![image](https://user-images.githubusercontent.com/107078763/177809410-6d8609ac-6638-4a3b-9fce-9ef81127094b.png)


Updated Average Reading by Grade


![image](https://user-images.githubusercontent.com/107078763/177809589-de9bdf77-6df4-4957-a883-d84ce90bd637.png)


Scores by school spending
With the updated formats of scores and % passing, there was no impact to the $631-$645 spending bin where Thomas High School is categorized.  If we expand the decimal places there is a minimal drop in overall passing % from 62.85% to 62.77%.

Original 
![image](https://user-images.githubusercontent.com/107078763/177811724-613cd6aa-73ff-4950-bb9b-5cfacd6e15a1.png)

Updated
![image](https://user-images.githubusercontent.com/107078763/177812072-42140b4d-6007-41b0-ab86-f47ede04bdca.png)

Scores by school size
Original

Updated

![image](https://user-images.githubusercontent.com/107078763/177813330-ae2cbf3f-2d52-462d-b241-e334a2cd17be.png)




Scores by school type

## Summary: Summarize four changes in the updated school district analysis after reading and math scores for the ninth grade at Thomas High School have been replaced with NaNs.
