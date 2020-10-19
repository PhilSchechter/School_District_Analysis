# School_District_Analysis
####Columbia Data Analytics, module 4

## Overview, purpose of original study

This is a school-district study of the peformance of schools within the district. The metrics of success are
- avg math scores 
- avg reading scores
- % of math scores passing (70 or over)
- % of reading scores passing
- % of passing students : students having both passing math and reading scores.
The final metric is the most critical, and how schools are ranked.

These results are shown for the district as a whole, by school and grade, and for various grouping of schools (charter/public, size bands, spending per student bands)

## Purpose of this revision

There is some suspicion of improper test results for the 9th grade in Thomas High; the school board wants to exlude these from any results presented; this revision takes these scores and regenerates the analysis.

## Results

### impact on district summary
[District Level Results](Resources/district_results.png)

In the linked chart, the top row contains the revised results and the bottom has the original. For the discrict overall, excluding the Thomas 9th graders
- dropped average math by 1/10th of a point
- had no impact on the reading score
- reduced passing math rate from 75.9% to 74.8%
- reduced passing math rate from 86.0% to 85.7%
- reduced the combined passing rate from 65.9% to 64.9%

### impact on school summary

[School Level Results - New](Resources/school_results_new.png)

[School Level Results - Original](Resources/school_results_orig.png)

This did not impact any schools other than Thomas High.

In Thomas, excluding the 9th grade caused a small drop in the overall passing rate (a fraction of a percent), a 4% drop in the reading passing percent (97 down to 93) and almost no impact on the math passing rate. 

### impact on thomas compared to other schools

[Top 5 schools](Resources/top_schools_new.png)

With the results excluded, Thomas still ranks as the #2 school in the district by overall pass rate

### Other Impacts
-- math and reading scores by grade: impacts only Thomas, shows NaN instead of actual grades for the 9th grade
-- scores by school spending: 
--- [by Spending](Resources/by_spending_new.png)
--- minor impact: for the $30-644 range, the % passing rading fell from 84 to 83. All other metrics stay the same
-- scores by school size : only change is in Medium schools, % passing reading dropped from 97 to 96%
    [by_Size](Resources/by_size_new.png)
-- scores by school type: Charter reading pass rate dropped from 97 to 96%, all else stayed the same
     [by_Type](Resources/by_type_new.png)

## Summary

The major change (other than to the Thomas 9th graders) was the reading pass rate. This changed enouigh to be noticeable for Thomas High and other grouping including Thomas, i.e.
- School in the 2nd highest per-pupil spending bracket
- Medium sized schools and
- Charter schools


