# Sky model pictures (300x300 pixels) for the following cities:
  
### Switzerland
* BAS:	Basel, Switzerland, lat=47.33
* BIEL:	Biel, Switzerland, lat=47.1416
* FRIB:	Fribourg, Switzerland, lat=46.804
* GVA:	Geneva, Switzerland, lat=46.2447
  
### Europe
* ATHENS:	Athens, Greece, lat=37.967
* BERLIN:	Berlin, Germany, lat=52.47
* DELFT:	Delft, Holland, lat=52.0001
* HEL:	Helsinki, Finnland, lat=60.19
* LDN:	London, UK, lat=51.517
* VENEZIA:	Venezia, Italy, lat=45.5
  
### North America
* DENVER: Denver, USA, lat=39.83
* NY:	New-York, USA, lat=40.65
  
### South America
* MEXICO:	Mexico, lat=19.4
  
### Asia
* HKG:	Hong-Kong, lat=22.317 
* MUMBAI:	Mumbai, India, lat=19.117
* SEOUL:	Seoul, South Korea, lat=37.567

* SING:	Singapore, lat=1.37
  
All sky model pictures for a specific location are stored into a single tar file. 
Sky model pictures are named **LLLLXX.pic** where LLL refers to the location as abbreviated above
and XX to the time period over which the cumulative sky model is calculated (either months referred as **01** for January, **02** for February, ...
or **00** for the full year). For locations where a heating season can be identified (all days for which the mean outdoor temperature <=12°C),
two additional sky models are provided: **HH** for the heating season and **SS** for all other days.

All these sky model pictures have been generated from irradiation data provided by [Meteonorm](http://www.meteonorm.com/en/) software.
