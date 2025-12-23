# Airline Flights Analysis with Python (Pandas, Matplotlib, Seaborn)

![](image/plane.jpg)

### **Objective:**
This notebook analyzes the [Airline Flights](/dataset/airlines_flights_dataset.csv) dataset to explore pricing patterns, class-based differences, and the impact of various factors such as stops, departure/arrival time, source/destination cities, days_left, and more on ticket prices.  
The analysis is performed in Google Colab using Pandas, Matplotlib, and Seaborn.

### **Table of Contents**
- Part 1 — Dataset inspection and basic statistics  
- Part 2 — Visualization and relationship analysis  
- Part 3 — Price and class analysis  

### **Files**
- [Airline Flights Dataset](/dataset/airlines_flights_dataset.csv) — Dataset used in the analysis  
- [Airline Flights Analysis](/code/Airlines_flight_analysis.ipynb) — Google Colab notebook  

### **Key Findings**
- Ticket prices vary significantly across airlines, with Vistara having the highest prices and AirAsia offering the lowest.
- Business class tickets are considerably more expensive than Economy class tickets, while most flights belong to the Economy class.
- Business class flights also tend to have longer average durations compared to Economy class flights.
- Departure and arrival times have a noticeable impact on ticket prices, with evening and night flights generally being more expensive.
- Direct flights are the cheapest in this dataset, while one-stop flights have the highest average prices.
- Ticket prices increase sharply when bookings are made close to the departure date, especially within 0–12 days before the flight.
- Source and destination cities affect pricing, with certain cities (e.g., Chennai and Kolkata) showing higher average prices.
- Delhi is the source city with the highest number of flights, and it also offers relatively lower average prices.
- The most expensive flights in the dataset are dominated by Vistara, while the cheapest flights are mainly operated by GoFirst and Indigo.