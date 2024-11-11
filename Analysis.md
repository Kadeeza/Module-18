# Pre-Processing
The data analysed in this challenge is from January 2023. Originally, the data set included 100,000 rows repesenting 100,000 distinct ride IDs. After pre-processing, rows with empty or null values were dropped to allow better visualiation.  The resulting data set is 995687 rows representing 995687 distinct rides.


# Introduction
The purpose of this visualiation and accompanying document is to analyse Citi bike rides in New York for the month of January 2023. Insights have been broken down in the analysis section below


# Analysis

## Map Trends
The top three most popular stations were *W 21 St & 6 Ave, **6 Ave & W 33 St and **1 Ave & E 68 St. The first two are close to popular tourist attractions like The empire state building and Madison Square Park

The map legend is sorted in order of most bike rides. You can interact with the map by selecting one or several station names. Any station name(s) selected will be highlighted in the map.

## Peak Hours - Starting vs. Ending
The top 5 peak hours for starting a bike ride were 5 PM, 4 PM, 6 PM, 3 PM and 8 AM respectively. The evening time slots on this list correspond with times when people are moset likely get off from work. A lot of people start work at 9 AM so it would makes sense that a large number of commuters are using the rideshare program at 8 AM to get to work.

Based on these times, it appears people are more likely to use the bike share program commuting back from work as opposed to to work. 
 
The top 5 peak hours for ending a bike ride were 5 PM, 6 PM, 4 PM, 3 PM and 8 AM respectively. Though we see a slight shift in the order of times, we can make similar assumptions as we did regarding the top 5 times to start a bike ride

## Peak Days - Starting vs. Ending
When looking at days of the week, both starting and ending had the same trend. In order of popularity, the most popukar days for bike rides are as follows: Tuesday, Monday, Friday, Wednesday, Sunday, Saturday and Thursday.

Since most citi bikes rides start and end on the same day (i.e. no overnight or cross country rides), It makes sense the popular days for bike rides do not change between starting and ending.

That being said the order of popularity is interesting and would warrant additional investigation. It would be beneficial to understand if this trend hokds across several months and years and if could identify and trends that could be contribiting to the popularity of some days over others

## Casual vs. Member - Ride Count and Trip Duration
87% of the rides in January were completed members while 13% of the rides were completed by non-members or causal riders. 

By comparison, the average duration of trips completed by casual members was about 30 minutes, while the average duration of all rides completed by members was about 12 minutes. 


## Popular Stations - Starting vs. Ending

There number most popular station in January 2023  W 21 st & 6 Ave. This station was the most popular one for rides starting and ending. 

This station is located centrallyin Manhattan. Some notable places nearbly include the Empire state build, the Flatiron building and madison square park*. The central location of this station, as well as it's proximity to popular tourist attractions could have boosted the popularity of this particular station


* Sources:
*https://mapcarta.com/N3708656735
** https://mapcarta.com/N3708656229
*** https://mapcarta.com/N4572533038