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
   * Lindberg F, Grimmond CSB, Nithiandamdan Y, Kotthaus S, Allen L (2013) Impact of city changes and weather on anthropogenic heat flux in Europe 1995–2015, Urban Climate 4, 1-13 [http://dx.doi.org/10.1016/j.uclim.2013.03.002](http://dx.doi.org/10.1016/j.uclim.2013.03.002)
   * Gabey AM, Grimmond CSB, I. Capel-Timms (2018) Anthropogenic heat flux: advisable spatial resolutions when input data
are scarce Theoretical and Applied Climatology [https://link.springer.com/article/10.1007%2Fs00704-018-2367-y](https://link.springer.com/article/10.1007%2Fs00704-018-2367-y)
   * Lindberg F, Grimmond CSB, Gabey A, Huang B, Kent CW, Sun T, Theeuwes N, Järvi L, Ward H, Capel-Timms I, Chang YY, Jonsson P, Krave N, Liu D, Meyer D, Olofson F, Tan JG, Wästberg D, Xue L, Zhang Z (2017) Urban Multi-scale Environmental Predictor (UMEP) - An integrated tool for city-based climate services.  Environmental Modelling and Software, 99, 70-87 [https://doi.org/10.1016/j.envsoft.2017.09.020]( https://doi.org/10.1016/j.envsoft.2017.09.020) 
   * 	Grimmond, Sue, Lindberg, Fredrik, Allen, Lucy, Yogeswaran, N, Kotthaus, Simone (2018): LUCY: Large scale Urban Consumption of Energy. University of Reading. [Software http://dx.doi.org/10.17864/1947.149](http://dx.doi.org/10.17864/1947.149)

* Versions
   * Apple/Linux/Windows Version in [UMEP](https://umep-docs.readthedocs.io) called [LQF](http://umep-docs.readthedocs.io/en/latest/OtherManuals/LQF_Manual.html#lqf-manual)
   * Windows 7 standalone version: V2014a (25 June 2014) includes options to change spatial resolution.
     * [Model-32bit](http://researchdata.reading.ac.uk/149/3/LUCYSetup32bit.exe.zip)
     * [Model-64bit](http://researchdata.reading.ac.uk/149/2/LUCYSetup64bit.exe.zip)
     * See manual for the MCR download
     * Translation tool between Matlab binary format and ASCII raster: [mat2ascGUI.exe](http://researchdata.reading.ac.uk/149/4/mat2ascGUI.exe.zip) (11 March 2013)


* Manual
   *  [Standalone Version Manual http://dx.doi.org/10.17864/1947.149](http://dx.doi.org/10.17864/1947.149)
   *  [LQF Manual](http://umep-docs.readthedocs.io/en/latest/OtherManuals/LQF_Manual.html#lqf-manual)
   
 * Hints - if the standalone windows version has a problem running
    1.	Open a command prompt window (cmd.exe) as administrator. This is done by right-clicking on cmd.exe and choosing 'Run as Administrator'.
    2.	Locate the folder where the LUCY program is located.
    3.	Run the program, make your settings and press EXECUTE.
    4.	Report back any output from the command prompt.
    5.	Also check if a log text file was created in the LUCY folder. If so, attach it to your response (in GitHub). Please report issues [here](https://github.com/Urban-Meteorology-Reading/Urban-Meteorology-Reading.github.io/issues)

* Background

  The Large scale Urban Consumption of energY model (LUCY) simulates all components of anthropogenic heat flux (Q<sub>F</sub>) from the global to neighborhood scale at spatial resolutions ranging from 30 x 30 arc-second to 0.5° x 0.5°. Any day between 1900 and 2099 can theoretically be considered. The success of the outcome depends on the data available.

  The model includes a database of different working patterns and public holidays, vehicle use and energy consumption in each country. The databases can be edited to include specific diurnal and seasonal vehicle and energy consumption patterns, local holidays and flows of people within a city. If better information about individual cities is available within this (open-source) database, then the accuracy of this model can only improve, to provide the community data from global-scale climate modelling or the individual city scale in the future.

  The results show that Q<sub>F</sub> varied widely through the year, through the day, between countries and urban areas. An assessment of the heat emissions estimated revealed that they are reasonably close to those produced by a global model and a number of small-scale city models, so results from LUCY can be used with a degree of confidence.

  From LUCY, the global mean urban Q<sub>F</sub> has a diurnal range of 0.7 to 3.6 W m<sup>-2</sup>, and is greater on weekdays than weekends. The heat release from building is the largest contributor (89 to 96%), to heat emissions globally. Differences between months are greatest in the middle of the day (up to 1 W m<sup>-2</sup> at 1pm).
    * December to February, the coldest months in the Northern Hemisphere, have the highest heat emissions.
    * July and August are at the higher end. The least QF is emitted in May.

  The highest individual grid cell heat fluxes (W m<sup>-2</sup>) in urban areas were located in New York (577), Paris (261.5), Tokyo (178), San Francisco (173.6), Vancouver (119) and London (106.7).




