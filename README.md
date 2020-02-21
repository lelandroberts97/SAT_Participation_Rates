# Project 1: SAT & ACT Analysis
## Problem Statement
In March 2016, a new format for the SAT was released. Scores have been historically low in Utah, and the State wants to know where to spend their money to best increase participation rates for the SAT.
## Executive Summary
The data I examined for analysis were the scores and participation data for the 2017 and 2018 ACT and SAT standardized tests. I first took a look at the data to get a feel for it and see if there were any obvious issues. There were a few incorrect datatypes and incorrect values I had to fix. I also renamed the columns so they were more intuitive and easier to work with. After cleaning the data, I combined the 4 diferent tables into a single table. Next, I did some exploratory data analysis. I examined the descriptive statistics and sorted the data to find high or low participation rates. I ended up creating a new column to show the change in participation from 2017 to 2018 and found a few states with very large increases. This provided some direction for where I would do outside research later. I then visualized the data by making several different types of plots. One of the most useful was the Choropleth map showing the participation rates for each state on the map of the US. Finally, I did some outside research on a few states, including, but not limitted to, the states with large increases in participation. I found that large increases were due to contracts the state made with the company administering the test allowing the state to offer the test for free and mandate it to juniors in high school. This is the case for most of the states with very high participation rates. From this I was able to draw some conclusions on how to increase participation rates in the state of Utah.
## Data Dictionary
|Feature|Type|Dataset|Description|
|---|---|---|---|
|state|object|2017/18 SAT/ACT|State in the United States where test was taken|
|sat17_participation|float|2017 SAT|Percent of high school seniors to take the SAT in 2017|
|sat17_reading_and_writing|int|2017 SAT|Average score out of 800 for the reading and writing section of the 2017 SAT|
|sat17_math|int|2017 SAT|Average score out of 800 for the math section of the 2017 SAT|
|sat17_composite|int|2017 SAT|Score out of 1600 for the combined score of the 2017 SAT (including math and reading and writing)|
|act17_participation|float|2017 ACT|Percent of high school seniors to take the ACT in 2017|
|act17_english|float|2017 ACT|Average score out of 36 for the english section of the 2017 ACT|
|act17_math|float|2017 ACT|Average score out of 36 for the math section of the 2017 ACT|
|act17_reading|float|2017 ACT|Average score out of 36 for the reading section of the 2017 ACT|
|act17_science|float|2017 ACT|Average score out of 36 for the science section of the 2017 ACT|
|act17_composite|float|2017 ACT|Score out of 36 (calculated by taking the arithmetic mean on all four sections of the 2017 ACT)|
|sat18_participation|float|2018 SAT|Percent of high school seniors to take the SAT in 2018|
|sat18_reading_and_writing|int|2018 SAT|Average score out of 800 for the reading and writing section of the 2018 SAT|
|sat18_math|int|2018 SAT|Average score out of 800 for the math section of the 2018 SAT|
|sat18_composite|int|2018 SAT|Score out of 1600 for the combined score of the 2018 SAT (including math and reading and writing)|
|act18_participation|float|2018 ACT|Percent of high school seniors to take the ACT in 2018|
|act18_composite|float|2018 ACT|Score out of 36 (calculated by taking the arithmetic mean on all four sections of the 2018 ACT)|
## Conclusions & Recommendations
<p> The midwest has low SAT participation and high ACT participation for both 2017 and 2018. This means that there is a lot of opportunity to increase SAT participation. Colorado and Illinois has lead the way with about 90% increase in participation from 2017 to 2018. This is due to mandating the SAT for all juniors starting in the 2016/2017 school year. The state also offers the test for free. This allows for students with low income backgrounds to take the SAT, and has clearly led to an increase in participation. I recommend the State of Utah to follow this trend and mandate the SAT for all juniors and provide it for free. This entails making a contract with College Board. <p/>
<p> I also found that Ohio offers the SAT for free, but it offers students a choice between the ACT or the SAT. Since historically students prefer the ACT, they continue to choose what is familiar and SAT participation rates are still very low. Utah already has a contract with the ACT Company, and the ACT is historically very popular. Therefore, College Board will have to wait to make their bid until that contract expires (much like Illinois). <p/>
<p> Further research is necessary to find ways in which the SAT is a better measurement of success than other standardized tests toincrease the chance of the state choosing the SAT. <p/>

*This was a project completed through General Assembly's Data Science Immersive program.*