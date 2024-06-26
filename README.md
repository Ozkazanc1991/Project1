# Project-1 Stock Market Analysis and Trends.

# Download the PDF to view the report slides.

***SUMMARY (Mete):***
In this project, we will be analyzing trends that take place on the NASDAQ over a 5 year time-period. We will be looking at data from 2019 - 2024.

***OBJECTIVES (Sonu):***
The objective of this project is to define and understand the changes taking place over a 5 year time-period to better educate investors on unusual fluctuations in the market due to events that could be considered "outliers", and how one could best-prepare for an outlier event.

***OUR DATASET (Ryan):***
In our NDX.CSV, we pulled information from "Go-Charting".

***ISSUES WITH OUR DATASET (Ryan):***
We do not believe the to be any descrepancies with our dataset, however, we do note that the NYSE has the hours of 9:30AM - 4:00PM, Monday - Friday and is not open certain days of the calendar year due to holidays. Therefore, any calculations predicting or forecasting may be slightly misconstrued due to the inability of the software understanding which days of the calendar year are United States national holidays; when the NYSE is not in operation. Furthermore, any calculations regarding the utilization rate of our data would also be slightly misconstrued.

***NOTABLE HOLIDAYS (Ryan):***
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

***API Key Creation (Brandon):***
Utilizing our API Key and program created by Brandon, we were able to identify data such as outliers, spikes, and drops easier.

***IDENTIFYING POSSIBLE OUTLIERS IN THE DATA (Brandon):***
To identify outliers in our data, we utilized a New York Times API key to filter-search articles for each day pertaining to the filter words such as "United States Economy, Inflation, and Recession". We filter-searched this information to indicate the possibility of outlier data near or on the date of possible fluctuations in the market.

***EXPECTED OUTLIERS (Ryan):***
Before running our analysis, we expect outlier datapoints in our dataset due to events such as COVID-19, Global Conflicts, and Interest Rate fluctuations.

***STATISTICS / GRAPHICS (Ryan, Mete, Sonu):***
In analyzing our dataset, we sub-categorized the 5 year time-period into six seperate datasets as follows:

**A stable market (Year - 2019)**

_One 2019 as-is dataset_ & _One 2019 forecasted dataset._

**A market in duress due to outlier events (Year 2020 - 2022)**

_One 2020 – 2022 as-is dataset_ & _One 2020 – 2022 forecasted dataset._

**A recovering market on the verge of stability yet still experiencing outlier events (Year 2022 - 2024)**

_One 2022 – 2024 as-is dataset_ & _One 2022 – 2024 forecasted dataset._

***APPLICATION (Mete):***
The application of this code could be utilized in making investment related decisions. This code does not take into account investor risk aversion, but instead underlines the conceptual understanding of global outlier events and graphically evaluates how the market fluctuated and further what could be forecasted.

***Conceptual Example (Mete):*** Recently, in light of events in the Middle East, the NASDAQ dropped around 600 points over the weekend. (April 13-15).

****RESEARCH QUESTIONS****

***Historical Impact Analysis (Sonu):***

**What was the immediate impact of the US-China Trade War on stock markets in the US and China, and how did it affect global markets starting from its intensification in March 2018?
How did the announcement and progression of Brexit negotiations influence stock market performance in the UK and the EU following the June 23, 2016 referendum, particularly up to the formal exit on January 31, 2020?**

***Policy and Economic Responses (Sonu & Brandon):***

How did Federal Reserve interest rate cuts, beginning in July 2019, affect market liquidity and investor behavior across different sectors?
What were the economic consequences of COVID-19 on global markets, starting from its identification in December 2019, with significant impacts from March 2020 onward?

***Sector-Specific Effects (Sonu):***

Which sectors were disproportionately affected by the Russia/Ukraine war, particularly regarding the energy crisis, and what were the broader market implications following the invasion on February 24, 2022?
How did regulatory changes in China targeting technology and education sectors impact both domestic and international stock markets, beginning in early 2021?

***Event-Driven Market Volatility (Sonu & Brandon):***

How did major elections (e.g., the 2020 US Presidential Election on November 3, 2020) and geopolitical conflicts (e.g., Russia/Ukraine war starting February 24, 2022) contribute to market volatility, and were there observable patterns in investor sentiment and market performance?

***Long-Term Trends and Recovery (Sonu & Brandon):***

Following major disruptions such as the COVID-19 pandemic identified in December 2019 with impacts from March 2020 and the energy crisis due to the Russia/Ukraine conflict starting February 2022, what were the patterns of economic recovery and market adjustment?
How have advancements in AI, becoming more prominent around 2023, influenced market sectors differently, particularly technology and manufacturing industries?

***Predictive Insights and Future Preparedness (Mete, Sonu, Ryan, and Brandon):***

Based on past market responses to geopolitical events and economic policies, what predictive models can be developed to anticipate future market reactions?
Considering the ongoing effects of interest rate policies and geopolitical stability as observed in 2024, how can investors prepare for potential market shifts?

***MISC NOTES:***

_Programming Language Used: Python._

_Packages Used: Anaconda, Matplotlib, Pandas, PyPlot, SciPy, and Numpy._

_Tools Used: Jupyter Notebook (IPython)._

_Credit & Contributors: ballen614, Ozkazanc1991, 2Hail, and sharmasonu2081._

# Files
* data folder - a folder containing data that was used for analysis
* 2019_US_Terrifes On China.ipynb
* 2020_Covid Impact.ipynb
* 2021_US President Election.ipynb
* 2022_Russian_Invasion_Ukraine.ipynb
* Gaza Terrorist Attack on Israel.ipynb
* Project-1 PDF.pdf - Our final presentation slides. 
* README.md - This file.
* nasdaq_data_analysis_brandon.ipynb - Brandon's keyword analysis of the NYT and NDQ data.
* nasdaq_data_analysis_ryan.ipynb
* nyt_keyword_analysis.ipynb - This was an exploratory jupyter notebook and did not overall contribute to the final report.
* pull_nyt_headline_data.ipynb - This code was used to pull and build the "us_economy_data" csv files in the /data folder.







 main
