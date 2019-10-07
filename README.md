<h1><center>DS 5500 Assignment 1</center></h1>

<h2><center>Problem 1</center></h2>

Received a score of 6 out of 13. Yes, some of the answers related to poverty, literacy rate and health did suprise me.

Question: In the last 20 years the proportion of people living in extreme poverty worldwide, has...?
Answer: been halved

It is very intriguing to find out that the percentage of people living in extreme poverty worldwide have reduced by
such a siginficant amount in the last 20 years. Some deeper analysis to understand the trend of percentage of people living in extreme poverty might reveal some interesting things.


Analysis:

Collected extreme poverty data which is percent of people earning less than $1.90/day. Aggregating extreme poverty
percent for each year will show us the trend with respect to time.

Note: Included only years where we have the data available for least 25 countries

![alt text](https://github.com/ItsmeKumar/DS5500-HW1/blob/master/plots/Q1.png)

The line plot clearly expresses how percent of people living in extreme poverty is chaning over the years. We can see from the above plot that there is infact a big decline in extreme poverty over the last 30 years, with biggest
change coming between the years 2000-2005.

<h2><center>Problem 2</center></h2>

Collected Gross domestic product (GDP) per capita in terms of purchasing power parity ($PPP) adjusted for inflation

![alt text](https://github.com/ItsmeKumar/DS5500-HW1/blob/master/plots/Q2.gif)
World map with each of the countries mapped to GDP per capita over the years gives various insights of the across regions

![alt text](https://github.com/ItsmeKumar/DS5500-HW1/blob/master/plots/Q2.png)
Line plot shows how GDP per capita is has increased over time in different continents of the world

Summary:

* The GDP per capita throughout the world increases at a higher rate during 1940-1960's
* African countries consistently had lower GDP per capita
* GDP per capita went down a bit during the recession of 1980 and 2007

Caveats:
* The disadvantage using a world map to visulaize GDP of countries is that, countries with smaller area will get masked by the bigger countries and makes it hard to get an understanding of the growth comparison
* The GDP per capita legend in terms of color in the world map was maxed out at $20K to reduce the effect of countries with very high values

<h2><center>Problem 3</center></h2>

![alt text](https://github.com/ItsmeKumar/DS5500-HW1/blob/master/plots/Q3.gif)
Scatter plot of life expectancy and gdp per capita with infant mortality rate as size is displayed for each of the continents

GDP and Life expectancy are both positively correlated, and are negatively correlated with infant mortality rate

Summary:
* Life expectancy increased siginifacntly during the 1940-1980 throughout the world
* Many African countries still have lower GDP, lower life expectancy and higher infant mortality comparitively
* Infant mortality has decreased gradually after 1950's

Trends and/or Outliers:
* Every other country in Oceania apart from Australia and New Zealand have siginficantly lower life expectancy and GDP
* Afghanistan in Asia is also very isloated in terms of GDP and life expectancy from rest of the countries

<h2><center>Problem 4</center></h2>

Analysed the trends of carbon emissions and coal consumption per person over the years and investigated if they are correlated in any manner 

![alt text](https://github.com/ItsmeKumar/DS5500-HW1/blob/master/plots/Q4.gif)
Scatter plot of CO2 emissions per person vs coal production per person seperated by coloring of continents

Summary:
* CO2 emission per person has slightly positive correlation with coal production per person
* Coal consumption is showing a sligtly decreasing trend in many counties during recent times
* Top 4 countries (Saudi Arbia, United States, Australia, Canada) in terms of carbon emissions except Saudi Arabia, have reduced their emissions per peson in recent years

Trends and/or Outliers:
* Carbon emissions per person in 2014 (latest year with available data) is highest for Saudi Arabia, but its coal production is one of the lowest. Even though Saudi Arabia is the world's largest exporter of oil, not surprisingly consumption of petroleum products represents the bulk of the countries' fossil-fuel CO2 emissions

<h2><center>Problem 5</center></h2>

I have used interactive plots to answer the previous problems.

Using interactive/dynamic visualizations versus static visualizations.

Advantages:
* Gives better and in depth understanding of the data
* Has more flexibilty to include more dimensions

Disadvantages:
* Too complex to build
* Hard to interpret in some cases

Relative Usefulness:
Use of either interactive or static visualizations mainly depend on the type of data and problem we are trying to solve. If static visualizations can do the job without compromising on the results we are trying to communicate, then it is better to go ahead with it. But, when the static visualizations are restricting us to include more information, interactive visualization would be more relevant.

