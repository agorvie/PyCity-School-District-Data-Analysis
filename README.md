# PyCity School District Data Analysis

## Table of Contents
1. [Background](#background)
2. [Instructions](#instructions)
3. [District Summary](#district-summary)
4. [School Summary](#school-summary)
5. [Highest-Performing Schools (by % Overall Passing)](#highest-performing-schools)
6. [Bottom Performing Schools (By % Overall Passing)](#bottom-performing-schools)
7. [Math Scores by Grade](#math-scores-by-grade)
8. [Reading Scores by Grade](#reading-scores-by-grade)
9. [Scores by School Spending](#scores-by-school-spending)
10. [Scores by School Size](#scores-by-school-size)
11. [Scores by School Type](#scores-by-school-type)
12. [Analysis Conclusion](#analysis-conclusion)
13. [References](#references)

---

### 1. Background<a name="background"></a>
Welcome to the PyCity Schools Data Analysis Project. The task is to aggregate the School Districts data to showcase obvious trends in school performance.  The data contains district-wide standardized test results including every student's math and reading scores, as well as various information on the schools they attend. The results of the analysis will be helping the school board and mayor make strategic decisions regarding future school budgets and priorities.

### 2. Instructions<a name="instructions"></a>

Using Pandas and Jupyter Notebook, I will create a report that includes the following data. The report will include a written description of observable trends based on the data.

### 3. District Summary<a name="district-summary"></a>

Calculate and display the following district-level statistics:

- Total number of unique schools
- Total number of students
- Total budget
- Average math score
- Average reading score
- Percentage of students who passed math (math scores greater than or equal to 70%)
- Percentage of students who passed reading
- Percentage of students who passed both math and reading

<img width="446" alt="image" src="https://github.com/agorvie/pandas-challenge/assets/122469792/51331f91-ec2c-42dc-b843-5827f5d5df5b">

### 4. School Summary<a name="school-summary"></a>

Calculate and display the following statistics for each school:

- School type
- Total student count
- Total school budget
- Per student budget
- Average math score
- Average reading score
- Percentage of students who passed math
- Percentage of students who passed reading
- Percentage of students who passed both math and reading

<img width="277" alt="image" src="https://github.com/agorvie/pandas-challenge/assets/122469792/2be62c9d-cb3f-46c4-abb5-b49a275b84c7">

### 5. Highest-Performing Schools (by % Overall Passing)<a name="highest-performing-schools"></a>

Sort the schools by % Overall Passing in descending order and display the top 5 performing schools.

<img width="445" alt="image" src="https://github.com/agorvie/pandas-challenge/assets/122469792/7c0e37b8-61c3-435b-a7db-4a5b354f93b8">

### 6. Bottom Performing Schools (By % Overall Passing)<a name="bottom-performing-schools"></a>

Sort the schools by % Overall Passing in ascending order and display the bottom 5 performing schools.

<img width="446" alt="image" src="https://github.com/agorvie/pandas-challenge/assets/122469792/e6c03ce8-cc4d-440b-9331-d8d672dde109">

### 7. Math Scores by Grade<a name="math-scores-by-grade"></a>

Display the average math scores for students of each grade level (9th, 10th, 11th, 12th) at each school.

### 8. Reading Scores by Grade<a name="reading-scores-by-grade"></a>

Display the average reading scores for students of each grade level (9th, 10th, 11th, 12th) at each school.

### 9. Scores by School Spending<a name="scores-by-school-spending"></a>

Group schools into spending ranges per student and calculate the following statistics:

- Average math score
- Average reading score
- Percentage of students passing math
- Percentage of students passing reading
- Overall passing rate

<img width="436" alt="image" src="https://github.com/agorvie/pandas-challenge/assets/122469792/13db085e-e2a3-46af-919c-dfe804df75df">

### 10. Scores by School Size<a name="scores-by-school-size"></a>

Group schools by size (small, medium, large) based on the total number of students and calculate the following statistics:

- Average math score
- Average reading score
- Percentage of students passing math
- Percentage of students passing reading
- Overall passing rate

<img width="403" alt="image" src="https://github.com/agorvie/pandas-challenge/assets/122469792/137d7da5-96a0-4573-931e-0f212edb15fb">

### 11. Scores by School Type<a name="scores-by-school-type"></a>

Group schools by type (charter or district) and calculate the following statistics:

- Average math score
- Average reading score
- Percentage of students passing math
- Percentage of students passing reading
- Overall passing rate
  
<img width="428" alt="image" src="https://github.com/agorvie/pandas-challenge/assets/122469792/5e921370-d522-40dc-afd6-9716f8b90372">

## Analysis Conclusion

* The data reveals that, on the whole, smaller populated schools, predominantly Charter Schools, outperformed their larger populated counterparts, which were Public District schools. Although the Charter Schools exhibited superior performance across all categories examined when compared to the District Public schools, it is important to note that the sample size of the data may not be sufficient to establish a definitive conclusion regarding their academic superiority.

* The correlation between school funding and academic performance was found to be inconclusive, as per the spending summary analysis.
Surprisingly, students with lower per student budgets exhibited superior performance compared to those with larger per student budgets. This finding highlights the need for decision makers to consider not just the amount of funds allocated to schools, but also how those funds are utilized to achieve desired outcomes. Merely spending more per student does not guarantee success or excellence. It underscores the importance of prudent budget utilization to optimize educational outcomes.

* Moreover, the analysis of school data indicates that students, on average, are performing significantly better in Reading as compared to Math. Across all categories, students achieved higher scores in Reading, suggesting that Math may be perceived as more challenging. This underscores the need for increased emphasis on promoting Math excellence through enhanced encouragement and additional resources to foster proficiency in this subject area.

## References
Data generated by Mockaroo, LLCLinks to an external site., (2022). Realistic Data Generator. Data for this dataset was generated by edX Boot Camps LLC, and is intended for educational purposes only.
