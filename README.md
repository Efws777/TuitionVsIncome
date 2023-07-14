**Average Cost of Tuition Compared to Average Income** 
<br>Adrian Martinez 
<br>Evan Shields
<br>April 11, 2023


**Introduction**
After completing high school, many students seek higher education to further their knowledge in specific areas to achieve a desired career. However, the cost of higher education varies in different states in the US, with some states having higher tuition rates than that of other states. Similar to tuition rates, some states have a higher average household income than other states. 
The purpose of this paper is to answer the question: Is there a correlation between tuition rates and average income? Meaning as average income across a state increases, does the cost of tuition also increase?. The results of this analysis may help current high school students when planning their undergraduate education, as it helps visualize which states  tend to have more expensive tuition, as well as provides a general cost of living for various states in the country, demonstrated through the average household income. 

**Methods**
The first set of data was compiled from the National Center of Education Statistics Annual Digest. The data measures the cost of university tuition for full time students from every state in the United States ranging from the year 2013 to 2021 for three different types of  universities: private, public in-state, and public out-of-state . For each state, tuition costs are broken up into fees/tuition and room/board. 
The second data set was collected by the United States Census Bureau, based off of the population survey from the previous calendar year. The data demonstrates the average household income in each state from 1984 to 2018. It lists these amounts in terms of 2018 dollars, adjusted for inflation, and current dollars, the actual income in the year the data was collected.
Both data sets do not mention any potential sources of bias. 

**Results**
Through our analysis of 2018 median household income we have found that the average median annual household income across the fifty states and D.C. in 2018 was $64,411. The standard deviation is $10,363. In looking at 2018 data for college tuition/fees and room/board, we have found the combined costs for private colleges, on average across all fifty states (excluding Wyoming) and D.C., to be $39,077 per year. The standard deviation is $11,352. For in-state public colleges, the average in 2018 was a little more than half of that of private colleges at $19,947. The standard deviation is $3,530. For out-of-state public colleges, the 2018 average was $35,475. The standard deviation is $6,413. Note that these figures from the college data do not account for any scholarships or financial aid that students may receive or any other costs associated with college (e.g, book or transportation). They are solely based on four factors: tuition, fees, room, and board. 
As expected, public in-state colleges cost the least on average while private colleges cost the most. The standard deviations also make sense. A lower standard deviation for the cost of public in-state colleges is logical since those costs are generally closer to each other in order to maintain competition with other colleges. Meanwhile, a higher standard deviation for the cost of private colleges is logical since many private schools try to differentiate themselves from other colleges by marketing their name recognition out to prospective students. The main purpose of this analysis is to see how much of a correlation there is between median annual household income of each state and the cost of college in each state. We used three categories of colleges (private, in-state, out-of-state) to do this analysis and to identify any key differences or similarities between them.          


 
Above is the scatter plot for private colleges only with the regression line in blue. There is a noticeable upward trend (though fairly weak) in the data. The regression line equation is y=.4337x+11130. This means that for every dollar that median annual income increases, the cost of private colleges increases by 43.37 cents. The correlation coefficient (r value) for this scatterplot is .3998, indicating a weak positive correlation. Something interesting to note is that the three data points (clustered in the top right corner) representing places with the highest income (D.C., Maryland, and Massachusetts) are also among those with the highest average cost of private colleges.

Above is the scatter plot for in-state colleges only with the regression line in blue. There is a noticeable upward trend (still fairly weak) in the data. The regression line equation is y=.1499x+10290. This means that for every dollar that median annual income increases, the cost of private colleges increases by 14.99 cents. The correlation coefficient (r value) for this scatterplot is .44, indicating a moderate positive correlation. Something interesting to note is that there is a rather large empty space right in the middle where no data points are present, indicating that none of the 51 samples had a college cost that was near the average across all samples while at the same time having an average annual income close to the average across all samples.

Above is the scatter plot for out-of-state colleges only with the regression line in blue. There is a noticeable upward trend (a little stronger than the first two scatter plots) in the data. The regression line equation is y=.3016x+16180. This means that for every dollar that median annual income increases, the cost of private colleges increases by 30.16 cents. The correlation coefficient (r value) for this scatterplot is .4706, indicating a moderate positive correlation. Something interesting to note is that the correlation between college cost and average annual income gets weaker as annual income increases, as the residuals between the regression line and the data points get larger and larger, especially in the $60000-$70000 range.

**Discussion** 
The main purpose of this analysis is to discover if there is a relationship between the average household income in each state when compared to the average cost of college tuition in each state. Public colleges had the lowest tuition while private colleges had the highest average cost of tuition. When analyzing the cost of private college tuition cost vs household income, we discovered that there was a weak positive correlation. As household income increases, the cost of tuition at a private college increases 43.37 cents. There were three outliers, D.C., Maryland, and Massachusetts, where both income and tuition were the highest. When analyzing the cost of public in-state colleges to household income, the average cost of tuition increases 14.99 cents for every extra dollar earned. Our correlation coefficient of 0.44 indicated a positive correlation. When looking at out-of-state tuition compared to the average income, the cost of tuition rose 30.16 cents when the average income increased. There was a moderate positive correlation between tuition and income. Generally, the average cost of tuition increased as the average household income increased across the United States. 
To improve this study, the data from a range of years could be considered rather than using a single year. Using more recent years would provide more accurate and relevant conclusions. A broader dataset containing a variety of universities in each state would broaden the dataset, creating accurate conclusions. A follow up study that could be carried out is discovering how the average cost of tuition varies amongst students from different backgrounds, such as racial, ethnic, or  nationality. 



References 
KenmoreToast. (2023, January 17). AVG cost of Undergrad College by State. Kaggle. Retrieved 
February 12, 2023, from https://www.kaggle.com/datasets/kfoster150/avg-cost-of-undergrad-college-by-state 
U.S. Census Bureau. (2019). Table H-8. Median Household Income by State. Census.gov. Retrieved February 13, 2023, from https://www2.census.gov/programs-surveys/cps/tables/time-series/historical-income-households/h08.xls

Appendix 
https://github.com/Efws777/DATA363-Project/blob/main/DATA363Project.Rmd 
R version 4.2.2 (2022-10-31)

