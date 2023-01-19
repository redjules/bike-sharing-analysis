# Ford GoBike System Exploration

## by Ana Pedra

## Dataset

The dataset comprises 183,000 records of bike-sharing rides in the San Francisco Bay region. It includes details such as the duration of each ride in seconds, the date and time, the type of customer, and the rider's gender, among other information.

## Summary of Findings

During my analysis, I discovered that the average duration of all trips was approximately 500 s. The most popular days for trips were Thursdays and Tuesdays, while weekends had the least number of trip records, despite having longer trip durations than other weekdays. Additionally, I found that there were higher trip records during the 8th and 9th hours in the morning and the 17th and 18th hours in the evening, likely due to clients commuting. The majority of rides were taken by subscribers, with over 70% of total rides taken by male riders.

Furthermore, I found that normal customers had longer trip durations compared to subscribers and that female riders had longer trip durations than male riders. Most likely, only subscribers are able to share bikes on trips, and trips with bike sharing accounted for about 10% of total rides.

The user type 'customer' did not seem to vary the number of rides on any given day.

## Key Insights for Presentation

In the presentation, I concentrate on the ride frequencies per hour, day, and user type, while disregarding other variables. I begin by analyzing the frequencies of trips by hours, days of the week, and user type, utilizing seaborn's countplot.

Next, I focus in each categorical variable individually. To begin, I use box plots to examine the duration of trips across days and user type. Afterwards, I examine the remaining two categorical variables, days and user type, using point plots. I've taken care to use distinct color schemes for each variable to ensure they are easily distinguishable in the plots.
