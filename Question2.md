# Normalize the data

To answer this question I would like to sugest that we could create a normilized table (from occurrence.onca.csv) with information about the location of the occurrences (countries and states also include longitude and latitude) and the date, month, and year of the occurrence.
With this information we could obtain an indication of the predominant area of habitat, and we can identfy if the animal is changing the area of habitat over the years.

Column | Data Type | Description
-------|------------|----------
ID | integer | create a ID for each observation
species | char | describe the specie analyzed
countryCode | char | the country of the observation
stateProvince | char | the state or province of the observation
decimalLatitude | real | the latitude of the observation
decimalLongitude | real | the longitude of the observation
day | integer | the day of the observation
month | integer | the month of the observation
year | | integer | the year of the observation
