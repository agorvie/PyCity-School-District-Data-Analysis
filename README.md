
# PyCity-School-District-Data-Analysis

## Table of Contents
1. [Introduction](#introduction)
2. [Dependencies and Setup](#dependencies-and-setup)
3. [Data Loading and Preparation](#data-loading-and-preparation)
4. [District Statistics Summary](#district-statistics-summary)
    * 4.1 [Gender-Based Analyses](#gender-based-analyses)
5. [School Performance Analyses](#school-performance-analyses)
	* 5.1 [School Budget Analysis](#school-budget-analysis)
	* 5.2 [School Summary](#school-summary)
	* 5.3 [Highest-Performing Schools and Bottom-Performing Schools](#highest-performing-schools-and-bottom-performing-schools)
	* 5.4 [Math Scores by Grade and Reading Scores by Grade](#math-scores-by-grade-and-reading-scores-by-grade)
6. [School Spending vs Student Performance Analysis](#school-spending-vs-student-performance-analysis)
7. [School Size Analysis](#school-size-analysis)
8. [School Type Analysis](#school-type-analysis)
9. [Correlation Analysis](#correlation-analysis)
10. [Analysis Conclusion](#analysis-conclusion)
11. [References](#references)


## Introduction
Welcome to the PyCity School District Data Analysis Project. The task is to aggregate the School Districts data to showcase obvious trends in school performance.  The data contains district-wide standardized test results including every student's math and reading scores, as well as various information on the schools they attend. The results of the analysis will be helping the school board and mayor make strategic decisions regarding future school budgets and priorities.

## Dependencies and Setup
To run this project, you need to have the following Python libraries installed:

*  pandas
*  matplotlib
*  seaborn
*  numpy
*  plotly.express
  
You can install these libraries using pip:

Copy code:

'pip install pandas matplotlib seaborn numpy plotly'

The project also relies on two CSV files for data: "schools_complete.csv" and "students_complete.csv" located in the "Resources" directory.

### Data Loading and Preparation
The project begins by loading and preparing the data. It reads the school and student data from the CSV files and merges them into a single dataset called PyCitySchools_df.

<img width="433" alt="image" src="https://github.com/agorvie/PyCity-School-District-Data-Analysis/assets/122469792/19a34cc6-e819-4d52-ae08-80e4b6e58d24">

### District Statistics Summary
This section of the project focuses on calculating various statistics related to the district's performance. It includes calculations for the total number of unique schools, total number of students, and statistical measures (mean, median, and standard deviation) of reading and math scores. Visualizations like violin plots are used to visualize the distribution of scores.

![image](https://github.com/agorvie/PyCity-School-District-Data-Analysis/assets/122469792/1cd2f01e-c378-403d-9dba-f422d57674a4)

![image](https://github.com/agorvie/PyCity-School-District-Data-Analysis/assets/122469792/c1297a29-dae2-4cb6-a221-f15e129d0a6b)



#### Gender-Based Analyses
The project analyzes gender-based differences in student performance, calculating average scores by gender and visualizing them using bar plots. Pass rates for reading and math are also calculated and visualized by gender.

![image](https://github.com/agorvie/PyCity-School-District-Data-Analysis/assets/122469792/7ed50c1e-8094-4054-8aa7-0eb0bb831ea5)

![image](https://github.com/agorvie/PyCity-School-District-Data-Analysis/assets/122469792/f87c76e0-87ae-4126-b0d1-c6b30c611556)

### School Performance Analyses
This section explores how student performance varies by grade level and calculates school performance metrics based on average scores and budget per student. The schools are ranked accordingly, and a comparison of school performance is visualized.

![image](https://github.com/agorvie/PyCity-School-District-Data-Analysis/assets/122469792/23e474a5-0001-4346-966c-a6f53d7a4ef8)

#### School Budget Analysis
Here, the project calculates the total budget and explores the relationship between school budget and student performance in both reading and math. The performance of district schools vs. charter schools is also compared.

![image](https://github.com/agorvie/PyCity-School-District-Data-Analysis/assets/122469792/0acf3fcb-fbc7-44ac-bfdd-07e8fa9ecb60)

![image](https://github.com/agorvie/PyCity-School-District-Data-Analysis/assets/122469792/9c372866-06ff-414e-9535-8ddc3f1ded80)


#### School Summary
This section provides a summary of school performance metrics, including average math and reading scores, percentage of students passing math and reading, and overall passing rates. It also includes a pie chart showing the distribution of students among schools and other key metrics.

![image](https://github.com/agorvie/PyCity-School-District-Data-Analysis/assets/122469792/b49c9c2c-09e8-4ddd-ad28-70d1693ab468)

#### Highest-Performing Schools and Bottom-Performing Schools
The project identifies and presents the highest-performing and bottom-performing schools based on overall passing rates.

#### Math Scores by Grade and Reading Scores by Grade
These sections analyze math and reading scores by grade level, providing insights into how student performance changes as they progress through different grades.

![image](https://github.com/agorvie/PyCity-School-District-Data-Analysis/assets/122469792/a2808a7e-f052-40b7-bd7d-77371dc97f2e)

![image](https://github.com/agorvie/PyCity-School-District-Data-Analysis/assets/122469792/1b70c521-ef24-4559-8fd1-5f586f363e98)

#### School Spending vs Student Performance Analysis
The project investigates the relationship between school spending per student and student performance, considering both average scores and passing rates. This analysis helps to determine if higher spending correlates with better student outcomes.

![image](https://github.com/agorvie/PyCity-School-District-Data-Analysis/assets/122469792/6f5c6e91-c9f5-4884-b397-a1eca19a811c)

#### School Size Analysis
The relationship between school size and student performance is explored, looking at average scores and passing rates in relation to school size.

![image](https://github.com/agorvie/PyCity-School-District-Data-Analysis/assets/122469792/93d10cae-1dd3-4562-bb77-35294ca9dce1)

#### School Type Analysis
This section compares average reading and math scores by school type (district or charter schools) to identify if school type has an impact on student performance.

![image](https://github.com/agorvie/PyCity-School-District-Data-Analysis/assets/122469792/f44f963d-9fab-4692-bcb9-069df2025f9f)

#### Correlation Analysis
The project concludes with a correlation analysis, exploring relationships between various variables in the dataset. A heatmap is used to visualize these correlations, and their interpretations are provided.

![image](https://github.com/agorvie/PyCity-School-District-Data-Analysis/assets/122469792/33b7ccf5-6622-438a-9049-5e893060f28d)

Please refer to the specific sections in the project code for detailed implementations of each analysis and visualization. Enjoy exploring the insights from the PyCitySchools project!

## Analysis Conclusion

* The data reveals that, on the whole, smaller populated schools, predominantly Charter Schools, outperformed their larger populated counterparts, which were Public District schools. Although the Charter Schools exhibited superior performance across all categories examined when compared to the District Public schools, it is important to note that the sample size of the data may not be sufficient to establish a definitive conclusion regarding their academic superiority.

* The correlation between school funding and academic performance was found to be inconclusive, as per the spending summary analysis.
Surprisingly, students with lower per student budgets exhibited superior performance compared to those with larger per student budgets. This finding highlights the need for decision makers to consider not just the amount of funds allocated to schools, but also how those funds are utilized to achieve desired outcomes. Merely spending more per student does not guarantee success or excellence. It underscores the importance of prudent budget utilization to optimize educational outcomes.

* Moreover, the analysis of school data indicates that students, on average, are performing significantly better in Reading as compared to Math. Across all categories, students achieved higher scores in Reading, suggesting that Math may be perceived as more challenging. This underscores the need for increased emphasis on promoting Math excellence through enhanced encouragement and additional resources to foster proficiency in this subject area.

## References
Data generated by Mockaroo, LLCLinks to an external site., (2022). Realistic Data Generator. Data for this dataset was generated by edX Boot Camps LLC, and is intended for educational purposes only.
