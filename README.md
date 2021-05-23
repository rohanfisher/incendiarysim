# incendiarysim
Netlogo savanna fire simulation
## WHAT IS IT?

This model is a work in progress for a north Australian landscape fire simulation game. The primary idea is to show how a range of variables effect fire spread when conducting aerial incendiary management burns early in the dry season and how these fuel reduction fires effect the spread of late season wild fires.


## HOW IT WORKS

The model currently uses the following variable to determine if a pixel will ignite:

- a grass vegetation map derved from Landsat Satellite imagery and a time since burnt layer (from NAFI) to produce a fuel load variable.  The  vegetation layer shows grass, low cover and mangrove types.

- an elevation layer (SRTM-DEM) is used to determine slope in relation to fire spread direction.

- a topographic wetness layer, derived from the DEM, is used to represent differntial landscape curing.

- Fire danger as an value from 1 (wet season) to 10 (late dry season). This combines the influence of curing and temperature on fire spread.

- Wind speed from none (no wind influence) to strong. Wind speed increses the directionality and likelyhood of a pixel ignighting.

- wind direction (the direction a fire will spread)


## HOW TO USE IT

Click the drop incendaries button and use the cursor to ignite some initial pixels. Change curing, wind direction and wind speed to set your fire senario. Use the variable-wind button to allow the model to  randomly change the wind speed as the model runs. Use the view drop list to display a one of a range of landscape layers.


## THINGS TO NOTICE

Fires should not run down slope as well as up slope.
Fire do not burn will on recently burnt hummock grasslands.

## THINGS TO TRY

Try running the model to set fire breaks early in the in the dry season (fire danger 6-7) then run the model with some single ignition points late in the dry (curing 9-10). Are you able to prevent fires spreading through your early season burns.

Try runing the model with some of the different landscape layers displayed.

Try running it projected over a sandpit sculpted with refernece to the elevation layer.

## EXTENDING THE MODEL

- Variable fire spread speed
- Burn severity
- An estimate of chopper time/cost
- An estimate of burn cost to burn area and fire severity as a measure of management     burn effectiveness.


## RELATED MODELS

Based on the fire break model.

## CREDITS AND REFERENCES

This model was produced in May 2017, More information about the model can be found at: https://rohanfisher.wordpress.com/incendiary-a-fire-spread-modelling-tool/

Copyright 2017 Rohan Fisher.

![CC BY-NC-SA 3.0](http://ccl.northwestern.edu/images/creativecommons/byncsa.png)

This work is licensed under the Creative Commons Attribution-NonCommercial-ShareAlike 3.0 License.  To view a copy of this license, visit https://creativecommons.org/licenses/by-nc-sa/3.0/ or send a letter to Creative Commons, 559 Nathan Abbott Way, Stanford, California 94305, USA.
