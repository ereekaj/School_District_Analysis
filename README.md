# School District Analysis

## Overview of the school district analysis: 
I've been working on analyzing math and reading testing scores for a school district where Maria works.  Now the school board has notified Maria the data we originaly used shows evidence of academic dishonesty. I have been tasked with replacing the math and reading scores for all 9th grade students at Thomas High School (THS) with NaNs while keeping the rest of the data intact, redoing all of my analysis on the school district data and describing how these changes affected the overall analysis.

## Results: 
*- How is the district summary affected?*
The district summary used the overall student count to calculate the average scores and the average passing percentages for the district as a whole. When removing the 9th grade students grades, that lessened the student count by a little over 400 students which also adjusted the data calculations. This change was very slight and each passing percentage only changed about a 10th of a percent which you can see below. 

The original district summary is below:
![Original district summary](https://github.com/ereekaj/School_District_Analysis/blob/main/Resources/DistrictSummaryOLD.png)

The new district summary:
![New district summary](https://github.com/ereekaj/School_District_Analysis/blob/main/Resources/DistrictSummaryNEW.png)


*- How is the school summary affected?*
The School Summary catergorized the data per each school, so with changing the THS school data, the row with THS data was the only row with results that changed. None of the other school data was affected.  

*- How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?*
THS's overall performance went way up after replacing the 9th grade scores. THS's original scores before the change can be seen below:
![Chart with original scoring % for THS](https://github.com/ereekaj/School_District_Analysis/blob/main/Resources/THSscreenshotOLD.png)


The scores after the change are also shown below:  
![Chart with updated scoring % for THS](https://github.com/ereekaj/School_District_Analysis/blob/main/Resources/THSscreenshotNEW.png)

By eliminating the 9th grade scores, THS's overall passing % took them from being ranked 8th in the District to ranking 2nd.  '% Passing Math' scores improved from 67% to 93%. '% Passing Reading' scores improved from 70% to 97%.  '% Overall Passing' scores improved from 65% to 91%.  

*- How does replacing the ninth-grade scores affect the following:*

  *- Math and reading scores by grade:*
  Changing the 9th grade THS scores only affected the scores for that school. This had no affect on the other grades or the other schools score so the integrity of the rest of the data was maintained. 
  
  *- Scores by school spending:*
  Removing the data did not change THS's data for school spending so they were still in the $631-$645 bin. As with the District Summary, not using the THS 9th grade student count and scores did change the the average reading, math and overall scores and the average passing percentages for the $631-$645 bin. However, the change was so slight that when all of the numbers were rounded, the original and new results were exactly the same. See below:

  Original Data:
![Chart with original scores by school spending](https://github.com/ereekaj/School_District_Analysis/blob/main/Resources/schoolspendingdataold1.png)

![Chart with original scores by school spending](https://github.com/ereekaj/School_District_Analysis/blob/main/Resources/schoolspendingdataold2.png)

  New Data:
![Chart with new scores by school spending](https://github.com/ereekaj/School_District_Analysis/blob/main/Resources/schoolspendingdatanew1.png)

![Chart with new scores by school spending](https://github.com/ereekaj/School_District_Analysis/blob/main/Resources/schoolspendingdatanew2.png)
  
  *- Scores by school size:*
  Removing the 9th grade students from the THS total did not move them from the 'Medium (1000-2000)' school size bin.  Much like the Scores by School spending analysis, not using the THS 9th grade student count and scores did change the the average reading, math and overall scores and the average passing percentages for the 'Medium (1000-2000)' school size bin. Again, the change was so slight that when all of the numbers were rounded, the original and new results were exactly the same. See below:
  
  Original Data:
![Chart with old scores by school size](https://github.com/ereekaj/School_District_Analysis/blob/main/Resources/Schoolsizeold.png)

  New Data:
![Chart with new scores by school size](https://github.com/ereekaj/School_District_Analysis/blob/main/Resources/SchoolsizeNEW.png)
  
  *- Scores by school type:*
  Removing the 9th grade students from the THS total did not change the fact that THS is a Charter School. Again removing the data did slightly change the average reading, math and overall scores and the average passing percentages for the Charter schools but after rounding the results were exactly the same. See below: 

  Original Data:
![Chart with old scores by school type](https://github.com/ereekaj/School_District_Analysis/blob/main/Resources/typeOLD.png)

  New Data:
![Chart with new scores by school type](https://github.com/ereekaj/School_District_Analysis/blob/main/Resources/TypeNEW.png)

## Summary: 
By eliminating the 9th grade THS scores to NaNs, some of the data did change significantly. See below. 
1. THS's overall passing % took them from being ranked 8th in the District to ranking 2nd. This was a big move.  
2. THS's '% Passing Math' score improved by from 67% to 93%. This is a double digit improvement. 
3. THS's '% Passing Reading' score improved from 70% to 97%. 
4. THS's '% Overall Passing' score improved from 65% to 91%. 

All of the last three changes were double digit improvements. Usually with alleged academic dishonesty, if grades were changed, you'd think the changes would increase the scores. However, in this case the potentially altered results actually lowered the scores for THS 9th grade students trememdously. If there was any academic dishonesty, it didn't help the students grades. 
