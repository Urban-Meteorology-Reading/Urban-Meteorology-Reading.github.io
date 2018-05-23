---
layout: default
---

<!-- Text can be **bold**, _italic_, or ~~strikethrough~~. -->

<!-- [Link to another page](./another-page.html). -->

<!--
There should be whitespace between paragraphs.

There should be whitespace between paragraphs. We recommend including a README, or a file with information about your project. -->


Links to public releases of softwares developed by Urban Meteorology Group at University of Reading.
Please report issues [here](https://github.com/Urban-Meteorology-Reading/Urban-Meteorology-Reading.github.io/issues)

# SUEWS 
* References
  * Jarvi et al. (2011) J. Hydrology
  * Jarvi et al. (2014) GMD 
  * Ward et al. (2016) [Urban Climate](https://www.sciencedirect.com/science/article/pii/S2212095516300256)
  * Grimmond CSB  Oke TR & Steyn DG (1986) Urban water balance: 1. A model for daily totals. Water Resources Research 22(10) 1397-140
  * Grimmond CSB & Oke TR (1991). An evapotranspiration-interception model for urban areas. Water Resources Research 27(7) 1739-1755
  * Grimmond CSB, Cleugh HA & Oke TR (1991) An objective urban heat storage model and its comparison with other schemes. Atmospheric Environment 25B 311-326
* Manual
  * Latest version of the [Manual](http://suews-docs.readthedocs.io)
* Versions
  * There is a version in [UMEP](https://umep-docs.readthedocs.io/en/latest/) 
  * Standalone V2017b
    * macOS <a href="other files/SUEWS_V2017b_macOS.zip" download>Download </a>
    * Windows10x64 <a href="other files/SUEWS_V2017b_Win10x64.zip" download>Download</a>


# SUEWS
* Brief
  * urban radiaion – energy and water balance model. Includes LUMPS and can be used to calculate QF.
* References
  * Grimmond & Oke (1991) WRR
  * Jarvi et al. (2011) J. Hydrology
  * Jarvi et al. (2014) GMD 
  * Ward et al. (2016) [Urban Climate](https://www.sciencedirect.com/science/article/pii/S2212095516300256)
* Manual
  * Latest version of the [Manual](http://suews-docs.readthedocs.io)
* Versions
  * There is a version in [UMEP](https://umep-docs.readthedocs.io/en/latest/) 
  * Standalone V2017b
    * Apple IOS <a href="other files/SUEWS_V2017b_macOS.zip" download>Download </a>
    * Windows10x64 <a href="other files/SUEWS_V2017b_Win10x64.zip" download>Download</a>
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
   * Version in <a href="https://umep-docs.readthedocs.io/en/latest/">UMEP</a> called <a href="https://umep-docs.readthedocs.io/en/latest/OtherManuals/LQF_Manual.html#">LQF</a> 
   * Current version: V2014a (25 June 2014) includes options to change spatial resolution. 
     * [Model-32bit](http://www.met.reading.ac.uk/micromet/documents/SoftwareDownloads/LUCYdownload/LUCYSetup_32bit.exe)  
     * [Model-64bit](http://www.met.reading.ac.uk/micromet/documents/SoftwareDownloads/LUCYdownload/LUCYSetup64bit.exe)
     * See manual for the MCR download
     * Translation tool between Matlab binary format and ASCII raster: [mat2ascGUI.exe](http://www.met.reading.ac.uk/micromet/documents/SoftwareDownloads/LUCYdownload/mat2ascGUI.exe) (11 March 2013)
* Manual 
   *  [Manual](http://www.met.reading.ac.uk/micromet/documents/SoftwareDownloads/LUCYdownload/LUCY-UserManual.pdf)
* Background 
  * The Large scale Urban Consumption of energY model (LUCY) simulates all components of anthropogenic heat flux (Q<sub>F</sub>) from the global to neighborhood scale at spatial resolutions ranging from 30 x 30 arc-second to 0.5° x 0.5°. Any day between 1900 and 2099 can theoretically be considered. The success of the outcome depends on the data available. The model includes a database of different working patterns and public holidays, vehicle use and energy consumption in each country. The databases can be edited to include specific diurnal and seasonal vehicle and energy consumption patterns, local holidays and flows of people within a city. If better information about individual cities is available within this (open-source) database, then the accuracy of this model can only improve, to provide the community data from global-scale climate modelling or the individual city scale in the future. The results show that Q<sub>F</sub> varied widely through the year, through the day, between countries and urban areas. An assessment of the heat emissions estimated revealed that they are reasonably close to those produced by a global model and a number of small-scale city models, so results from LUCY can be used with a degree of confidence. From LUCY, the global mean urban Q<sub>F</sub> has a diurnal range of 0.7 to 3.6 W m<sup>-2</sup>, and is greater on weekdays than weekends. The heat release from building is the largest contributor (89 to 96%), to heat emissions globally. Differences between months are greatest in the middle of the day (up to 1 W m<-2at 1pm). December to February, the coldest months in the Northern Hemisphere, have the highest heat emissions. July and August are at the higher end. The least QF is emitted in May. The highest individual grid cell heat fluxes (W m<sup>-2</sup>) in urban areas were located in New York (577), Paris (261.5), Tokyo (178), San Francisco (173.6), Vancouver (119) and London (106.7).

# GreaterQF
* Brief
   * Calculation of QF for London 200 m x 200 m spatial resolution and 30 min temporal resolution.
* References
   * Iamarino M, Sean Beevers, C. S. B. Grimmond (2011) High Resolution (Space, Time) Anthropogenic Heat Emissions: London 1970 – 2025. [International Journal of Clmatology](http://onlinelibrary.wiley.com/doi/10.1002/joc.2390/abstract)
   * Gabey et al. (2018) [TAC](https://link.springer.com/article/10.1007%2Fs00704-018-2367-y)
    * Lindberg et al. (2018)
* Versions
   * More generic version (i.e. not just for London) in <a href="https://umep-docs.readthedocs.io/en/latest/">UMEP</a> called  <a href="https://umep-docs.readthedocs.io/en/latest/OtherManuals/GQF_Manual.html#">GQF</a> 
  * <a href="./other files/GreaterQFV3.2.7z" download>Download</a>






# LUMPS
* Brief
   * Surface flux model that utilises standard meteorological observations and land cover characteristics. It can model the variability in fluxes both spatially and temporally.
* References
  * Grimmond CSB. & Oke TR (2002). Turbulent heat fluxes in urban areas: Observations and a local-scale urban meteorological parameterization scheme (LUMPS). Journal of Applied Meteorology 41 792-810
  * Loridan T – CSB Grimmond BD Offerle DT Young T Smith L Jarvi F Lindberg (2011). Local-Scale Urban Meteorological Parameterization Scheme (LUMPS): longwave radiation parameterization & seasonality related developments Journal of Applied Meteorology & Climatology.doi: [10.1175/2010JAMC2474.1](http://journals.ametsoc.org/doi/pdf/10.1175/2010JAMC2474.1)
   * Offerle B  Grimmond CSB & Oke TR (2003). Parameterization of net all-wave radiation for urban areas.Journal of Applied Meteorology 42 1157-1173
   * Grimmond CSB & Oke TR (1999). Heat storage in urban areas: Local-scale observations and evaluation of a simple model. Journal of Applied Meteorology 38 922-940
* Manual 
  * <a href="other files/LUMPSv5_6_IO.pdf" download> Manual PDF</a>
* Versions
  * V5_6<a href="other files/LUMPS_V5_6.zip" download> Download</a>
  * Within SUEWS (see above)

# GreaterQF
* Brief
   * Calculation of QF for London 200 m x 200 m spatial resolution and 30 min temporal resolution.
* References
   * Iamarino M, Sean Beevers, C. S. B. Grimmond (2011) High Resolution (Space, Time) Anthropogenic Heat Emissions: London 1970 – 2025. [International Journal of Clmatology](http://onlinelibrary.wiley.com/doi/10.1002/joc.2390/abstract)
   * Gabey et al. (2018) [TAC](https://link.springer.com/article/10.1007%2Fs00704-018-2367-y)
    * Lindberg et al. (2018)
* Versions
   * More generic version (i.e. not just for London) in <a href="https://umep-docs.readthedocs.io/en/latest/">UMEP</a> called  <a href="https://umep-docs.readthedocs.io/en/latest/OtherManuals/GQF_Manual.html#">GQF</a> 
  * <a href="./other files/GreaterQFV3.2.7z" download>Download</a>

# SVF - IU - Sky view factor
* Brief
   * Sky View Factor from digital images   Software download form
* Manual
  * Output, File generated: svf_res.txt 
      * SVF    1-SVF   WHITE   BLACK    %WHITE   nring   ny    ichoice   FOV  Input File
  * Input, File with list of files: file_in.svf
      * contents: list of filenames with images to be analysed  -  quote marks should be around each filename
  * Format of files analyzed:  pgm format
     * can be generated using IfranView   The image should only have two colors (black and white)
  * Language
     * Fortran
     * Array size should be changed to meet camera resolution 
* Reference
  * Grimmond CSB, SK Potter, HN Zutter, C Souch 2001: Rapid methods to estimate sky view factors applied to urban areas. International Journal of Climatology 21 903-913
* Version
  * <a href="./other files/svf.zip" download>Download</a>
  
  
  
  
  

  
# FRAISE
* Brief
  * Flux Ratio – Active Index Surface Exchange
  * Midday (within 3 h of solar noon)
  * calculates active surface – and fluxes
* Language
  * R code
* Software
  * Download *****
   * Version 2012

* Manual
  * [Manual](http://www.met.rdg.ac.uk/micromet/documents//FRAISE_UserManual_Aug2011.pdf)
* References
  * Loridan TCSB Grimmond (2012) Characterization of <strong>energy flux partitioning in urban environments: links with surface seasonal properties Journal of Applied Meteorology and Climatology 51 219-241 [doi: 10.1175/JAMC-D-11-038.1](http://journals.ametsoc.org/doi/pdf/10.1175/JAMC-D-11-038.1) [colour figures](http://www.met.reading.ac.uk/micromet/publications/Colour_Figures_LoridanGrimmond2012JAMC.pdf)

# Publications


  * SUEWS OHM – LUMPS
*
  * LUMPS NARP – SUEWS 
* Offerle B (2003) The energy balance of an urban area: Examining temporal and spatial variability through measurements – remote sensing and modeling. PhD thesis Indiana University
  * LUMPS
* Xu W Wooster MJ & Grimmond CSB (2008). Modelling of urban sensible heat flux at multiple spatial scales: A demonstration using hyperspectral imagery of Shanghai and a temperature-emissivity separation approach. Remote Sensing of Environment 112 3493-3510
  * LUMPS – NARP – OHM.
* Järvi L - CSB Grimmond A Christen (2011) The<strong>S</strong>urface <strong>U</strong>rban <strong>E</strong>nergy and <strong>W</strong>ater Balance <strong>S</strong>cheme (SUEWS): Evaluation in Vancouver  and Los Angeles. [Journal of Hydrology doi:10.1016/j.jhydrol.2011.10.001](http://www.sciencedirect.com/science/article/pii/S0022169411006937)
  * SUEWS
* Järvi L, Grimmond CSB, Taka M, Nordbo A, Setälä H, Strachan IB (2014) Development of the Surface Urban Energy and Water balance Scheme (SUEWS) for cold climate cities.[Geoscientific Model Development 7 1691-1711. doi](http://dx.doi.org/10.5194/gmd-7-1691-2014) 
 * SUEWS
* Allen L - F Lindberg CSB Grimmond (2011) Global to city scale model for anthropogenic heat flux<i> International Journal of Climatology</i> 31 1990-2005
   * LUCY
* Lindberg F Grimmond CSB Nithiandamdan Y Kotthaus S Allen L (2013) Impact of city changes and weather on anthropogenic heat flux in Europe 1995–2015 [Urban Climate](http://dx.doi.org/10.1016/j.uclim.2013.03.002)
   * LUCY
* Iamarino M Sean Beevers CSB Grimmond (2011) High Resolution (Space - Time) Anthropogenic Heat Emissions: London 1970 – 2025. [International Journal of Clmatology](http://onlinelibrary.wiley.com/doi/10.1002/joc.2390/abstract)
   * GreaterQF
* Lindberg F, CSB Grimmond 2010:  Continuous sky view factor from high resolution urban digital elevation models [Climate Research 42: 177-183 doi:10.3354/cr00882] 
  * SVF




<!--
This is a normal paragraph following a header. GitHub is a code hosting platform for version control and collaboration. It lets you and others work together on projects from anywhere.

## Header 2

> This is a blockquote following a header.
>
> When something is important enough, you do it even if the odds are not in your favor.

### Header 3

```js
// Javascript code with syntax highlighting.
var fun = function lang(l) {
  dateformat.i18n = require('./lang/' + l)
  return true;
}
```

```ruby
# Ruby code with syntax highlighting
GitHubPages::Dependencies.gems.each do |gem, version|
  s.add_dependency(gem, "= #{version}")
end
```

#### Header 4

*   This is an unordered list following a header.
*   This is an unordered list following a header.
*   This is an unordered list following a header.

##### Header 5

1.  This is an ordered list following a header.
2.  This is an ordered list following a header.
3.  This is an ordered list following a header.

###### Header 6

| head1        | head two          | three |
|:-------------|:------------------|:------|
| ok           | good swedish fish | nice  |
| out of stock | good and plenty   | nice  |
| ok           | good `oreos`      | hmm   |
| ok           | good `zoute` drop | yumm  |

### There's a horizontal rule below this.

* * *

### Here is an unordered list:

*   Item foo
*   Item bar
*   Item baz
*   Item zip

### And an ordered list:

1.  Item one
1.  Item two
1.  Item three
1.  Item four

### And a nested list:

- level 1 item
  - level 2 item
  - level 2 item
    - level 3 item
    - level 3 item
- level 1 item
  - level 2 item
  - level 2 item
  - level 2 item
- level 1 item
  - level 2 item
  - level 2 item
- level 1 item

### Small image

![Octocat](https://assets-cdn.github.com/images/icons/emoji/octocat.png)

### Large image

![Branching](https://guides.github.com/activities/hello-world/branching.png)


### Definition lists can be used with HTML syntax.

<dl>
<dt>Name</dt>
<dd>Godzilla</dd>
<dt>Born</dt>
<dd>1952</dd>
<dt>Birthplace</dt>
<dd>Japan</dd>
<dt>Color</dt>
<dd>Green</dd>
</dl>

```
Long, single-line code blocks should not wrap. They should horizontally scroll if they are too long. This line should be long enough to demonstrate this.
```

```
The final element.
``` -->
