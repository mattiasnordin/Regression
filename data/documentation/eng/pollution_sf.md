# Data on weather and pollution in San Francisco, 2010-2021

**Name**: ```pollution_sf```

**Description**: Daily time-series data on weather and pollution from the San Francsisco area in the US from January 1st 2010 to December 31st 2021.

**Source**: Pollution data come from the United States Environmental Protection Agency, while weather data come from NCEP North American Regional Reanalysis (NARR), provided by NOAA PSL, Boulder, Colorado, USA. Data have been processed by the R package author and neither EPA nor NOAA bear any responsibility for the final data.

**Variable list**:

-```utcdate```: Date of observation in year-month-day format.

-```pm25```: Average of hourly PM2.5 measurements during the give date in San Francisco city and county (fipscode 6075). PM2.5 is the mass of particles less than 2.5 micrometer in diameter measured in micrograms per cubic meter.

-```precipitation```: Precipitation in kilograms per square meter (equivalent to millimeters). Sum over eight measurements (every three hours).

-```temperature```: Temperature in degrees Celsius. Average of eight measurements during the given date.

-```wind_speed```: Wind speed in meters per second. Average of eight measurements during the given date.

-```wind_direction```: Wind direction in degrees with 0 (and 360) being wind from north, 90 wind from east, 180 wind from south and 270 wind from west. Average of eight measurements during the given date.

