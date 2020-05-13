# Build Data Dashboards: Flight Delays and Cancellations

## Project description
Create 3 visualizations to reveal insights from the Flight Delays and Cancellations data set. 


## About the data

This data comes from a Kaggle dataset and can be found [here](https://www.kaggle.com/usdot/flight-delays#flights.csv), it tracks the on-time performance of US domestic flights operated by large air carriers in 2015. 

The file used to create the data visualizations is the ''flights.csv'' file. 

The files ''airlines.csv'' and ''airports.csv'' are only used in conjustion with the main file to enhance the main data. 

Some questions include those pertaining to the following areas:

**Which airlines or airports have the worst delays?**

Determine which destinations and arrival destinations have the most delays? Doing this using maps is actually pretty difficult, but you may choose an alternative visual to provide this information. Think about what kind of aggregates might work best to determine which airlines and airports are the best and worst in terms of delays.

**What causes delays?**

Think about if you work at an airline and you want to decrease delays. What part of the flight causes the most delays? Do these causes vary by airport or time of year?


### Review the column Metadata
flghts.csv
- Delete first column: it had the line number, was not needed
- DAY_OF_WEEK replaced the numbers with the actual names of the day, starting with 1 as Monday. 
- CANCELLATION_REASON
Some of the columns you want to use in your project will have coded values that represent longer more readable values. For instance the cancellation_reason column in the flights data set has the values: A, B, C, D These letters are not understandable by themselves. You need to replace these letters with the full reason to make your visualizations including this data more readable.

These letters correspond with the following reasons.

A - Airline/Carrier

B - Weather

C - National Air System

D - Security

You should review the Column Metadata tab on Kaggle for each data set to find details about the data like the one I have outlined above.


## Contents
- ''flights.csv'' file
	- YEARYear of the Flight Trip
	- MONTHMonth of the Flight Trip
	- DAYDay of the Flight Trip
	- DAY_OF_WEEKDay of week of the Flight Trip
	- AIRLINEAirline Identifier
	- FLIGHT_NUMBERFlight Identifier
	- TAIL_NUMBERAircraft Identifier
	- ORIGIN_AIRPORTStarting Airport
	- DESTINATION_AIRPORTDestination Airport
	- SCHEDULED_DEPARTUREPlanned Departure Time
	- DEPARTURE_TIMEWHEEL_OFF - TAXI_OUT
	- DEPARTURE_DELAYTotal Delay on Departure
	- TAXI_OUTThe time duration elapsed between departure from the origin airport gate and wheels off
	- WHEELS_OFFThe time point that the aircraft's wheels leave the ground
	- SCHEDULED_TIMEPlanned time amount needed for the flight trip
	- ELAPSED_TIMEAIR_TIME+TAXI_IN+TAXI_OUT
	- AIR_TIMEThe time duration between wheels_off and wheels_on time
	- DISTANCEDistance between two airports
	- WHEELS_ONThe time point that the aircraft's wheels touch on the ground
	- TAXI_INThe time duration elapsed between wheels-on and gate arrival at the destination airport
	- SCHEDULED_ARRIVALPlanned arrival time
	- ARRIVAL_TIMEWHEELS_ON+TAXI_IN
	- ARRIVAL_DELAYARRIVAL_TIME-SCHEDULED_ARRIVAL
	- DIVERTEDAircraft landed on airport that out of schedule
	- CANCELLEDFlight Cancelled (1 = cancelled)
	- CANCELLATION_REASONReason for Cancellation of flight: A - Airline/Carrier; B - Weather; C - National Air System; D - Security
	- AIR_SYSTEM_DELAYDelay caused by air system
	- SECURITY_DELAYDelay caused by security
	- AIRLINE_DELAYDelay caused by the airline
	- LATE_AIRCRAFT_DELAYDelay caused by aircraft
	- WEATHER_DELAYDelay caused by weather
	
- ''airlines.csv'' file
	- IATA_CODE
	- AIRLINE
- ''airports.csv'' file
	- IATA_CODE
	- AIRPORT
	- CITY
	- STATE
	- COUNTRY
	- LATITUDE
	- LONGITUDE
- A PDF or Markdown report that includes the following sections:
	- Links to your dashboards or story: You must submit url links for each of your visuals from Tableau Public. If you need a reminder on how to save to Tableau Public, please see the next concept.
	- Summary: brief description of the visualization and the main story or findings conveyed
	- Design: explain any design choices you made including changes to the visualization after collecting feedback
	- Resources: list of Web sites, books, forums, blog posts, GitHub repositories etc that you referred to or used in this submission (Add N/A if you did not use such resources).

## Tools 
- [Tableu Public](https://public.tableau.com/en-us/s/) 
