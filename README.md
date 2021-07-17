# School_District_Analysis


## Overview

The purpose of this analysis was to determine the difference in school metrics after removing 9th grade scores at Thomas High School from the dataset.


## Resources
- Data source: schools_complete.csv & students_complete.csv
- Software: Python 3.7.6, Jupyter Notebook, 1.58.0
## Results

* In the district summary, the average math score decreased by one tenth, from 79.0 to 78.9.

* In the school summary for Thomas High School, the average score for Math showed a minor decrease when scores were removed while the average reading scores showed a minor increase. The passing percentages all showed minor decreases. 

*Table 1 - Thomas High School Summary with and without 9th Grade Scores*
|                      |Thomas High with 9th Grade Scores | Thomas High without 9th Grade Scores|
| Average Math Score   | 83.42 | 83.35 |
| Average Reading Score| 83.84 | 83.90 |
| % Passing Math       | 93.27 | 93.19 |
| % Passing Reading    | 97.30 | 97.02 |
| % Overall passing    | 90.95 | 90.58 |

* Thomas High still ranks in the top 5 schools, coming in as the school with the second highest scores in the district even without the 9th grade data, as can be seen in table 2. The bottom 5 schools also remain the same. They are Rodriguez High, Figueroa High, Huang High, Hernandez High, and Johnson High.

*Table 2 - Top 5 Schools*

* All Math and Reading averages stayed the same by grade level with the exception of Thomas High School where the scores were removed and could not be determined.

*Table 3 - Math and Reading averages for Thomas High School*

|        | 9th | 10th | 11th | 12th |
|Reading Averages| nan | 84.3 | 83.6 | 83.8 |
|Math Averages | nan | 83.1 | 83.5 | 83.5|

* School spending per student remained unaffected by the removal of the 9th grade data (see table 4).

*Table 4 - Spending Summary*

* The scores based on school size also remained unaffected (see table 5).

*Table 5 - Score by School Size*

* The scores by school size remiained unaffected (see table 6).

*Table 6 - Score by School Size*


## Summary

The 9th grade students at Thomas High made up a very small percentage of the overall district data, so there were very few changes to the overall analysis. Minor changes are listed below.
    1 - The overall district scores showed a slight but insignificant decrease in average math scores after removing the subset of data from Thomas High (a mere tenth of a point)
    The average math score for all students at Thomas High decreased slightly.
    2 - The average reading score for all students at Thomas High increased slightly.
    3 - The percentages of students passing math, reading, and both math and reading slightly decreased, but did not decrease by a significant amount.
    4 - 
    
Overall, there was not much change in the district analysis. This begs the question, is it really necessary for all students in all grades to be given an assessment each year? Testing takes up significant time from instruction and learning and causes added stress and tension for both teachers and students. 

The scores from Thomas High in the upper grades seem to suggest that there was no reason for students or teachers to cheat. Thomas High is a high performing school. It is also a charter school, which, according to the data, seems to out perform the district schools significantly. So, why did students and/or teachers feel that cheating was necessary? Are we putting too much emphasis on testing so much so that the pressure to perform causes unethical decisions.

Perhaps it is time to rethink our current assessment methods. Could a smaller set of students chosen randomly throughout the district give us the same information about how effective instruction is at a school level and how appropriate curriculum is at a district level? Reducing the amount of testing could also allow the district to reallocate funding to schools needing greater support. Although, from the data, it doesn't look like more money spent per student correlates with higher performance in math and reading. Which also makes me question how funding in schools with higher spending per student is being allocated.


## Limitations

Due to the   