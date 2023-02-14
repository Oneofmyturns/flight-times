# flight-times
Data collected on flight times in the US by year, for the purpose of examining changes in number of flights and delays over time.
Data is organized into folders by airport, then by Departures, Arrivals, and Cancellations.
The filenames have the format 'AirportCode-Airline-Year-Arr.csv', 'AirportCode-Airline-Year-Dep.csv', or 'AirportCode-Airline-Cncl.csv'.

### Data Attributes - Departures, Arrivals, Cancellations
Carrier Code, Date (MM/DD/YYYY), Flight Number, Tail Number, Origin/Destination Airport, Scheduled arrival/departure time, Actual arrival/departure time, Scheduled elapsed time (Minutes), Actual elapsed time (Minutes), Arrival/Departure delay (Minutes), Delay Carrier (Minutes), Delay Weather (Minutes), Delay National Aviation System (Minutes), Delay Security (Minutes), Delay Late Aircraft Arrival (Minutes)

### Data Attributes - Weather
"STATION" - Station ID, 
"NAME" - Station Name, 
"DATE" - Date, 
"AWND" - Average Wind, 
"FMTM" - Fastest 1-minute Wind (HHMM), 
"PGTM" - Peak Gust Time (HHMM), 
"PRCP" - Precipitation (inches), 
"PSUN" - Percent of Possible Sunshine, 
"SNOW" - Snowfall (inches), 
"SNWD" - Snow Depth, 
"TAVG" - Average Temperature, 
"TMAX" - Max Temperature, 
"TMIN" - Min Temperature, 
"TSUN" - Total Sunshine, 
"WDF2" - Direction of Fastest 2-Minute Wind, 
"WDF5" - Direction of Fastest 5-Minute Wind, 
"WESD" - Water Equivalent of Snow on Ground, 
"WSF2" - Fastest 2-Minute Wind Speed, 
"WSF5" - Fastest 5-Minute Wind Speed, 
"WT01" - Fog, 
"WT02" - Heavy/Freezing Fog, 
"WT03" - Thunder, 
"WT04" - Ice pellets, sleet, snow, small hail, 
"WT05" - Hail, 
"WT06" - Glaze of Rime, 
"WT07" - Dust, Volcanic Ash, Blowing Dust/Sand/Obstructions, 
"WT08" - Smoke or Haze, 
"WT09" - Blowing or Drifting Snow, 
"WT10" - Tornado, Waterspout/Funnel Cloud, 
"WT11" - High/Damaging Winds, 
"WT13" - Mist,
"WT14" - Drizzle, 
"WT15" - Freezing Drizzle, 
"WT16" - Rain, 
"WT17" - Freezing Rain, 
"WT18" - Snow, Snow pellets/grains, Ice Crystals, 
"WT19" - Precipitation(Unknown Source), 
"WT21" - Ground Fog, 
"WT22" - Ice Fog/Freezing Fog, 
"WV01" - Fog, Ice/Freezing Fog in Vicinity, 
"WV03" - Thunder in Vicinity

### EDA
Files are still in .csv format, but the data contained is sufficient for basic analysis of trends in differences in delay times and cancellations. The columns denoting the specific reasons for delays will also make for interesting analysis (e.g. even if delays themselves have not changed significantly, have the portion of delays due to security concerns or extreme weather changed?).

Weather data has been added for all four tracked airports

### Other Ideas
  
  If I can obtain weather data for each airport's area, I can also analyze how much the weather affects delays and cancellations.
  I have received this data from the NOAA.
  
  
