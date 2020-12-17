# Carnegie Mellon University: Telling Stories with Data

CMU Telling Stories with Data Class, link to live site [Home Page](https://bripperg.github.io/tell_stories_CMU/)

# DataViz Exercise Number 2: Introduction to Public Data Vizs with Free Software

### Government Debt OECD

Notice the Americas, as compared to other continents!


<iframe src="https://data.oecd.org/chart/65F7" width="860" height="645" style="border: 0" mozallowfullscreen="true" webkitallowfullscreen="true" allowfullscreen="true"><a href="https://data.oecd.org/chart/65F7" target="_blank">OECD Chart: General government debt, Total, % of GDP, Annual, 2018</a></iframe>

### Government Debt-to-GDP Ratio

Government Debt-to-GDP is a great way to visualize relative debt between countries. 

An upward trajectory means countries' debts are rising faster than their respective GDP. Notice how Japan has more than doubled since 1995. The United States of America, Great Britain, and France all started taking on debt around 2007 (US stock market crashed at that time), potentially so that each country could stabilze their economy. Germany and Canada have been on downward trends since 2012 and 1996, respectively.

<div class="flourish-embed flourish-chart" data-src="visualisation/3748811" data-url="https://flo.uri.sh/visualisation/3748811/embed" aria-label=""><script src="https://public.flourish.studio/resources/embed.js"></script></div>


### Government Debt-to-GDP Ratio Take 2


<div class="flourish-embed flourish-chart" data-src="visualisation/3758309" data-url="https://flo.uri.sh/visualisation/3758309/embed" aria-label=""><script src="https://public.flourish.studio/resources/embed.js"></script></div>


Choosing the best chart to visulaize governemnt debt takes a few attempts. 

In the first attempt, I referenced a bar chart from the OECD webiste. It's extremely quick to notice the relative debt outliers, Japan and Greece. One note, we are specifically looking at 2018. This is important, because in order to keep bar charts manageable, we can really only look at one year. Even if we have mutliple years. Our readers can quickly distinguish the countries in relative debt, but they can't tell which countries are just having a bad year vs countries that have been consistently accruing debt. 

In the second attempt, I built a grid of line charts. Each chart has the same scale for both x and y. This chart is extremely benefitical! We are able to see individual countries clearly. We are also able to see how each country's ratio has been moving through time. The only limitation is that the chart layout makes it dificult to analyze what years had similar affects on countries. If one year caused mutliple countries to spike. 

In the final attempt, I built an overlayed line-chart. This, although providing a lot of crossing lines charts, provides data to understand how years affect multiple countries simaltanously. I was able to show how in 2011, 3 countries took on debt. Two have their ratios starting to recover, while one was still on an upwards trend. 

In my opinion, the grid of lines provides the best balance of data and simplicity. I was still able to point out how France, USA, and Great Britain each had to take on debt during 2008. We are also able to clearly see country's final data point with a tragetory. While the bar chart and overlay line chart each have helpful applications, the grid was great. 

