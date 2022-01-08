# Kickstarting with Excel

## Overview of Project
	Our client Louise, is interested in knowing if their is a relationship between campaign outcomes with their lauch date or their moentary goal. 
	I've done an analysis To show these relationships in hope of finding a pattern to why certain campaigns succeed over others. 
	In this analysis you will see a few different charts I created from the raw data that better that better summarize the relationships we are looking for. 

### Purpose
	The purpose of this assignment is to do an analysis on the raw data to determine what impacts whether a campaign succeed, fails, or is canceled. 
	Determining what impacts these outcomes could help to increase future successful campaigns.

## Analysis and Challenges
	### Analysis of Outcomes Based on Launch Date
		First, using the raw date, I created a chart that shows the success, failure, and cancelation of the theatre campaigns in the data. 
		In order to do this, I had to create a pivot chart, that filtered 'Year' and our 'Parent Categoy'. 
		The'Date Launch Created' goes into our rows field and 'Outcomes' goes into both the columns field, as well as, the values field.
		From there, I filtered the category to only show the outcomes for the theatre category and created a line graph. 
		This chart shows the outcomes of campaigns launching throughout the year. All three of the outcomes we are most interested in are pictured on the same chart to better analyze patterns between the three. 

	### Analysis of Outcomes Based on Goals
		We have to keep analyzing the data in order to find out why some campaigns succeed over others, so next I tried to find a pattern between campaigns success and their monetary goal. 
		I did this by creating a table calculating the percentage of successful, percentage of failed, and percentage of canceled campaigns.
		This was done using the COUNTIF() shortcut, to determine the number of each outcome there was  for each goal range in the dataset.
		I then took the respective number of successful, failed, and canceled for each range and divided them over the total number of outcomes for that range, giving me the percentage of each. 
		This is shown in the sheet "Outcomes Based on Goals". 

	### Challenges and Difficulties Encountered
		A challenge when doing this dataset is figuring out how to manipulate this data to only calculate the monetary goals of each outcome for the Parent Category of 'theatres' only.
		When doing a COUNTIF() equation to limit the data analyzed to the theatre category, I was given the value of 0, for each entry. Due to this upset, I did not limit the data based on the theatre category.
		I then created a line chart from this new table showing the outcomes of goal, I did this using a pivot chart. Another challenge one might face is deciding which data goes into what field to create the best graph. 

## Results

- What are two conclusions you can draw about the Outcomes based on Launch Date?
	WE can make a couple conclusions about with the new data we created. One conclusion we can make is that theatre campaigns were most successful when they launched in May. 
	We know this because the highest point on the line of successful outcomes is over the month May, on the Y axis. Another conclusion is that cancelations are impacted little to none based on there launch date. 
	This is apparent by the relatively steadt line for the cancellation outcome across the timeline. Slight shift over time are expected but larger peaks and values can often occur due to a specific factor. 

- What can you conclude about the Outcomes based on Goals?
	The Outcomes based on goals table concludes that the Monetary goal can significantly effect the success and failure of a campaign. The graph does a pretty good job of showing an overall trend of campaigns being related to the monetary goal.
	 Successful campaigns are more likely when the monetary goal is lower, success then begins to decline. When the goal is between 15000 and 19999, there is an equal amount of successful and failed campaigns, from then on, as prices rise, failed campaigns begin to surpass successful campaigns. 

- What are some limitations of this dataset?
	One limitation of the dataset is that out 'Outcomes based on Goals' chart is created from a larger portion of the dataset. It is not limited to the theatre category, where the 'Theatre Outcomes by Lauch Date' is. 
	This can cause a slightly skewed analysis when comparing the two charts. Another limitation is that the data we chose to analyze only gives us part of the story, we could have additional factors that have a larger affect on whether or not a campaign succeeds or fails. 
	For example, the number of backers could have a larger impact on campaign outcomes than when the campaign launch occured. Another factor could be the amount of time given for the campaign to raise money. We would have to further analyze the data in order to figure out if these factors largely impact the outcomes or not. 

- What are some other possible tables and/or graphs that we could create?
	A possible chart we could create is one that compares outcomes to number of backers or average donation. Another great chart would be one that compares the outcome to the amount of time the campaign has to collect money. 
