# Report on the Colorado Election Audit Results


## Overview of Election Audit

Maria is the Chief Data Scientist for a city school district. She is tasked with providing insights for all standardised testing for the city school disctrict, for analysis, reporting and presentation to provide insights and help drive discussion on school performance trends and patterns, and to make decision about budget. I am helping Maria analyzing data on school budget and students' math and reading proficiency scores. I will aggregate the data and showcase analysis on tens of thousands of student records on math and reading scores by grade level and allocated budgets. Ultimately, this analysis will help the school boards and superintendent in making informed decisions regarding the school budgets and school funding priorities.


### Results

There are 39,170 students across the city school district. In order to ensure accurate analysis, I clean the data using Pandas Jupyter Notebook and stripped out 461 students records for grade 9 students' records that needs to be isolated and further looked into.


### District Summary
As a results, the district summary is showcased as follows:

![image](https://user-images.githubusercontent.com/104689265/171949381-5a64345c-aaac-4f8c-b079-ef343bfcd3bf.png)

Given the above, the school district summary gives an overview of total schools, students and allocated budgets. The average math and reading scores, which are in percentages, were somewhat comparable. The passing criteria has been set at 70% and above. The last 3 columns depicts this, as 86% of students in the district got 70% and therefore passed with their reading scores. Overall, 65% of student passed both math and reading with their scores. 

### School Summary

The school summary depicts performance trends and patterns across the 15 schools in the city district. For each school, there are metrics / variables, such as total students. In order to determine school performance, I ranked the top (1st image) and bottom (2nd image) performing school by '% Overall Passing'.

## Top Performing Schools
![image](https://user-images.githubusercontent.com/104689265/171950086-e825b1e2-e942-4788-b380-ff01f1c54f94.png)

## Botttom Performing Schools
![image](https://user-images.githubusercontent.com/104689265/171950150-6fec7e69-a01d-496a-848b-87d70102beb4.png)

As per the image, one can see that the top 5 performing high schools, as determined by students whose math and reading scores were over 70% are: Cabrera, Griffin, Wilson, Pena and Wright. 

The bottom 5 performing high schools (ascending order) were: Rodriguez, Figueroa, Huang, Hernandez and Johnson.

Given the above, the school summary gives an overview of total schools, students and allocated budgets by school. It is not clear whether the amount of budgets allocated to each school have a linear relationship with math and reading scores.

## Thomas High School
As mentioned earlier, grade 9 students records were isolated in this city school analysis. 
## Metrics with grade 9 - 12 Levels
![image](https://user-images.githubusercontent.com/104689265/171951772-208beb45-f538-46f9-8c13-5f8ae20126b1.png)

## Metrics with grade 10 - 12 Levels
![image](https://user-images.githubusercontent.com/104689265/171952208-cab44808-6016-46ed-9c88-3a0a8c16664a.png)

The above image depicts including and excluding grade 9 math and reading scores for Thomas High School. In the second image, grade scores was replaced with NaN and not accounted for. It shows that students at grade levels 10 and above outperformed grade 9 students at Thomas High School, by a siginificant margin as the overall passing rate jumped from 65% to 91% when grade 9 proficiency scores were excluded. 

This is significant because, with the exclusion of grade 9 scores in Thomas High Schools, allowed Thomas to join the ranks of top performing schools, whereby it would have been amongst underperforming schools if the grade 9 scores were included.


### How Replacing Ninth Grade Scores impacted Metrics

# Math and Reading Scores by Grade
This likely worsened both math and reading average score for ninth graders across school district as Thomas High School were amongst the high scores in both proficiencies averaging 83%. The other grade levels would not have been impacted. However, exclusion of the ninth grade scores will have minimal impact to the overall 
passing % for the school district.

# Scores by School Spending
This has no impact to scores by school spending as budget is already allocated for each school

# Scores by School Size
Thomas High School is a medium sized school. The removal of ninth graders in Thomas High will improve the avergae scores for medium sized schools, however, there will
be no impact for both small and large sized schools.

# Scores by School Type
Thomas High is a charter school. Charter schools were already performing better than district schools, and the removal of 9th graders will only enhance Thomas High standing and also increase the overall passing % for charter schools

#### Summary

In summary, the report depicts insights on schools performance trends and showcase proficiency scores for math and reading by schools, grade levels, budget bins, school size and type. This will allow the school board to make informed budget allocation decisions and provide adequate funding to top performing schools.

