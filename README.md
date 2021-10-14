# Taxi Ride Analysis

## Project Description
In this project a in depth analysis has been carried out for a fictive new ride-share company named Zuber which is launching in Chicago.  
To find patterns and preferences in the passengers behaviour and the impact of external factors the company provided data in a database containing info on taxi rides in Chicago.

## Data aggregation
In order to select and use the necessary data a SQL query has been developed and executed.  
Additional to the provided data, the weather data of given time period has been scraped.  
To enable an in-depth understanding of the cab rides and the high variance in rides per company the public available datasets for medallion owners in Chicago has been downloaded via the API on the website of the city.

## Conclusion
The following steps have been performed within the project:

- Data mining, aggregation and merging
- Data preprocessing 
- Extensive Exploratory Data Analysis

Observations within the project:
- There are two different types of cab drivers: affiliations and independent drivers. The percentage of surrendered independent cab drivers since 2017 is pretty high. Therefore the Zuber needs to pay attention to bind their drivers pretty well
- The amount of rides to the city centre is significant higher than to the outer districts
- The weather does not influence the routes from the city center to the airport drastically, but for the rest of the destinations, the weather has an impact. (bad weather leads to an increase in rides) 
- The duration of the trips from the airport to the city centre differs. This can be explained by the general increased use of cars due to bad weather and consequentially fuller streets.
