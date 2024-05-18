# pandas-challenge
In this challenge we have data of a school district and we analysed the data to show trends in school performance. we have follwed following steps to complete pandas challenge
1. . Usig the merge function we joined student_data table and school_data table to make school_data_complete
2. Then we calculated district summery by using functions like nunique(), count(), sum(), mean(). Using dataframe we created new dataframe named district_summary.
3. In school summary we used 'groupby' on school_name to calculate values for each school and created dataframe per_school_summary.
4. to calculate highest and bottom performing school we used sort_values on dataframe per_school_summary in decending and ascending order respectively 
5. to calculate math score and reading score by grade we first seprated 9th, 10th, 11th and 12th graders then used groupby for each grade scores and calculated mean.
6. by using bins, lables and cut we calulated scores by school spending and score by school size. and created respective dataframe
7. in the end we calculated scores by school type by ising groupby on school type and mean function on average scores and % passing. 