# students-Performance
Data Science project on students performance

**The StudentsPerformance Dataset can be found in Kaggle Website using the following link**
**https://www.kaggle.com/spscientist/students-performance-in-exams**

**This dataset consists of 1000 rows (instances) and 8 columns (variables) including gender, race, parental level of education, lunch, test preparation course, math score and writing score**





## Introduction 

Most of the students think if they did not perform well in an exam, it is because they did not work well, or they are not as smart as their peers. 
Students' performance can be affected by various factors, such as the lunch type they had before doing the exam, their gender, or taking a test preparation course. 

In this project, I will define four hypotheses to check if there is any statistically significant relationship between different variables of the students' performance dataset. 

A statistical hypothesis is an assumption about a population parameter, this assumption may or may not be true.

**A Null hypothesis: A statistical hypothesis to be tested**

**Alternative hypothesis: The alternative to the null hypothesis.**

For example, we can come up with the following Null and Alternative hypothesis

**Null 1 : There is no relationship between gender and the exam's score**
**Alt1: The opposite is True**

**Null 2 : There is no relationship between the lunch type of students and their exams' scores.
Alt2 : The opposite is true**

**Null 3: There is no relationship between students' parental level of education and their exams' scores.
Alt3: The opposite is true**

**Null 4: There is no relationship between the test preparation course and students' exams' scores.
Alt4: The opposite is True**


## Method

First of all, it is a good start to know the distribution of the numerical variables( "math score" , "reading score" , " writing score" ). As can be seen, they have a normal distribution.

![](images/1.png)


we can answer our hypothesis question using groupby function to group the students by gender, then take each exam's mean based on their gender and evaluate which group received higher marks in which exam.

![](images/2.png)

But it is not a reliable answer since we do not know if our dataset can represent the population well enough. Therefore, we should run a hypothesis test. Hypothesis testing is a statistical method that is used in making statistical decisions using experimental data. Hypothesis Testing is an assumption that we make about the population parameter. We use hypothesis testing to find if a finding is statistically significant or not. 

By checking the notebook provided in this repository you can see that there is statistically significant relationship for the hypotheses 1, 2 and 3 but 4. In other words, students performance in the exam can be affected because of their gender, the type of lunch that they had before exam and the test preparation course that they took, but there is not a significant relationship between students' performance and thier parental level of education. 





