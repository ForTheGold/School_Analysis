# School_Analysis
An analysis of school the effects of school funding on performance in Python, Pandas, and Jupiter Notebook

## Overview

Maria is the head of data science for a city school district and that role includes analyzing data from a variety of different sources.  She has recently been charged with preparing, analyzing, and reporting on findings of standardized test data and to find patterns and present performance trends among the students.  These data are used to make data driven decisions at the school and district level.

### Background

Maria has given us information on the funding, Math and Reading test scores as well as a variety of other information on the schools that the students attend.  We are going to be using this data to find and showcase trends in the data and school performance.  Maria tells us that our findings will be used by the school board in order to make decisions regarding budgets and priorities.

### Note

While performing this analysis it came to our attention that some of the data was falsified.  The analysis was performed twice because of this.  In order to correct this problem the ninth grade test results were removed from the analysis.  The analysis with the results removed can be found in the PyCitySchools_Challenge.ipynb file found HERE.  The original analysis can be found in the PyCitySchools_Challenge_W_Incorrect_THS_Data.ipynb file found HERE.

## Results

As noted above the analysis was performed twice due to problems with the data.  Here is an outline as to how the results were changed with the second analysis.

* Effects on District Summary
The math score decreased by 0.1% and the reading by 0.2% amounting to a 0.3% decrease overall.  
District Summary - Thomas High School 9th Graders Removed
![District Summary Fixed](https://github.com/ForTheGold/School_Analysis/blob/main/Resources/District_Summary_Fixed.png)
District Summary - Original
![District Summary Original](https://github.com/ForTheGold/School_Analysis/blob/main/Resources/District_Summary_Orig.png)

* Effects on School Summary
The math average decreased about 0.1% and the reading average less than 0.1%.  The percent passing math decreased by less than 0.1% and the percent passing reading decreased by less than 0.3% amounting to an overall decrease of just over 0.3%.  
School Summary - Thomas High School 9th Graders Removed
![School Summary Fixed](https://github.com/ForTheGold/School_Analysis/blob/main/Resources/School_Summary_Fixed.png)
School Summary - Original
![School Summary Original](https://github.com/ForTheGold/School_Analysis/blob/main/Resources/School_Summary_Orig.png)

* Effects on Thomas High School’s Performance Relative to Other Schools
The average reading score was originally slightly higher than Shelton High School, but it ended up lower than Shelton High School in that category afterward.  The other changes were too small to play a major role relative to the other schools.

* Additional Effects:
	* Scores by Math and Reading Scores by Grade
The only change here is that the 9th grade scores are NaN (Not a Number) while there was a score previously.
Math - Thomas High School 9th Graders Removed

Math - Original

Reading - Thomas High School 9th Graders Removed

Reading - Original


	* Scores by School Spending
There was no effect on this category.  This is probably because the table does not measure accurately enough.
School Spending - Thomas High School 9th Graders Removed

School Spending - Original


	* Scores by School Size
The effect was also too small to be noticed in this category.
Size - Thomas High School 9th Graders Removed

Size - Original


	* Scores by School Type
No effect could be seen in this category either.
Type Fixed

Type Original


## Summary

The original analysis had some incorrect data associated with it, so the analysis was done a second time. There were a number of differences between the original analysis and the second analysis with some of the data removed.

### 0.3% Decrease Overall in the District Summary
It is amazing how impactful a single school can be on the entire district.  The data show that the falsification of the data at Thomas High School lead to an overall decrease of 0.3% overall for the entire district.  
District Summary - Thomas High School 9th Graders Removed
![District Summary Fixed](https://github.com/ForTheGold/School_Analysis/blob/main/Resources/District_Summary_Fixed.png)
District Summary - Original
![District Summary Original](https://github.com/ForTheGold/School_Analysis/blob/main/Resources/District_Summary_Orig.png)

### 0.1% Decrease in Math in the School Summary
The school summary shows us that there was a decrease in the number of students who were able to pass Mathematics overall.  This decrease amounted to approximately 0.1%.  
School Summary - Thomas High School 9th Graders Removed
![School Summary Fixed](https://github.com/ForTheGold/School_Analysis/blob/main/Resources/School_Summary_Fixed.png)
School Summary - Original
![School Summary Original](https://github.com/ForTheGold/School_Analysis/blob/main/Resources/School_Summary_Orig.png)

### 0.3% Decrease in Reading in the School Summary
One of the greatest changes in performance at Thomas High School with the new data was the decrease in percentage of students passing reading.  This decreased by 0.3%.  
School Summary - Thomas High School 9th Graders Removed
![School Summary Fixed](https://github.com/ForTheGold/School_Analysis/blob/main/Resources/School_Summary_Fixed.png)
School Summary - Original
![School Summary Original](https://github.com/ForTheGold/School_Analysis/blob/main/Resources/School_Summary_Orig.png)

### Average Reading Score Drops Below Shelton High School


### Thomas High School Does Not Change Ranking
Sometimes it is important what does not change along with what changes.  Thomas High School was originally ranked the number two school overall, and it is still ranked the number two overall.  It was closer to the number one school in terms of performance prior, but that does not change the fact that it did not change its ranking.  
Top Schools - Thomas High School 9th Graders Removed

Top Schools - Original
