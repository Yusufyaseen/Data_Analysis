# Diamonds Data Exploration

## Dataset

The data consists of information about udemy courses which consists of 12 columns [ course_id , course_title , url , is_paid , price , num_subscribers , num_reviews , num_lectures, level , content_duration , published_timestamp , subject ]
and it can be found from this link ( https://www.kaggle.com/andrewmvd/udemy-courses )


## Summary of Findings

In the exploration, I found that there lots of findings : 
	1 - The paid courses ( 91.4 % ) is more than free courses ( 8.6 % ).
	2 - The courses that are for all levels are the most, and The courses for expert level are the least.
	3 - The Business Finance courses are the most, and The Graphic Design courses are the least.
	4 - Lots of courses in the dataset were published in 2016.
	5 - In all subjects the paid courses are the most.
	6 - Web Development courses has the much prices amoung the others, and The Musical Instruments has the least 	prices.
	7 - Web Development courses has the much number of subscribers the amoung the others, and The Musical 		Instruments has the least.
	8 - Web Development courses has the much number of lectures amoung the others, and The Musical Instruments 		has the least.
	9 - The paid courses has much subscribers.
	10 - Number of subscribers has positive correlation with number of reviews.
	11 -  Number of lectures has positive correlation with content duration.


## Key Insights for Presentation : 
	1 - The paid courses ( 91.4 % ) is more than free courses ( 8.6 % ).
	2 - Web Development courses has the much number of subscribers the amoung the others, and The Musical 			Instruments has the least.
	3- Number of subscribers has positive correlation with number of reviews.
   	4- Number of lectures has positive correlation with content duration.
	5 -The paid courses has much subscribers.
For the presentation, I focus on just the influence of the four Cs of diamonds and leave out most of the intermediate derivations. I start by introducing the price variable, followed by the pattern in carat distribution, then plot the transformed scatterplot.

Afterwards, I introduce each of the categorical variables one by one. To start, I use the bar plots of price and subscribers  clarity. 
and used cluster bar chart with lots of columns and then scatter plot to see the correlation betwenn different columns