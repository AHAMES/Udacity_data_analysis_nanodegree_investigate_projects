# Lyft System Data exploration
## by Ahmed ElSabbagh


## Dataset

I have selected the GoFordBikes dataset which belongs to Lyft.

It consists of the information about the rides people have taken, when and where it started and ended, the duration, and if the person having the ride is subscriber to the service or a casual user.

The dataset was divided into the months of the years 2018-2019-2020. Which I have taken have cleaned, combined and matched the labeling and columns in both before I started my exploration. 

Wrangling included changing the labels for subscribers, finding the duration for 2020 which is not directly added. Finding whether the trip was in week day or weekend. 



## Summary of Findings


The following was found:

1- Lyft has lost too much of it's income in 2020 because of covid-19 - in explanatory

2- The biggest source of income are subscribers, and their usage of the service severely dropped - in explanatory

3- Ride durations have increased in 2020 for no apparant reason - in explanatory

4- Those who have increased their ride duration are casual user, again for no apparant reason - in explanatory

5- Weekend rides are almost unaffected by covid-19, and in fact has increased in duration (if not frequency) - in explanatory



## Key Insights for Presentation

The key points I have focused on and tried to put in narrative are the following:

1- Lyft is losing money because of losing rides.

2- How bad is the loss and what could be causing it.

3- The unusual trends that don't seem that they should apply regarding everything else.

To focus on that I have trimmed away most of the box plots and violin plots, while they explain to me how the situation have changed, they did not offer any direct useful information that can be communicated visually to the average viewer.

I have also ignored some of the weekend statistics because they are only of limited use most of the exploration, let alone explanation. 

In one bar chart, I have reversed the hue and x-axis to make it by year, the orignal was a bit crowded and harder to process immediately.

