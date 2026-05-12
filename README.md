# Earth211
Earth Science 211: Data Analysis in Earth and Environmental Sciences Final Project

Research Question 1: Ozone Concentration

How does annual average ozone concentration vary across counties in Michigan, and how does average ozone concentration change over time and in relation to population change?

I want to investigate ozone concentration across Michigan to get a better understanding of how air pollution varies across the state. I also want to investigate how this pollution has changed over time and explore whether pollution might be associated with population change. This is meaningful because it is important to understand how pollution varies in different areas across time so that we can understand the magnitude of this issue and where it is the most prevalent. This exploration would require variables such as ozone concentration, population, location, and date, which could be acquired from EPA air quality data and census data. After acquiring the annual averages or estimates and matching up the county locations, I could map out the ozone concentrations across counties, use ANOVA to determine whether average ozone concentrations change year to year, and use regression analysis to examine the association between ozone concentration and population.

Dataset: Michigan Population, by County
Source: U.S. Bureau of the Census and Michigan Department of Management and Budget
Spatial Coverage: state of Michigan, by county
Temporal Coverage: 1990, 1995, 2000, 2005, 2010, 2015, 2020-2024
Variables: annual population count
File Format: pdf

Dataset: Ozone Concentration in Michigan
Source: United States Environmental Protection Agency
Spatial Coverage: 29 different stations across the state of Michigan
Temporal Coverage: March 1-October 30, 2024 (years 1990-2026 also available)
Variables: Date, Daily Max 8-Hour Ozone Concentration, Daily AQI Value, County, Site Latitude, Site Longitude
File Format: csv


Research Question 2: Air Temperature

How does annual average air temperature vary across counties in Michigan, and how does average air temperature change over time and in relation to population change?

I want to investigate air temperature across Michigan to get a better understanding of how air temperature varies across the state. I also want to investigate how this temperature has changed over time and explore whether temperature might be associated with population change. This is meaningful because it is important to understand how temperature varies in different areas across time so that we can understand where climate change might be prevalent in the state. This exploration would require variables such as air temperature, population, location, and date, which could be acquired from NOAA data and census data. After acquiring the annual averages or estimates and matching up the county locations, I could map out the air temperature across counties, use ANOVA to determine whether average air temperatures change year to year, and use regression analysis to examine the association between air temperature and population.

Dataset: Michigan Population, by County
Source: U.S. Bureau of the Census and Michigan Department of Management and Budget
Spatial Coverage: state of Michigan, by county
Temporal Coverage: 1990, 1995, 2000, 2005, 2010, 2015, 2020-2024
Variables: annual population count
File Format: pdf

Dataset: Air Temperature in Michigan
Source: National Oceanic and Atmospheric Administration
Spatial Coverage: 585 different stations across the state of Michigan
Temporal Coverage: January 1-July 31, 2024 (other years also available)
Variables: name, latitude, longitude, date, TMAX, TMIN, TOBS
File Format: csv

Not all of the stations include temperature data, so missing data would have to be removed. Then each station would be matched to the county it’s in, using the latitude and longitude. The annual average air temperature would be calculated for each county for 1990-2024, and an ANOVA would be run for each county to determine if the annual averages differ at all. A regression analysis would also be performed to examine the association between average annual air temperature and population for counties for the years where population data is available. Some summary visualizations could be created, such as a map of average temperature for each county for the most recent year, a map of population in each county for the most recent year, and a time series graph of average monthly temperature for the whole state of Michigan. A scatterplot for the regression analysis could also be shown. Interactive data visualizations could be created to show how these values change over time or to allow users to select a specific year or county. In addition to these visualizations, the final project will also include the results from the ANOVA and regression analysis and will outline which findings are statistically significant. This will show which counties have seen a significant change in average air temperature and whether there is an association between average air temperature and population.
