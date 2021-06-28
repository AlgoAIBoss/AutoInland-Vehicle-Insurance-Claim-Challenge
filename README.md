# AutoInland-Vehicle-Insurance-Claim-Challenge

## Introduction


 

| Title | Text |
| ------ | ------ |
| Intro | In 2021 during three months, Nigerian car insurance company held a competition in African data science competition platform called `Zindi`. In this competition the organizer wanted to know _wheter or not a client will submit a vehicle insurance claim in the next 3 months_. In this competition 600+ competitors participated. |
| Data | The dataset consisted of Train == 12000, Test == 1200, Sample_Submition, Nigerian_State_LGA_Name. |
| Metrics | F1_score for evaluating our algorithm.|
| ML Task | Binary Classification task.|


## Problems

1. The dataset was unbalanced.
2. It had missing values in some columns.
3. `Age` column had outliers.
4. Despite distinct IDs duplicated rows existed.
5. State and LGA column names were incorrect.
6. Some duplicated rows had different target.

## Solved

1. Used resampling algorithm to oversample the minority target rows.
2. I tried to impute NaNs with Iterative-Imputer and KNN-Imputer.
3. I used absolute value of Age to fix negative values.
4. When I deleted duplicated values I got lower F1_score in public LB so I did not fix it. But in private LB I found out I should have deleted it.
5. Interestingly I used Nigerian_State_LGA_Name dataset to correct Names in LGA and State.
6. I again did not fix duplicated rows with different targets.


## Solved

1. Used resampling algorithm to oversample the minority target rows.
2. I tried to impute NaNs with Iterative-Imputer and KNN-Imputer.
3. I used absolute value of Age to fix negative values.
4. When I deleted duplvate LB I found out I should have deleted it.
5. Interestingly I used Nigerian_State_LGA_Name dataset to correct Names in LGA and State.
6. I again did not fix duplicated rows with different targets.






<br/>

<h3> 🛠 &nbsp;Tech Stack</h3>

- :space_invader:
  ![Python](https://img.shields.io/badge/Python-14354C?style=for-the-badge&logo=python&logoColor=white)
  ![POSTGRESQL](https://img.shields.io/badge/PostgreSQL-316192?style=for-the-badge&logo=postgresql&logoColor=white) 
  ![MSExcel](https://img.shields.io/badge/Microsoft_Excel-217346?style=for-the-badge&logo=microsoft-excel&logoColor=white) 
- 🌐 &nbsp;
  ![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
  ![CSS](https://img.shields.io/badge/CSS-239120?&style=for-the-badge&logo=css3&logoColor=white)
  ![JavaScript](https://img.shields.io/badge/JavaScript-323330?style=for-the-badge&logo=javascript&logoColor=F7DF1E)
- ⚙️ &nbsp;
  ![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
  ![GitHub](https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white)
  ![Markdown](https://img.shields.io/badge/Markdown-000000?style=for-the-badge&logo=markdown&logoColor=white)
- 💻 &nbsp;
  ![Windows](https://img.shields.io/badge/Windows-0078D6?style=for-the-badge&logo=windows&logoColor=white)
  ![iOS](https://img.shields.io/badge/iOS-000000?style=for-the-badge&logo=ios&logoColor=white)


<br/>
Nigerian car insurance company competition in African data science platform "Zindi".
