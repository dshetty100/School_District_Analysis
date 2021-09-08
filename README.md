# School District Analysis

## Overview of the Project
The purpose of this project is to assist Maria, who is a chief data scientist for a city school district, in analyzing standardized test data from various schools in a district and look for any performance trend and pattern. By analyzing the data on student's math and reading scores, along with school funding for each student, and other information on the school they attend, Maria will be able to help school board and suprintendent in making decisions regarding school budgets and priorities.

The data was analyzed to see how: 
  1. Math and reading scores of students compared with their grade
  2. Scores compared with school spending
  3. Scores compared with school size
  4. Scores compared with school type

During the analysis, the reading and math grades for Thomas High School ninth-graders were found to have been altered. The data was therefore also analyzed to see how replacing the math and reading scores for Thomas High School with NaNs while keeping the rest of the data intact, affected the overall analysis.

The analysis was performed using CSV files, schools_complete.csv, and students_complete.csv, which can be found in the Resources folder. The complete code for the analysis can be found here, http://github.com/dshetty100/School_District_Analysis

## Results
The analysed data shows the following:

- **District Summary:** There are 15 schools in the district with a total of 39,170 students. The average math and reading scores in the district is 78.9 and 81.9, respectively. The percentage of students passing math test is 74.8%, and those passing reading test is 85.7%. The overall percentage of students passing both math and reading tests is 64.9%. The result is as summarized in the table below. 

![Figure1](/Images/District_Summary.PNG)

- **School Summary**

- How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?
The overall pasing percentage for Thomas High School before replacing the ninth-grade scores is as shown below.
![Figure1](/Images/THS_School_Summary_before.PNG)

The overall passing percentage for Thomas High School after replacing the ninth-grade scores is as shown below.
![Figure1](/Images/THS_School_Summary_after.PNG)

The result shows that Thomas High School's performance improved significantly after replacing the ninth-grade scores. Its overall passing percentage increased from % to %. It is now placed at second place amongst the top 5 performing schools





- How does replacing the ninth-grade scores affect the following:
  1. Math and reading scores by grade
  
![Figure2](/Images/MathScore_Grade.PNG)

  
  
  
  
![Figure3](/Images/ReadingScore_Grade.PNG)

  3. Scores by school spending

![Figure4](/Images/Score_Spending.PNG)

  5. Scores by school size

![Figure5](/Images/Scores_Size.PNG)

  7. Scores by school type

![Figure6](/Images/Scores_type.PNG)
  
## Summary
Summarize four changes in the updated school district analysis after reading and math scores for the ninth grade at Thomas High School have been replaced with NaNs.
