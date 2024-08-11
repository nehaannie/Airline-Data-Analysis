# Airline-Data-Analysis

## Airline Data Analysis
This project focuses on analyzing airline ticket and flight data to gain insights into revenue generation, ticket pricing, and flight performance. Using SQL and Python, we explore different aspects of the dataset, such as total revenue by flight, average ticket prices by fare condition, and the demand for premium seating.

## Project Structure
data/: Contains the SQLite database (travel.sqlite) with all the relevant tables.
notebooks/: Jupyter notebooks used for data analysis and visualization.
scripts/: Python scripts that automate the analysis and visualization.
README.md: Project overview and instructions.

## Tables in database

aircrafts_data: Information about different aircraft models.
airports_data: Details about various airports.
boarding_passes: Boarding passes issued for flights.
bookings: Details about flight bookings.
flights: Information about different flights.
seats: Seat information for different aircraft.
ticket_flights: Ticket information for each flight.
tickets: General ticket information.

## Questions addressed

How many planes have more than 100 seats?
How have the number of tickets booked and the amount earned changed over time?
What are the average charges of each aircraft with different fare conditions?
For each aircraft, calculate the total revenue per year and the average revenue per ticket.
What is the average occupancy per aircraft?
Calculate by how much the total annual turnover could increase by giving all aircraft a 10% higher occupancy rate.
Which cities have the most airports?
What are the most common time zones for airports?
What are the top aircraft models by range?
Which seats are the most frequently occupied?
Which fare condition generates the most revenue overall?

## Technologies used

Python: Data processing and visualization.
SQLite: Database management and SQL queries.
Pandas: Data manipulation and analysis.
Matplotlib: Data visualization.

## How to Run

Clone the repository.
Install the necessary libraries:
Run the Python scripts to perform the analysis.

## Conclusion
This analysis provides insights into various aspects of the airline industry, such as revenue generation, seat occupancy, and aircraft efficiency. The SQL queries and Python scripts can be modified to explore further questions and derive additional insights.
