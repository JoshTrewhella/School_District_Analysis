# School_District_Analysis
## Overview
During our meeting with Maria, she asked us to assist in analyzing the data of the schools in her district, and present the data in table format. We are to include the performance of each school based on math and reading scores along with the the budget, size, and type of each school. Due to academic dishonesty, we were asked to replace the reading and math scores for Thomas High School with NaNs and analyze how the outcomes were effected. 

## Results
  - District Summary with THS Scores
    ![alt text](Resources/District_Summary_with_THS.PNG)
    District Summary without THS Scores
    ![alt text](Resources/District_Summary_without_THS.PNG)
    - Average Math Score decreased by <1%
    - Average Reading Score remained unaffected
    - % Passing Math decreased by <1%
    - % Passing Reading decreased by <1%
    - % Overall Passing decreased by <1%
  - School Summary with THS Scores
    ![alt text](Resources/School_Summary_with_THS.PNG)
    School Summary without THS Scores
    ![alt text](Resources/School_Summary_without_THS.PNG)
    - We can see that changing the 9th grade scores to NaNs, only changed THS's overall passing percentage by less than 1% and didn't change the rankings at all. 
  - How does replacing the ninth-grade scores affect the following:
    - Math and reading scores by grade
      - Math Scores by Grade
    
        ![alt text](Resources/math_scores_by_grade.PNG)
      - Reading Scores by Grade
    
        ![alt text](Resources/reading_scores_by_grade_fixed.PNG)  
    - Scores by School Size
      - With THS scores
        ![alt text](Resources/scores_by_size_with_THS.PNG)   
      - Without THS scores
        ![alt text](Resources/scores_by_size_without_THS.PNG)  
    - Scores by School Type 
      - With THS scores
        ![alt text](Resources/type_with_THS.PNG)   
      - Without THS scores
        ![alt text](Resources/type_without_THS.PNG)      
  
## Summary
Due to the little change that replacing the THS scores with NaNs created there wasn't many things that changed. If score changes were more significant this would effect the rankings of the schools, which would effect the budgets along with the spending per student. However, what did change are the average math and reading score along with the overall passing scores. This negatively effected the THS scores.
