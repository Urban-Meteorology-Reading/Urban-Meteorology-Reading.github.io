---
layout: default
---
[*back to main page*](./)

Please report issues [here](https://github.com/Urban-Meteorology-Reading/Urban-Meteorology-Reading.github.io/issues)


# SVF - IU - Sky view factor
* Brief
   * Sky View Factor from fisheye digital images
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
  * Lindberg F, CSB Grimmond 2010:  Continuous sky view factor from high resolution urban digital elevation models [Climate Research 42: 177-183 doi:10.3354/cr00882]
* Version
  * <a href="./other files/svf.zip" download>Download</a>
