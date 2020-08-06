# How Has Covid-19 Changed America's Media Consumption Habits?

### Project Overview
The pandemic has changed the way Americans are living their lives. Stuck at home while restaurants are closed and office spaces are slow to reopen, Americans are adapting their behaviors by spending more of their time online and as a result, consuming more media. The United States is also approaching an election which may be, to many Americans, as important as any election before it.

I want to find out which historically important voter issues Americans are most focused on today and if it has changed when compared to recent election years. For this project I will use the New York Times API to retrieve data that is assumed to be representative of media content the average voter is consuming. I will focus on data from March, April, May, June and July in each of the previous four election years (2008, 2012, 2016, 2020) during the analysis.

### Questions I Want To Answer
1. Which historically important voter issues are becoming more or less frequent in media publications when compared to recent election years?
2. Which historically non-important topics are becoming more or less frequent in media publications when compared to recent election years?
3. Assuming the New York Times publishes news content based on the average voter's preference, how has the average voter's content preferences changed over time?

### Data Source
The New York Times API provides us with raw data related to all published articles by month and year. I used API requests to pull raw data on all articles published between March - July of 2008, 2012, 2016 and 2020. Collecting the individual keywords and calculating their counts overtime allowed me to plot these keywords in a way that will give the reader a visual representation of the average American voter's media consumption habits.

### If I Had More Time...
I would like to use Natural Language Processsing to analyze these same questions. Part of the returned data from a NYT API call is the lead paragraph of each article. I would like to use the Natural Language Toolkit to complete my own keyword analysis instead of relying on NYT's keywords. Using NLP algorithms I will be able to analyze for myself what people are talking about most.


### Image Samples:
![Top NYT's Keywords](https://github.com/loganbonsignore/Media_Consumption_Analysis/blob/master/Images/pies.png?raw=true)
![Covid vs Election Media Coverage](https://github.com/loganbonsignore/Media_Consumption_Analysis/blob/master/Images/covid_vs_elections.png?raw=true)

![Spotlight on small business](https://github.com/loganbonsignore/Media_Consumption_Analysis/blob/master/Images/economy_1.png?raw=true)

![Industries built for a pandemic](https://github.com/loganbonsignore/Media_Consumption_Analysis/blob/master/Images/economy_2.png?raw=true)

![Healthcare - At the forefront of american minds.](https://github.com/loganbonsignore/Media_Consumption_Analysis/blob/master/Images/healthcare.png?raw=true)
