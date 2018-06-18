# Tebleau Story for U.S. Flight Delays

## Summary

In this project, I created interactive visualizations using Tableau for U.S.
flight delays data from 2010 to 2018, which is downloaded from The U.S.
[Bureau of Transportation Statistics](https://www.transtats.bts.gov/OT_Delay/OT_DelayCause1.asp).
The purpose of my visualizations is to answer the following questions:

- How does flight delay time change over time in comparison to the number of
arrived flights? Is there any variation in delay time in different quarters of
the year?
- How much time is delayed by each delay cause? Does the proportion change over
time?
- Which airports have more flight delays? Is the delay time related to the
number of arrived flights?

Through the visualizations, I showed that:

- Flight delay time have greater fluctuations compared to number of flights.
The total number of minutes delayed usually increases in the first and second
quarter of the year and decreases in the third and fourth quarter of the year.
- Late aircraft contributes to the longest flight delays, followed by carrier,
national air system, weather, and security reasons. This proportion remains
fairly constant over time.
- Airports with vary in delay time regardless of the number of arrived flights.

## Process of Creating the Visualizations

The visualizations were created through an iterative process. Every time after
I created a draft of the visualizations, I showed it to multiple people,
obtained feedbacks from them, and made improvements using those feedbacks. The
detail of the process, including the link to each draft, is recorded in
`Tableau Story Project Report.pdf`. The final iteration of the visualizations
can be viewed
[here](https://public.tableau.com/profile/xiang.hui.low#!/vizhome/FlightsDataVisualizations-Draft4/FlightDelaysTableauStory).

## Datasets

- `airline_delay_jan10_mar18.csv`: Original dataset downloaded from the Bureau
of Transportation Statistics.
- `airline_delay_jan10_mar18_master.xlsx`: Wrangled dataset, which contains a
date column. Saved in `.xlsx` format for easier processing in Tableau. The
wrangling process and the codes involved can be found in
`flights_data_assess_wrangle.ipynb`.

## Other Files

- `Tableau Story Project Report.pdf`: A report that records the process of
creating each iteration of the visualizations, the thoughts involved, feedbacks
received, and URLs to each iteration.
- `flights_data_assess_wrangle.ipynb`: Jupyter notebook that contains details
and codes of the data wrangling process.
