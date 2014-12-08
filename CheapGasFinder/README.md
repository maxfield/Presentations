![Fuel Around logo](http://i.imgur.com/iEhaDLt.png) *Fuel Around*
---
Fuel Around is an Android app that calculates where the cheapest place to buy gas is.
Other apps can tell you where the cheapest price per gallon is, but Fuel Around factors in your
driving distance. You enter some information about your car, select how much gas your want,
enter a destination, and the app calculates the total cost of buying gas at each station
around you.

GitHub: (https://github.com/CSUChicoSoftwareEngineering/CheapGasFinder)

*Screenshots*
---
![Select Gas Amount screenshot](http://i.imgur.com/p90IRRy.png)
![Map of nearby gas stations](http://i.imgur.com/sk4rcXB.png)
![List of nearby gas stations](http://i.imgur.com/lspLFA8.png)

*How it works*
---
Gas prices comes from MyGasFeedAPI. Information about cars, such as tank size, MPG, and fuel type, comes from CarQueryAPI. Google Maps calculates the route from the starting location, to the gas station, and to the destination.

*Roadmap*
----
* All Java code is located in app/src/main/java/edu/csuchico/cheapgasfinder
* All tests are located in app/src/androidTest/java/edu/csuchico/cheapgasfinder
* XML files for views are located in app/src/main/res

*The team*
---
* Patrick Gibbons - CSCI major, from Pleasanton CA, Sigma Chi President
* Matthew Riddell - CSCI major, born & raised in Vermont, plays M:tG.
* Mason Wiley - CSCI major, lived in the small town Yreka, CA for most of my life.
* Zach Bloom - CSCI major, from Lafayette, CA, member of Sigma Chi Chico State
