# PyCitySchools with Pandas

## Overview of the school district analysis

Upon completing the original school district analysis on student_complete.csv and school_complete.csv, evidence of academic dishonesty was discovered on reading and math grades from Thomas High School ninth grade class. District required new analysis after replacing the Thomas High School ninth grade reading and math scores with NaNs

## Results

### How is the district summary affected?

![This is an image](Resources/district_summary_A.PNG)
District Summary - Original

![This is an image](Resources/district_summary_B.PNG)
District Summary - Updated
#### The removal of the Thomas High School ninth grade reading and math score reduced the overall average and passing percentages of the district.







### How is the school summary affected?

![This is an image](Resources/per_school_summary_A.PNG)
School Summary - Original

![This is an image](Resources/per_school_summary_B.PNG)
School Summary - Updated
#### The removal of the Thomas High School ninth grade reading and math scores had no impact on the other school scores. Thomas High School has a overall reduction in their own math, reading and overall passing percentages.



### How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?

![This is an image](Resources/Thomas_High_A.PNG)
Thomas High School including ninth grade scores

![This is an image](Resources/Thomas_High_B.PNG)
Thomas High School removing ninth grade scores

#### Analysis was conducted to remove the ninth grade scores and recalculate the scores for Thomas High School with only 10th, 11th, and 12th grade scores. The removal of the ninth grade scores placed Thomas High School back into the top performing schools in the district. The removal of the Thomas High School ninth grade reading and math scores improved the overall performance of the school.



### How does replacing the ninth-grade scores affect the following:

![This is an image](Resources/replaced_math.PNG)
math scores

![This is an image](Resources/replaced_reading.PNG)
reading scores

#### Replacing the Thomas High School ninth grade scores returns NaNs for Thomas High School ninth grade data.



![This is an image](Resources/spending_summary_A.PNG)
Spending Summary - Original

![This is an image](Resources/spending_summary_B.PNG)
Spending Summary - Updated

#### Scores by school spending: No noticeable change in school spending when Thomas High School ninth grade data is omitted from the analysis.



![This is an image](Resources/size_summary_A.PNG)
Size Summary - Original

![This is an image](Resources/size_summary_B.PNG)
Size Summary - Updated

#### Scores by school size: No noticeable change in school spending when Thomas High School ninth grade data is omitted from the analysis.



![This is an image](Resources/type_summary_A.PNG)
Type Summary - Original

![This is an image](Resources/type_summary_B.PNG)
Type Summary - Updated

#### Scores by school type: No noticeable change in school spending when Thomas High School ninth grade data is omitted from the analysis.

## Summary

Summarize four changes in the updated school district analysis after reading and math scores for the ninth grade at Thomas High School have been replaced with NaNs:

![This is an image](Resources/Thomas_High_ORIGINAL.PNG)
Thomas High School - Original

![This is an image](Resources/Thomas_High_A.PNG)
Thomas High School - Updated

![This is an image](Resources/Thomas_High_B.PNG)
Thomas High School - ONLY 10th, 11th, and 12th Grade

#### 
