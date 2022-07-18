# An Analysis of School District Standardized Test Data

## Project Overview
Maria, a chief data scientist for a school district, is preparing all standardized test data for analysis, reporting and presentation to provide insights about performance trends and patterns to the school board. She asked for my help in analyzing the data on student funding and student’s standardized test scores. Per her request I aggregated the data and showcased trends in school performance. 

Unfortunately, after completing my analysis it was determined that due to evidence of academic dishonesty; the reading and math grades for ninth grader at one school, Thomas High School, should be ignored by replacing these scores with NaNs. Therefore, Maria has asked me to repeat the school district analysis and summarize how the requested change affected the overall analysis.

### Results
- How is the district summary affected?

As displayed below, although Total Schools, Total Students and Total Budget remained unaffected, as expected, there was a slight decrease in the average math score, and all passing percentages.


<picture>
 <source media="(prefers-color-scheme: light)" srcset="https://github.com/ODaniels852/School_Ditrict_Analysis/raw/main/Resources/district_summary_df.png">
<img alt="Shows the district summary before and after the change."/>

</picture> 

- How is the school summary affected?

The school summary was affected in a similar way as the district summary. Specifically for Thomas High School the Total Students, Total School Budget, and Per Student Budget remained unaffected, as expected. As shown below the average math score decreased slightly, the average reading score increased slightly, and all passing percentages decreased. 
 

<picture>
 <source media="(prefers-color-scheme: light)" srcset="https://github.com/ODaniels852/School_Ditrict_Analysis/raw/main/Resources/per_school_summary_df.png">
<img alt="Shows the school summary  results for Thomas High School before and after the change."/>

</picture> 

- How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?

Although, the passing percentages for the school all lowered slightly, after this change Thomas High School remained the 3rd top performing school based on Overall Passing %. This updated % of 90.630 wasn’t low enough to fall below Griffin High School’s Overall Passing % of 90.599.
 

<picture>
 <source media="(prefers-color-scheme: light)" srcset="https://github.com/ODaniels852/School_Ditrict_Analysis/raw/main/Resources/top_schools.png">
<img alt="Shows the district summary before and after the change."/>

</picture> 

- How does replacing the ninth-grade scores affect the following:
	- **Math and reading scores by grade.**
	As shown below, after replacing ninth-grade scores at Thomas High School the summaries of math scores by grade and reading scores by grade show Nan for 9th grade at Thomas High School. All other values remain unchanged.

	<sub>Math Scores by Grade</sub>
	<picture>
 	 <source media="(prefers-color-scheme: light)" srcset="https://github.com/ODaniels852/School_Ditrict_Analysis/raw/main/Resources/math_scores_by_grade.png">
	<img alt="Shows math scores by grade for the district."/>

	</picture> 


	<sub>Reading Scores by Grade</sub>
	<picture>
 	 <source media="(prefers-color-scheme: light)" srcset="https://github.com/ODaniels852/School_Ditrict_Analysis/raw/main/Resources/reading_scores_by_grade.png">
	<img alt="Shows reading scores by grade for the district."/>

	</picture> 


	- **Scores by school spending.**
	As shown below, after replacing ninth-grade scores at Thomas High School the summaries of scores by school spending remain unchanged.
 
	<picture>
 	 <source media="(prefers-color-scheme: light)" srcset="https://github.com/ODaniels852/School_Ditrict_Analysis/raw/main/Resources/spending_summary_df.png">
	<img alt=" Shows scores by school spending."/>

	</picture> 


	- **Scores by school size.**
	Like scores by school spending, as shown below, after replacing ninth-grade scores at Thomas High School the summaries of scores by school size remain unchanged.
 
	<picture>
	 <source media="(prefers-color-scheme: light)" srcset="https://github.com/ODaniels852/School_Ditrict_Analysis/raw/main/Resources/size_summary_df.png">
	<img alt="Shows scores by school size."/>

	</picture> 

	- **Scores by school type.**
	Like scores by school spending and size, as shown below, after replacing ninth-grade scores at Thomas High School the summaries of scores by school type remain unchanged.

 
	<picture>
	 <source media="(prefers-color-scheme: light)" srcset="https://github.com/ODaniels852/School_Ditrict_Analysis/raw/main/Resources/type_summary_df.png">
	<img alt="Shows scores by school type."/>

	</picture> 

##  Summary
Changes in the updated school district analysis after reading and math scores for the ninth grade at Thomas High School have been replaced with NaNs include
