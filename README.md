# Summary & Recommendations for Pandas Challenge

Summary

As acting Chief Data Scientist for my city’s school district, I analyzed data across the 15 schools within the district with the goal of helping our school board and mayor make strategic decisions regarding future school budgets and priorities. 

Using a csv for student data as well as a csv for school data, I looked at trends across a few key dimensions: school type, number of students, school budget, per student budget, average math score, average reading score, % passing math, % passing reading, and % overall passing. 

Findings

* District Summary: the 15 schools in our district leverage a total budget of $24,649,428 to serve its 39,170 students. On average, our students have an average Math score of 79 and an average Reading score of 82, which translates to 75.0% of our students passing Math (passing meaning scoring 70 or higher), 85.8% passing Reading, and an overall passing rate of 65.2%.
* School Performance Summary: our district is home to 7 District schools and 8 Charter schools. The top 5 highest performing schools by overall pass rate are all Charter schools, with Cabrera High School leading the way with a 91.3% overall passing rate. The lowest 5 performing schools were all District schools, with Rodriguez High School having the lowest overall passing rate of 53.0%. Beyond the difference between school type in the highest and lowest performing schools, the highest performing schools have a lower average number of students than the lowest performers (1,641 vs. 3,852) and a lower average overall budget as well ($989,484 vs. $2,491,816). 
* Grade Performance Summary: While Math and Reading scores differ between schools, when we look at how students perform between grades 9 through 12 per school we don’t see much variance between grades. Most high schools vary at most 2 points total between grades.
* Scores by School Spending: Schools who spend less than $585 per student have higher Math scores, Reading scores, and overall passing rate. Additionally, the more schools spend per student, the lower their overall passing rate.
* Scores by School Size: Medium (1000-2000 students) and Small (<1000 students) schools have slightly better Math Scores and Reading Scores, but by far have a higher Math, Reading, and overall passing rate than large schools (2000-5000 students) in our district.
* Scores by School Type: Charter schools have higher Math scores, Reading scores, and overall passing rates than District schools. 

Recommendations

* Distribute student volume for larger, District schools
    * One of the most dramatic trends was between the performance of schools with 2000+ students and those with less, especially when it comes to the passing rates. Schools with 2000+ students only have an overall passing rate of 58.3% compared to the ~90% passing rate of Small and Medium sized schools. If we want all of our students to succeed and leave with a diploma, then we first must address the problem with oversized schools that seemingly leave some students behind. One option we have would be to redistribute student volume more evenly across schools and/or create new schools to take on student volume. 
* Avoid throwing money at the problem
    * There is no correlation between spending more and student success. In fact, schools that spend less per student tend to have better passing rates and test scores. Additionally, our lowest 5 performing schools are all District schools that have over double the budget of the top 5 performing schools. More spending doesn’t create more successful schools.
* Research and model Charter schools
    * On average, Charter schools are doing more with less - they tend to have higher scores and passing rates while having a lower budget per student. This particular data set only gives us so much information and further quantitative and qualitative research should be conducted to learn more about what makes Charter schools more successful.
