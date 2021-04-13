# JH-COVID-Global-TS
Gather time series data from JHU GitHub to create a time series

[JHU COVID-19 Time Series Data](https://github.com/CSSEGISandData/COVID-19/tree/master/csse_covid_19_data/csse_covid_19_time_series)

---

## Overview:
* `merge()` 3 .csv files into 1 data frame
* Data was given in wide format, I had to convert to long format using `melt()`
* Plotted data together and by individual coutry

## Global Deaths Time Series
![all_conutries](jhu_all_countries_deaths_ts.png)



## U.S.A Deaths Time Series
![usa](jhu_usa_deaths_ts.png)



## China Deaths Time Series
![China](jhu_china_deaths_ts.png)



## France Deaths Time Series
![France](jhu_france_deaths_ts.png)



## Brazil Deaths Time Series
![Brazil](jhu_brazil_deaths_ts.png)



## Italy Deaths Time Series
![Italy](jhu_italy_deaths_ts.png)



## Japan Deaths Time Series
![Japan](jhu_japan_deaths_ts.png)



---

Future Updates: Add time series for confirmed cases and recovered, automate
