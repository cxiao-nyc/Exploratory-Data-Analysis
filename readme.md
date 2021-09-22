## Exploring MTA Ridership and Median Property Value in New York City during COVID-19 Pandemic

Connie Xiao

---
Exploring MTA Ridership

Abstract
---

A committee of legislatives wants to give back to New York City's community after the pandemic. New Yorkers went through a big hump during these difficult times and they wanted to create more jobs for communities that did not have the privilege to work from home. They were interested in D line locations where the residents were still going into work during the pandemic.
To tackle this project, I used MTA turnstiles dataset to see which stations that had the least change in ridership activities. To explore more into the changes, I measured affluency by looking at each neighborhoods median property values. I wanted to see if more affluent neighborhoods had a more dramatic decrease in ridership levels compared to less affluent neighborhoods. I also wanted to explore the changes for each individual station.
For this project, my goal was to see the impact of COVID-19 Pandemic on New York City's MTA ridership. The main chunk of this project will be exploring ridership levels pre-COVID and during COVID. I will also be taking New York City's neighborhood's property value status into consideration to see how it certain neighborhoods affected ridership levels. After cleaning my data, I wanted to see the connection between the ridership activities in with median property values. To do so, I built graphs and plots to analyze my findings.



### Data
---
The MTA dataset contains 585,842 row for each turnstiles 4 hours apart. Each turnstile showed up about 6 times for each day. The data provides weekly updates for each turnstiles in the system. Each turnstile was identified by an unique combo of C/A, UNIT, SCP, STATION. After querying my median property value data, it contains 18 data points with 7 columns. I also imported longitude and latitude locations for station entrances for the purpose of visualizations.

### Results
---
Taking the average median property values from the January 2020 to June 2020.
Splitting data set into two time periods.
Averaging the weekly number of entries for each station.
Averaged the weekly number of entries for each station, then find the percentage change for each individual station pre-covid and present covid. This helped exam each station more closely to see if there were any outliers or anything unusual on this line. To look at the bigger picture, I added up all the weekly entries for all stations, for each respective time period and found the percent decrease. To observe the relationship of ridership with neighborhoods, I mapped the station's neighborhood to the average median property. A map of New York City is shown with it's respective stations plotted to understand how location affected ridership levels.

Findings:
The D line had a decrease of 89% ridership collectively.
The biggest decrease in ridership was in SoHo, Manhattan and it's average median value was about 2.5 million.
The smallest decrease in ridership was in Coney Island, Brooklyn and it's average median value was about 430 thousand.
Manhattan had the largest difference in average weekly ridership.

### Tools
---
SqlAlchemy 
Pandas 
Matplotlib
Seaborn
Plotly 
Geopandas 
