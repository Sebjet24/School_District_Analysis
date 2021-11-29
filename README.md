# School_District_Analysis

## Overview of the school district analysis

### Purpose:

 - After creating the school district analysis for Maria, she has now let me know that the board has found academic dishonesty within the [schools_complete.csv](https://github.com/Sebjet24/School_District_Analysis/files/7614742/schools_complete.csv) and
[students_complete.csv](https://github.com/Sebjet24/School_District_Analysis/files/7614743/students_complete.csv), specifically regarding the 9th grade class at Thomas High School. To uphold the data, I need to clean out the 9th grade class's reading and math grades from the end result. Maria would like me to repeat the school district analysis that I did and write up a report to describe how these changes affected the overall analysis.

## Results

### Addressing each Outcome:

Using Jupiter, I created a python file from the data that helped me to replace all the 9th grade student's grades at Thomas High School with NaN:

 - First I installed numpy using conda. Then I used the loc method to filter out the reading scores and then did the same for the math scores. Then I printed the last 10 students data to see the effect:
![Screenshot (29)](https://user-images.githubusercontent.com/91230277/143793346-69cbf958-d5b4-4edb-b406-a11baf6f8f94.png)

I then repeated the school district analysis I did in this module, and recreated the following metrics:

 - The district summary
 - The school summary
 - The top 5 and bottom 5 performing schools, based on the overall passing rate
 - The average math score for each grade level from each school
 - The average reading score for each grade level from each school
 - The scores by school spending per student, by school size, and by school type

For this task, I recalculated the total student count by subtracting the number of ninth-grade students in Thomas High School from the total student count, then I recalculated the passing math and passing reading percentages, and the overall passing percentage with the recalculated total student count:
![Screenshot (30)](https://user-images.githubusercontent.com/91230277/143793721-694b26fd-16b1-4476-90f5-b6b57c177b45.png)

I then executed the code from this module that creates and formats the School Summary DataFrame, then updated the school summary using the 10th-12th graders from Thomas High School.

 - So I calculated the number of 10th-12th graders in Thomas High School:
![Screenshot (31)](https://user-images.githubusercontent.com/91230277/143793919-b94493e2-6faf-4092-8ee3-474cb1b82105.png)
 - Then I created three new DataFrames for the 10th-12th graders from Thomas High School: students who passed math, students who passed reading, and students who passed both math and reading:
![Screenshot (32)](https://user-images.githubusercontent.com/91230277/143793977-27f7b1ac-723e-421d-b7b1-864761d28d8a.png)
![Screenshot (33)](https://user-images.githubusercontent.com/91230277/143794003-80f4869d-a3db-4547-973c-98ab33b887ee.png)
![Screenshot (34)](https://user-images.githubusercontent.com/91230277/143794042-e8693df4-4919-449c-9099-80c07103ef54.png)
 - Using these DataFrames, I recalculated the percentage of students who passed math, passed reading, and passed both math and reading for Thomas High School only:
![Screenshot (35)](https://user-images.githubusercontent.com/91230277/143794113-f5da9ef9-2737-4f62-b7d2-2c1a718ac43d.png)
 - I then replaced the % Passing Math, % Passing Reading, and % Overall Passing scores in the current School Summary DataFrame with the new passing percentages for Thomas High School:
![Screenshot (37)](https://user-images.githubusercontent.com/91230277/143794182-ca9d857f-7a94-472b-bb29-70106084d39c.png)
 - I finally, I showed the top 5 and bottom 5 performing schools, based on the overall passing rate, 
![Screenshot (38)](https://user-images.githubusercontent.com/91230277/143794323-087385f1-82b9-476e-a984-15b5ac53ec97.png)
 - the average math score for each grade level from each school, 
![Screenshot (39)](https://user-images.githubusercontent.com/91230277/143794385-649d19b2-2269-4a97-9360-79aa90fe9ae4.png)
 - the average reading score for each grade level from each school, 
![Screenshot (40)](https://user-images.githubusercontent.com/91230277/143794498-e8f6482a-a5b4-4c92-9b15-1c210a8be9ab.png)
 - and the scores by school spending per student, by school size, and by school type:
![Screenshot (41)](https://user-images.githubusercontent.com/91230277/143794603-d80786ab-9aaa-4411-b366-fc323af063dc.png)
![Screenshot (42)](https://user-images.githubusercontent.com/91230277/143794660-3500bf62-5f69-417d-a575-e81247875a6b.png)
![Screenshot (43)](https://user-images.githubusercontent.com/91230277/143794781-3db589e2-0020-4b22-9530-a8c8c4656a4c.png)

## School Analysis Summary

### Final Thoughts:

 - 


 
