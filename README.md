# ENERGY-CONSUMPTION-ANALYSIS-SQL
📌 Project Overview

This project presents a comprehensive SQL-based analysis of global energy trends.
By integrating datasets related to energy consumption, production, emissions, GDP, and population, the project explores how economic growth impacts energy usage and environmental sustainability.

The system enables structured analysis using a normalized relational database, making it suitable for analytical queries and real-world decision-making.

🗄️ Database Schema

The project uses a relational database named ENERGYDB2, designed with normalization principles to ensure data integrity, consistency, and scalability.

📊 Tables and Relationships

country
Central master table containing unique country identifiers (CID) and country names.

emission_3
Stores yearly CO₂ emission data and per-capita emission values, categorized by energy type.

population
Contains historical population data for each country across multiple years.

production
Tracks energy production volumes by energy type and year for each country.

consumption
Records total energy consumption figures per country and year.

gdp_3
Stores annual GDP values used for economic and emission efficiency analysis.

📌 All tables are linked using country-based foreign key relationships, forming one-to-many relationships with the country table.

📈 Key Analytical Insights

The SQL queries in this project support multiple analytical perspectives:

🔹 1. Comparative Analysis

Top Polluters
Identifies countries with the highest total emissions in the most recent year.

Global GDP Leaders
Lists the top 5 countries by GDP to study the relationship between economic strength and energy usage.

Energy Type Impact
Determines which energy sources (Coal, Oil, Gas, etc.) contribute most to global emissions.

🔹 2. Efficiency & Ratio Analysis

Emission-to-GDP Ratio
Measures environmental efficiency by calculating CO₂ emissions per unit of GDP.

Per Capita Trends
Analyzes energy consumption and production relative to population size over time.

Consumption vs GDP
Identifies countries with high energy demand compared to their economic output.

🔹 3. Growth & Trend Tracking

Year-over-Year (YoY) Changes
Uses SQL window functions like LAG() to calculate GDP and energy production growth rates.

Emission Improvement Analysis
Tracks countries that have successfully reduced per-capita emissions over time.

Global Averages
Computes yearly global averages for GDP, emissions, and population growth.

🛠️ Technical Skills Demonstrated

Advanced SQL Joins
Combining multiple tables to analyze relationships between population, wealth, and emissions.

Window Functions
Using LAG() and OVER (PARTITION BY …) for trend and growth analysis.

Aggregations & Filtering
Effective use of GROUP BY, HAVING, subqueries, and conditional filtering.

Database Normalization
Proper use of primary and foreign keys to maintain a clean and scalable schema.

This project demonstrates how SQL can be used for large-scale analytical problem solving, providing insights into global energy usage, economic growth, and environmental impact through a well-structured relational database.
