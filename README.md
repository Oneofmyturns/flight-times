# flight-times
Data collected on flight times in the US by year, for the purpose of examining changes in number of flights and delays over time.
Data is organized into folders by airport, then by Departures, Arrivals, and Cancellations.
The filenames have the format 'AirportCode-Airline-Year-Arr.csv', 'AirportCode-Airline-Year-Dep.csv', or 'AirportCode-Airline-Cncl.csv'.

### Data Attributes - Departures, Arrivals, Cancellations
Carrier Code, Date (MM/DD/YYYY), Flight Number, Tail Number, Origin/Destination Airport, Scheduled arrival/departure time, Actual arrival/departure time, Scheduled elapsed time (Minutes), Actual elapsed time (Minutes), Arrival/Departure delay (Minutes), Delay Carrier (Minutes), Delay Weather (Minutes), Delay National Aviation System (Minutes), Delay Security (Minutes), Delay Late Aircraft Arrival (Minutes)

### Data Attributes - Weather
"STATION" - Station ID,"NAME" - Station Name, "DATE" - Date, "AWND" - Average Wind, "FMTM" - Fastest 1-minute Wind (HHMM), "PGTM" - Peak Gust Time (HHMM), "PRCP" - Precipitation (inches), "PSUN" - Percent of Possible Sunshine, "SNOW" - Snowfall (inches), "SNWD","TAVG","TMAX","TMIN","TSUN","WDF2","WDF5","WESD","WSF2","WSF5","WT01","WT02","WT03","WT04","WT05","WT06","WT07","WT08","WT09","WT10","WT11","WT13","WT14","WT15","WT16","WT17","WT18","WT19","WT21","WT22","WV01","WV03"

### EDA
Files are still in .csv format, but the data contained is sufficient for basic analysis of trends in differences in delay times and cancellations. The columns denoting the specific reasons for delays will also make for interesting analysis (e.g. even if delays themselves have not changed significantly, have the portion of delays due to security concerns or extreme weather changed?).

Weather data has been added for all four tracked airports

### Other Ideas
  
  If I can obtain weather data for each airport's area, I can also analyze how much the weather affects delays and cancellations.
  I have received this data from the NOAA.
  
