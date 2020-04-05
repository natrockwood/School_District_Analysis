# School_District_Analysis
This is an analysis using Python for Module 4 of this course.
In the module, we calculated summaryies for a total of 39,170 students from 15 different schools.

With the use of DataFrames, we displayed the District Summary, School Summary, a list of High and Low Performing Schools, Math and Reading Scores by Grade, Scores by School Spending, Scores by School Size, and lastly, Scores by School Type.

#### District Summary
|Results      |Schools|Students|Total Budget|Ave. Math Score|Ave. Reading Score|Passing % Math|Passing % Reading|Overall Passing %  |
|-------------|-------|--------|------------|---------------|------------------|--------------|-----------------|-------------------|
|**Module**   |15     |39,170  |$24,649,428 |79.0           |81.9              |75%           |86%              |65%                |
|**Challenge**|15     |39,170  |$24,649,428 |78.9           |81.9              |74%           |85%              |64%                |

#### School Summary
##### Module
![School Summary_M](https://github.com/natrockwood/School_District_Analysis/blob/master/Module%20-%20School%20Summary.PNG)
##### Challenge
![School Summary_C](https://github.com/natrockwood/School_District_Analysis/blob/master/Challenge%20-%20School%20Summary.PNG)

# PyCity Schools Challenge Questions
In this challenge, we were instructed to remove the values of all 9th graders from Thomas High School for their Math and Reading Scores to test if this impacts the larger picture.
### How are the District and School Summaries affected?
However, we can summarize from the results that the impacts are very minor. In the **School Summary** tables, the only changes are in Thomas High School since those are the only values that we've changed.
### Recalculating the high- and low-performing schools.
##### How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance, relative to the other schools?
Before replacing values for the Thomas High School 9th Graders, Thomas High School was part of the Top 5 schools, Top 2, to be exact.
However, after replacing the values, Thomas High School dropped to 8th place. 
###### Initial Top 5
![Top 5 Schools_M](https://github.com/natrockwood/School_District_Analysis/blob/master/Module%20-%20Top%205.PNG)
###### Challenge: Top 5
![Top 5 Schools_M](https://github.com/natrockwood/School_District_Analysis/blob/master/Challenge%20-%20Top%205.PNG)
###### Bottom 5 Schools
The bottom 5 schools still remain the same.
![Bottom 5](https://github.com/natrockwood/School_District_Analysis/blob/master/Module%20-%20Bottom%205.PNG)
### Recalculating the scores by grade, scores by school spending, scores by school size, and scores by school type.
#### How does replacing the ninth-grade scores affect the...
##### Math and Reading Scores by Grade?
Thomas High School did not have any values for the 9th graders' reading scores nor their math scores.
###### Scores by School Spending?
Since Thomas High School was part of the 'Per Student Spending Ranges' of $630-$644, the Average Math and Reading scores slightly change. However, the Passing % Rates changed somewhat dramatically.

|Spending Range ($630 - $644) |% Passing Math|% Passing Reading|%Overall Passing|
|-----------------------------|--------------|-----------------|----------------|
|Module                       |74            |84               |63              |
|Challenge                    |67            |77               |56              |

All percentages decrease by around 7%.
###### Module
![Spending](https://github.com/natrockwood/School_District_Analysis/blob/master/Module%20-%20Spending%20Summary.PNG)
###### Challenge
![Spending](https://github.com/natrockwood/School_District_Analysis/blob/master/Challenge%20-%20Spending%20Summary.PNG)
###### Scores by School Size?
Like all other variables, the percentage of students that pass math and reading decrease after the 9th grader grades were removed.
###### Module
![Size](https://github.com/natrockwood/School_District_Analysis/blob/master/Module%20-Size.PNG)
###### Challenge
![Size](https://github.com/natrockwood/School_District_Analysis/blob/master/Challenge%20-Size.PNG)

|Size: Medium (1,000-2,000)   |% Passing Math|% Passing Reading|%Overall Passing|
|-----------------------------|--------------|-----------------|----------------|
|Module                       |94            |97               |91              |
|Challenge                    |88            |91               |85              |

All percentages decreased by 6%.
###### Scores by School Type?
Since Thomas High School is a Charter School, the Passing % for Math and Reading decrease.
###### Module
![Type](https://github.com/natrockwood/School_District_Analysis/blob/master/Module%20-%20Type.PNG)
###### Challenge
![Type](https://github.com/natrockwood/School_District_Analysis/blob/master/Challenge%20-%20Type.PNG)

|Charter Schools              |% Passing Math|% Passing Reading|%Overall Passing|
|-----------------------------|--------------|-----------------|----------------|
|Module                       |94            |97               |90              |
|Challenge                    |90            |93               |87              |

All percentages decrease by 3-4%.
