# School_District_Analysis

## Overview of the school district analysis: Explain the purpose of this analysis.
The goal of this analysis is to take student data and compare math and reading scores based on various categories. We also tested the results of removing certain students.

## Results: Using bulleted lists and images of DataFrames as support, address the following questions.

* How is the district summary affected?
![district_summary](https://user-images.githubusercontent.com/83841580/126079290-6fcdcc5e-2209-4396-9429-a06419a1dd36.png)

![district_summary_updated](https://user-images.githubusercontent.com/83841580/126079291-a995bd10-e32d-468e-8bc5-5198ee6812f3.png)
  * There were slight drops accross the board in scores due to removing the 9th graders from Thomas High School.

* How is the school summary affected?
![per_school_summary](https://user-images.githubusercontent.com/83841580/126079319-de75a73d-02ab-4dc3-b6b7-0c739a7ee7f6.png)
 
![per_school_summary_updated](https://user-images.githubusercontent.com/83841580/126079320-1c1a537a-19c2-4167-826b-8ea11efa5815.png)

  * For this chart only the scores for Thomas High school have been affected. All of the passing rates for that school are slightly reduced.
  
* How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?
  * Even after removing the 9th graders Thomas High Schools passing rates are still in line with the other schools.
  
* How does replacing the ninth-grade scores affect the following:
  * Math and reading scores by grade:
    * Since only the 9th graders scores from Thomas High School are removed, the rest of the schools are unaffected.
  * Scores by school spending:
    * Thomas high school has lower scores without 9th graders and spending the same amount so there is a decrease in value.
  * Scores by school size:
    * The number of the students is unchanged so there is no change to school size.
  * Scores by school type:
    * No school types were changed so both charts look the same.
 
## Summary: Summarize four changes in the updated school district analysis after reading and math scores for the ninth grade at Thomas High School have been replaced with NaNs.
We changed all of the 9th grade math and reading scores for Thomas High School to NaNs which resulted in lower pass rates for this school. This can be seen in most of the charts. Some of the data was largely unaffected because we never removed the students themselves so they were still counted towards things like the size of the school.
