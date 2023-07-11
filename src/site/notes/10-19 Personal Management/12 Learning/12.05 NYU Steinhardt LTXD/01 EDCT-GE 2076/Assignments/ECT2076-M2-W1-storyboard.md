---
{"dg-publish":true,"permalink":"/10-19-personal-management/12-learning/12-05-nyu-steinhardt-ltxd/01-edct-ge-2076/assignments/ect-2076-m2-w1-storyboard/"}
---


## Scene 1 
- (medium shot)
- What is SAS? SAS is a widely used statistical software suite for data management, statistical analysis, and advanced analytics. The tools that SAS provides include the SAS programming language, a graphical user interface for creating and running SAS programs, and a variety of software packages for data manipulation, analysis, and output. 

## Scene 2
- (animation)
- SAS originally stood for Statistical Analysis System, but in the 2000s, it went through a bit of a midlife crisis and decided that SAS actually didn't stand for anything at all — SAS is SAS. 
- The early development of SAS began in the 1960s at North Carolina State University by faculty members and research partners Anthony Barr and James Goodnight. 

## Scene 3
- (close-up shot)
- This makes SAS somewhat of a dinosaur in the world of statistical software, compared to newbies like Python, which was introduced in 1992, and R, introduced in 1993. 

## Scene 5
- (animation)
- It was originally created as a result of an NIH grant to analyze large amounts of agricultural data to improve crop yields, and eventually grew to be one of the most popular statistical software tools, becoming the largest privately-owned software company in 2012. 

## Scene 6
- (medium shot)
- Nowadays, SAS is used in a wide range of industries, such as healthcare, banking, and pharmaceuticals. In the rest of this video, we'll cover the basic structure of SAS programs and dive a little deeper into how to use SAS to process data.

## Scene 7
- (animation)
- Most SAS programs are made up of 2 components: DATA steps and PROC steps. 
- In a DATA step, you can input data into SAS or read it in from an external source, manipulate it, or combine it with other datasets. It's often used to prepare the data for a procedure, or a PROC step. 
- In a PROC step, you can perform analyses on the data and produce output from your analyses, such as reports or data visualizations. 

## Scene 8
- (medium shot)
- In a typical SAS program, you will combine DATA and PROC steps to achieve your data analysis goals. 
- The best way to learn SAS is to learn how SAS thinks, or how it handles data in the DATA step. So, let's jump into the mind of SAS and the details of the DATA step.

## Scene 9
- (animation)
- This is an example of what a DATA step can look like. 
	- Every data step will begin with "data" and end with "run". Notice also that in the SAS syntax, every statement must end with a semicolon. 
	- After the word "data", you can specify the name of the dataset. In this example, we're naming the dataset "FINAL_GRADES".
	- A "set" statement after the "data" statement tells SAS to copy over the data from the dataset "EXAM_SCORES". In this example, the "EXAM_SCORES" dataset contains the following data: (display data) the student's name and the scores they received on three exams. 
	- This next statement tells SAS to create a new variable in the "FINAL_GRADES" dataset called "grade", which takes the average of the student's exam scores. 
	- The next two statements tell SAS to create a new variable named "passed_course", which will be 1 (representing true) if the student's final grade is greater or equal to 70, and 0 (or false) if the student's grade is less than 70.
	- The last statement tells SAS to only keep three variables: the student's name, their grade, and the flag indicating whether they passed the course. All of the other variables, the three exam scores, will be removed from the final dataset.
 
```
data final_grades;
	set exam_scores; 
	grade = mean(score_exam1, score_exam2, score_exam3);
	if grade >= 70 then passed_course = 1; 
	else if 0 <= grade < 70 then passed_course = 0;
	keep name grade passed_course;
run;
```

## Scene 10
- (long shot)
- So, at a high level, this DATA step will create a new dataset that tells us a student's final grade and if they passed the course or not. 
- But if you want to become a master of SAS, we should dive even deeper into the low-level details of what exactly SAS is doing when it executes these statements.

## Scene 11
- (animation)
- Flow of action in a DATA step 

## Scene 12 
- (animation)
- Animated walkthrough of what happens in a data step

## Scene 13 
- (long shot)
- So, now you know the nitty gritty details of how SAS thinks and processes data in the DATA step. The example that we walked through here was a very basic one, but this knowledge will be an important foundation for manipulating data in more complex ways. With this knowledge, you are one step closer to becoming a SAS wizard!


---
# Sources

https://en.wikipedia.org/wiki/SAS_Institute
https://sankhyana.com/blog/The-History-and-Evolution-of-SAS-Data-Analytics-Then-Now-and-Later
https://www.stat.berkeley.edu/~spector/s100/sas.pdf
https://documentation.sas.com/doc/en/pgmsascdc/9.4_3.5/lepg/n0yuo79dkucm7pn1rvmlt6l13qmn.htm
https://www.lexjansen.com/nesug/nesug04/pm/pm20.pdf




