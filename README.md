# PyCity School District Analysis

## Overview of Project
The purpose of this analysis is to review, clean, and present the testing resutls from various schools in the district. We have been asked to present that data so it illistrates how the shools perfomed on a number of factors such grade level, shool size, type of shcool, and budget. This will help the school board drive strategy by understanding performance trends and patterns.

## Results
- How is the distric summary affected?
  Due to some concerns regarding academic dishonesty, we were asked to remove the math and reading scores for all 9th graders from Thomas High School. The average math and reading   scores remained the same. The passing percentage for math and reading decreased by a percent. Over all, the removal of the grade scores from 9th graders at Thomas High School     had little effect and did not change the schools ranking. 
  
  Before
 ![district_summary_with_9](Resources/district_summary_with_9.png)
  After
![district_summary_less_9](Resources/district_summary_less_9.png)

- How is the school summary affected?

  The school summary was not affected by the removal of the 9th grade scrores. When recalculating the percentages, the total number of students did not include 9th graders from     Thomas High Schools. There was not a noticable change in the schools suammary.
  
  Before
 ![per_school_summary_before](Resources/per_school_summary_before.png)
 
 After
![per_school_summary_after](Resources/per_school_summary_after.png)

- How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?
  Replacing the ninth graders math and reading scores had little affect in relation to the other schools. The percentage changed did not have an affect on the overall ranking of   the school. 
  
  Since the the change in average and percentage we minimal at the school level, when used in aggregate to calculate other data points such as scores, by spending, school size,  by school type, the remmoval of the 9th grade math and reading scores had little effect. 
  
![math_scores_before](Resources/math_scores_before.png) ![math_scores_after](Resources/math_score_after.png)

![spending_before](Resources/spending_before.png) ![spending_after](Resources/spending_after.png)

![type_before](Resources/type_before.png)  ![type_after](Resources/type_after.png)
