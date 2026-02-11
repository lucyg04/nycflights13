This file gives a brief description of each feature in the dataset.
The dataset originates from the OpenFlights database, and so you may find further information
on the [OpenFlights documentation pages](https://openflights.org/data.php?utm_source=chatgpt.com).

## Airlines

* **carrier**: IATA code used to refer to an airline
* **name**: the airline company name

## Airports

* **faa**: the FAA location identifier used to refer to an airport
* **name**: the name of the airport
* **lat**: the latitude of the airport
* **lon**: the longitude of the airport
* **alt**: the altitude of the airport, in feet
* **tz**: the timezone offset from UTC
* **dst**: daylight savings regime used by the airport. One of E (Europe), A (US/Canada), S (South America), O (Australia), Z (New Zealand), N (None) or U (Unknown).
* **tzone**: IANA timezone name

## Planes

* **tailnum**: the tail number of the aircraft
* **year**: the year of manufacture
* **type**: the aircraft type
* **manufacturer**: the aircraft manufacturer
* **model**: the aircraft model number
* **engines**: the number of engines on the aircraft
* **seats**: the passenger seating capacity
* **speed**: cruising speed in mph
* **engine**: type of engine

## Weather

* **origin**: the FAA location identifier of the aiport
* **year**: year 
* **month**: month of the year
* **day**: day of the month 
* **hour**: hour of the day 
* **temp**: the temperature in degrees Fahrenheit
* **dewp**: the dew point in degrees Fahrenheit
* **humid**: the relative humidity (%)
* **wind_dir**: wind direction in degrees
* **wind_speed**: the wind speed in mph
* **wind_gust**: wind gust speed in mph
* **precip**: precipitation in inches
* **pressure**: sea level pressure in millibars
* **visib**: visibility in miles
* **time_hour**: date and hour of the recording in ISO 8601 format

## Flights

* **year**: year
* **month**: month of the year
* **day**: day of the month
* **dep_time**: actual departure time (format HHMM or HMM) in the local timezone
* **sched_dep_time**: scheduled departure time (format HHMM or HMM) in the local timezone
* **dep_delay**: departure delay in minutes; negative times represent early departures
* **arr_time**: actual arrival time (format HHMM or HMM) in the local timezone
* **sched_arr_time**: scheduled arrival time (format HHMM or HMM) in the local timezone
* **arr_delay**: arrival delay in minutes; negative times represent early arrivals
* **carrier**: IATA airline code
* **flight**: flight number
* **tailnum**: plane tail number
* **origin**: FAA location ID of origin airport
* **dest**: FAA location ID of destination airport
* **air_time**: amount of time spent in the air, in minutes
* **distance**: distance between airports, in miles
* **hour**: hour of scheduled departure, in the local timezone
* **minute**: minute of scheduled departure, in the local timezone
* **time_hour**: scheduled departure time in ISO 8601 format