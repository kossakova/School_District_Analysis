# School District Analysis
In this module we worked with Maria, the chief scientist for city schools. 
We were responsible for preparing all standardized test data for analysis to provide insights about performance trends and patterns. 


### Resources 
- Jupiter Notebook
- Pandas library 
- Anaconda extension
- Python Software


# Overview
We were given a task to analyze data on students standardized test scores for School District to determine each school’s performance and budget distribution. 
We provided analysis for following objects:

- School budget 
- Per student budget 
- Math scores 
- Reading scores 
- Per subject passing scores percentage 
- Overall passing percentage  

After conducting all analysis, we discovered the data file that we worked with had shown evidence of academic dishonesty, specifically reading and math grades for Thomas High School ninth graders. Therefore, we cleaned the data so that wholesome analysis can be provided without missing value and keeping rest of the data intact.


# Results
In this analysis we performed following tasks:
- Generated the school District Summary 
- Generated the School Summary 
- Identified Hing performing Schools
- Identified Low performing schools 
- Calculated Math and Reading scores by grade 
- Grouped Scores by School Spending per Student
- Grouped Scores by School size
- Grouped scores by School type 


### District Summary 
Here we have two different analysis outputs for the original data which includes Thomas High School ninth grade data, and second output which excludes Thomas High School. Our analysis did not have many differences since the number of students we excluded was not significant comparing to a total of 39170 students in all of the Student District.

- Therefore, Average Math Score dropped 0.1 %
- Average Reading Score has not changed.
- Passing Math Percentage has dropped 0.2 %
- Passing Reading Percentage had dropped only 0.1 %
- Overall Parring Percentage had major decrease of 0.3 %

![Org_DistrictlSummary](https://github.com/kossakova/School_District_Analysis/blob/main/Analysis%20Images/Org_DistrictSummary.png)


![New_DistrictlSummary](https://github.com/kossakova/School_District_Analysis/blob/main/Analysis%20Images/New_DistrictlSummary.png)


### School Summary 
Along with District Summary our school summary was not impacted significantly. 


![school_summary_before](https://github.com/kossakova/School_District_Analysis/blob/main/Analysis%20Images/school_summary_before.png)


![school_summary_after](https://github.com/kossakova/School_District_Analysis/blob/main/Analysis%20Images/school_summary_after.png)

The first image represents an original analysis that includes ninth grade students' reading and math grades. As shown above in the following images, there were no significant differences to overall performance relative to other schools. Before and after removing the ninth grade students’ data, Thomas High School still remained the second school in the district. 

There were no significant data alterations relatively to math and reding scores as performance scores and percentages were dropped less than 1%. 
Therefore, as we replaced ninth grade students scores with NaN, those students were still counted, and changes did not affect total school or per student budgets. 


# Summary
As a result of potential academic dishonesty, we had removed 461 ninth grade students from the Thomas High School from the dataset. Despite all changes to the original dataset,  it had a modest impact on overall analysis results. In addition, changes were not significant enough to change Thomas High School performance as it remaned second in the district. 

