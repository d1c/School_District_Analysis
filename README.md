# School District Analysis

## Project Overview

The purpose of this project is to use data about a School Districts High Schools and their students to analyze performance in math and reading. During the analysis answers to how factors such as school size and school funding impact test scores will be explored. The analysis will then be provided to the District School Board to assist them in making planning decisions regarding student and school funding.

Close to the end of the initial analysis, the School Board informed the team that due to academic dishonesty all test scores for Ninth grade students at Thomas High School will be discarded. The School Board asked for the analysis to be rerun after the test scores were discarded and report how the changes impacted the analysis.

## Results of Analysis

### How is the District Summary affected?

  * The impact of dropping the test scores for one grade level from one High School were negligible. The count of students that took the tests went down from 39,170 to 38,709 representing 1.2% of total High School students in the District.

  * The impact to average test scores and the percentage of students passing each subject were also negligible. For example, the "% Overall Passing" metric was impacted down by only a tenth of a percent.

  * District Summary - Original Analysis
    * ![District Summary - Original Analysis](/Resources/District_Summary_Original_Analysis.png)

  * District Summary - Revised Analysis
    * ![District Summary - Revised Analysis](/Resources/District_Summary_Modified_Analysis.png)

### How is the School Summary affected?
  * Only Thomas High School test scores and passing percentages were impacted by the change.
  * However, even the changes to Thomas High School were negligible.
    * For example. the original analysis showed Thomas High School's "% Overall Passing" metric at 90.95%. The revised analysis brought that metric down only three tenths of a percent to 90.63%.
  * See the complete tables below for the full results.

  * School Summary - Original Analysis
    * ![District Summary - Original Analysis](/Resources/School_Summary_Original_Analysis.png)

  * School Summary - Revised Analysis
    * ![District Summary - Revised Analysis](/Resources/School_Summary_Modified_Analysis.png)

### How does replacing the ninth graders' math & reading scores affect Thomas High School's performance relative to the other schools.
  * Had the number of ninth grade students not been dropped from the calculations, Thomas High School would have dropped from the 2nd overall ranking to 8th place based on the "% Overall Passing" metric.
  * However, removing the number of 9th grade students, Thomas High School remained as the 2nd highest performing school.

### How does replacing the ninth-grade scores affect the following:
  * Math & Reading scores by grade?
    * Thomas High School 9th Grade shows no result compared to all other schools. 
  * Scores by school spending? By School Size? and By School Type
    * As reported above, the changes in these three reports were negligible to the point where I would say they were not impacted by dropping the students scores from the analysis.

    The test scores broken down by school spending, school size and school type were not impacted by the change to remove Thomas High School 9th grade students from the calculations.

## Summary

To complete the revised analysis, multiple changes had to be made to the data and the original analysis. First, all math and reading scores for 9th Grade Students at Thomas High School were removed from the dataset. 

As a result of that change, the total student count of High School students had to be revised to show only the number of students who now had test scores.

Perhaps the most noticible change is to the table showing "Test Scores by Grade" since the Thomas High 9th Grade students do not have a score.

Overall, since the Thomas High 9th Grade students only represented 1.2% of total High School students in the District, the impact to the overall District wide scores were negligible.