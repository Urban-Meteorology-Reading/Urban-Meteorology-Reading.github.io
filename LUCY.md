---
layout: default
---
[*back to main page*](./)

Please report issues [here](https://github.com/Urban-Meteorology-Reading/Urban-Meteorology-Reading.github.io/issues)


# LUCY

* Brief
   * Large scale Urban Consumption of energY
   * Model calculates anthropogenic heat fluxes for cities around the world.

* References
   * Allen L, F Lindberg, CSB Grimmond (2011) Global to city scale model for anthropogenic heat flux, International Journal of Climatology, 31, 1990-2005.
   * Lindberg F, Grimmond CSB, Nithiandamdan Y, Kotthaus S, Allen L (2013) Impact of city changes and weather on anthropogenic heat flux in Europe 1995–2015, [Urban Climate](http://dx.doi.org/10.1016/j.uclim.2013.03.002)
   * Gabey et al. (2018) [TAC](https://link.springer.com/article/10.1007%2Fs00704-018-2367-y)
   * Lindberg et al. (2018)

* Versions
   * Version in [UMEP](https://umep-docs.readthedocs.io) called [LQF](http://umep-docs.readthedocs.io/en/latest/OtherManuals/LQF_Manual.html#lqf-manual)
   * Current version: V2014a (25 June 2014) includes options to change spatial resolution.
     * [Model-32bit](https://github.com/Urban-Meteorology-Reading/Urban-Meteorology-Reading.github.io/raw/master/other%20files/LUCYSetup32bit.exe.zip)
     * [Model-64bit](https://github.com/Urban-Meteorology-Reading/Urban-Meteorology-Reading.github.io/raw/master/other%20files/LUCYSetup64bit.exe.zip)
     * See manual for the MCR download
     * Translation tool between Matlab binary format and ASCII raster: [mat2ascGUI.exe](other files/mat2ascGUI.exe.zip) (11 March 2013)


* Manual
   *  [Manual](other files/LUCYUserManual.pdf)

* Background

  The Large scale Urban Consumption of energY model (LUCY) simulates all components of anthropogenic heat flux (Q<sub>F</sub>) from the global to neighborhood scale at spatial resolutions ranging from 30 x 30 arc-second to 0.5° x 0.5°. Any day between 1900 and 2099 can theoretically be considered. The success of the outcome depends on the data available.

  The model includes a database of different working patterns and public holidays, vehicle use and energy consumption in each country. The databases can be edited to include specific diurnal and seasonal vehicle and energy consumption patterns, local holidays and flows of people within a city. If better information about individual cities is available within this (open-source) database, then the accuracy of this model can only improve, to provide the community data from global-scale climate modelling or the individual city scale in the future.

  The results show that Q<sub>F</sub> varied widely through the year, through the day, between countries and urban areas. An assessment of the heat emissions estimated revealed that they are reasonably close to those produced by a global model and a number of small-scale city models, so results from LUCY can be used with a degree of confidence.

  From LUCY, the global mean urban Q<sub>F</sub> has a diurnal range of 0.7 to 3.6 W m<sup>-2</sup>, and is greater on weekdays than weekends. The heat release from building is the largest contributor (89 to 96%), to heat emissions globally. Differences between months are greatest in the middle of the day (up to 1 W m<sup>-2</sup> at 1pm).
    * December to February, the coldest months in the Northern Hemisphere, have the highest heat emissions.
    * July and August are at the higher end. The least QF is emitted in May.

  The highest individual grid cell heat fluxes (W m<sup>-2</sup>) in urban areas were located in New York (577), Paris (261.5), Tokyo (178), San Francisco (173.6), Vancouver (119) and London (106.7).




## LUCY Community Database
  
* Click on link to view spreadsheets
    
    * [USERS/SOURCES](https://docs.google.com/spreadsheets/d/12T_7DSToe0DHtHIwsmOg6b-f68PQNj_Ygf5X2qESUXY/edit?usp=sharing&authkey=CK3PlvwI)
    
    * [Annual energy consumption (kWh) by country](https://docs.google.com/spreadsheets/d/1-1VCHjYkTw9nAuuuwFKWwMK61hklNVeXAfQy_J1sR1s/edit?usp=sharing&authkey=CMCUuc4D)
    
    * [Cars  [number of vehicles per 1000 people] by country](https://docs.google.com/spreadsheets/d/1VtO64iPeP39HBx_8ERV-APriZl8VR-MSpdMS_qodPjo/edit?usp=sharing&authkey=CO2CxO0C)
    
    * [Freight [number of vehicles per 1000 people] by country](https://docs.google.com/spreadsheets/d/1gtltBHzb2eJBSAurkWYcxORb-jpMbQiAqUX0mXGL-is/edit?usp=sharing&authkey=COnbv74E)
    
    * [Motorbikes [number of vehicles per 1000 people]  by country](https://docs.google.com/spreadsheets/d/1wpbApfCfc7_tCTXnRTrz3gJntLt0qSn8cdxXAIttah0/edit?usp=sharing&authkey=CL79rIUD)
  
* The ‘BASIC’ tables include the information provided with the LUCY distribution
 
* Tables 2, 3, 4, … etc. hold data that have been added by the LUCY user community
 
* If you have access to new data that are not yet available or your data might differ from those listed, please add into a new data table and include the relevant ‘SOURCE’ and ‘USER’ information in the associated tables, e.g. SOURCE 2 and USER 2 if you added data to Table 2.
 
* Please make sure that you also list all SOURCES under your USER ID in the tables USERS/SOURCES (first link).
After adding new data to the LUMA archive, please fill in the following form (click here) for each submission to help us keep track of the changes in the database.
