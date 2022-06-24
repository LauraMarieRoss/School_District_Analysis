# School District Analysis

## Project Overview
For this project the Py City School Board requested an analysis of the math and reading scores for high school students in their district. The source data contained discrepancies in the students names, such as some students listing "Dr." or "PhD" before or after the student name, and the district requested the names be reviewed and corrected. An initial analysis was provided, however the school board was notified that math and reading grades for grade 9 students at Thomas High School were inaccurate. A revised analysis was conducted with those scores removed. 

**NOTE**: Passing scores are scores of 70 and greater.

The requested analysis included:
- A district summary with the following elements:
  - The total number of schools.
  - The total student count.
  - The total district budget.
  - Average math scores for all students.
  - Average reading scores for all students.
  - Percentage of students passing math.
  - Percentage of students passing reading.
  - Percentage of students passing reading and math.
- A summary by school (with similar elements as the district summary).
- The top 5 and bottom 5 schools by overall reading and math score performance.
- Math and reading scores by school and grade level.
- An analysis of the per-student spending and scores by spending range.
- An analysis of the scores by school size.
- An analysis of the scores by school type (district or charter).

## Resources
Data Sources: schools_complete.csv, students_complete.csv

Software: Jupyter Notebook 6.4.8, Python 3.10.5, Pandas 1.4.2, Numpy 1.21.5

## Summary

### District Analysis Results
The initial analysis, which included Thomas High School 9th grade student scores, differed only slightly from the secondary analysis where these scores were removed. 
- School District Summary Comparison:
  As seen in the table comparison below, the impact to the overall school district scores was negligible. The impact on percentage passing math scores was a 0.2% decrease, percentage passing reading resulted in a 0.1% decrease, and the overall percentage passing score resulted in a 0.3% decrease.
    ![image](https://user-images.githubusercontent.com/105830645/175464101-4f7c035b-7543-4886-b901-095e204e8593.png)
    
- School Performance Comparison:
  The initial review placed Thomas High School as second in the district for overall passing percentage.
    ![image](https://user-images.githubusercontent.com/105830645/175464277-dd4b23e0-7509-457b-b534-617ceeb97a02.png)
  Once the 9th grade students scores were removed from the analysis (and the count of students at Thomas High School adjusted when determining passing rates), Thomas High School moved to third place in the district overall.
    ![image](https://user-images.githubusercontent.com/105830645/175464293-cc4eebc0-de57-42a4-bef5-6beca74a077e.png)
    
- Average math and reading scores from Thomas high school were largely unaffected by the removal of the 9th graders from the student count (as seen in the table above).

- Math and Reading scores by grade were also unaffected with the exception of Thomas High School. (Note a null value in the place of 9th grade scores at Thomas High School in the revised tables).
    ![image](https://user-images.githubusercontent.com/105830645/175467429-d6c20ad9-5f3d-452f-8db4-7707902a8adc.png)
    ![image](https://user-images.githubusercontent.com/105830645/175467599-957160c8-62f2-48ae-a5d5-0d075bd3c3d2.png)

- Scores by school spending ranges showed few changes (two tenths of a decimal in the $631-$645 spending range).
    ![image](https://user-images.githubusercontent.com/105830645/175466021-c6a641c1-b027-4519-813c-be63e0a8dac4.png)

- Scores by school size show only one tenth of a percentage difference in medium size schools reading passing percentage.
    ![image](https://user-images.githubusercontent.com/105830645/175466397-96ebec1e-9d9e-430d-9b76-924c6ab53cc2.png)

- Scores by school type showed no changes overall.
    ![image](https://user-images.githubusercontent.com/105830645/175466615-b96b1716-418d-424d-a0b1-7159cc448cb8.png)

#### Summary of Differences
As seen in the tables above, there were few changes noted as a result of removing the 9th grade students' reading and math scores from Thomas High School to the overall school district. 
Thomas high school had slight decreases in performance as follows:
  - 0.1 decreased average reading score.
  - 0.1% decreased in percentage passing math.
  - 0.3% decrease in percentage passing reading.
  - 0.3% decrease in overall passing percentage.

The overall school district the following changes:
  - 0.2% decrease in percentage passing math.
  - 0.1% decrease in percentage passing reading
  - 0.3% decrease in overall passing percentage.
