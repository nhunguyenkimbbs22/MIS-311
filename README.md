# MIS-311
1. Data Overview

This dataset contains detailed information on students’ academic performance and demographic background. It is designed to explore how factors such as gender, race/ethnicity, and parental education relate to students’ achievement in Math, Reading, and Writing.
<img width="1508" height="458" alt="image" src="https://github.com/user-attachments/assets/5dafc9c1-3615-4a36-b76e-f5fc2c39921d" />
<img width="1512" height="396" alt="image" src="https://github.com/user-attachments/assets/955b8679-7370-4497-883d-3f4eed084621" />
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
The dataset was compiled from student assessment data and serves as a resource for educational research and statistical analysis. It can be used to perform descriptive analytics, correlation, and regression analysis to identify relationships between background factors and student outcomes.
2. Data Cleaning

The dataset contained a total of 6 missing values including 4 in the Average Score column and 3 in the Parental level of education column. However, since 3 parental missing values were duplicated, only 2 unique missing values needed to be handled.
- For the missing values in Average Score, they were calculated using the formula:
<img width="1608" height="412" alt="image" src="https://github.com/user-attachments/assets/efe5c56f-4b08-4aab-8852-310272a45a1a" />
- For the missing values in Parental level of education, a Pivot Table analysis showed that “associate’s degree” was the most common value.
<img width="550" height="368" alt="image" src="https://github.com/user-attachments/assets/e260d133-49d3-41ba-83b6-16770748b7e1" />

- Therefore, the missing entries were filled with “associate’s degree.”
<img width="1610" height="388" alt="image" src="https://github.com/user-attachments/assets/471846b5-c05d-4913-a70f-e7989806f7f5" />



