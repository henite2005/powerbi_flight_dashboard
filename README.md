✈️ Airline Passenger & Flight Analytics Dashboard

![Home](https://github.com/user-attachments/assets/7d8f5bcc-9871-45a8-9f10-69fd47f85da3)


📌 Overview
This Power BI dashboard provides a comprehensive visual representation and analysis of airline passenger trends, flights, bookings, and travel behaviors. It is built around key datasets: Passengers, Flights, Airlines, Airports, and Customer Flights, linked via a robust relational model. The interface is designed for clarity, interactivity, and ease of navigation with an aviation-themed UI.

🧩 Problem Statement
- Airline and airport operators often struggle with gaining actionable insights into passenger demographics, flight delays, and operational efficiencies. Key challenges include:
- Identifying passenger travel behavior and spending patterns.
- Analyzing airline and airport performance.
- Tracking delays and disruptions across routes.
- Segmenting passengers based on job classification and region.
- Providing intuitive access to operational KPIs for stakeholders.

![Airlines](https://github.com/user-attachments/assets/2c02ffab-d0a1-4c60-ae96-abef69046dce)

🎯 Objectives
- To monitor passenger profiles and classification.
- To track and visualize flight performance and delays.
- To display real-time travel insights by region and airport.
- To highlight top-performing airlines and airports.
- To enable data-driven decisions by airline managers and data analysts.

📈 Key Performance Indicators (KPIs)
- Category	KPI Description
- Passenger	Total Passenger Count, Spend Per Passenger, Gender Distribution, Job Classification (White/Blue Collar, Other)
- Flights	On-Time vs Delayed Flights, Average Elapsed Time, Number of Diverted Flights
- Airlines	Airline Usage Frequency, Airline Popularity by Customer
- Airports	Top Origin and Destination Airports, Country and State Aggregates
- Bookings	Customer Booking Frequency, Airline Preference
- Travel Metrics	Real-time Date & Time Display, Travel History by Region

![Passengers](https://github.com/user-attachments/assets/f5711ff8-df4d-45ed-8bd2-8c9ce0d957c4)

🗃️ Data Model
The dashboard is built on a star-schema-like model with the following tables:
- PASSENGERS: Holds demographic and travel spending details.
- CUSTOMER_FLIGHTS: Links passengers to airlines.
- AIRLINES: Contains airline names, logos, and codes.
- FLIGHTS: Contains flight timings, delay metrics, and schedule details.
- AIRPORTS: Lists city, state, coordinates, and IATA codes of airports.

Relational integrity is maintained through keys like CustomerID, AIRLINE, and AIRPORT.

🧠 Key Features
- Modern Visual Navigation: Each dashboard section is easily accessible via icon-based, neumorphic-style navigation.
- 3D Donut/Pie Visualization: Job classification data is visualized interactively by region.
- Dynamic Date & Time Display: The dashboard updates to reflect real-time analytics.
- Gender & Classification Analysis: Quick filters and visuals to compare segments.
- Flight Delay Breakdown: View aircraft delay reasons and diverted flight trends.

![Passengers2](https://github.com/user-attachments/assets/9c283d83-8f9a-4c95-8bf3-4660349ed2e6)

🖥️ Dashboard Sections
- ✈️ Airlines – View performance, preferences, and airline profiles.
- 🌐 Airports – Explore airport-specific metrics and geographical data.
- 📖 Bookings – Customer flight logs and airline frequency.
- 🕐 Travel – Real-time travel dashboard with date and clock.
- 📊 Passengers – Demographic insights and classification segmentation.
- 📈 Overview – A high-level summary of travel operations and passenger flow.

🛠️ Technologies Used
- Power BI Desktop
- DAX for data modeling and KPIs
- Power Query for data transformations

![Travel-5](https://github.com/user-attachments/assets/3e750c9d-0b4d-4f36-a1c5-3976b7695721)

🧩 Usage Tips
- Use filters (e.g., Region, Airline, Gender) for drill-down analysis.
- Hover over 3D visuals for detailed tooltips and labels.
- Monitor date/time widgets for real-time context during presentations.
- Leverage table visuals to export granular-level data for reports.

📬 Feedback & Suggestions
I welcome improvements to enhance analytical scope or interface usability. 
Please report bugs or feature suggestions via henite2005@gmail.com 

![Travel-4](https://github.com/user-attachments/assets/0360a470-e94c-4200-8ee3-587c075e476d)


