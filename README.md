# School_District_Analysis

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
  After removing the data compromised data, 'Thomas High School' overall percentage decreased -0.32% but we can see that it didn't affect its position on the top five schools on the district.
  ##### Top Five Schools
![image](https://github.com/ejyongc/School_District_Analysis/blob/main/Resources/Top%205%20Schools.png)

  #### 2.4 How does replacing the ninth-grade scores affect the following:
  ##### a. Math and reading scores by grade
  We can see that after the data for 9th graders was removed (NaN Cells), there's no significant impact on the rest of schools. 
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

## 3. Summary
In conclusion, post the changes we applied to the data, we can see some changes that altered some of the dataframes.  
In the *District Summary* dataframe we can immediately see the number of students decrease by 461. This accounts for all the 9th grade students from *Thomas High School* we removed at the beguining of the analysis. 
We can also see a slight decrease on the math and reading passing percentages. Although we are seeing a change on this dataframe we believe is not significant enough to skew the data. 
Finally, the '*School Summary'* dataframe is where we are going to see the most significant change in terms of percentages. We are seeing a decrease of -0.32% on the percentage of passing students. This could be considered high in relation to the other changes mentioned above, but ultimately, it didn't create a significant change on the dat sice Thomas High School is still comes up second on the top five schools dataframe. 
