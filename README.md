# ![](https://ga-dash.s3.amazonaws.com/production/assets/logo-9f88ae6c9c3871690e33280fcf557f33.png) Project 1: Standardized Test Analysis

### Overview
The SAT and ACT are standardized tests that many colleges and universities in the United States require for their admissions process.
There was a change in format for SAT in 2016. Math is now taking a bigger weightage. Hence, Math results influence SAT score much more than ACT.

### Problem Statement
Was this decision beneficial for College Board in its competition against ACT Inc. in its fight for market share? 

     - Did this decision cause any change in SAT participation rate?

     - Did this decision encourage students strong in Mathematics to sit for SAT?

     - Did these students switch over to SAT and abandon ACT? Or did they take both tests?

### Data Dictionary
|Feature|Type|Dataset|Description|
|---|---|---|---|
|act_participation_rate_2017|float|ACT|ACT's Participation Rate in 2017|
|act_english_avg_score_2017|float|ACT|ACT's Average Score for English in 2017| 
|act_math_avg_score_2017|float|ACT|ACT's Average Score for Math in 2017| 
|act_reading_avg_score_2017|float|ACT|ACT's Average Score for Reading in 2017| 
|act_science_avg_score_2017|float|ACT|ACT's Average Score for Science in 2017|
|act_composite_avg_score_2017|float|ACT|ACT's Average Composite Score in 2017| 
|act_participation_rate_2018|float|ACT|ACT's Participation Rate in 2018|
|act_composite_2018|float|ACT|ACT's Average Composite Score in 2018| 
|act_participation_rate_2019|float|ACT|ACT's Participation Rate in 2019|
|act_composite_2019|float|ACT|ACT's Average Composite Score in 2019|
|sat_participation_rate_2017|float|SAT|SAT's Participation Rate in 2017|
|sat_ebrw_avg_score_2017|float|SAT|SAT's Average Score for Evidence-based Reading and Writing in 2017| 
|sat_math_avg_score_2017|float|SAT|SAT's Average Score for Math in 2017| 
|sat_total_avg_score_2017|float|SAT|SAT's Average Score for Total in 2017| 
|sat_participation_rate_2018|float|SAT|SAT's Participation Rate in 2018|
|sat_ebrw_avg_score_2018|float|SAT|SAT's Average Score for Evidence-based Reading and Writing in 2018| 
|sat_math_avg_score_2018|float|SAT|SAT's Average Score for Math in 2018| 
|sat_total_avg_score_2018|float|SAT|SAT's Average Score for Total in 2018|
|sat_participation_rate_2019|float|SAT|SAT's Participation Rate in 2019|
|sat_ebrw_avg_score_2019|float|SAT|SAT's Average Score for Evidence-based Reading and Writing in 2019| 
|sat_math_avg_score_2019|float|SAT|SAT's Average Score for Math in 2019| 
|sat_total_avg_score_2019|float|SAT|SAT's Average Score for Total in 2019| 


### Brief summary of your analysis
1. Relationship between ACT and SAT's participation rate
2. Trends of ACT and SAT's Average/Median Participation Rate over the years
3. Trends of ACT and SAT's Average/Median Scores over the years
4. Breakdown of SAT's scores - Math and EBRW


### Conclusions/recommendations
The new SAT format has attracted more students and has increased the participation rate. 
On the other hand, participation rate for ACT has dropped.
However, we do see a greater proportion of students who take both SAT and ACT.

Although the average score of SAT has dropped, the median score of SAT has increased slightly.

Looking at the details of the score, on the whole, scores for Math has improved. 
This could signal that more mathematically strong students are attracted by the change in format, and have decided to try SAT (instead of ACT). 

States who used to participate mainly in ACT, is now taking up SAT. Students are choosing to take up SAT (on top of ACT) to have a chance in both. 