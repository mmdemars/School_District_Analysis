# School_District_Analysis

## Overview of the Project
The purpose of the project is to provide an overview of the Py City Schools, comparing test scores with various metrics including school budgets, school sizes, and school types following the removal of test scores that may have been altered. 

## Results
# Effect on the District Summary
The removal of the suspect test scores had a small effect on the district summary, with a .2% drop in passing math, .3% drop in passing reading, and an overall passing .1% drop. 
![image of district summary here](/../main/resources/district_summary_df.png?raw=true)

# Effect on the School Summary
The removal of the suspect test scores had minimal effect on the School Summary once the number of students with missing test scores were removed from the analysis totals, only changing the passing percentages on one school out of fifteen, and changing all three scores (% passing math, % passing reading, and % overall passing) by less than 1% in each case. Pre removal the overall passing scores for Thomas HIgh School dropped to 65%.
![image of school summary after NaNs here](/../main/resources/pre_school_summary.png?raw=true)
![image of count adjusted numbers here](/../main/resources/per_school_summary_df.png?raw=true)

# Effect on Thomas High School relative to other schools
Removal of the suspect test scores did not change Thomas High School's rank of 2nd highest performaing overall once the number of students whose grades were omitted were removed from the analysis. 
![Top Schools]([image](/../main/resources/top_schools.png?raw=true)

# Effect on:
**Math and reading scores by grade** - The most obvious effect is on the 9th grade scores for Thomas High School, as they have been removed from the analysis entirely.

![Math scores by Grade](/../main/resources/math_scores_by_grade.png?raw=true) ![Reading scores by Grade](/../main/resources/reading_scores_by_grade.png?raw=true)

**Scores by school spending** - There was little to no effect on the scores categorized by spending. Schools with lower spending per student trend to have higher overall test scores.
![Scores by Spending](/../main/resources/scores_by_spending.png?raw=true)

**Scores by school size** - There was little to no effect on the scroes categorized by school size. Small to Medium schools trend to have higher overall test scores.
![Scores by school size](/../main/resources/scores_by_size.png?raw=true)

**Scores by school type** - There was little to no effect on the scores categorized by type. Charter schools trend to  have higher test scores than District schools.
![Scores by school type](/../main/resources/scores_by_type.png?raw=true)


## Summary: 
- Replacment of the ninth grade test scores with NaNs redued the pass percentage on math by .2%, on reading ny .3% and overall by .1%.  
- It affected the School Summary on one school out of 15,  changing all of the test scroes by less than 1% once the pass rate was adjusted to remove the student counts that had the grades removed.  
- Removal of the grades dropped the overall pass rate of Thomas High School to 65% before the student total was adjusted correspondingly. 
- Recovery of the actual test scores for the ninth graders of Thomas High may have a greater effect on the data overall.


