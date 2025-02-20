#**Flight Price EDA (Exploratory Data Analysis)**

**Project Overview**

The Flight Price EDA project aims to analyze and visualize flight ticket prices based on various factors such as airline, departure time, number of stops, class, and booking period. Through data exploration, we seek to identify trends, correlations, and insights that can help travelers, airlines, and travel agencies make data-driven decisions.

#**Dataset Description**
| Feature |  Description  | 
|:-----|:--------:|
| Airline | Name of the airline company (Categorical: 6 unique values) | 
| Flight   |  Flight code identifier (Categorical) |   
| Source City   | City from which the flight takes off (Categorical: 6 unique values) |   
| Departure Time |  Binned departure time periods (Categorical: 6 labels)  | 
|Stops|Number of layovers between source and destination (Categorical: 3 values)|
| Arrival Time   | Binned arrival time periods (Categorical: 6 labels) | 
| Destination City   |  City where the flight lands (Categorical: 6 unique values)  |   
| Class   | Seat class: Business or Economy (Categorical: 2 values) |    
| Duration |  Total travel time in hours (Continuous)  | 
| Days Left   | Days between booking date and travel date (Continuous, Derived) | 
| Price   |  Ticket price (Target variable, Continuous)  |   

#**Exploratory Data Analysis (EDA) Steps**  
**Data Cleaning & Preprocessing**: Handling missing values, duplicate entries, and data formatting.
**Feature Analysis**: Understanding distributions, relationships, and patterns in data.

#**Future Scope**
* Build a machine learning model to predict flight prices.
* Integrate real-time flight pricing data via APIs.
* Develop an interactive dashboard for dynamic analysis.

#**Conclusion**
This Flight Price EDA project provides valuable insights into airline ticket pricing, helping travelers make informed booking decisions and allowing airlines to optimize pricing strategies.
