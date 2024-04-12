# Project-1 Stock Market Analysis and Trends.

***SUMMARY:***
In this project, we will be analyzing trends that take place on the NASDAQ over a 5 year time-period. We will be looking at data from 2019 - 2024.

***OBJECTIVES:***
The objective of this project is to define and understand the changes taking place over a 5 year time-period to better educate investors on unusual fluctuations in the market due to events that could be considered "outliers", and how one could best-prepare for an outlier event.

***OUR DATASET:***
In our NDX.CSV, we pulled information from "Go-Charting". (HyperLink This)

***ISSUES WITH OUR DATASET:***
We do not believe the to be any descrepancies with our dataset, however, we do note that the NYSE has the hours of 9:30AM - 4:00PM, Monday - Friday and is not open certain days of the calendar year due to holidays. Therefore, any calculations predicting or forecasting may be slightly misconstrued due to the inability of the software understanding which days of the calendar year are United States national holidays; when the NYSE is not in operation. Furthermore, any calculations regarding the utilization rate of our data would also be slightly misconstrued.

***NOTABLE HOLIDAYS:***
As previously mentioned, the NYSE observes U.S. Holidays.

List of common holidays include:

  _New Year's Day_
  
  _Martin Luther King, Jr. Day_
  
  _George Washington's Birthday_
  
  _Good Friday_
  
  _Memorial Day_
  
  _Juneteenth National Independence Day_
  
  _Independence Day_
  
  _Labor Day_
  
  _Thanksgiving Day_
  
  _Christmas Day_

***IDENTIFYING POSSIBLE OUTLIERS IN THE DATA:***
To identify outliers in our data, we utilized a New York Times API key to filter-search articles for each day pertaining to the filter words "United States Economy". We filter-searched this information to indicate the possibility of outlier data near or on the date of possible fluctuations in the market.

***EXPECTED OUTLIERS***
Before running our analysis, we expect outlier datapoints in our dataset due to events such as COVID-19, Global Conflicts, and Interest Rate fluctuations.

***STATISTICS / GRAPHICS:***
In analyzing our dataset, we sub-categorized the 5 year time-period into six seperate datasets as follows:

**A stable market (Year - 2019)**

_One 2019 as-is dataset_ & _One 2019 forecasted dataset._

**A market in duress due to outlier events (Year 2020 - 2022)**

_One 2020 – 2022 as-is dataset_ & _One 2020 – 2022 forecasted dataset._

**A recovering market on the verge of stability yet still experiencing outlier events (Year 2022 - 2024)**

_One 2022 – 2024 as-is dataset_ & _One 2022 – 2024 forecasted dataset._

***APPLICATION:***
The application of this code could be utilized in making investment related decisions. This code does not take into account investor risk aversion, but instead underlines the conceptual understanding of global outlier events and graphically evaluates how the market fluctuated and further what could be forecasted.







