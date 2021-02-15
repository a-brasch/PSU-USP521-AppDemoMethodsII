# PSU-USP521-AppDemoMethodsII
PSU USP 521 Applied Demographic Methods II Independent Study  
Methods for Projecting Persons Per Household (PPH)  
Portland State University  
Graduate Certificate in Applied Social Demography  
USP 521 Applied Demographic Methods II Independent Study  
Summer Quarter 2019

---

**Abstract:** 
The Population Research Center (PRC) Oregon Population Forecast Program (OPFP) prepares population forecasts for all Oregon counties and cities (except for the Portland Metro Area) using a consistent suite of demographic methods. For counties and larger sub‐areas—those with populations greater than 8,000—OPFP uses a cohort‐component model, which measures demographic life events, such as births, deaths, and migrations over time, to forecast future populations. For each smaller sub‐area, OPFP utilizes the housing unit (HU) method, which forecasts future population based on changes in housing stock, type, occupancy, and persons per household (PPH) (Population Research Center 2019, 4). The HU method is recognized as one of the most commonly used methods of projecting small-area populations. The method has been used widely and consistently for decades. A 1978 study conducted by the U.S. Census Bureau showed that more than three-fourths of all agencies making sub-state population estimates use some form of the HU method (Smith and Mandell 1984, 282), and more recently, it has been advocated before Congress for use by the Census Bureau for sub-county population estimates (Swanson 2006 in Hauer, Evans, and Alexander 2015, 47). The HU method’s frequent use is no surprise, since it is often regarded as one of the most reliable methods for making population estimates for small areas (Hoque 2012, 93). It’s proven performance is due, in part, to the HU method’s ease of use—in that the population of any given geographic area is simply equal to the number of occupied housing units (households) multiplied by PPH, plus the population residing in group quarters (e.g., nursing homes, military bases university dormitories, prison, etc.).

However, one of the challenges to producing accurate forecasts for small areas using the HU method is quantifying the impact of local and regional demographic factors on average household size (i.e., PPH) and occupancy rates. In many applications of the HU method, PPH is adopted from the most recent census. While this technique provides relatively accurate estimates when the forecast horizon is close to the previous census, it becomes increasingly unreliable as the projection period is farther removed from the previous census. Another common method of estimating PPH is linear extrapolation of the trend between the two most recent censuses. This technique will produce accurate estimates when PPH follows a stable trend, but it will become increasingly inaccurate as trends change. For instance, in the U.S., PPH declined by 1.2% between 1950 and 1960, by 5.7% between 1960 and 1970, and by 12.1% between 1970 and 1980 (U.S. Bureau of the Census 1983c). This increased rate of decline would not be captured by simple extrapolation of intercensal PPH trends and would result in inaccurate projection for many places (in Smith 1986, 290). Neither of these techniques is likely to produce accurate measures of PPH when demographic trends are changing trajectory or are changing at different rates across time and geography.

The reliance of the HU method on simple, projected housing trends and generalized rates presents clear limitations on producing accurate populations for small areas. To better understand the effect of PPH and occupancy rates on population forecasts prepared using the HU method, this study investigates a variety of indicators, including headship rates, dependency ratios, changes in age structure, and total fertility rates (TFR). Generally, fewer children and more elderly persons suggest a decline of PPH and occupancy rates over time. In fact, declining fertility may be the most important immediate driver of changing household sizes (Bongaarts 2001 in Bradbury, Peterson, and Liu 2014, 80). Furthermore, aging of a population is likely to contribute to the decline of PPH, even in areas where fertility rates are stable, because households headed by the elderly typically have fewer occupants.

In an attempt to better capture demographic change, this study investigates the use of regression analysis to estimate PPH. One of the underlying goals of this research is an attempt to reduce the impact of an inherent quality of forecasting—that each step of the estimation process requires decision-making that commonly must be based on sketchy information or on intuition (Starsinic and Zitter 1968, 476)—by better quantifying the influence of demographic change. The study is divided into four main components, including 1) a review of relevant literature on the topic, 2) data acquisition and preparation for the area of interest (i.e., State of Oregon), 3) descriptive and inferential (regression) statistics and development of a conceptual framework for a prediction model to forecast PPH, and 4) a discussion of results, limitations, future research opportunities, and conclusions.

The above was accomplished by undertaking a review of academic research on the topic, as well as through the use of analytical methods to measure the impact of demographic variables on PPH over time. For analysis and reporting purposes, the project utilizes the R programming language and environment (RStudio), R Markdown, U.S. Census American Community Survey API, tidyverse packages (e.g., dplyr), and additional R packages (e.g., tidycensus). The geographic units of analysis are the 2018 Urban Growth Boundaries (UGB) of Oregon incorporated areas. The 1990-2000 and 2000-2010 decades serve as the base periods of analysis, with 2010 representing the launch year, and the forecast horizon extending to 2030. Although 5-year age cohorts are standard within demographic analysis, especially when conducting historical analyses, this study will also employ 10-year cohorts and broader age group categories like 0-17, 18-65, and 65+, in order to better suit existing forecast methods and available data. The results of this study are intended to provide the PRC OPFP with methods to project PPH based on statistical relationships, as well as a digestible means of communicating to county and city stakeholders and the general public how aging, household formation, and declining fertility impact population forecasts. The end product, as follows, consists of a research paper produced with R Markdown, including relevant code chunks and data visualizations.

---

**Contact Information:**  
Alex Brasch

Portland State University | Graduate Student  
Graduate Certificate in Applied Social Demography  
abrasch@pdx.edu

FLO Analytics | Population Geographer | Data Analyst  
abrasch@flo-analytics.com

Personal | Cyclist | Data Nerd | Homebrewer  
alexbrasch88@gmail.com
