# School District Analysis

## Overview

The school board believes the student_complete.csv file shows evidence of grade tampering for the 9th-graders’ reading and math scores from Thomas High School. With out further analyst the board wont know the full extent of the academic dishonesty, so Maria me to review, clean and analyze the data and provide an explanation on the impact the changes had to the schools’ performances and school district’s overall analysis.


## Results

* How is the district summary affected?

    The testing data of the 9th graders at Thomas High School was replaced with NaNs, which recalculated the percentages of passing math, 
    passing reading, and the overall passing. The total count of students did not change due to the fact that it runs on the count of the student ids, 
    which was not replaced with NaNs.
    
    Original 
    
    <img width="945" alt="original district_summary" src="https://user-images.githubusercontent.com/90155651/178984496-d30552b9-e2e5-45ab-a07a-1ded48b757d9.png">


    Adjusted
    
    <img width="932" alt="district_summary" src="https://user-images.githubusercontent.com/90155651/178984052-72969e86-9019-486f-87b2-d14c22a2fe1c.png">

    
    
    When comparing the two charts, removing less than 500 test scores had a nominal impact on the almost 40,000 student data set. The change was 
    less than a 1% difference and the numbers would still round to the same whole number.

* How is the school summary affected?

    * Average Math at Thomas High School decreased from 83.42 to 83.35%
    * Average Reading at Thomas High School increased from 83.84 to 83.89%
   

* How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?
    
    Replacing the THS 9th-graders’ math and reading scores only impact THS performance and has no bearing on the individual performance of the 
    remaining 14 schools.

* How does replacing the ninth-grade scores affect the following:


    * Math and reading scores by grade

    With the removal of the 9Th graders, only the average grades at THS were affected.

    * Scores by school spending:

    Did not have any impact to spending because the scores do not have bearing on the calculation and the total student population at THS was 
    unchanged (1,635).
    
    <img width="988" alt="Scores by School Spending" src="https://user-images.githubusercontent.com/90155651/178972812-379e011a-0a5a-46ca-af2f-b66d2a653c7c.png">

    
    
    * Scores by school size: 

    The average math- and reading- scores were not impacted because the school size at THS remained within the meduim range -- a population 
    of 1,174 students, excluding the 461 9th-graders. Conversely, the math- and reading- percentages spiked up due to removal of the 9th-graders' scores.
    
    <img width="775" alt="School Size" src="https://user-images.githubusercontent.com/90155651/178970618-3f2fc1cc-e710-46f7-a825-95fb8f6c61bf.png">
    
    
    
    * Scores by school type: 

    THS is a Charter school, therefore the cumulative performance result of the charter school is impacted
    
    <img width="715" alt="School Type" src="https://user-images.githubusercontent.com/90155651/178970349-4a3459c3-761b-416d-9ae4-eb657097f96a.png">
    
    
    
    
## Summary


    In conclusion, the 9th grade scores of Thomas High School don't definitively support the suspicion that math and reading scores were manipulated 
    because this data analysis performed demonstrates otherwise. By removing said academic misconduct stats, the performance of many score 
    indicators remained the same or increased, suggesting that the reading and math scores were probably honest values and not manipulated.


