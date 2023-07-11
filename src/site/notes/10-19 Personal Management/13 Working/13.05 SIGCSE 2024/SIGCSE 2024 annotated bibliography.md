---
{"dg-publish":true,"permalink":"/10-19-personal-management/13-working/13-05-sigcse-2024/sigcse-2024-annotated-bibliography/"}
---

## [[10-19 Personal Management/13 Working/13.05 SIGCSE 2024/Krause-Levy et al. 2021; The Relationship Between Sense of Belonging and Student Outcomes in CS1 and Beyond\|Krause-Levy et al. 2021; The Relationship Between Sense of Belonging and Student Outcomes in CS1 and Beyond]]

### Research questions
1.  What do students in lower-division computing courses report as their incoming sense of belonging in computing; and how does this vary by gender, BLNPI, first-generation and transfer-student status? 
2. How does sense of belonging change over time both within a course and across courses as students work through the lower-division computing curriculum; and how does this vary by gender, BLNPI, first-generation and transfer-student status? 
3. Does sense of belonging correlate with student outcomes such as course pass rates, rates of retention between courses, overall course grades and final exam scores in computing courses? 

### Methods
- Summed the Likert-scaled ratings in the survey
- Normalized the sense of belonging scores, overall course grades, and final exam scores via z-score per course. (Normalizing the data is especially important as students sense of belonging may vary by course and in the case of student grades and final exam scores, not all courses or course offerings are equally difficult.) 
- Found that their data was not normally distributed, and thus applied non-parametric tests (Mann-Whitney U tests instead of independent sample t-tests, Wilcox signed-rank tests instead of paired t-tests, and Spearman correlations instead of Pearson correlations). 
- Due to the large number of statistical tests run during their analysis, adjusted p-values to account for increased chance of Type I errors using the Holm-Bonferroni adjustment method
For RQ3:
- Used logistic regression with Holm-Bonferroni-adjusted p-values; independent variable was the sense of belonging score, dependent variable was a binary measure of whether the student passed the course
- Also ran it with independent variables of sense of belonging, gender, BLNPI, first generation and transfer status

### Results
- Found the most robust differences by gender and first generation status
	- Due to this finding, they looked at the intersectionality of gender with first generation status to see if the effect is compounded for first generation women, and found that it was
- Found mixed results by race/ethnicity 
- Found that sense of belonging and gender was predictive of pass rates
- Found that sense of belonging was correlated with student course grades

---
## [[10-19 Personal Management/13 Working/13.05 SIGCSE 2024/Mooney and Becker 2020; Sense of Belonging - The Intersectionality of Self-Identified Minority Status and Gender in Undergraduate Computer Science Students\|Mooney and Becker 2020; Sense of Belonging - The Intersectionality of Self-Identified Minority Status and Gender in Undergraduate Computer Science Students]]

### Defining sense of belonging
- Sense of belonging has been described as “one’s personal belief that one is an accepted member of an academic community whose presence and contributions are valued”. 

### Research topic
- The relationship between undergraduate computer science students' sense of belonging, gender identity, and self-declared minority status 

### Methods
- Belongingness was measured as the sum of positively framed question scores minus the sum of negatively-framed question scores
- Imputed missing values with the mean Likert score for the question

### Results
- Identifying as a woman and as a minority are weakly correlated with belief that success in CS depends on inherent ability
- Participation in networking/mentoring/outreach activities had a very weak correlation with belongingness
- Belongingness is not significantly lower in self-identified male minorities (compared to males that did not self-identify as a minority), but was significantly lower in self-identified female minorities.
- Prior experience with computing appeared to have a positive impact on male, but not female, student belongingness. 

 ![[00-09 Meta/01 Assets/mooneySenseBelongingIntersectionality2020/image-3-x45-y70.png \| 300]]
 
  ![[00-09 Meta/01 Assets/mooneySenseBelongingIntersectionality2020/image-4-x36-y283.png \| 300]]

---
## [[10-19 Personal Management/13 Working/13.05 SIGCSE 2024/Moudgalya et al. 2021; Students' Sense of Belonging in Introductory CS Courses\|Moudgalya et al. 2021; Students' Sense of Belonging in Introductory CS Courses]]

### Defining sense of belonging
- The authors define sense of belonging as "the feeling of fitting in or being an integral part of an environment".

### Research questions
This study was threefold: the authors 
1. presented a factor analysis of a 30-item survey to measure sense of belonging in CS,
2. studied how students' sense of belonging using the survey correlated to their learning and interest to pursue more CS, and
3. studied differences in sense of belonging between Process Oriented Guided Inquiry Learning (POGIL) classrooms and non-POGIL classrooms. 

### Methods
- Correlational analysis; Fisher r-to-z transformation to determine if two correlation coefficients were significantly different

### Results
- Table 3: All individual factors correlated with each other, and with students' interest to pursue CS and their learning assessments.
 ![[00-09 Meta/01 Assets/moudgalyaMeasuringStudentsSense2021/image-4-x62-y415.png \| 300]]
- Table 4: Sense of belonging seemed to correlate more strongly (based on Fisher r-to-z transformation) with the interest to pursue CS for both Black and Latinx students compared to Asian students. However, sense of belonging scores were not significantly correlated with learning assessment scores for race and ethnically minoritized students.
![[00-09 Meta/01 Assets/moudgalyaMeasuringStudentsSense2021/image-5-x46-y323.png \| 300]]

---
## [[10-19 Personal Management/13 Working/13.05 SIGCSE 2024/Moya et al. 2023; "I Can Do That Too" - Factors Influencing a Sense of Belonging for Females in Computer Science Classrooms\|Moya et al. 2023; "I Can Do That Too" - Factors Influencing a Sense of Belonging for Females in Computer Science Classrooms]]

### Defining sense of belonging
- A common definition of school belonging for students is "the extent to which they feel personally accepted, respected, included, and supported by others - especially teachers and other adults in the school environment".

### Research questions
1. How do student experiences in, and perceptions of, high school computer science courses vary by gender? 
2. What are the factors that influence students' sense of belonging in these courses? 

### Methods 
- Mixed methods convergent design procedure
- Quantitative: two-sample t-tests to compare male and female students; paired sample t-tests for pre- and post-surveys
- Qualitative: phenomenological approach

### Results
- Relationships: females were very satisfied with their relationships with their teachers in these courses, which is also correlated with a sense of belonging at the classroom level
- Efficacy: The survey data shows many impacts on students’ perceptions of efficacy in computing, with evidence that the course reduced female and male gender gaps for this variable. 
- Sense of belonging: Female responses to questions associated with a sense of belonging point to some of the challenges for females in developing a sense of fit to the field of computer science. 
- Several factors, including quality relationships with teachers, collaborative work environments, and equity-minded curriculum contributed to females’ sense of belonging in the courses.

---
## [[10-19 Personal Management/13 Working/13.05 SIGCSE 2024/Veilleux et al. 2013; The relationship between belonging and ability in computer science\|Veilleux et al. 2013; The relationship between belonging and ability in computer science]]

### Research questions 
- What is the relationship between a sense of belonging and a student's assessment of their own ability to perform in a given field? 

### Methods
