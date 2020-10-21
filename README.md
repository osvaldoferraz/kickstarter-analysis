# Kickstarting with Excel

## Overview of Project
Analysis of a Data Set based on fundrasing campaings around the globe.

### Purpose
Louise is a playwriter that wants information on how she can get the best outcome for her play *Fever* Kickstarter Fundraising Campaing. To achieve that, she wanted to know how launch dates and funding goals would impact the success of the fundraiser.

## Analysis and Challenges
In order to answer Louise's questions, I used the Kickstarter Data Set to gather information about the outcomes based on launch dates and also outcomes based on goals.


### Analysis of Outcomes Based on Launch Date
For this analysis, I created a Pivot Table that summarized all the final outcomes - Success, Failed and Cancelled - for the plays, against months of the year that those plays had started their campaigns. This sample ranges from 2009 to 2017, totalling 1369 campigns, an amount that can give a good idea about the seasonality of these successful events.

![Launch Date PivotTable](https://user-images.githubusercontent.com/72593264/96397437-2b563e80-118f-11eb-9647-9553facee9b5.png)

To make the results clear, a line graph was created that clearly shows in what months we have the most successful campaings and also the most unsucceful ones too.

![Theater_Outcomes_vs_Launch](https://user-images.githubusercontent.com/72593264/96398080-99e7cc00-1190-11eb-997b-4f4844aac188.png)

Based on this graph, seasonality plays an important role in successful campaigns, with a big spike in the month of May bringing the most number of succesfull campaings. It is also worthwihle to notice that December is a month with very few successfull outcomes.
Seasonality does not seem to play a hughe role on failed campaigns though, as the line is almost the same during the whole year.

### Analysis of Outcomes Based on Goals

The analysis of outcomes based on goals reveals that goals can influence the success of a given campaign. The sample in the data set was very broad, ranging from less than $1k to more than $100k in goals. To narrow the data, taking in consideration that Louise's goal is arround $10k, I filtered the plays that would range from less than 1k up to 50k. Below is a line graph that reflects the success rate against various goals. 

![Outcomes_vs_Goals](https://user-images.githubusercontent.com/72593264/96680268-cd665a00-133a-11eb-8730-5592eef26349.png)

It is noticeble that the smaller the goal, higher the chance of a successful capaign. That seems to be true from less then 1k until 29.9k, with special attention to the very succesful range of 1k to 5k (73% success of rate). After that there is a new spike of successful capaings with goals between 30k and 44.9k.


### Challenges and Difficulties Encountered


## Results

- *What are two conclusions you can draw about the Outcomes based on Launch Date?*
Best month to begin a Fundraising Campaign for Theater is May.
The worst month to begin a Fundraising Campaign for Theater is December.

- *What can you conclude about the Outcomes based on Goals?*
Most successful Fundraising Campaigns for Theater had goals up to $5000.

- *What are some limitations of this dataset?*
The table does not have enough information to draw conclusions in an accurate way.
For example: Outcomes Based on Goal graph can give a false impression on the outcomes, because the data is not properly weighted. 
It shows that 73-76% of the campaign goals below $5000 were successful, seconded by goals from $35000 to $45000, with a success rate of 67%.
However, the Kickstart table gives a sample of 317 successful entries below $5000, but only 6 succesful entries with goals between $35000 and $45000 (see below)
This discrepancy between these two samples gives a false impression that goals between 35-45k can be almost as successful than its pair below 5k, which is not necessarily truth.

![35_45k_6 entries](https://user-images.githubusercontent.com/72593264/96394998-0ced4480-1189-11eb-83b7-2b4233ddea31.png)

- *What are some other possible tables and/or graphs that we could create?* Statistical graphs could give a better picture than a line graph for Outcomes vs Goals. Using data from successful theater capaings in the U.S., this type of graph allows us to pinpoint and filter out some outliers that may affect directly the results. Looking at the MEAN I can extract the average of the most successful goals ($3446) and considering the MEDIAN I can find the 50th percentile on goals ($2750). These two numbers would already give a better idea on what would be a very successful goal, way more clearer than the line graph used in Outcomes Based on Goals.
![Stats_us_successful](https://user-images.githubusercontent.com/72593264/96682958-27691e80-133f-11eb-8750-8ddbf8202962.png)




