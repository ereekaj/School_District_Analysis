# School District Analysis

## Overview of the school district analysis: 
I've been working on analyzing math and reading testing scores for a school district where Maria works.  Now the school board has notified Maria the data we originaly used show evidence of academic dishonesty. I have been tasked with replacing the math and reading scores for 9th grade students at Thomas High School (THS) with NaNs while keeping the rest of the data intact, redoing all of my analysis on the school district data and describing how these changes affected the overall analysis.

## Results: 
- How is the district summary affected?
The district summary used the overall student count to calculate the average scores and the average passing percentages for the district as a whole. When removing the 9th grade students grades, that lessened the student count by a little over 400 students which also adjusted the data calculations. This change was very slight and each passing percentage only changed about 1/10th of a percent which you can see below. 

The original district summary is below:
![Original district summary](https://github.com/ereekaj/School_District_Analysis/blob/main/Resources/DistrictSummaryOLD.png)

The new district summary:
![New district summary](https://github.com/ereekaj/School_District_Analysis/blob/main/Resources/DistrictSummaryNEW.png)


- How is the school summary affected?
The School Summary catergorized the data per each school, so with changing the THS school data, the row with THS data was the only row with results that changed. 

- How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?
THS's overall performance went way up after replacing the 9th grade scores. THS's original scores before the change can be seen below:
![Chart with original scoring % for THS](https://github.com/ereekaj/School_District_Analysis/blob/main/Resources/THSscreenshotOLD.png)


The scores after the change are also shown below:  
![Chart with updated scoring % for THS](https://github.com/ereekaj/School_District_Analysis/blob/main/Resources/THSscreenshotNEW.png)

By eliminating the 9th grade scores, THS's overall passing % took them from being ranked 8th in the District to ranking 2nd.  '% Passing Math' scores improved from 67% to 93%. '% Passing Reading' scores improved from 70% to 97%.  '% Overall Passing' scores improved from 65% to 91%.  

- How does replacing the ninth-grade scores affect the following:
  - Math and reading scores by grade
  Changing the 9th grade THS scores only affected the scores for that school. This had no affect on the other grades or the other schools score so the integrity of the rest of the data was maintained. 
  
  - Scores by school spending
  
  
  - Scores by school size
  
  
  - Scores by school type


## Summary: 
Summarize four changes in the updated school district analysis after reading and math scores for the ninth grade at Thomas High School have been replaced with NaNs.
