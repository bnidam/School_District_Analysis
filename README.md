# School_District_Analysis

## Overview of the project
This project consisted of analyzing a dataset of reading scores, math scores, and budget amounts for a school district consisting of 15 high schools with varying numbers of students.

### Purpose
In order to conduct the analysis, I created a Python environment, then used jupyter notebooks and pandas to perform a standard process for a dataset with a .csv format.  

### Description
The standard process has 3 steps:
1. Collect the data
2. Prepare the data
3. Analyze the data

In Step 1, the dependencies for panda and os were used to read the .csv file.

In Step 2, using various panda commands, the data was reviewed for missing data, duplicates, datatypes. Any issues that might impact the analysis results were identified and resolved.

In Step 3, using more panda commands, the dataset was reviewed for analysis with summary statistics for the dataset as a whole and then sorted, filtered, and grouped in various ways, including scores by school type, by a particular school, by grade level.

## Summary
Below is my summary of the school district data, along with my recommendation for the further analysis based on my summary.

At a quick glance, this data shows some results that could be expected:

   Reading scores overall are higher than math scores, assuming from the minimums and maximums that the scoring is from 1 to 100.

   Charter schools have higher math scores than Public schools.

There are a few interesting results that are worth noting:

   Public schools have higher budgets than do Charter Schools, both average budgets overall and budgets for each grade. All budgets are between $817,615 and $991,918. It is unknown if this range is significant or not. 

   While Charter schools have higher average math scores, the difference in average scores by grade between Charter schools and Public schools is not that great. In fact, the biggest difference is in average math scores is only 8.71 points different.

    The number of students per school does vary greatly, ranging from 171 to 2,038.  

I recommend digging into the ratio of budget dollars per student and how that might correlate to both math and reading score levels. This analysis could go as far as budget dollars per student per grade per school, compared average math and/or reading scores per grade per school for each of the 15 schools in order to see if there correlation between math and/or reading scores and the budget dollars per student.


