# code to create the table 

CREATE TABLE 'location' (
'ID' INTEGER NOT NULL PRIMARY KEY AUTOINCREMENT,
'species' char NOT NULL DEFAULT '', 
'countryCode' char NOT NULL DEFAULT '',
'stateProvince' char NOT NULL DEFAULT '',
'decimalLatitude' REAL NOT NULL DEFAULT'',
'decimalLongitude' REAL NOT NULL DEFAULT '',
'day' INTEGER NOT NULL DEFAULT '',
'month' INTEGER NOT NULL DEFAULT '',
'year' INTEGER NOT NULL DEFAULT '');
