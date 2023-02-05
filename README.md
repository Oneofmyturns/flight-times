# flight-times
Data collected on flight times in the US by year, for the purpose of examining changes in number of flights and delays over time.
Data is organized into folders by airport, then by Departures or Arrivals. 
The filenames have the format 'AirportCode-Airline-Year-Arr.csv' or 'AirportCode-Airline-Year-Dep.csv'

Attributes contained in the data are Carrier Code, Date (MM/DD/YYYY), Flight Number, Tail Number, Origin/Destination Airport, Scheduled arrival/departure time, Actual arrival/departure time, Scheduled elapsed time (Minutes), Actual elapsed time (Minutes), Arrival/Departure delay (Minutes), Delay Carrier (Minutes), Delay Weather (Minutes), Delay National Aviation System (Minutes), Delay Security (Minutes), Delay Late Aircraft Arrival (Minutes)

The data contained is currently sufficient for basic analysis of trends in differences in delay times. 

Other Ideas:
  If I can locate weather data for each airport's area, I can also analyze how much the weather affects delays and cancellations.
