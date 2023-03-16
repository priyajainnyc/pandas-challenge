# pandas-challenge
Homework 4 for the pandas module of Datavis bootcamp

My Resources folder contains the two CSV files I used, schools_complete.csv and students_complete.csv - my script paths to these files.

A file called PyCitySchools.ipynb contains the main script to run the analysis. 

Below is the analysis summary and conclusions or comparisons drawn from the data.

Analysis Summary

We are analyzing data from a city’s school district to help the school board and mayor make strategic decisions regarding future school budgets and priorities. We have been asked to analyze the district-wide standardized test results, reviewing every student’s math and reading scores, as well as various pieces of information on the schools they attend. We are tasked with aggregating the data to showcase obvious trends in school performance.  

There are a total of 15 schools and 39,170 students with a total budget of close to $25M. The approximate average math score and % passing math are 80 and 75%, and the approximate average reading score and % passing reading are 82 and 85%, indicating higher performance in reading.

From the school summary, we see that of the 15 schools, 7 of them are at the district level, and 8 are at the charter level, with Holden High having as few as 427 students and Bailey High having as many as 4976 students. Generally, district schools have more students than charter schools, while charter schools have higher scores across all metrics.

The top 5 highest performing schools are all charter schools, while the bottom 5 lowest performing schools are all district schools. Cabrera High School, a charter school, has the highest overall passing rate at 91.33%, while Rodriguez High School, a district school, has the lowest overall passing rate at 52.99%.

Looking at scores by school spending, Bailey High School has the greatest budget of over $3M, while Holden High School has the lowest budget at just under $250K. Huang High School has the greatest budget per student, while Wilson High School has the lowest budget per student. Both Bailey and Huang High Schools have higher budgets but are bottom performing schools. The total district school budgets of over $17M is higher than charter school budgets of close to $7.3M; charter schools outperform district schools and spend about $40 less per student. 

For school scores by size, schools under 2000 students, generally charter schools, have much higher passing rates than those with student populations above 2000, generally district schools. And it is clear, that when looking at scores by school type, charter schools with an overall pass rate of over 90% outperform district schools with an overall pass rate of just under 54%.

Extracting from the analysis summary, below are several conclusions or comparisons drawn from the calculations.

From the school summary, we see that of the 15 schools, 7 of them are at the district level, and 8 are at the charter level, with Holden High having as few as 427 students and Bailey High having as many as 4976 students. Generally, district schools have more students than charter schools, while charter schools have higher scores across all metrics; we can deduce that as the number of students increases, student achievement decreases.

Looking at scores by school spending, when the budget per student increases student's average math score, average reading score, math passing rates, reading passing rates, and overall passing rates actually decrease; we can deduce that additional funding does not necessarily result in improved student achievement and perhaps the allocation of resources needs to be revisited.

Math passing rates are always consistently lower across every metric, but the difference between math and reading passing rates is greater among lower performing schools, large schools, and higher spending per student, which we can deduce, all seem to correlate. Average math and reading scores stay consistent across grade levels when grouped by school; we can conclude that there is no major improvement in scores from any school.
