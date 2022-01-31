# School District Score/Budget Analysis

## Overview of the school district analysis 
The purpose of this analysis is to to update and configure scores that were not reliable on a high school and from there revise to see if those changes affected any budegting and overall scoring. Those removed scores for Thomas High School were replaced with NaNs as the rest of the scores were still provided. 

## Results
* How is the district summary affected? The district summary was only affected by the most minimal amount. The overall passing percentage changed by less than one percent. 
* How is the school summary affected? The school summary is only affected per row bases in this case for Thomas High School.
* How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools? The school summary for Thomas High School was really affected. The overall average score from 9th-12th grade was 65.07 percent and once the 9th grade data was removed it jumped to 90.63 percent.
* Changes analysis after the 9th grade score removals:
     - The average scores for both math and reading went up after the 9th grade scores was removed. 
     - The spending for Thomas High School stayed at 638 as it stayed in the same bin of $630-644. 
     - The school size number is not affected at the counts are still based on the ids. 
     - The charter school type numbers are the only ones to change in this case given that Thomas High School is a charter type. The overall charter percentage increases given that removing the 9th grade for Thomas High School directly affects the charter schools all together. 
   
## Summary 
Overall the data adjustment regarding the 9th grade for Thomas High School to NaNs did esentially affect the overall grades of the school itself significantly. With that in hand, it ended up changing the Charter number for reading and math overalls but with no significant change. The score on the size of category under Thomas High School was also affected. 
