# ANALYZING HEALTH DATA OF MEDICAL STUDENTS 

## INTRODUCTION
This data set is presented to analyze the health of medical students. It is done to provide insight on the physical and medical status of students.
The dataset contains 200,000 rows and 16 columns of information.
![](initial_dataset.png)
## PROBLEM STATEMENT
The data analysis is set to show the following:
1. Average values for the following for Male and Females (Age, BMI, Temperature, Heart Rate, Blood Pressure, and Cholesterol)
2. Average Height and Weight for both Genders (in 2 decimal places)
3. Number of students across the different Blood Types
4. Number of Students who smoke and those who don’t
5. Number of Students who have diabetes and those who don’t

## DATA CLEANING
For the analysia process, I first started with cleaning the data set by doing the following 
1. Chaging the Data Type:
   I first changed the columns to the correct data types by using number format on the columns with numerical data. 
2. Filling in the Blanks:
   This data came with a lot of blanks that needed to be filled in.
- For the first column which was the student id, I noticed it was numbered 1 to 200000. Because of that, I created a new column and numbered it as usual from 1 to 200000 using flash fill. Then, I deleted the 
  original first column that came with the data set.
- For the numerical columns, I calculated the average and used that to fill in the blank spaces 
- For the gender and blood type column, I used the most occurring values which were FMALE and O respectively
- For the last two columns which were yes or no answers, I used not specified to fill in the columns.
![](aftercleaning.png)
## ANALYZING THE DATA
To answer the questions, I used pivot tables and created charts to illlustrate the findings. 
---
### Average values for the following for Male and Females (Age, BMI, Temperature, Heart Rate, Blood Pressure, and Cholesterol)

  ![](Pivot1.png)
  ![](Picture1.png)

  - From this, it is seen that the average values of the parameters are quite similar annd there are no significant differences between male and female students.
---

### Average Height and Weight for both Genders (in 2 decimal places)

![](Pivot2.png)
![](Picture2.png)

- Here, we also see that male and female students have quite similar height and weight.
---

###  Number of students across the different Blood Types

![](Pivot3.png)
![](Picture3.png)

- From this analysis, it shows that the mosT common Blood Type is _**O**_ having  _**65,511**_ students, the other having ver 40,000 students and _**A**_ having the least with _**44,466**_ students.
---

### Number of Students who smoke and those who don’t

![](Pivot4.png)
![](Picture4.png)

- It is shown here that the number of students who do not smoke is significantly lower than those who smoke.
---

### Number of Students who have diabetes and those who don’t

![](Pivot5.png)
![](Picture5.png)

- Here, we see that the ammount of students with diabetes is lower that those without diabetes.
---

## CONCLUSION
This analysis has shown that physical traits like height and weight are similar for students of both gender. It also shows that other health parameters are also similar amongst stdents.
Finally, this analysis has shown that there can be further analysis into lifestyle and habits of students which in turn can be useful to create events and plans for healthy living of students. 
  
