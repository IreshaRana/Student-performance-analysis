# Student Performance Analysis

## Background
As a voluntary project, I conducted a student performance analysis for a course I was teaching. The aim was to uncover insights and provide data-driven recommendations to improve student performance.

### Requirements for the Analysis:
- The course was experiencing low grades, necessitating strategies to improve grades and enhance its popularity among students.
- As the course was taken by students from various degree programs, the course coordinator sought to identify areas where additional support might be required.

Since the original project cannot be shared due to confidentiality, a synthetic dataset was generated to replicate the analysis.

---

## Project Goal, Objectives, and Deliverables  

### Goal:
- Identify areas of improvement to increase course grades.

### Objectives:
1. Analyze patterns in student performance, online engagement, and enrollment data.
2. Identify factors influencing success or underperformance.
3. Visualize insights to share with stakeholders (course coordinator, degree program leads).
4. Provide recommendations to improve teaching and learning activities.

### Deliverables:
- Key statistics and insights about student performance.

---

## Data  

**Synthetic Dataset**  
The synthetic dataset closely resembles the original merged dataset and includes the following variables:  

**Student Performance Data:**  
1. `Student ID`: Unique identifier for each student (e.g., S001, S002, ..., S480).
2. `Program Code`: Values from 1 to 15 (representing different programs).
3. `Assessment Scores`: Scores for the assessments, calculated as per the weights:  
   - Online Quiz: 15%  
   - Written Assessment: 35%  
   - Group Project: 35%  
   - Reflective Piece: 15%
4. `Final Score`: Weighted average of the assessments.
   
**Online Engagement Data:**  
5. `Log-in Frequency`: Number of log-ins per week.  
6. `Session Duration`: Time spent on the LMS per week.  

**Enrollment Data:**  
7. `Enrollment Status`: Full-time or Part-time.  

---

## Data Preparation  

### Original Project:
- **Merging Data Files:**  
   - Combined student performance, engagement, and enrollment data from three sources.  
   - Addressed data mismatches and excluded students without a live enrollment status.  
- **Data Manipulation:**  
   - Transformed log files to calculate weekly averages for log-in frequency and session duration.  

### Current Project:  
- Generated a synthetic dataset reflecting the structure and scale (~480 students) of the original data.  

---

## Data Generation and Analysis  

### Steps:
1. **Data Generation:** Created synthetic data mimicking the original dataset.  
2. **Data Exploration:** Calculated summary statistics.  
3. **Data Manipulation:** Added a `Grades` column based on final scores.  
4. **Analysis and Visualization:**  
   - Assessment scores distribution: **Box plot**.  
   - Program codes and grades: **Bar chart**.  
   - Enrollment status and grades: **Pie chart**.  
   - Session duration and final scores: **Scatter plot**.  

### Code:
Open the Jupyter Notebook: [Student_performance.ipynb](Student_performance.ipynb)  

### Technologies Used:
- **R Programming:** dplyr, tidyr, ggplot2  

---

## Conclusions and Recommendations  

### Insights from the Original Dataset:
1. **Assessment Scores:**  
   - Assessment 3B had significantly lower scores compared to other assessments.  
2. **Program-Specific Performance:**  
   - Students from certain degree programs exhibited higher failure rates.  
3. **Engagement and Performance:**  
   - Session duration had a positive correlation with final scores.  
4. **Enrollment Status:**  
   - No significant differences in grades between full-time and part-time students.  

### Recommendations:
- Provide clearer guidelines for Assessment 3B and revisit its rubric criteria.  
- Collaborate with program leads of low-performing degree programs to align the course with their objectives.  
- Encourage active engagement through reminders and interactive elements on the LMS.  

---

## Next Steps  

1. Analyze student engagement throughout the semester to enable timely interventions and improve outcomes.  
2. Set metrics for the next course offering (e.g., engagement benchmarks for the first quarter, first half, etc.) and monitor progress.  
