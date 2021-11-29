# School_District_Analysis

## Overview of the school district analysis

### Purpose:

 - After creating the school district analysis for Maria, she has now let me know that the board has found academic dishonesty within the [schools_complete.csv](https://github.com/Sebjet24/School_District_Analysis/files/7614742/schools_complete.csv) and
[students_complete.csv](https://github.com/Sebjet24/School_District_Analysis/files/7614743/students_complete.csv), specifically regarding the 9th grade class at Thomas High School. To uphold the data, I need to clean out the 9th grade class's reading and math grades from the end result. Maria would like me to repeat the school district analysis that I did and write up a report to describe how these changes affected the overall analysis.

## Results

### Addressing each Outcome

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

#### The district summary
