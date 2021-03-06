# School_District_Analysis
Analysis on school exams and grades. Anaconda - Python and Pandas - will be used for this project.
## Overview of the school district analysis:
This report was created to aid Maria in delivering an analysis report on the average math and reading grades throughout high schools in the district. A previous report with the same analyzing goal was reviewed. Recently, however, some grades of ninth-graders at Thomas High School have been altered — this violates the rules pertaining to academic dishonesty. To keep with the Academic Dishonesty policies the district has in place, the grades from Thomas High School must be excluded when delivering a report. Due to this policy, I have performed a different analysis from the first showing the difference between the school district data including Thomas High School and excluding the school. 

## Results:
### How is the district summary affected?
* The district summary remained the same and did not change - even when excluding Thomas High School. This is a photo from before the replacement:
![district_summary_pycityschools](https://github.com/shireenkahlon/School_District_Analysis/blob/main/district%20summary%20pycityschools.png)
Attached below is a photo of the district summary after the replacement:
![district_summary_challenge](https://github.com/shireenkahlon/School_District_Analysis/blob/main/district%20summary%20challenge.png)
### How is the school summary affected?
* After dropping the ninth graders’ grades from the report, the percent passing math and percent passing reading, we can see that for each subject, as well as overall percent passing, there was a significant drop by approximately 30% for each. The average reading score decreased by approximately 3 points and the average math score decreased by approximately 7 points. Below is a screenshot from the first report:
![school_summary_pycityschools](https://github.com/shireenkahlon/School_District_Analysis/blob/main/school%20summary%20pycityschools.png)
The school summary from the current report is shown below:
![school_summary_challenge](https://github.com/shireenkahlon/School_District_Analysis/blob/main/school%20summary%20challenge.png)
### How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?
* Before the academic dishonesty policy came into play in this scenario, Thomas High School was performing phenomenally well compared to other schools; Thomas High School was the second best school in the district. However, after dropping students grades, Thomas High School fell to 8th place in the district. Photos of prior to the academic honesty policy taking place are shown below: 
![top_schools_pycityschools](https://github.com/shireenkahlon/School_District_Analysis/blob/main/top%20schools%20pycityschools.png)
Attached below is a screenshot from the top schools after the academic dishonesty policy came into play:
![top_schools_challenge](https://github.com/shireenkahlon/School_District_Analysis/blob/main/top%20schools%20challenge.png)
## How does replacing the ninth-grade scores affect the following:
### Math and reading scores by grade
* The math and reading scores are only affected for Thomas High School 9th graders. The score prior to dropping the grades for math and reading were 83.5 and 83.7, respectively, and have been dropped in order to be excluded from the overall analysis.
### Scores by school spending
* I created bins to include data within each spending group. One of the groups - $631-$645/student is where the difference came from due to the academic dishonesty. In the first report, the percentages for passing math and passing reading were approximately 1%, and 7%, respectively, higher. The overall percent was also impacted - after the changes in grades, the percentage for $631-645 was down approximately 6%. A screenshot from prior to the replacement is shown below:
![spending_ranges_pycityschools](https://github.com/shireenkahlon/School_District_Analysis/blob/main/spending%20ranges%20pycityschools.png)
A screenshot from after the grade replacement is attached below:
![spending_ranges_challenge](https://github.com/shireenkahlon/School_District_Analysis/blob/main/spending%20ranges%20challenge.png)
### Scores by school size
* The school size was impacted. Before the replacement of grades, the passing math percentage was up by 1%, the passing reading percentage was up by 6%, and the overall passing percentage was up by 6%. A photo showing the grades correlated with school size prior to the replacement is shown below:
![size_summary_pycityschools](https://github.com/shireenkahlon/School_District_Analysis/blob/main/size%20summary%20pycityschools.png)
A photo of the impact the grade replacement had in the average grades per school size is attached below:
![size_summary_challenge](https://github.com/shireenkahlon/School_District_Analysis/blob/main/size%20summary%20challenge.png)
### Scores by school type
* The Charter school percentage of passing reading and overall passing was also affected by the academic dishonesty policy. Both categories were down by approximately 3% after removing 9th graders’ scores from the data. A photo from how the report showing the grades in school type before the replacement is shown below:
![school_type_pycityschools](https://github.com/shireenkahlon/School_District_Analysis/blob/main/type%20summary%20pycityschools.png)
A screenshot showing how the grade replacement impacted the grades per school type is attached below:
![school_type_challenge](https://github.com/shireenkahlon/School_District_Analysis/blob/main/type%20summary%20challenge.png)

## Summary:
There were many effects from replacing the grades. A major change was that Thomas High School dropped six places down after replacing the grades, compared to other schools. The grades dramatically dropped how well Thomas was performing compared to other schools. Due to the replacement, the school may receive more or less spending (based on how budgets will be increased/decreased) due to the grade replacement. The overall passing percentage was down 7% in the range that Thomas High School would apply to which could make for a dramatic change in funding. A couple of other changes from the grade replacement are that district schools were not impacted, however charter schools’ overall passing and percentage of passing reading went down both by 3%, which may impact funding. Finally, the grades of the overall school were brought down due to the academic dishonesty policy, which may impact funding which has a direct impact on other areas of the school, such as extra-curriculars and athletics. In conclusion, dropping the 9th graders from Thomas High School has impacted every category that has been analyzed and could possibly impact the school in multiple ways - especially regarding funding
