# School_District_Analysis
Challenge Week 4. Working with Pandas & Jupiter notebook.

## Overview of the school district analysis
  We started  with the Data Analytics team in a study about the Results of the Proficiency Standard Test for Math and Reading in the High Schools of the area. We got the performance of the School based on its budget, its population and the type of School, in order to help the School Board in making decisions.
  Subsequently, based on a report of academic dishonesty in the 9th grade of the Thomas High School, we have been asked to repeat the previous analysis and determine how much the firts results were affected with this new conditions.
  
## Results: 

For this proyect, we taked the information from two data files, one with all the data for the School and other with the results of the Profiency Tests: Schools_complete.csv and Students_complete.csv. For the analysis,   I used Pandas DataFrames.

First, I discard the THS 9th grade results in Math and Reading in order to begin tne analysis. I did it replacing the grades with NaN.

<img width="997" alt="ReplaceScores" src="https://user-images.githubusercontent.com/102195803/165669021-008c9106-07b4-40f0-9f9c-63aa19487019.png">

### Resulting DataFrame 

<img width="500" alt="THS 9th_replacedscores" src="https://user-images.githubusercontent.com/102195803/165583518-e8c2e7a7-3d02-4dfe-8225-b7fc7a5f495f.png">

From these new data, I repeated the analysis of the schools performance in Reading and Math to determine how the data previously replaced affects the past results.   

### How is the district summary affected? 
  In general, The District Summary was little affected. The **Avergage Reading Score** remains equal, but the **Average Math Score**, the **% Passing Math** an % **Passing Reading** and the **% Overall Passing** decreased less tha 0.2%.
 
 *New District Summary* 
<img width="551" alt="DistrictSummary_DF" src="https://user-images.githubusercontent.com/102195803/165670662-25160a3b-539d-4dde-899b-97954d52705a.png">

  <img width="560" alt="District_Summary_THSreplaced" src="https://user-images.githubusercontent.com/102195803/165587841-336755cd-1340-4e93-a609-9e3e7878f22f.png">

### How is the school summary affected
In this case the Thomas High School results were little affected. Math & Reading Averages had an imperceptible decrease, but the Reading Passing Percentages decreased 0.3%. But, although 9th grade results oh the THS were not considered, the performance of the 10th-12th grades are outstanding, so it permited Thomas High School remains among the the Top 5 Schools of the District. 

*New School Summary*
<img width="535" alt="SchoolSummary_DF" src="https://user-images.githubusercontent.com/102195803/165669852-29b58565-69a4-40d1-a165-abe670ca55d1.png">

 <img width="600" alt="SchoolSummary_without 9th grade THS" src="https://user-images.githubusercontent.com/102195803/165654939-94a0bd88-e63d-42bc-9838-1aaa041b3e84.png">

### How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?
It did not affect, because the THS remains en the second place betweeen the Top 5 Schools of the district. The average remains almmost the same. 
*Top 5 Schools of the Area*
<img width="1008" alt="Top5_schools_comparison" src="https://user-images.githubusercontent.com/102195803/165642154-68c57b71-4411-456b-ae93-708ee69299c1.png">

### How does replacing the ninth-grade scores affect the following:
### -Math and Reading Scores by Grade
As the only grade modified was the 9th of the THS, it was the only affected. The average for Math and Reading scores of the other grades did not have changes.

<img width="818" alt="GradeSeries" src="https://user-images.githubusercontent.com/102195803/165669949-74176c0d-8a29-490a-862b-0cf23962761c.png">

### Average Math Score

The Average Math Score did not change. 
<img width="313" alt="AverageMathScoresB" src="https://user-images.githubusercontent.com/102195803/165659302-c93cb0d8-019f-48b3-a51b-1e0dcb7165c2.png"> 

### Average Reading Score 
The change in this Score was imperceptible, it decreased a 0.06% 
<img width="329" alt="AverageReadingbyGradeB" src="https://user-images.githubusercontent.com/102195803/165659327-efbaf6dd-0552-4e2e-afb4-86bb6e3fa183.png">

### -Scores by school spending 
As in the other cases, this table generally does not change substantially: THS continues in the same Spending Budget per Student range because the school's budget and the number of students remain the same, but the averages and percentages are modified. in the same way as in the previous cases.
<img width="870" alt="Spending RangesB" src="https://user-images.githubusercontent.com/102195803/165650122-73bb7111-3a2b-4e18-b03e-587a1717f1b6.png">

### -Scores by school size
Just like the previous one, the Score by School Size remains unchanged.
<img width="792" alt="Score by School Size" src="https://user-images.githubusercontent.com/102195803/165650085-e2b88279-b7fa-47a1-a7b4-c3bcc13b31ef.png">

### -Scores by school type.
This data remain unchanged.
<img width="716" alt="SchoolTypeB" src="https://user-images.githubusercontent.com/102195803/165650160-e5c8bfc5-7ea3-492d-a764-b377f3dab286.png">

## Summary: 
Summarize four changes in the updated school district analysis after reading and math scores for the ninth grade at Thomas High School have been replaced with NaNs.
A case as this, when one grade complete is isoleted, could affect the performance of its school. A small school could be serious affected for something like this. But in the case, the Thomas High School is a medium size that was one of the top 5 schools in the district, and the replace scores did not affected so much. The **Average Math Score**, **Average Reading Scores**, **% Passing Math**, **% Passing Reading**  and **%Overall passing*. 

