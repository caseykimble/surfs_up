# Surf's Up

### Overview

The purpose of this analysis was to review weather data for temperatures throughout the year on the island of Oahu in Hawaii, due to a client's desire to open a combination surf shop and ice cream parlor. He'd like to know if this would be a sustainable year-round business model. I used Python and Pandas functions and pulled queries through SQLAlchemy for an analysis on temperatures in June and December to see how the weather varied through different seasons.

### Results

* In Oahu during the month of June, temperatures are very moderate with the average daily temperature being about 75 degrees, and never dropping below 64 degrees.

<img width="636" alt="june_temps_df" src="https://user-images.githubusercontent.com/105175961/205181452-4b9fa898-f72c-4be9-9c9d-ffb191c2599f.png"><img width="863" alt="june_temps_summary" src="https://user-images.githubusercontent.com/105175961/205181457-e6a294a4-8240-4a68-a763-20c07d7404c8.png">

* December on the island of Oahu doesn't look too different from June in regards to the temperature. Average daily temps for December are about 71 degrees, with it never dropping below 56. So maybe some slightly colder days but overall the average temperature isn't very different from June.

<img width="608" alt="dec_temps_df" src="https://user-images.githubusercontent.com/105175961/205181672-e692d7e9-20ff-4816-8e41-b1a04db98244.png"><img width="792" alt="dec_temps_summary" src="https://user-images.githubusercontent.com/105175961/205181678-e8b9fd34-3819-4e7e-ac75-435c37ac8b58.png">

* Both datasets offered a minimum of 1500 datapoints for each month over the course of six to seven years so I feel this is a good representation of recent weather trends on the island.

### Summary

It looks like Oahu has very moderate temperatures that don't vary too much throughout the year, be it summer or winter. This seems like an ideal situation for a surf shop and ice cream parlor, as my client was concerned about the viability of such a business throughout the entire year. For an additional analysis I would like to review precipitation and wind speed weather data to determine whether average daily weather was warm AND sunny rather than just warm with less ideal weather, as I'm sure this would have an impact on both ice cream sales and surfing conditions.
