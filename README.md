# QTH Locator Functions
Python functions for converting decimal coordinates to QTH locator and backwards.

## Overview
To be completed...

## QTH Locator Format

![QTH locator format](https://raw.githubusercontent.com/4x5dm/qth_locator_functions/master/images/qth_locator_format.png)

```
World (18x18 fields):
           -180° to +180°
        +-----------------+
   +90° |                 |
    to  |      18x18      |
   -90° |      fields     |
        |                 |
        +-----------------+

	   
Fields (10x10 squares):
               20°
        +-----------------+
        |                 |
    10° |      10x10      |
        |     squares     |
        |                 |
        +-----------------+

	   
Squares (10x10 subsquares):
                2°
        +-----------------+
        |                 |
     1° |      24x24      |
        |    subsquares   |
        |                 |
        +-----------------+


Subsquares (10x10 extended squares):
                5"
        +-----------------+
        |                 |
     1" |      10x10      |
        |   ext. squares  |
        |                 |
        +-----------------+


Extended squares:
               0.5"
        +-----------------+
        |                 |
  0.25" |                 |
        |                 |
        |                 |
        +-----------------+
```
       


## Links
1. http://www.jonit.com/fieldlist/maidenhead.htm
2. https://en.wikipedia.org/wiki/Maidenhead_Locator_System
3. http://qthlocator.free.fr/index.php
4. http://www.egloff.eu/googlemap_v3/carto.php

