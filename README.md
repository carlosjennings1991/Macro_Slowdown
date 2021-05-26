# Macro Slowdown

Exploring the connection between workforce growth, population growth, economic growth and industry. 

Land, labor, capital, and entrepreneurship. Those are the four pillars of economic growth. While economic crises come and go, the underlying inputs remain the same. With this study, we're going to explore how population colors the economic picture. We attempt to understand its ebbs and flows, how that affected our economic past, and what it tells us about our economic future. 

*Land, labor, capital, and entrepreneurship. The ingredients of our economic stew.*

<img src="https://github.com/carlosjennings1991/Macro_Slowdown/blob/main/the_four_horsemen%20copy.png">

___

### Sources: 

Source Data Here - 
<br>
Analysis & Charts Here - 
<br>
Finished Dashboard - 
___

### Tools Used: 

- [x] Excel
- [x] Pandas
- [x] PostgreSQL
- [x] Tableau
___

### Population Growth

The increase in US population has more than doubled since 1950, albeit with some decades greatly exceeding the growth of others. This story is a mix of two factors, natural increase (births exceeding deaths) and immigration. First, lets look at the the yearly growth rates since 1950. 

<img src="https://github.com/carlosjennings1991/Macro_Slowdown/blob/main/Charts/Pop_Growth_Rate.png" width="609" height="345">

As we can see, growth rates tend to be higher on the left side of the chart, i.e the 1950s and 1960s. There's a notable uptick in growth rates in the beginning of the 1990's but this is followed by a return to the general downward trend. 

Next, lets look at how the growth rate compares to the US fertility rate, which is simply a measure of how many children an American woman can expect to have in her lifetime. 

##

<img src="https://github.com/carlosjennings1991/Macro_Slowdown/blob/main/Charts/Growth_vs_Fertility_Rate.png" width="630" height="345">

We can see that the high growth rates of the 1950's and early/mid 1960's are closely mirrored by high fertility rates during this time. While there is a modest rebound in fertility rates from 1983 to 2007 (1.80 to 2.12), the major source of growth during this period (especially the 1990's) comes from immigration. 

Of course, people have kids because they believe they can support that child. Besides asylum seekers, people immigrate for economic reasons. So let's look at the population growth rates vs economic growth rates

##

<img src="https://github.com/carlosjennings1991/Macro_Slowdown/blob/main/Charts/Growth_vs_Econ_Growth.png" width="738" height="345">

Given the nature of economic cycles, this above chart is a little difficult to read, so let's see the above chart but with trendlines for both growth rates. 

<img src="https://github.com/carlosjennings1991/Macro_Slowdown/blob/main/Charts/Growth_vs_Econ_Growth_with_trendlines.png" width="738" height="345">

As we can see above, as economic growth has declined, so has population growth. The extent to which this is a causal loop is unknown, and there are many factors causing both, but there is undoubtedly a connection between the two. 
___

### Workforce Growth

Understanding the connection between population growth and economic growth cannot overlook the size of the workforce. Generally speaking, the workforce is able-bodied men and women between 18 and 65 years of age, who are not in school. These are the people earning and most importantly  ***spending*** a paycheck. 

Below, we can see the 5 year rolling average of the yearly growth of the US workforce. 

##

<img src="https://github.com/carlosjennings1991/Macro_Slowdown/blob/main/Charts/workforce_growth_rate.png" width="591" height="345">

As we can see, there is an upward trend, peaking in the late seventies, and a downward trend thereafter. Growth levels are particularly high between the late-sixies to early-eighties, were growth rates remain above 2 percent per year. 

Now lets see how this compares to the fertility rate. 

##

<img src="https://github.com/carlosjennings1991/Macro_Slowdown/blob/main/Charts/workforce_growth_fertility.png" width="591" height="345">

The above chart tells us three unique stories. 

1. The baby-boomers, those born in the high-fertility era from the late 40's to early 60's, caused the workforce to dramatically increase when they entered the job market.

2. Women of multiple generations, not just female Baby-Boomers, entered the workforce beginning in the mid-sixties, a trend which continued up until the mid-eighties when that previously untapped supply of workers ran dry. 

3. While the Baby-Boomers grew up in large families, they had fewer kids than their parents. So naturally, workforce growth rates would be smaller when the children of the Baby-Boomers (the Millenials) enter the workforce. 

___

### Labor Force Participation

It's important to note the difference between labor force participation and workforce. While the workforce is the total number of workers in an economy, the labor force participation rate is the ***percentage of potential workers*** actually working. So those who are temporarily unemployed would *lower* the labor participation rate. Secondly, those who get laid off and give up looking for a new job exit the labor force. These people lower the size of the overall workforce but not the labor force participation rate, so keep that in mind. 

First things first, let's look at the labor force participation rate over the years. 

##

<img src="https://github.com/carlosjennings1991/Macro_Slowdown/blob/main/Charts/labor_participation_rate.png" width="591" height="345">

As we can see in the above graphic, the participation rate is basically flat until the mid-sixties where it begins to increase. This of course is due to a much larger percentage of women entering the workforce. However, this increse is not as dramatic as the increase in the size of the workforce and peak much later. For instance, labor force participation hits an all-time high of 67.1% in 2000, shortly before the dot-com bubble burst. 

Now let's see what, if any, correlation there is between economic growth and labor force participation

##

<img src="https://github.com/carlosjennings1991/Macro_Slowdown/blob/main/Charts/labor_participation_and_gdp_growth.png" width="738" height="345">

___

### Real Growth Rates

___

## Predictions

