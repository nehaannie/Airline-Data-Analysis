# Airline-Data-Analysis

## Airline Data Analysis
This project focuses on analyzing airline ticket and flight data to gain insights into revenue generation, ticket pricing, and flight performance. Using SQL and Python, we explore different aspects of the dataset, such as total revenue by flight, average ticket prices by fare condition, and the demand for premium seating.

## Project Structure
data/: Contains the SQLite database (travel.sqlite) with all the relevant tables.<br>
notebooks/: Jupyter notebooks used for data analysis and visualization.<br>
README.md: Project overview and instructions.<br>

## Tables in database

**aircrafts_data**: Information about different aircraft models.<br>
**airports_data**: Details about various airports.<br>
**boarding_passes**: Boarding passes issued for flights.<br>
**bookings**: Details about flight bookings.<br>
**flights**: Information about different flights.<br>
**seats**: Seat information for different aircraft.<br>
**ticket_flights**: Ticket information for each flight.<br>
**tickets**: General ticket information.<br>

## Questions addressed

How many planes have more than 100 seats?<br>
How have the number of tickets booked and the amount earned changed over time?<br>
What are the average charges of each aircraft with different fare conditions?<br>
For each aircraft, calculate the total revenue per year and the average revenue per ticket.<br>
What is the average occupancy per aircraft?<br>
Calculate by how much the total annual turnover could increase by giving all aircraft a 10% higher occupancy rate.<br>
Which cities have the most airports?<br>
What are the most common time zones for airports?<br>
What are the top aircraft models by range?<br>
Which seats are the most frequently occupied?<br>
Which fare condition generates the most revenue overall?<br>

## Technologies used

**Python**: Data processing and visualization.<br>
**SQLite**: Database management and SQL queries.<br>
**Pandas**: Data manipulation and analysis.<br>
**Matplotlib**: Data visualization.<br>

## How to Run

Clone the repository.<br>
Install the necessary libraries<br>
Run the Python scripts to perform the analysis.<br>

## Conclusion
This analysis provides insights into various aspects of the airline industry, such as revenue generation, seat occupancy, and aircraft efficiency. The SQL queries and Python scripts can be modified to explore further questions and derive additional insights.
