---
layout: post
title:  "Are we still falling into the ozone hole?"
subtitle: "A self learning visualisation approach to the silent ozone hole progression."
date:   2022-04-13 17:35:43 +0200
categories: visualisations ozone  
---
# My Inspiration and goals
As I listened to an episode of the Startalk podcast (deGrasse Tyson, 2021) I was reminded of the ozone depletion which was a threat in my infant and teen years. Since then, I have not heard of any developments in recent years. So, I decided to check this topic and get some experience in data visualisation as well. My idea was to create an interactive plot for the timeline of the ozone hole size. In this plot I will mark the important events in the timeline and add a description to them. 
My aim is that you as a reader know about the ozone hole progression and if we are silently falling into a pitfall or if there is a solution in sight. You may also learn, along with me, the basics of a building an interactive visualisation.


# Action Plan
After some initial thinking I tried to map out an action plan for the upcoming steps. Creating the plot needs actions like finding a fitting dataset, reading data, assessing data quality, plotting the variables, researching events, and adding descriptions in the plot. 
Starting out with searching for a data set was the task which seemed most logical to me.

# Finding a dataset and its pitfalls
After some research I found a NASA Website which provided daily data from 1979 on. The daily data points are available, but they are separated in a file for each year with its own link. So, I was looking for an automated download for each year. NASA does not provide a single file or download for all the daily data. So, I started thinking how I would achieve this.
I recognised that the URL "https://ozonewatch.gsfc.nasa.gov/meteorology/figures/ozone/to3caps_{Year}_toms+omi+omps.txt"(Ozonewatch, 2021) includes a year. I then checked if this is the same for the other downloads.
Indeed, this is the case for all the downloads. From prior experience I reckoned that a loop through these URL's (changing the year in each loop) should be sufficient to download all the files and merge them together. Luckily, I had already learned these skills because else it would be a gruesome task to download them all by hand. Always be on the lookout while looking for a dataset and do not easily dismiss good data. Be aware that there are always workarounds for most time-consuming tasks.
 
# Data and it’s gaps
I asked the curator of the data repository, why there is a big gap between 1994 and 1996 and what might cause the other missing values, and he answered with the following response: 
There were no satellites available during that period that measured global total column ozone. The last TOMS instrument was onboard the Meteor-3 satellite that ended in 1994. The Earth Probe TOMS satellite wasn't launched until 1996. Other missing data here and there throughout the data record are due to technical issues with either the instrument or the satellite (E. R. Nash, personal communication, December 14, 2021).

By "that period" he is referring to the big gap in data.
A big takeaway of this interchange is that you should never be afraid to ask anyone about their field. Most people like to talk about their work and are happy to explain their expertise to you.
Missing observations are set to the value -9999 by NASA. I removed these with the pandas package and put the numpy NAN value instead for easier handling with the visualisation packages. NAN is processed by the visualisation packages as a missing value, whereby -9999 would be processed as the number -9999 and would therefore be a negative outlier. 
I looped through each year and added them to a full dataframe in pandas. 
Now I have a full time series with daily values from 1979 to today. 

# Events 
I then started researching important events for the ozone hole progression. Thinking about interesting events I declared the following events categories are worth looking into:
-	Political Decisions
-	Consumer Changes
-	Observational Changes
-	Scientific Discoveries

Each event can also be categorised in negative and positive events for the ozone hole progression.
After researching on these categories I found several events which could be added to my visualisation (Ozonewatch, 2018). 

# Some background knowledge to ozone
Researching these events, I learned some hard facts about the dynamics of ozone in our atmosphere as well as the different physical processes 
For example, ozone is measured in Dobson units (DU). This is a measuring unit which describes the density of a gas in a specific volume in the atmosphere. With this metric a depletion of ozone is 
One important number to remember in this context is 220 (DU), it is the threshold of a depletion of the ozone layer. Scientists defined this limit because prior to 1979 it was never measured. Keeping this in mind for my visualisation I continued.

