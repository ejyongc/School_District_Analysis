# School_District_Analysis

The analysis should contain the following:
    1. Overview of the school district analysis: Explain the purpose of this analysis.

## 1. Analysis Overview
The *School District Analysis* was created to provide the school board detailed information that will assist them on the decision making process for next year.  The analysis can be divided into five sections:
  
  1. **District Summary -** Cobined dataframes and calculated totals and averages for the entire school district. 
  2. **School Summary -**  This data frame is the breakdown of the *Districs Summary* data by school. 
  3. **High & Low Performing Schools -** Sorted schools based on the *Percentage of Overall Passing* students. 
  4. **Math and Reading Scores by Grade -** Created two separate dataframes that breaks down *math* and *reading* scores by *grade* for each school. 
  5. **Score analysis:-** Segmented the data to determine the impact that *Budgets*, *School Sizes*, and *School Types* have on the *Scores*
      a. Scores by School Spending 
      b. Scores by School Size
      c. Score by School Type 
  
  In this script, we will start off by cleaning the data due to some academic dishonesty implications that compromised the data, and then proceeding with the *Disctrict Analysis*.  

    2. Results: Using bulleted lists and images of DataFrames as support, address the following questions.
        How is the district summary affected?
        How is the school summary affected?
        How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?
        How does replacing the ninth-grade scores affect the following:
            Math and reading scores by grade
            Scores by school spending
            Scores by school size
            Scores by school type

## 2. Results
  #### 2.1 How is the *District Summary* affected? 
  After removing the implicated data, we noticed a small decrease on the following metrics: *'Average Math Score' (-0.1%), '% Passing Math' (-0.2%), '% Passing Reading' (-0.1%), and '% Overall Passing' (-0.3%).*
##### Old District Summary 
![image](https://github.com/ejyongc/School_District_Analysis/blob/main/Resources/Old%20District%20Analysis.png)
##### New District Summary
![image](https://github.com/ejyongc/School_District_Analysis/blob/main/Resources/New%20District%20Analysis.png)

  #### 2.2 How is the school summary affected?
  We can see that the *'Percentage Passing Math' (-0.08%), 'Percentage Passing Reading' (-0.29%), and '% Overall Passing' (-0.32%)* metrics were impacted after removig and replacing the compromised data. 
  ##### Old School Summary 
![image](https://github.com/ejyongc/School_District_Analysis/blob/main/Resources/Old%20School%20Summary.png)
  ##### New School Summary
![image](https://github.com/ejyongc/School_District_Analysis/blob/main/Resources/New%20School%20Summary.png)
  

  #### 2.3 How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?
  After removing the data compromised data, 'Thomas High School' overall percentage decreased -0.32% but we can still that it didn't affect its possion on the top five schools on the district.
  ##### Top Five Schools
![image](https://github.com/ejyongc/School_District_Analysis/blob/main/Resources/Top%205%20Schools.png)

  #### 2.4 How does replacing the ninth-grade scores affect the following:
  ##### a. Math and reading scores by grade
  We can see that after the data for 9th graders was removed, there's no significant impact on the rest of schools
  ![image](https://github.com/ejyongc/School_District_Analysis/blob/main/Resources/Math%20and%20Reading%20Scores%20by%20Grades.png)
  ##### b. Scores by school spending
  There's no significant change on the data for *Scores by School Spending*.
  ![image](https://github.com/ejyongc/School_District_Analysis/blob/main/Resources/Spending%20Summary.png)
  ##### c. Scores by school size
  Similarly to *Scores by School Size*, replacing the *ninth-grade scores* didn't impact the *Scores by School Size* dataframe. 
  ![image](https://github.com/ejyongc/School_District_Analysis/blob/main/Resources/Size%20Summary.png)
  ##### d. Scores by school type
  Finally, we are not seeing any changes on *Scores by School Type*
  ![image](https://github.com/ejyongc/School_District_Analysis/blob/main/Resources/Type%20Summary.png)
    

    3. Summary: Summarize four major changes in the updated school district analysis after reading and math scores for the ninth grade at Thomas High School have been replaced with NaNs
