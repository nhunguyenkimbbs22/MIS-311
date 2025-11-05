# MIS-311
**1. Data Overview**

This dataset contains detailed information on students’ academic performance and demographic background. It is designed to explore how factors such as gender, race/ethnicity, and parental education relate to students’ achievement in Math, Reading, and Writing.

<img width="1508" height="458" alt="image" src="https://github.com/user-attachments/assets/5dafc9c1-3615-4a36-b76e-f5fc2c39921d" />

The dataset consists of 203 rows and 8 columns, where each row represents a single student record.
The variables included are:
  - Gender
  - Race/Ethnicity 
  - Parental Level of Education
  - Math Score
  - Reading Score
  - Writing Score
  - Total Score
  - Average Score

The dataset was compiled from student assessment data and serves as a resource for educational research and statistical analysis.

**2. Data Cleaning**

**a. Missing values**

The dataset contained a total of 6 missing values including 4 in the Average Score column and 3 in the Parental level of education column. However, since 3 parental missing values were duplicated, only 2 unique missing values needed to be handled.
- For the missing values in Average Score, by analyzing the existing data, I noticed that Average Score was calculated as Total Score ÷ 3, so I used this formula to fill the missing values:
<img width="1608" height="412" alt="image" src="https://github.com/user-attachments/assets/efe5c56f-4b08-4aab-8852-310272a45a1a" />

- For the missing values in Parental level of education, I used a Pivot Table to summarize and count the frequency of each category in the Parental level of education column. This helped identify that “associate’s degree” was the most common value.

  <img width="383" height="177" alt="Ảnh màn hình 2025-11-05 lúc 09 30 05" src="https://github.com/user-attachments/assets/6df80afc-1374-4462-9db1-1e61d17684c8" />
 

- Therefore, the missing entries were filled with “associate’s degree.”

  <img width="1610" height="388" alt="image" src="https://github.com/user-attachments/assets/471846b5-c05d-4913-a70f-e7989806f7f5" />

**b. Duplicate rows**

I found three duplicate rows in the dataset and removed them to keep the data accurate and unbiased. 
  <img width="514" height="490" alt="image" src="https://github.com/user-attachments/assets/b4ce87e6-c6ff-4194-850b-2dcef7c8795f" />

**3. Descriptive Statistics**

**Insight 1** - Average Subject Scores by Ethnic Groups

<img width="567" height="293" alt="image" src="https://github.com/user-attachments/assets/f827536e-05c9-46c8-8f12-3a5f334982b6" />

<img width="438" height="106" alt="image" src="https://github.com/user-attachments/assets/abdc222f-51dc-4348-9e9d-269095efc0f8" />



The chart shows that ethnic background appears to influence student performance. Students from Group D and Group E consistently outperform those from other groups, achieving the highest average scores in all three subjects, especially group E with Math (70.96) and Reading (71.30). 

In contrast, Group A shows the lowest overall results, indicating possible disparities in learning outcomes. Overall, the data highlights that students’ ethnic backgrounds have a considerable impact on their learning outcomes. Differences in performance emphasize the need for better educational strategies to support all groups equally.

**Insight 2** - Average of Total Score by Parental Level of Education

<img width="529" height="314" alt="image" src="https://github.com/user-attachments/assets/219b8b01-86dd-4a75-a9aa-a3643e0d88e6" />


The chart presents a clear positive relationship between parental education level and students’ average total scores. Students whose parents have higher education, such as a bachelor’s or master’s degree, achieve the highest averages of 219.10 and 216.82, showing strong academic performance. Those whose parents completed some college or hold an associate’s degree have moderate scores, 203.10 and 195.61. 

In contrast, students whose parents only finished high school or some high school have much lower averages of 186.87 and 181.39. This indicates that parents’ higher education levels may provide better academic support, motivation, or learning environments for their children, leading to higher student achievement.

**Conclusion** : 

In conclusion, the data highlights important patterns in student performance and helps identify which areas need more support or improvement. For educators or policymakers, the focus should be on how the data can guide actions to improve student learning outcomes and create a more effective learning environment for all students.




