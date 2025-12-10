# Global-CO-Emissions-Dashboard-Power-BI
A comprehensive analysis of global CO₂ emissions from 2010–2023 using publicly available data. This project demonstrates data cleaning, transformation, DAX modeling, and interactive Power BI visualization to uncover major environmental insights.

Project Overview -
This project analyzes global CO₂ and GHG emissions using a country-wise dataset containing yearly emission metrics, economic indicators, and energy usage.
The dashboard explains:
• Global trends in CO₂ emissions
• Top emitting countries and regional behaviour
• Factors influencing emissions
• Per-country deep-dive
• Insights derived from time-series & influencer visuals

Dataset
Source: Our World In Data (OWID) – CO₂ & Greenhouse Gas Emissions Dataset

Final cleaned dataset includes:-
•	Country, Year, ISO code
•	Population
•	GDP
•	CO₂ Emission
•	CO₂ Per Capita
•	Coal, Oil, Gas, Cement CO₂
•	Total GHG
•	Methane & Nitrous Oxide
•	Energy indicators (Energy per capita, Energy Intensity, Energy per GDP)
•	Other Calculated columns for analysis (Total Fossil & Fossil Share)

All data for non-country aggregates (World/Continents/Income Groups) were removed.

Data Cleaning & Preparation -
Cleaning was done in Excel, and modeling in Power BI.
Steps Performed -
•	Removed aggregate rows (World, continents, income groups)
•	Standardized column names
•	Replaced missing emission values with 0
•	Kept GDP & population blank when entire country-year was missing
•	Validated Total GHG from OWID (CH₄ & N₂O already in CO₂-equivalent)
•	Added calculated helper fields:
- Total Fossil = Coal + Oil + Gas
-	YoY CO₂ Growth (absolute + %)
•	Ensured correct data types & year sorting
•	Verified country grouping for proper time intelligence

Key Insights
•	Global CO₂ emissions continue to rise, driven by population and economic expansion.
•	China, US, India, and Russia dominate global emissions.
•	GDP and population are major influencing factors (Key Influencer visual).
•	Coal is the largest contributor to emissions worldwide.
•	Future trend shows continued emission growth.




