# PyCity-District-School-Analysis
## Overview of PyCityShcools Challenge
The goal of this challenge was to analyize the standardized testing results from a large number of schools state-wide. The test results covered both Math and Reading from 9th to 12th grade. The purpose of this analysis was to see how removing test results from Thomas High School's 9th grade class affect the overall results we obtained from the assignment in Module 4. In Module 4 we found the overall passing percentage of the students and determined whether there is any correlation with the budget per student using numpy-python.

## Results
### - How is the district summary affected
After taking a close look at both district summaries it can be noted that there is not a lot of change after in the district summary after removing grade 9 scores of Thomas High School.

Before Data Clean-up
    <img width="1060" alt="District Summary-before" src="https://user-images.githubusercontent.com/100812308/161450907-b9cad126-abae-4418-b843-11477d0f2e1e.png">
    
After Data Clean-up
    <img width="1024" alt="District Summary-After" src="https://user-images.githubusercontent.com/100812308/161450928-1bb429e8-9eb0-4a24-9210-a59359c90812.png">

### - How is the school summary affected?
The overall passing percentage changed considerably for Thomas High School after the data clean-up and affected the placement of the school as well. 

Before Data Clean-up
<img width="950" alt="School Summary-Before" src="https://user-images.githubusercontent.com/100812308/161451160-9e2ce5fa-1668-4a48-b942-4e76643c08bc.png">

After Data Clean-up
<img width="911" alt="School Summary- After" src="https://user-images.githubusercontent.com/100812308/161451167-46e9df1b-8e38-4443-9284-2d5a05cc74b4.png">

### -How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?
Replacing ninth graders’ math and reading scores affect Thomas High School’s performance between the other schools, Relative ranking for Thomas High School changed from 2nd place to 8th (see images above).

### - How does replacing the ninth-grade scores affect the following:
#### - Math and reading scores by grade
For the purpose of analysis, grade 9 scores for math and reading were set to NaN for Thomas High School. The only change seen after the clean-up was in the student count as shown below
        
Before Data Clean-up: Student Count = 1635
   <img width="396" alt="Student Count-Before" src="https://user-images.githubusercontent.com/100812308/161451626-c8e3cc98-04e6-478c-ae89-f6d1f4c35dbf.png">
        
After Data Clean-up: Student Count = 1174     
   <img width="869" alt="Student Count- After" src="https://user-images.githubusercontent.com/100812308/161451654-fb71f1d2-7e16-4cb8-b1e3-1dff8e019680.png">
   
#### - Scores by school spending 
Thomas High school was in the $630 to $644 spending range and was one of the high schools in that range, their % passing math was higher than the average prior to removing the 9th grade test results and so reduced the averages for schools in that range when the test results dropped from 90.95% down to 65.08%

#### - Scores by school size
Overall passing percentage did not change after grade 9 results were removed for Thomas High School.

<img width="842" alt="School by size" src="https://user-images.githubusercontent.com/100812308/161452988-dbca0a09-f1e0-41bb-a712-a445331a1e76.png">

#### - Scores by school type
Scores by school type are not altered at all either. 

<img width="734" alt="School type" src="https://user-images.githubusercontent.com/100812308/161453742-59e2fa7d-438e-4463-bc01-611cab04b141.png">

## Summary
Once the results have been modified to control for potential academic dishonesty, we lost any data for the 9th grade at Thomas High School. The average scores for the district were not strongly shifted, but it decreases district-level scores slightly.

This analysis shifts entirely future models and expectations for the 9th-grade class since these scores are not accurate. The potential academic dishonesty reduces confidence in the administration and future scoring of Thomas High School.



        
        
        
        
