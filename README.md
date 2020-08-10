# School-District-Analysis
## Overview 
The purpose of this school district analysis was to first remove the freshman at Thomas  High School reading and math scores from the main data frame due to some academic integrity issues. This will change my previous analysis I have constructed in the PyCitySchools python file which includes Thomas High School freshman math and reading test scores. In a brief disucssion, with this new analysis I have createdn the follwing with the math and reading scores for 9th graders at Thomas High School and without them: 
1. A District summary Data frame
2. A School summary dataframe
3. The top 5 and bottom 5 schoools based on overall passing rate 
4. The average math score for each grade level from each school
5. The average reading score for each grade level from each school
6. The math and reading scores by school spending per student, by school size, and by school type

## Results

 **DISTRICT SUMMARY** 
  * **Before ,removing Thomas HS 9th graders scores**
<img width="641" alt="Screen Shot 2020-08-09 at 6 01 27 PM" src="https://user-images.githubusercontent.com/67808057/89745697-6ab72f00-da6a-11ea-9557-06876d75d605.png">

  * **After , removing Thomas HS 9th graders scores**
<img width="661" alt="Screen Shot 2020-08-09 at 6 02 22 PM" src="https://user-images.githubusercontent.com/67808057/89745721-99cda080-da6a-11ea-8af5-8a552005dc81.png">

  **Analysis**

The following categories had decreases before the changes made to the data: Passing Reading Percentage(From 86% to 85%), Passing Math Percentage(From 75% to 74%), and Overall Passing Percentage(From 65% to 64%). The averages were about constant the whole time and minor changes. To state, the passing requirement was greater than or equal to 70%. This rule applies to the rest of the data we will go through. 
  
  
**SCHOOL SUMMARY** 
  * **Before**
<img width="821" alt="Screen Shot 2020-08-09 at 6 41 19 PM" src="https://user-images.githubusercontent.com/67808057/89746702-f7b0b700-da6f-11ea-93f1-d21e5ea942ad.png">

 * **After** 
<img width="1020" alt="Screen Shot 2020-08-09 at 6 34 57 PM" src="https://user-images.githubusercontent.com/67808057/89746547-16627e00-da6f-11ea-9f58-7782c80dae61.png">

  **Analysis**
  
From these two data frames we can see that there is a significant difference from when freshman were included to not being included. Our overall passing percentage goes from about 91% to 65%. Relative to other schools, Thomas High School dropped significantly considering it was one of the best high school in the district at the number 2 spot based overall passing both math and reading. Now it is the 8th best out of 15 other schools. 


**9th GRADER SCORES**
 * **Before**
 <img width="814" alt="Screen Shot 2020-08-09 at 6 53 32 PM" src="https://user-images.githubusercontent.com/67808057/89747048-cd5ff900-da71-11ea-843b-1a0bc2281af2.png">
<img width="719" alt="Screen Shot 2020-08-09 at 6 54 02 PM" src="https://user-images.githubusercontent.com/67808057/89747091-fe402e00-da71-11ea-8344-e3242ee45746.png">

* **After**
  
  **Analysis**
  
  The data for the freshman at Thomas High school for both reading and math scores were removed and placed with a NaN value, thus they are at the bottom of each list. 


**BY SCHOOL SPENDING**
* **Before**
<img width="743" alt="Screen Shot 2020-08-09 at 7 02 45 PM" src="https://user-images.githubusercontent.com/67808057/89747315-1795aa00-da73-11ea-975e-54b45c1b42ba.png">

* **After**
<img width="752" alt="Screen Shot 2020-08-09 at 7 05 17 PM" src="https://user-images.githubusercontent.com/67808057/89747358-5297dd80-da73-11ea-9692-7ddd2836a7da.png">

  **Analysis**
  
To start, Thomas High School was apart of the $630-644 group in which we saw major decreases in many different aspects. To start, we see the following categories decrease: Passing Math Percentage (From 73% to 67%), Passing Reading Percentage (Fromn 84% to 77%), Overall Passing Percentage(From 63% to 56%). On the other hand our averages did stay constant. 


**BY SCHOOL SIZE**
* **Before**
<img width="766" alt="Screen Shot 2020-08-09 at 7 17 18 PM" src="https://user-images.githubusercontent.com/67808057/89747769-0ea5d800-da75-11ea-80c1-b2e35cfb5cf8.png">

* **After** 
<img width="774" alt="Screen Shot 2020-08-09 at 7 18 53 PM" src="https://user-images.githubusercontent.com/67808057/89747802-37c66880-da75-11ea-9253-4f3ca69cccfc.png">
 
 **Analysis** 
 
Thomas High School is a Medium sized high school again saw a significant decrease in the following categories: Passing Math Percentage(From 94% to 88%), Passing Reading Percentage(From 97% to 91%), and Overall Passing Percentage(From 91% to 85%). Our averages stayed constant for both reading and math. 


**BY SCHOOL TYPE**
* **Before**
<img width="726" alt="Screen Shot 2020-08-09 at 7 31 56 PM" src="https://user-images.githubusercontent.com/67808057/89748221-09498d00-da77-11ea-84e7-2fb33fdc83bc.png">

* **After**
<img width="735" alt="Screen Shot 2020-08-09 at 7 32 55 PM" src="https://user-images.githubusercontent.com/67808057/89748241-2da56980-da77-11ea-8d85-fd4ee815dec4.png">

**Analysis**

Thomas High School is a Charter high school and saw a significant decrease in the following categories: Passing Math Percentage(From 94% to 90%), Passing Reading Percentage(From 97% to 93%), and Overall Passing Percentage(From 90% to 87%). Our averages stayed constant for both reading and math. 

## Summary 

In conclusion, with the by school size, type and school spending groups the following categories had the biggest changes when we removed the freshman scores for Thomas High School: Passing Math Percentage, Passing reading Percentage, and Overall Passing Percentage. Our School Summary showed Thomas High School relative to other schools when we removed the freshman which showed the significant decrease in their positioning from the top of the schools to mid table. 



