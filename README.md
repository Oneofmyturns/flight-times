# flight-times
Data collected on flight times in the US by year, for the purpose of examining changes in number of flights and delays over time.
Data is organized into folders by airport, then by Departures, Arrivals, and Cancellations.
The filenames have the format 'AirportCode-Airline-Year-Arr.csv', 'AirportCode-Airline-Year-Dep.csv', or 'AirportCode-Airline-Cncl.csv'.

### Data Attributes
Carrier Code, Date (MM/DD/YYYY), Flight Number, Tail Number, Origin/Destination Airport, Scheduled arrival/departure time, Actual arrival/departure time, Scheduled elapsed time (Minutes), Actual elapsed time (Minutes), Arrival/Departure delay (Minutes), Delay Carrier (Minutes), Delay Weather (Minutes), Delay National Aviation System (Minutes), Delay Security (Minutes), Delay Late Aircraft Arrival (Minutes)

### EDA
The data contained is currently sufficient for basic analysis of trends in differences in delay times and cancellations. Weather data would make the data much more robust. 

### Other Ideas
  
  If I can obtain weather data for each airport's area, I can also analyze how much the weather affects delays and cancellations.
  I have requested this data and am awaiting a response from NOAA.
  Combined with a forecast of increases in certain weather, this could allow for predictions of future challenges.
