
Australian Renewable Energy Mapping Infrastructure
==================================================

[AREMI](http://nationalmap.gov.au/renewables) is a website for map-based access to Australian spatial data relevant to the Renewable Energy industry - with a focus on Developers, Financiers, and Policy Makers. It is funded by the [Australian Renewable Energy Agency](http://arena.gov.au/) and developed by [NICTA](http://www.nicta.com.au/) in partnership with the [Clean Energy Council](https://www.cleanenergycouncil.org.au/) with hosting being provided by [Geoscience Australia](http://www.ga.gov.au/).

AREMI is based on NICTA's Open Source TerriaJS web geospatial platform: https://github.com/TerriaJS/terriajs
The [National Map](http://nationalmap.gov.au) is a website for map-based access to Australian spatial data from government agencies. It is an initiative of the Australian Commonwealth Government's [Department of the Prime Minister and Cabinet](http://www.dpmc.gov.au/) and the software has been developed by [NICTA](http://www.nicta.com.au/) working closely with the Department of the Prime Minister and Cabinet, [Geoscience Australia](http://www.ga.gov.au/) and other government agencies.

The National Map is designed to:
* Provide easy access to authoritative and other spatial data to government, business and public
* Facilitate the opening of data by federal, state and local government bodies
* Provide an open framework of geospatial data services that supports commercial and community innovation

### Getting Started ###
Please don't use **this** repo. Instead, start your map from https://github.com/TerriaJS/Map, which is maintained as a starting point for third-party maps, without the NationalMap branding.

Pre-requisites: Git, NodeJS, NPM, GDAL (optional). (See the wiki for details)

 ```
 sudo npm install -g gulp                     # Install gulp, the build tool
 git clone https://github.com/TerriaJS/Map    # Get the code
 cd Map
 npm install                                  # Install dependencies
 npm start                                    # Start the server in the background
 gulp watch                                   # Build the site, and watch for changes.
 ```

See the [wiki](https://github.com/NICTA/nationalmap/wiki) for more detailed information about Terria and how to build and run it.
