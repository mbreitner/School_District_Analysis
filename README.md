# School_District_Analysis
Anaconda, Jupyter Notebook, Pandas

## Overview of the School District Analysis
The school board identified evidence of academic dishonesty from the 9th graders at Thomas High School and wanted us to update our analysis with those scores excluded. We ultimately wanted to see the true numbers from Thomas High School (only including 10th-12th grade scores) and how they effected our overall analysis. 

## Results
- How is the district summary affected?
  - Much of the analysis remained the same because the amount of students were we removed the scores was a low percentage of the overall total
  ![image](https://user-images.githubusercontent.com/84791455/125169373-aff24e00-e15e-11eb-86e7-f94726477c16.png)

- How is the school summary affected? 
  - Now this is where we say the most changes when we removed the 9th grade scores at Thomas High School from our analysis. We were able to see a large increase in the % of    students at Thomas High School who passed math and reading. This ultimately led to a total increase in the amount of overall students who were passing. The images below show the before and after effects of our analysis. 
  - Before
  ![image](https://user-images.githubusercontent.com/84791455/125169529-74a44f00-e15f-11eb-80cd-1dee7c254895.png)
  
  - After
  ![image](https://user-images.githubusercontent.com/84791455/125169595-c6e57000-e15f-11eb-9961-6033647bdd0d.png)

- As you can see here, the % of students passing math and reading and the overall passing % all increased from the mid 60's up into the 90's. This shows the 10th-12th graders all performed very well and our analysis was being skewed previously when we removed the results of the 9th graders. 

- How does replacing the ninth graders math and reading scores affec Thommas High School's performance relative to the other schools
  - Removing the 9th grade scores catapults Thomas High School into the top 5 best performing schools. It suddenly becomes the number 2 overall school when looking at the % Overall Passing 
  ![image](https://user-images.githubusercontent.com/84791455/125169748-6d317580-e160-11eb-8def-1cd7717fa117.png)
  
- How does replacing the ninth-grade scores affect the following:
  - Math and reading scores by grade: Thomas High School 10-12th grade scores remain the same but the 9th grade scores are replaced with nan
  
    Math scores by grade:
    
      ![image](https://user-images.githubusercontent.com/84791455/125169799-acf85d00-e160-11eb-961e-43c50317cd56.png)
      
    Reading scores by grade:
    
      ![image](https://user-images.githubusercontent.com/84791455/125169850-e8932700-e160-11eb-8a9c-9debcd15bbbc.png)
   
  - Scores by school spending: Because it wasa only a small subset of students across the whole population size, the scores by school spending is mainly unaffected. 
  
      ![image](https://user-images.githubusercontent.com/84791455/125169932-4aec2780-e161-11eb-93e9-d3dcd123e434.png)
      
  - Scores by school size: With our new analysis, we aer seeing the medium sized schools now have the highest % of overall students pasing with 91%
  
      ![image](https://user-images.githubusercontent.com/84791455/125170020-c6e66f80-e161-11eb-805d-b93e0daf3593.png)

  - Scores by school type: The charter schools vastly out perform the district schools. % overall passing is 36% higher in charter schools compared to district schools. 
  
      ![image](https://user-images.githubusercontent.com/84791455/125170059-f1d0c380-e161-11eb-8793-e39d28c637be.png)
      
## Summary
One change that happened in our updated analysis is the Thomas High School is the 9th grade scores were replaced with actual numbers to NaN. Another change is we recalculated the total # of students at Thomas High School to find a more accurate representation of the 10th-12th grade schools, so ultimately the % passing math and % passing reading numbers were drastically increased. This in turn changed the overall % of students who were passing at Thomas to 90%. With the increase in overall passing percentage at Thomas High School, it catapulted them into the second spot when analyzing the top performing schools. 

This change in our analysis did not effect the overall analysis since it was a low percentage of students but the results at Thomas High School itself were much improved with the new scores. 

      

    

      

