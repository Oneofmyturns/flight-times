# flight-times
Data collected on flight times in the US by year, for the purpose of examining changes in number of flights and delays over time.
Data is organized into folders by airport, then by Departures, Arrivals, and Cancellations.
The filenames have the format 'AirportCode-Airline-Year-Arr.csv', 'AirportCode-Airline-Year-Dep.csv', or 'AirportCode-Airline-Cncl.csv'.

### Data Attributes
Carrier Code, Date (MM/DD/YYYY), Flight Number, Tail Number, Origin/Destination Airport, Scheduled arrival/departure time, Actual arrival/departure time, Scheduled elapsed time (Minutes), Actual elapsed time (Minutes), Arrival/Departure delay (Minutes), Delay Carrier (Minutes), Delay Weather (Minutes), Delay National Aviation System (Minutes), Delay Security (Minutes), Delay Late Aircraft Arrival (Minutes)

### EDA
Files are still in .csv format, but the data contained is sufficient for basic analysis of trends in differences in delay times and cancellations. The columns denoting the specific reasons for delays will also make for interesting analysis (e.g. even if delays themselves have not changed significantly, have the portion of delays due to security concerns or extreme weather changed?).

Weather data would make the dataset much more robust. Historical data from weather stations located at each airport has been requested from NOAA.

### Other Ideas
  
  If I can obtain weather data for each airport's area, I can also analyze how much the weather affects delays and cancellations.
  I have requested this data and am awaiting a response from NOAA.
  Combined with a forecast of increases in certain weather, this could allow for predictions of future challenges.
