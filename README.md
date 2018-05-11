# World Water Scarcity
This is a leaflet map showing world water scarcity based on the the World Resource Institute (WRI) Aqueduct dataset
The files in this repository show that appended the World Bank population data for 1960 and 2016 to the Aqueduct dataset, as well as the change in population from 1960 to 2016. These data are held in attribute fields ```Field6```, ```Field7```, and ```Field8``` respectively. The file ```wriwaterscarcity-wbpop.geojson``` has the entire (WRI) dataset with those three extra attributes, while the ```wriwaterscarcity-wbpop-clipped.geojson``` file has only the total mean water scarcity index score from WRI with the three population fields. 

The WRI data is from 2013 and can be downloaded from http://www.wri.org/resources/data-sets/aqueduct-country-and-river-basin-rankings

The World Bank data is from 2018 and can be downloaded from https://data.worldbank.org/indicator/SP.POP.TOTL
