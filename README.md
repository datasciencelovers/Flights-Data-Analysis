# Flights-Data-Analysis
Big Data Analysis with Python

_**Project Video available on YouTube - https://youtu.be/gu3Ot78j_Gc**_

### Airlines Flights Dataset for Different Cities

The Flights Booking Dataset of various Airlines is a scraped datewise from a famous website in a structured format. The dataset contains the records of flight travel details between the cities in India. Here, multiple features are present like Source & Destination City, Arrival & Departure Time, Duration & Price of the flight etc.

This data is available as a CSV file. We are going to analyze this data set using the Pandas DataFrame.

This analyse will be helpful for those working in Airlines, Travel domain.

## Using this dataset, we answered multiple questions with Python in our [Project]([url](https://youtu.be/gu3Ot78j_Gc)).

Q.1. What are the airlines in the dataset, accompanied by their frequencies?

Q.2. Show Bar Graphs representing the Departure Time & Arrival Time.

Q.3. Show Bar Graphs representing the Source City & Destination City.

Q.4. Does price varies with airlines ?

Q.5. Does ticket price change based on the departure time and arrival time?

Q.6. How the price changes with change in Source and Destination?

Q.7. How is the price affected when tickets are bought in just 1 or 2 days before departure?

Q.8. How does the ticket price vary between Economy and Business class?

Q.9. What will be the Average Price of Vistara airline for a flight from Delhi to Hyderabad in Business Class ?

## These are the main Features/Columns available in the dataset :

1) Airline: The name of the airline company is stored in the airline column. It is a categorical feature having 6 different airlines.

2) Flight: Flight stores information regarding the plane's flight code. It is a categorical feature.

3) Source City: City from which the flight takes off. It is a categorical feature having 6 unique cities.

4) Departure Time: This is a derived categorical feature obtained created by grouping time periods into bins. It stores information about the departure time and have 6 unique time labels.

5) Stops: A categorical feature with 3 distinct values that stores the number of stops between the source and destination cities.

6) Arrival Time: This is a derived categorical feature created by grouping time intervals into bins. It has six distinct time labels and keeps information about the arrival time.

7) Destination City: City where the flight will land. It is a categorical feature having 6 unique cities.

8) Class: A categorical feature that contains information on seat class; it has two distinct values: Business and Economy.

9) Duration: A continuous feature that displays the overall amount of time it takes to travel between cities in hours.

10) Days Left: This is a derived characteristic that is calculated by subtracting the trip date by the booking date.

11) Price: Target variable stores information of the ticket price.
