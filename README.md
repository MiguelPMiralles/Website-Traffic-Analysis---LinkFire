# Website-Traffic-Analysis---LinkFire
This repository includes the responses to the take-home assignment for data science positions as hosted in StrataScratch: https://platform.stratascratch.com/data-projects/website-traffic-analysis

While the assignment demands the questions to be solved using Python, I found them suitable for SQL, as this is a single table with different dimensions (categorical and numerical) that can be grouped and sliced using the ´CASE WHEN´ and ´GROUP BY´ operatos, as the responses to the questions will show. Also, BigQuery is robust enough it can provide correlation coefficients.

# Assignment
The goal of this project is to understand this traffic better, in particular the volume and distribution of events, and to develop ideas how to increase the links' clickrates. With that in mind, please analyze the data using the Python libraries Pandas and SciPy where indicated, providing answers to the presented questions:

1) How many total pageview events did the links in the provided dataset receive in the full period, how many per day?
2) What about the other recorded events?
3) Which countries did the pageviews come from?
4) What was the overall click rate (clicks/pageviews)?
5) How does the clickrate distribute across different links?
6) Is there any correlation between clicks and previews on a link? Is it significant? How large is the effect? Make sure to at least test for potential linear as well as categorical (think binary) relationships between both variables.

# Data Description
The data set provided (traffic.csv) contains web traffic data ("events") from a few different pages ("links") over a period of 7 days including various categorical dimensions about the geographic origin of that traffic as well as a page's content: isrc.
