# School_District_Analysis

#Overview
The school district analysis started with two raw data sets: students_complete and schools_complete. Applying the new pandas skills we learned in module 4, we took the raw data sets and analyzed them. The freshmen data as removed because they suspected the freshman of cheating. The variables included: the amount of money the school receives, the number of Students in the school and the difference between the Charter and District.

#Results
•	How is the district summary affected? In the original District Summary the average math score, the percent passing math, the percent passing reading, and the percent over all passing had scores of: 79.0, 75.0, 85.8, and 65.2, respectively. In the new District Summary with the freshman removed, all of these values went down to 78.9, 74.8, 85.7, and 64.9. This most certainly indicates the school boards suspicions may be true! 
•	How is the school summary affected? When the 461 freshmen students are removed for the dataset, the percent passing math went from 93.2 to 93.1, the percent passing reading went from 97.3 to 97.0, and the overall passing percent went from 90.0 to 90.6.
•	How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools? Interestingly enough, Thomas High School held up position at second place when compared to other schools, in spite of the overall passing score going from 90.9 to 90.6. 

##Results Continued
•	How does replacing the ninth-grade scores affect the following:
o	Math and reading scores by grade- both the math and reading scores for the 9th graders were replaced with the nan function.
o	Scores by school spending- No significant changes were made after adjusting for the suspected cheaters. 
o	Scores by school size- No significant changes were made after adjusting for the 9th graders.
o	Scores by school type – Again, no significant changes are seen in this data. It does however, show significant difference between the overall passing percent of District verses Charter schools

#Summary
•	The overall passing score for the freshman were taken out of the data set because the scores were high and raising the distribution
•	Distributing the money spent on students is more effective when schools spend a little but less
•	The number of students enrolled is important due to the teacher to student ratio
•	There is a proportional correlation between school size and spending money on students because having a large school and a high spending rate means the students overall score is approximately 60%. Smaller schools tend to spend less per student this does however result in higher scores overall.
