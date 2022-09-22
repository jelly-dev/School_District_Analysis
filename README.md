# School_District_Analysis

## Overview
The school board has requested this project after being notified that the reading and math grades for Thomas High School ninth graders appear to have been altered, suggesting academic dishonesty. I have been asked to replace the math and reading scores for Thomas High School with NaNs while keeping the rest of the data intact, repeat the school district analysis, and write up a report to describe how these changes affected the overall analysis.

## Results

- Replacing the scores for Thomas High School ninth graders affects the district summary in the following ways:
    - The percentage of students in the district passing math decreased  slightly, from 75% to 74.8%.
    - The overall percentage of students in the district passing decreased slightly, from 65% to 64.9%.
![District Summary DataFrame](/static/images/district_summary_df.png "District Summary DataFrame")

- Replacing the scores for Thomas High School ninth graders affects the school summary in the following ways:
    - Average math scores at Thomas High School decreased from 83.42% to 83.35%.
    - Average reading scores at Thomas High School increased from 83.84% to 83.89%
    - No scores for other schools change.
![School Summary DataFrame](/static/images/school_summary_df.png "School Summary DataFrame")

- Replacing the scores for Thomas High School ninth graders affected the school's performance relative to others in the following ways:
    - Thomas High school dropped out of the top 5 high schools in the district.
    - Wright High School moved into the top 5 high schools in the district.
    - Bottom 5 performing schools remained the same.
![Top 5 and Bottom 5 Schools](/static/images/top5_bottom5.png "Top 5 and Bottom 5 Schools")

- Replacing the scores for Thomas High School ninth-graders also affected the following:
    - Math and reading scores for all other grades remained the same.
    - Scores by school spending changed at the $601-650 range:
        - Percentage of students passing math decreased from 73% to 67%.
        - Percentage of students passing reading decreased from 84% to 77%.
        - Overall percentage of students passing decreased from 63% to 56%.
![Scores by School Spending](/static/images/scores_by_spending.png "Scores by School Spending")

    - Scores by school size changed for medium-sized schools (1000-2000):
        - Percentage of students passing math decreased from 94% to 85%.
        - Percentage of students passing reading decreased from 97% to 91%.
        - Overall percentage of students passing decreased from 91% to 85%.
![Scores by School Size](/static/images/scores_by_size.png "Scores by School Size")

    - Scores by school type were affected in the following ways:
        - Percentage of students passing math decreased from 94% to 90%.
        - Percentage of students passing reading decreased from 97% to 93%.
        - Overall percentage of students passing decreased from 90% to 87%.
![Scores by School Type](/static/images/scores_by_type.png "Scores by School Type")