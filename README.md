# School District Analysis

## Project Overview

The purpose of this project is to use data about the High Schools and the students of these schools to analyze their performance in math and reading. During the analysis answers to questions such as "how does school size" and "how does school funding" impact test scores. The analysis will be provided to the District School Board to assist in making planning decisions regarding student and school funding.

Near the end of the analysis, the School Board informed the team that due to academic dishonesty all test scores for Ninth grade students at Thomas High School will need to be discarded. The School Board asked us to discard those scores and rerun the analysis and report how the changes impacted the analysis.

## Results of Analysis

### How is the District Summary affected?

  * The impact of dropping the test scores for one grade level at one High School were negligible. The count of students that took the tests went down from 39,170 to 38,709 representing 1.2% of total High School students in the District.

  * The Average test scores and percent of students passing each subject were also negligible. The "% Overall Passing" metric was impacted down by only a tenth of a percent.

  * District Summary - Original Analysis
    * ![District Summary - Original Analysis](/Resources/District_Summary_Original_Analysis.png)

  * District Summary - Revised Analysis
    * ![District Summary - Revised Analysis](/Resources/District_Summary_Modified_Analysis.png)


### How is the School Summary affected?
  * Comparing the School Summary analysis, academic dishonesty at Thomas High School significantly impacted the "% Passing" Math and Reading metrics. For example, the "% Passing Math Score" went down from 93.3% to 66.9%. while the "% Passing Reading" metric showed a similar drop from 97.3% to 69.7%. The percentage of students at Thomas High School passing both subjects dropped from 90.9% to 65.1%. See the tables below for additional detail.

  * School Summary - Original Analysis
    * ![District Summary - Original Analysis](/Resources/School_Summary_Original_Analysis.png)

  * School Summary - Revised Analysis
    * ![District Summary - Revised Analysis](/Resources/School_Summary_Modified_Analysis.png)

### How does replacing the ninth graders' math & reading scores affect Thomas High School's performance relative to the other schools.
  * Leaving the ninth grade students in the calculations, Thomas High School's performance dropped from the 2nd overall ranking based on "% Overall Passing." However, when the ninth graders are removed leavng only the 10th through 12th grade students in the calculation, Thomas High School maintains its #2 ranking of High School in the District.

### How does replacing the ninth-grade scores affect the following:
  * Math & Reading scores by grade?
    * Thomas High School 9th Grade shows no result compared to all other schools. 
  * Scores by school spending? By School Size? and By School Type
    * The test scores broken down by school spending, school size and school type were not impacted by the change to remove Thomas High School 9th grade students from the calculations.

## Summary

Summarize the four changes in the updated school district analysis after reading and math scores for the ninth grade at Thomas High School have been were replaced with NaNs.
