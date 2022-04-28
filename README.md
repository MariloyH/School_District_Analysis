# School_District_Analysis
BootCamp Week4 Working with Pandas
The analysis should contain the following:
## Overview of the school district analysis
  Previously, we supported the Data Analytics team in a study about the results of schools in the area in the Proficiency Standard Test for math and reading, based on the type of school, its population and its budget, in order to help the School Board in making decisions.
  Subsequently, based on a report of academic dishonesty in the 9th grade of the Thomas High School, we have been asked to repeat the previous analysis and determine how much the previous results are affected if we discard the results in question.
  
## Results: 
Using bulleted lists and images of DataFrames as support, address the following questions.
First, I discard the THS 9th grade results in Math and Reading in order to begin tne analysis. I did it replacing the grades with NaN.

<img width="500" alt="THS 9th_replacedscores" src="https://user-images.githubusercontent.com/102195803/165583518-e8c2e7a7-3d02-4dfe-8225-b7fc7a5f495f.png">


From these new data, I repeated the analysis of the schools performance in reading and math to determine how the results previously found were affected and how. 


<img width="560" alt="District_Summary_THSreplaced" src="https://user-images.githubusercontent.com/102195803/165587841-336755cd-1340-4e93-a609-9e3e7878f22f.png">


### How is the district summary affected? 
  In particular, the district summary was little affected. The **Avergage Reading Score** remains equal, but the **Avergae Math Score**, the **% Passing Math** an % **Passing Reading** and the **% Overall Passing** decreased less tha 0.2%.  So, in this particular case, the not considered scores were not relevant.

### How is the school summary affected
in this case, the School Summary was affected because all the permormance rates decreased, not to much, but they did it. Althougt  9th grade results oh the THS were not considered, the performance of the 10th-12th grades are outstanding, so it permited thar Thomas High School remains among the the top 5 school of the district. 

### How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?
It did not affect, because the THS remains en the second place betweeen the Top 5 Schools of the district. The average remains almmost the same. 
<img width="1008" alt="Top5_schools_comparison" src="https://user-images.githubusercontent.com/102195803/165642154-68c57b71-4411-456b-ae93-708ee69299c1.png">
How does replacing the ninth-grade scores affect the following:
### Math and reading scores by grade
In this case, the only grade affected is the 9th, which was the grade replaced.. The rest of the grades remains unchanged.

### Scores by school spending 
In this case, the Average Reading Score was almost the same, it only increased 0.05%. The other performing values decreased. The budget per student remains equal, because it only depends of the Budget per School and the Total Students number per school. 
<img width="870" alt="Spending RangesB" src="https://user-images.githubusercontent.com/102195803/165650122-73bb7111-3a2b-4e18-b03e-587a1717f1b6.png">

### Scores by school size
Just like the previous one, the Score by School size remain unchanged.
<img width="792" alt="SchoolSizeB" src="https://user-images.githubusercontent.com/102195803/165650085-e2b88279-b7fa-47a1-a7b4-c3bcc13b31ef.png">

### Scores by school type.
This data remain unchanged. It ac
<img width="716" alt="SchoolTypeB" src="https://user-images.githubusercontent.com/102195803/165650160-e5c8bfc5-7ea3-492d-a764-b377f3dab286.png">

##Summary: Summarize four changes in the updated school district analysis after reading and math scores for the ninth grade at Thomas High School have been replaced with NaNs.
A case as this, when one grade complete is isoleted, could affect the performance of all the school. A small school could be serious affected for something like this. But in the case of the Thomas High School that was one of the top 5 schools in the district, this case did no affected so much. Only the Average Math Score, Average Reading Scores and its percentages were a little affected. 

<img width="660" alt="Original_DistrictSummary" src="https://user-images.githubusercontent.com/102195803/165601474-5047450c-e8a1-4f91-ab07-f2da45127d09.png">

Deliverable 3 Requirements
Structure, Organization, and Formatting (7 points)
The written analysis has the following structure, organization, and formatting:

There is a title, and there are multiple sections (2 pt).
Each section has a heading and subheading (3 pt).
Links to images are working, and code is formatted and displayed correctly (2 pt).
Analysis (18 points)
The written analysis has the following:

Overview of the school district analysis:

The purpose of this analysis is well defined (3 pt).
Results:

There is a bulleted list that addresses how each of the seven school district metrics was affected by the changes in the data (10 pt).
Summary:

There is a statement summarizing four changes to the school district analysis after reading and math scores have been replaced (5 pt).
Submission
Once you’re ready to submit, make sure to check your work against the rubric to ensure you are meeting the requirements for this Challenge one final time. It’s easy to overlook items when you’re in the zone!

As a reminder, the deliverables for this Challenge are as follows:

Deliverable 1: Replace ninth-grade reading and math scores
Deliverable 2: Repeat the school district analysis
Deliverable 3: A written report for the school district analysis (README.md)
Upload the following to your School_District_Analysis GitHub repository:

The PyCitySchools_Challenge.ipynb file.
The Resources folder with the schools_complete.csv and students_complete.csv files.
An updated README.md that has your written analysis.
To submit your challenge assignment for grading in Bootcamp Spot, click Start Assignment, click the Website URL tab, then provide the URL of your School_District_Analysis GitHub repository, and then click Submit. Comments are disabled for graded submissions in BootCampSpot. If you have questions about your feedback, please notify your instructional staff or the Student Success Manager. If you would like to resubmit your work for an improved grade, you can use the Re-Submit Assignment button to upload new links. You may resubmit up to 3 times for a total of 4 submissions.
