# New York City Citi Bike Analysis

## Purpose

The purpose of the project was to use data from New York City's Citi Bike program and see if it would be possible to recreate the program in De Moines, Iowa.
In order to complete this analysis, I used Python's pandas library to clean up the data and then created visualizations of that data using Tableau. 

## Results

Throughout this analysis I wanted to answer the following questions:

1. How long do users bike for?
2. Who is using the bikes?
3. Where are they biking to and from?
4. When are users using the bikes?

To answer these questions I came up with the following visualizations.

### How long do users bike for?

This visualization shows the length of time of every bike ride during the month of August in 2019. It shows that riders typically like to bike between 2 and 15 minutes.

![checkout_times_fo_users](https://github.com/Wall-E28/bikesharing_analysis/blob/main/visualizations/checkout_time_for_users.png)

### Who is using the bikes?

This visualization shows the breakdown of riders by gender and duration of times showing that most of the users are men.

![checkout_times_by_gender](https://github.com/Wall-E28/bikesharing_analysis/blob/main/visualizations/checkout_times_by_gender.png)

To further these findings, this visualizations shows that the most common user is a male subscriber (meaning that they have signed up for a long term contract with citi bike) and
there most frequent day of the week to ride on is Thursday.

![user_trips_by_gender](https://github.com/Wall-E28/bikesharing_analysis/blob/main/visualizations/user_trips_by_gender.png)

### Where are they biking to and from?

These two visualizations show the the top starting and ending locations. The first thing to note is that most rides start in the most populous areas in mid and lower Manhattan. Second, due to shorter ride times, the ending locations are also in those same populous areas.

![top_starting_locations](https://github.com/Wall-E28/bikesharing_analysis/blob/main/visualizations/top_starting_locations.png)

![top_ending_locations](https://github.com/Wall-E28/bikesharing_analysis/blob/main/visualizations/top_ending_locations.png)

### When are users using the bikes?

This visualizations shows that weekday rider traffic peaks at traditional commuting times, while weekends see gradual use throughout the day.

![trips_by_weekday_per_hour](https://github.com/Wall-E28/bikesharing_analysis/blob/main/visualizations/trips_by_weekday_per_hour.png)

To further these findings, this visualization shows a similar patterns when broken down between genders.

![trips_by_gender](https://github.com/Wall-E28/bikesharing_analysis/blob/main/visualizations/trips_by_gender.png)

## Summary

Based on the findings above, these are the top takeaways to create a successful citi bike program in De Moines.

1. Advertising should target men as they are the main user demographic
2. Bikes should be positioned in the most populous areas
3. Offer incentives to push for daily use throughout the week during traditional communting hours

For a more in depth and interactive view of this analysis, checkout the Tableau link below

[link to dashboard](https://public.tableau.com/profile/riley4086#!/vizhome/NYCCitiBikeAnalysis_16031262141460/NYCCitiBikeAnalysis?publish=yes)