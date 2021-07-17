# School_District_Analysis


## Overview

The purpose of this analysis was to determine the difference in school metrics after removing 9th grade scores at Thomas High School from the dataset.


## Resources

- Data source: schools_complete.csv & students_complete.csv
- Software: Python 3.7.6, Jupyter Notebook, 6.3.0

## Results

* In the district summary, the average math score decreased by one tenth, from 79.0 to 78.9.

* In the school summary for Thomas High School, the average score for Math showed a minor decrease when scores were removed while the average reading scores showed a minor increase. The passing percentages all showed minor decreases (table 1).

*Table 1 - Thomas High School Summary with and without 9th Grade Scores*

|                      |Thomas High with 9th Grade Scores | Thomas High without 9th Grade Scores|
|----------------------|:-----:|:-----:|
| Average Math Score   | 83.42 | 83.35 |
| Average Reading Score| 83.84 | 83.90 |
| % Passing Math       | 93.27 | 93.19 |
| % Passing Reading    | 97.30 | 97.02 |
| % Overall passing    | 90.95 | 90.58 |

* Thomas High still ranks in the top 5 schools, coming in as the school with the second highest scores in the district even without the 9th grade data, as can be seen in table 2. The bottom 5 schools also remain the same. They are Rodriguez High, Figueroa High, Huang High, Hernandez High, and Johnson High.

*Table 2 - Top 5 Schools*

![top_5_no_9th](https://github.com/jisellejones/School_District_Analysis/blob/main/Resources/top_5_no_9th.png)

* All Math and Reading averages stayed the same by grade level with the exception of Thomas High School where both the math and reading scores were removed and could not be determined at 9th grade

*Table 3 - Math and Reading averages for Thomas High School*

|        | 9th | 10th | 11th | 12th |
|:------:|:---:|:----:|:----:|:----:|
|Reading Averages| nan | 84.3 | 83.6 | 83.8 |
|Math Averages | nan | 83.1 | 83.5 | 83.5|

* School spending per student remained unaffected by the removal of the 9th grade data (see table 4).

*Table 4 - Spending Summary*

![spending_summary_no_9th](https://github.com/jisellejones/School_District_Analysis/blob/main/Resources/spending_summary_no_9th.png)

* The scores based on school size also remained unaffected (see table 5).

*Table 5 - Score by School Size*

![score_by_size_no_9th](https://github.com/jisellejones/School_District_Analysis/blob/main/Resources/spending_summary_no_9th.png)

* Finally, the scores by school type remiained unaffected (see table 6).

*Table 6 - Score by School Type*

![score_by_type_no_9th](https://github.com/jisellejones/School_District_Analysis/blob/main/Resources/score_by_type_no_9th.png)


## Summary

The 9th grade students at Thomas High made up a very small percentage of the overall district data, so there were very few changes to the overall analysis. Minor changes are listed below.

    1. The overall district scores showed a slight but insignificant decrease in average math scores after removing the subset of data from Thomas High (a mere tenth of a point).
    2. The average math score for all students at Thomas High decreased slightly.
    3. The average reading score for all students at Thomas High increased slightly.
    4. The percentages of students passing math, reading, and both math and reading slightly decreased, but did not decrease by a significant amount.
    
Overall, there was not much change in the district analysis. This begs the question, is it really necessary for all students in all grades to be given an assessment each year? Testing takes up significant time from instruction and learning and causes added stress and tension for both teachers and students. 

The scores from Thomas High in the upper grades seem to suggest that there was no reason for students or teachers to cheat. Thomas High is a high performing school. It is also a charter school, which, according to the data, seems to out perform the district schools significantly. So, why did students and/or teachers feel that cheating was necessary? Are we putting too much emphasis on testing so much so that the pressure to perform causes unethical decisions? Are there better ways we can assess that will give more valuable information to students, parents, teachers, administrators, and districts while creating enthusiasm for learning?

Perhaps it is time to rethink our current assessment methods. Could a smaller set of students chosen randomly throughout the district give us the same information about how effective instruction is at a school level and how appropriate curriculum is at a district level? 

Reducing the amount of testing could also allow the district to reallocate funding spent on testing to schools needing greater support. Although, the data suggests that more money spent per student does not correlate with higher performance in math and reading. It may behoove the district to investigate how funding is being allocated in schools that spend fewer dollars per student than those that spend a greater amount of dollars per student. Why is it that more dollars per student does not yield higher math and reading scores?

### Limitations

While removing the Thomas High 9th grade scores from the district analysis did not render much difference in the overall analysis, there is no way to determine how the Thomas High ninth grade scores would have effected the average math and reading scores and percentages for Thomas High School had cheating not been a factor. The district could consider reviewing the scores from the same students in their eighth grade year as well as run an analysis on the eleventh through twelfth grdade students from their prior year to determine if there is any significant differences among the metrics of the analysis.
