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

YoY growth rates can be erratic, so those are represented by the highly opaque red line in the background. The solid red line shows the 1950-2020 trendline, which is slowly decreasing. At first once might conclude that there is no correlation between growth rates and labor-force participation rates. 

However, that isn't quite true. Before women joined the work-force starting in the mid-sixties and after that process had completed by the mid-eighties economic downturns *do* correlate with decreases in the participation rate. For instance, the 1949, 1954, 1957, 1961, and 1971 recessions do show a dip in participation. 

Despite the 1974-75 and early 1980's recessions being particularly severe (especially on Manufacturing), participation rates don't budge - but they don't increase either. Those deep recessions temporarily halt the increase in the participation rate. There is a reason for this, those recessions primarily affected men, leaving women who were primarily entering the service industry to continue to push up the participation rate. 

Moreover, after the mid-eighties recessions do trigger a decline in labor force participation. We see slight dips during the early 90's recession, the early 2000's recession, 2008, and the coronavirus-induced lockdown recession of 2020. 

##

Interestingly, while there was a dramatic upturn in the labor participation rate that was culturally unprecedented in a peace-time setting, it has to be understood in context. The below chart shows overall workforce against the backdrop of the total US population. 

<img src="https://github.com/carlosjennings1991/Macro_Slowdown/blob/main/Charts/Population_and_Workforce.png" width="738" height="345">

With this context, we see the increase in the labor force as a percentage of the overall population looks a but more muted. The ratio between workforce to population hits a low in 1959 of 0.38 to 1, it narrows to only 0.51 to 1 in 2000. In fact, it's been essentially flat between 1986 and 2019, oscillating between 0.49 and 0.51 during those years. 

___

### Real Growth Rates

Imagine you own a business. How do you grow your business? Easy - get more customers. If you simply attract more customers, you can grow your business without having to do the difficult tasks of innovating or lowering your costs. 

When it comes to a country like the United States, the easiest way to grow an economy is simply to have more people. Even if they aren't in the workforce, everyone spends money. Even babies, since someone is spending a lot of money for them. 

So when it comes to GDP figures, you have to keep workforce growth in mind. Subtracting workforce growth from gdp growth yields a figure which I call 'Real Growth'. Real Growth better reflects productivity per-capita than headline GDP Growth. 

For starters, lets review the GDP chart below. 

#

<img src="https://github.com/carlosjennings1991/Macro_Slowdown/blob/main/Charts/Yearly_Growth_Rates.png" width="700" height="345">

We can see that growth tended to be higher before the 1980s, albeit with more frequent recessions. Conversely growth has been lower from the 1980s until now, but with fewer recessions. The red line indicates the overall trend line. 

Now, lets look at the same chart but with the added layer of workforce growth rate. 
#

<img src="https://github.com/carlosjennings1991/Macro_Slowdown/blob/main/Charts/gdp_growth_and_workforce_growth.png" width="738" height="345">

From the above we can see that the ratio between workforce growth and overall gdp growth has been uneven over time. Now lets *subtract* the workforce growth rate from the GDP growth rate and chart the resulting figures. 
#

<img src="https://github.com/carlosjennings1991/Macro_Slowdown/blob/main/Charts/real_growth_with_trendline.png" width="700" height="345">

So what does this tell us? This shows that when factoring for workforce growth rate, the slowdown in real growth is a gentler decline compared to the slowdown in headline gdp growth. Sure, real growth going down from about 2.2% in the 1950's to 0.5% in the 2010's, but so is population and workforce growth.

We can also see that the 1950's were very uneven, the period between 1970 and 1982 basically saw no real growth, and the period between 1983 and 2007 witnessed remarkably consistent real growth. 

If this seems like heartening news, keep this in mind - workforce growth *should* be higher. Consequently, real growth *should also* be lower. Since the 1980's millions of working-age, able-bodied people (mostly men) left the workforce. Not only is this a drag on headline growth since those are millions of people not earning and spending a paycheck, but bodes ill for future growth. 
___

## Predictions

**1. Workforce Growth Rate will continue to decline, even going negative in the 2020's.**
This is due to a smaller cohort of people entering the workforce (Gen Z) and a larger cohort leaving it (Baby Boomers). 

**2. Workforce as a percentage of the population will decline.**
While it's unlikely we'll see a ratio as low as 0.38 to 1, since that figure was at the height of the baby boom, were there were lots of children who weren't working, we'll see a figure in the mid-40's by the middle of this decade. 

**3. Economic Growth will be productivity driven, not population driven.**
Women entering the workforce and baby boomers entering the workforce *at the same time* definitely lifted growth. Coupled with large-scale immigration after 1965, and you have a triple-whammy of forces positively effecting the economy. However, an economy cannot rely on this sort of growth in the long run. 

Future growth will be dependent on productivity growth since all sources of workforce growth have been spent. Even immigration will be less of a factor, as most immigrant-sending countries (Mexico, India, China, etc) experienced baby-busts not long after the United States. 

**4. It'll get worse before it gets better**
A declining population means fewer customers for most businesses. Fewer customers = layoffs, business closures, debt defaults. This is how you get a deflationary spiral.

Secondly, fewer customers will prompt many businesses to automate, putting more people out of work. Of course, this is bad for those laid-off workers, and we actually have a terrible track-record of retraining people for new careers. 

However, automation is expensive. A business automates because of two things 1.) They believe they can save money in th long-run, and 2.) There will be sufficient demand in the future. 

Declining demographics impact both of those points. A business can secure capital to invest in automation because capital is plentiful, at the moment. Capital is typically generated from savings. Who saves? People at the height of their earning potential, which is typically the years before retirement. A simple rule of thumb is that young workers consume, middle-aged workers produce, older workers invest. It's the investment of older workers which has created an oversupply of capital in the world economy. Why is this? It's because older workers need to save for retirement. The closer one approaches retirement, the more one saves for retirement. When the population has a lot of people (Baby Boomers) on the verge of retirement relative to the overall population, you get an oversupply of capital. That capital needs something to invest in to get a return. 

*Retiring Baby Boomers, the cause and solution to all economic problems*

<img src="https://github.com/carlosjennings1991/Macro_Slowdown/blob/main/Charts/retiring_baby_boomers.jpeg" width="422" height="250">

##

However, this flips the day that person actually retires. Instead of generating an excess of capital, that person is now drawing down capital. When do people retire? Usually in their mid-sixties. That means by the mid 2020's, most baby boomers will have retired. We will go from capital over-supply, to capital under-supply. This means the price of money will increase. This means business will typically have a harder time getting the money to invest in automation. Automation would have to become dramatically less expensive for it to continue at the same rate it has in the past few decades.

Less customers spurring less demand will surely prompt cost-cutting measures from businesses. However, automation only saves money in the long-term. It's very expensive up front. Furthermore, the more physical items automation touches in the production process, the more expensive it is. This is why manufacturing automation is very expensive. Conversely, automating service industry jobs with few physical inputs will be the automation of the future. 

While the economic adjustment will be painful in the near to medium term, it will be beneficial for the typical worker in the long run. With less people around, the relative worth of each person increases. With less capital available for automtion, the average workers will have less to fear about losing their job (at least to automation), they might lose their job to lack of demand. 

This may sound dire, but I'm cautiously optimistic and you should be too. 

When the black death killed 1/3rd of Europe in the middle part of the 14th Century, average incomes ***rose*** substantially for the average person. It was the nobility, the landlords who suffered economically. All of the sudden, the survivors of the calamity had a lot more bargaining power. 

<img src="https://github.com/carlosjennings1991/Macro_Slowdown/blob/main/Charts/black_death_and_cash.png">

So for
