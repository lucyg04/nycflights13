# nycflights13
This project explores the nycflights13 dataset containing flights originating from New York City (JFK, LGA and EWR) to predict arrival delays and identify the primary factors contributing to those delays.

## Project Overview
This project addresses two questions:
1. **Predictive Modelling:** can we predict if a flight will arrive late before it departs?
2. **Feature Correlation:** which factors (weather, carrier, time of day, etc. are most strongly correlated with delays?

## Dataset
This analysis utilises a subset of the nycflights13 dataset, which includes:
* **flights.csv:** scheduled and actual departure/arrival times
* **weather.csv:** hourly meteorological data for the departure airports
* **planes.csv:** construction metadata for individual aircraft
* **airports.csv:** airport names and locations
* **airlines.csv:** two-letter codes mapped to full airline names
