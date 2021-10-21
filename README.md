# School District Analysis

## Overview
This analysis used Python and Pandas to explore data and determine replacing the grades for the 9th grade class at Thomas High School would impact the overall report.

## Results

### District Summary 

<img width="928" alt="district_summary_after" src="https://user-images.githubusercontent.com/16244455/138351764-53d868d3-893c-4e08-916b-10363cdaedb6.png">

- Replacing the grades did not impact the District Summary much, with the % overall passing math and overall passing reading only going down .1% and overall passing only going down .2%

### School Summary
<img width="993" alt="school_summary_after" src="https://user-images.githubusercontent.com/16244455/138353723-ac010663-0e71-40c0-9577-d101e7d696f8.png">
- The school summary is also not impacted much, with Thomas High School scores decreasing between .1% and .3%

<img width="985" alt="school_top_bottom_after" src="https://user-images.githubusercontent.com/16244455/138354073-2898cccf-5601-4584-b752-8eade18d8713.png">
- The top performing schools is impacted, as Thomas High School has fallen out of the top 5, however the scores did not decrease enough to put them into the bottom 5.

### Math & Reading Scores by Grade
<img width="303" alt="reading_by_grade" src="https://user-images.githubusercontent.com/16244455/138354481-dc39a11f-e875-488a-91ba-a0f8238a2c87.png">
<img width="306" alt="math_by_grade" src="https://user-images.githubusercontent.com/16244455/138354485-a9193faf-8a07-4907-badd-896f2d53f9af.png">
- Only the scores for 9th graders in Thomas High School were replaced with NaN, and therefore did not impact any other aspects of this DataFrame.

### Spending Ranges & Size
<img width="824" alt="spending_ranges" src="https://user-images.githubusercontent.com/16244455/138355240-8959dd9c-b5cf-4f64-8803-e2f565184ac2.png">
<img width="761" alt="size_ranges" src="https://user-images.githubusercontent.com/16244455/138355559-544b772a-5684-456f-9631-c55512d72c9b.png">
<img width="710" alt="school_type" src="https://user-images.githubusercontent.com/16244455/138355681-4ec1dcb9-0630-4d7c-bded-7beacce52251.png">
- The % passing math, reading, and overall were greatly impacted, and all changed by 6-7% in the $630-$644, Medium, and Charter categories respectively.

## Overall Summary
1. Changing the scores for 9th graders in Thomas High School to "NaN" impacted the % overall passing math and reading by 0.1%
2. The math and reading scores by grade were only impacted for the 9th grade students at Thomas High School
3. The Spending Range summary saw the % passing math, % passing reading, % overall passing all decrease by 6% - 7%
4. The Size Range summary saw the % passing math, % passing reading, % overall passing all decrease by 6% - 7%
