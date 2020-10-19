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

In Thomas, the results were a bit surprising:
- dropping the suspect scores **increased** the average math and reading scores by a fair bit (7-10 points)
- dropping the suspect scores **decreased** the passing rates by a lot (about 30%)
This is partly due to the methodology; the students whose scores were dropped are still counted in the denominator for the passing percent.

### mpact on thomas compared to other schools

With the results excluded, Thomas drops out of the top 5.

### Other Impacts
-- math and reading scores by grade: impacts only Thomas
-- scores by school spending
-- scores by school sized
-- scores by school type

** Summary
- list 4 major changed in teh analysis after math, reading scores replaced with NaN

