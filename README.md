# 550Project
## Folder Descriptions
***
* Colab Notebook: Notebook for Data Cleaning and Entity Resolution.
* Table Data: Data that are generated from cleaning.

## Tables
Table  | Columns
------------- | -------------
GlobalTempCountry.csv | AveTemp, Country, Year, Month, Day
GlobalTempMajorCity.csv | AveTemp, City, Country, Latitude, Longitude, Year, Month, Day
GlobalTempState.csv | AveTemp, State, Country, Year, Month, Day
wb_CO2_filtered.csv | CCode, CName, SCode, SName, 1990, 1991,...,2008
wb_CountryCode.csv | CCode, CName, Region, Group, Category
wb_CountryPrec.csv | CCode, January, February,..., December, Annual
wb_CountryTemp.csv | CCode, January, February, … , December, Annual
wb_Res.csv | CCode, CName, SCode, SName, Value, Year

1. Motivation for the idea/description of the problem the application solves 
We are interested in analysis of carbon emission and climate data because climate change is one of the most important issues in today’s world. The effect of carbon emission on the environment has risen to the forefront of science news, and we are interested in developing an analysis tool to make sense of carbon emission and climate data to show the effects on climate change.
We hope that the application can not only be an analysis tool for those researching the topic of climate change, but also a source of information for people who are less familiar with climate change. We want to provide useful predictions as well as clear demonstrations of how climate change is affecting the environment.
2. List of features you will definitely implement in the application 
World map view (ability to display % change of different features in a heat map)
Historical times series (ability to toggle features to display in time series)
Correlation charts
Impact of climate work (split time view of Issued Certified Emission Reductions, Issued Emission Reduction Units, Hosted Clean Development Mechanism (CDM) projects)
3. List of features you might implement in the application, given enough time 
Forecasting/ historical scenario development: If we had reduced CO2 emissions by X% percentage, what would have been that impact on avg. temps/ droughts/ floods
4. List of pages the application will have and a 1-2 sentence description of each page.
We expect that the functionality of each page will be meaningfully different than the
functionality of the other pages. 
Overview page
Geo display: Show % change in avg. temperature on a World Map (heat map)
Historical time series: Show abs. Avg temperature
Correlation page - show statistical relationship between:
Avg. temperature & CO2 emissions
Doughts & CO2 emissions
Floods & CO2 emissions
Extreme temps & CO2 emissions
Impact of climate work
Pre vs. post Issued Certified Emission Reductions
Pre vs. post Issued Emission Reduction Units
Pre vs. post Hosted Clean Development Mechanism projects
Interactive pages
Geo display of any variable of your choice
Historical time series of any variable of your choice
Correlation page between 2 variables of your choice
