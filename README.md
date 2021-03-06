# School_District_Analysis

## Overview
The school board has notified Maria and her supervisor that the "students_complete.csv" file shows evidence of academic dishonesty. as a result, the reading and math grades for Thomas High School ninth graders score will be omitted. The purpose of this analysis is to compare the result of the data frame before and after the omission of the reading and math grades for Thomas High School ninth graders score. To perform this analysis, "students.complete.csv" and "schools_complete.csv" were analyzed via PythonData in Jupyter Notebooks.

## Results

### How is the district summary affected?
*Before*

![](Resources/District_Summary_before.PNG)

*After*

![](Resources/District_Summary_After.PNG)

- The average math score went down by 0.1
- The average reading score stayed the same.
- The passing math percentage went down by 0.2%.
- The passing reading percentage went down by 0.3%.
- The overall passing percentage went down by 0.1%.

### How is the school summary affected?
*Before*

![](Resources/School_Summary_before.PNG)

*After*

![](Resources/School_Summary_After.PNG)

- The average math score went down by 0.1.
- The average reading score went up by 0.1.
- The passing math percentage went down by 0.1%.
- The passing reading percentage went down by 0.3%.
- The overall passing percentage went down by 0.3%.

### How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?
*Before*

![](Resources/Top_5_Before.PNG)

*After*

![](Resources/Top_5_After.PNG)

Conclusion: Even with replacing the ninth grader's math and reading scores, Thomas High School's performance is still the second top school relatively to other schools.

### How does replacing the ninth-grade scores affect the following:
- Math and reading scores by grade

*Before*

*Math Score by Grade Before*

![](Resources/mathscore_by_grade_before.PNG)

*Reading Score by Grade Before*

![](Resources/readingscore_by_grade_before.PNG)

*After*

*Math Score by Grade After*

![](Resources/mathscore_by_grade_after.PNG)

*Reading Score by Grade After*

![](Resources/readingscore_by_grade_after.PNG)

Conclusion: Based on this analysis, only the 9th graders data for Thomas High School were removed. All other scores stayed the same.

- Scores by school spending

*Before*

![](Resources/scoresby_spending_before.PNG)

*After*

![](Resources/scoresby_spending_after.PNG)

Conclusion: Based on this analysis, there was no change between the before and after removing the 9th graders data for Thomas High School.

- Scores by school size

*Before*

![](Resources/scoresby_size_before.PNG)

*After*

![](Resources/scoresby_size_after.PNG)

Conclusion: Based on this analysis, there was no change between the before and after removing the 9th graders data for Thomas High School.

- Scores by school type

*Before*

![](Resources/scoresby_type_before.PNG)

*After*

![](Resources/scoresby_type_after.PNG)

Conclusion: Based on this analysis, there was no change between the before and after removing the 9th graders data for Thomas High School.



## Summary
After the reading and math scores for the ninth grade at Thomas High School have been replaced with NaNs, four major changes are identified for the updated school district analysis:

- For the District Summary Analysis, the passing math percentage, passing reading percentage, and the overall percentage decreased in a slight amount.
- For the School Summary Analysis,  the passing math percentage, passing reading percentage, and the overall percentage decreased in a slight amount.
- For the Math and Reading Score By Grade Analysis, the 9th grade math and reading score was replaced with NaN.
- Thomas High School is the second top school despite the removal of the 9th grade math and reading score. This is because the passing math, reading, and overall percentage were not heavily affected by the data removal.
