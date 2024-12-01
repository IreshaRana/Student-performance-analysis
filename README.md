# Student-performance-analysis-dashboard
## Background
I conducted a project, as a vonluntary effort during my university teaching role, to analyse student performance of a course, with the aim of improving teaching and learning activities. With the insights from this analysis I was able to provide recommendations for the course coordinator, on which areas to improve. 
As the original project cannot be shared owing to confidentiality, I tried to replicate it.

## Project goal, objectives and deliverables
Goal: 
- Provide recommendations to improve teaching and learning activities of this particular course.  
Objectives:
- Analyze patterns in student performance, online engagement and enrolement data.
- Identify factors influencing success or underperformance.
- Visualize insights to share with stakeholders (course coordinator, program lead).
Deliverables:
- Key statistics and insights about the students.
- A dashboard that allows interactive exploration of the data.

## Data
I generate a synthetic data set for this project, as the original data is confidential.
Student performance data:
1.	Student ID: Unique identifier for each student (e.g., S001, S002, ..., S790).
2.	Program Code: values from 1 to 15 (representing different programs).
3.	Assessment scores: Scores for the assessments, calculated as per the weights (15% for the quiz, 35% for the written assessment, 35% for the group project, and 15% for the reflective piece).
4.	Final Score: Weighted average of the assessments
Online engagement (with the university Learning Management System or the LMS) data:
5. Log-in Frequency: number of times per week
6. Session Duration: time spent on LMS per week
Enrolment data:
8.	Enrollment Status: Full-time or Part-time

## Data preparation

In the original project, 
- I had to merge data files.
  - I retrieved student performace data, student engagement data and enrolment data from 3 different sources and merged them together.
  - There were data mismatches between the datasets, so only the students who had a live enrolment status (fulltime or parttime) were included in the final analysis.
- I conducted some data manimupations.
-   The log-in frequency and session durations data were in a log fie. I manilupated the data so that I could get an average per week value for the duration of the semester.
  
In this project, 
- A synthetic dataset was generated to closely resemble the original merged dataset.
  - Similar variables and number of students) with a sinthetic dataset.
  - I also did some backward engineering so that the nature of the dataset is also similar to the original one (so that I gain similar insights).
 
## Analysis
The analysis was conducted in the following areas:
- Assessment scores distribution
- Session duration over final scores
- Enrolment status vs. final scores
- Program code vs. grades

Code:
Technologies used:


## Conclusions and Recommendations
- 
- 
### Next steps
- Analyse student enagement throughout the semster, so that timely interventions (e.g. reminders, announcements) can be made to increase student enagement.
- Set metrices for next course offering and monitor the progress. 


