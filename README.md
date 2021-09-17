# School_District_Analysis
In this module we worked with Maria, the chief scientist for city schools. 
We were responsible for preparing all standardized test date for analysis to provide insights about performance trends and patterns. 

## Resources 
- Jupiter Notebook
- Pandas library 
- Anaconda extension
- Python 

# Overview
We were given a task to analyze data on students standardized test scores for School District to determine each school’s performance and budget distribution. 
We provided analysis for following objects:
- School budget 
- Per student budget 
- Math scores 
- Reading scores 
- Per subject passing scores percentage 
- Overall passing percentage  

After conducting all analysis, we discovered that data file what we worked with was shown evidence of academic dishonesty, specifically, reading and math grades for Thomas High School ninth graders. Therefore, we cleaned the data so that wholesome analysis can be provided without missing value and keeping rest of the data intact.

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
Here we have two different analysis outputs for original data which includes Thomas High School ninth grade data and second which excludes Thomas High School. Our analysis did not have many differences since number of students we excluded was not significant comparing to total of 39170 students in all Student District.
![New_DistrictlSummary](https://github.com/kossakova/School_District_Analysis/blob/main/Analysis%20Images/New_DistrictlSummary.png)
![Org_DistrictlSummary](https://github.com/kossakova/School_District_Analysis/blob/main/Analysis%20Images/Org_DistrictSummary.png)


### School Summary 
Along with District Summary our school summary was not impacted significantly. 
![school_summary_before](https://github.com/kossakova/School_District_Analysis/blob/main/Analysis%20Images/school_summary_before.png)

![school_summary_after](https://github.com/kossakova/School_District_Analysis/blob/main/Analysis%20Images/school_summary_after.png)

As shown above in following images there were no significant difference to overall performance relative to other schools. 

Data alteration relativity to Math and Reding scores.
As we dropped ninth grade students scores for math and reading subjects, those students scores were replaced by NaN and were not counted. 
Therefore, school size, school type and school spending data were not affected relatively to other schools 

# Summary
As a result of potential academic dishonesty, we had removed 461 ninth grade students from Thomas school from dataset. Despite all changes to original data set it had modest impact on over all analysis results. In addition, changes were not significant enough to change Thomas High School performance as second in the district. 

