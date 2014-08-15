gdal2tiles
==========

This is a fork of `gdal2tiles` from GDAL 1.9.2.

This work was initiated by Marion Bechennec for her internship.

The objectives were to refactor the original `gdal2tiles` code, to improve its maintainability, and to allow parallel processing of tiles.

The parallel processing has been added using the `multiprocess` python module.


#### mike's addendum

fixed the TMS issue where tiles get flipped on Y. got the code from 
[this GIS stackexchange answer](http://gis.stackexchange.com/questions/63024/gdal2tiles-maptiles-from-bsb-kap-are-switched/63025#63025).

