# School_District_Analysis

## Overview of the School District Analysis

### Purpose
Our team was hired to provide an analysis of a High School district Test scores and conduct an investigation into possible academic dishonesty.  The preliminary data shows that Reading and Math grades for Thomas High School (THS) ninth graders appear to have been altered.
### Executive Summary
The team has parsed the data and concluded that overall the removal of the  math, reading and overall scores of the THS 9th grader does not impact the overall district metrics.
However, it is important to note that when looking at the overall scores of the THS academic performance, there is a substantial (> 25%) shift in the percentage of students with passing grades for math and reading.

## Results
In this section, our team will answer the following set of questions and will provide evidence of our findings.
- How is the district summary affected?
- How is the school summary affected?
- How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?
- How does replacing the ninth-grade scores affect the following:
  - Math and reading scores by grade
  - Scores by school spending
  - Scores by school size
  - Scores by school type

*Note: herein, NEW Data refers to all analysis performed by removing the scores in Math and Reading for all 9th graders in Thomas High School (THS).*

### How is the district summary affected?
Overall, we see negligible changes in the District Summary:
                    Original    New Data    Delta
Avg. Math Score       79.0%      78.9%       0.1%
% Passing Math        75.0%      74.8%       0.2%
% Overall Passing     65.2%      64.9%       0.3%
*Insert Images here*

### How is the school summary affected?
When digging deeper into the School Summary, we see a substantial shift in some of the data:
                    Original    New Data    Delta
% Passing Math        66.9%      93.2%      26.3%
% Passing Reading     69.7%      97.0%      27.3%
% Overall Passing     65.1%      90.6%      25.5%
*Insert Images here*

### How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?
The analysis outlined in the previous section indicates that scores from 9th grade highlight, on average, a 26% decrease in academic performance at THS.
When we removed the 9th grader scores from the data, we see a sharp increase in the overall academic performance at THS.

### How does replacing the ninth-grade scores affect math and reading scores by grade?
At this time, we cannot make any inferences about the effect on scores for the entire 9th grade population in the district when the math and reading scores for THS students were removed from the population.
Our original analysis did not include an analysis breakdown by grade.  In the near future we can provide an addendum to this report with a complete analysis of this data.

### How does replacing the ninth-grade scores affect the scores by school spending?
When we look and compare the data when grouped by the spending ranges (per student), there is no discernible change in the scores, percentage of students passing math or reading, nor the overall average.  When we look at the raw data, we see a miniscule (<0.1%) shift in the percentages:
*insert data*
This seemingly contradictory finding is due to two factors:
- The aggregation of data across the various grade populations and the overall school scores being averaged for all grades is not affected by the substraction of a small population
- The 9th grade population removed from the entire pool of students is miniscule and would not be expected to shift the results:
  - Total student population = 39170
  - THS 9th grade population = 461 (or 1.2%)

### How does replacing the ninth-grade scores affect the scores by school size?
Similarly to the findings when analyzing the data when broken down by school spending, the removal of the 9th grade scores did not affect the original analysis.
 *insert by_size images*

### How does replacing the ninth-grade scores affect the scores by school type?
Similarly to the findings when analyzing the data when broken down by school spending, the removal of the 9th grade scores did not affect the original analysis.
 *insert by_type images*

## Additional Data (Top/Bottom Analysis)
### Top Schools
Although this data was not expressedly requested, during our analysis of the data, we found that the order of the top five schools was not affected. in fact, there were negligible shifts in the overall THS performance when 9th graders' math and/or reading scores were removed.  The changes are outlined here:
                    Original    New Data    Delta
% Passing Math        93.27%     93.19%     0.08%
% Passing Reading     97.31%     97.02%     0.29%
% Overall Passing     90.95%     90.63%     0.32%
*insert top images*
### Bottom Schools
The data did not affect the order or overall statistics of the bottom five schools:
*insert bottom images*

## Summary
We can summarize the following:
1. The scores are negligible affected for the entire district whether we take into consideration the 9th grade math and/or reading scores.
2. The THS 9th grade population has a significant (~26%) increase in the percentage of students passing when removed from the THS population
3. We can produce more data on the impact at the 9th grade level for the distric with a few tweaks of our code.
4. The removal of scores did not affect how the scores are calculated when the data is grouped by school size, school spending budget (per student) or the type of school.
5. The overall order of top schools was not affected. 