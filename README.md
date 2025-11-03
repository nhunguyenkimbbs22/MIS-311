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

a. Missing values

The dataset contained a total of 6 missing values including 4 in the Average Score column and 3 in the Parental level of education column. However, since 3 parental missing values were duplicated, only 2 unique missing values needed to be handled.
- For the missing values in Average Score, by analyzing the existing data, I noticed that Average Score was calculated as Total Score ÷ 3, so I used this formula to fill the missing values:
<img width="1608" height="412" alt="image" src="https://github.com/user-attachments/assets/efe5c56f-4b08-4aab-8852-310272a45a1a" />

- For the missing values in Parental level of education, I used a Pivot Table to summarize and count the frequency of each category in the Parental level of education column. This helped identify that “associate’s degree” was the most common value. 
<img width="550" height="368" alt="image" src="https://github.com/user-attachments/assets/e260d133-49d3-41ba-83b6-16770748b7e1" />


-> Therefore, the missing entries were filled with “associate’s degree.”

<img width="1610" height="388" alt="image" src="https://github.com/user-attachments/assets/471846b5-c05d-4913-a70f-e7989806f7f5" />

b. Duplicate rows

I found three duplicate rows in the dataset and removed them to keep the data accurate and unbiased. 
<img width="514" height="490" alt="image" src="https://github.com/user-attachments/assets/b4ce87e6-c6ff-4194-850b-2dcef7c8795f" />

3. Descriptive Statistics

<img width="1090" height="242" alt="image" src="https://github.com/user-attachments/assets/e5e357ee-1a5c-4ee7-9d97-e2757ad4b93e" />
<img width="1006" height="584" alt="image" src="https://github.com/user-attachments/assets/9c05f746-6290-4e7f-8495-4fe47c057976" />

The chart shows that ethnic background appears to influence student performance. Students from Group D and Group E consistently outperform those from other groups, achieving the highest average scores in all three subjects, especially in Math (70.96) and Reading (71.30). 

In contrast, Group A shows the lowest overall results, indicating possible disparities in learning outcomes. Overall, the data highlights that students’ ethnic backgrounds have a considerable impact on their learning outcomes. Differences in performance emphasize the need for better educational strategies to support all groups equally.

Besides ethnic background, gender differences can provide further insight into how demographic factors influence students’ math performance.

<img width="550" height="308" alt="Ảnh màn hình 2025-11-03 lúc 10 36 15" src="https://github.com/user-attachments/assets/67f1fb99-6118-4092-b484-3415cac061c6" />

The mean math score of female students (64.86) is slightly higher than that of male students (63.57). This means that, on average, female students perform a bit better in math than males. Although the difference is small, it may indicate that females have slightly stronger or more stable learning outcomes in mathematics.

Meanwhile, when looking at the variance in sccores, the standard deviation is higher for males (16.22) than for females (15.64), showing that male students’ scores are more spread out. Some male students perform very well, while others score much lower. Female students, on the other hand, have more consistent results, with most scores staying close to the average.




