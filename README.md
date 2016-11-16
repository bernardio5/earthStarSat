# earthStarSat
Objective-C lib for celestial observation

Three class sets:

"Eearth": calculates 4x4 transform matrix, given time, GPS, and accelerometer readings, of an observer's position relative to the Earth at the moment of vernal equinox. I think that there is also some code for the Sun's position, as well. 

"Satellites": Objective-C classes for loading and viewing objects orbiting the earth. Includes data from (do not remember) and PHP for parsing that data, which is in the "TLE" format, into XML that ObjC can read easily. 

"Stars": Obj-C classes for loading and viewing the stars. Includes data from the Yale survey, and a PHP kit for parsing it into XML, for easy loading. 

Caveats: no eyes have ever troubleshot this but mine. The orbits look right, but I need to do better with how satellite speed varies with time/distance from orbit foci. But, since the overwhemling majority of artificial, low-orbit satellites have practically circular orbits, this error is probably negligible. 

Intentions: 
I'd like to add the exoplanets! 
