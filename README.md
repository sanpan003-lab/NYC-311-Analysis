# NYC-311-Analysis
Analyzing NYC 311 service request data to predict response times.

NYC 311: Predicting City Service Response Times

Project Overview
This project analyzes thousands of service requests submitted to New York City’s 311 system. The goal is to determine if the type of complaint significantly impacts the time it takes for city agencies to resolve the issue. By calculating "Resolution Hours," this analysis identifies which city services are most efficient and which ones experience the longest delays.

The Problem
City resources are often stretched thin. For residents and city planners, knowing the expected turnaround time for a complaint (like a noise violation vs. a broken water main) is vital for setting expectations and improving municipal transparency.

Data & Methodology
Source: NYC Open Data - 311 Service Requests (via SODA API).

Tools: Python, Pandas, Matplotlib, and Seaborn.

Data Cleaning: Real-world data is rarely perfect. I handled thousands of rows, converted date strings into datetime objects, and removed records with missing "Closed Dates" to ensure an accurate calculation of resolution times.

Key Insights
The Efficiency Leaders: The data shows that high-volume complaints, such as "Noise - Commercial" and "Illegal Parking," are typically resolved much faster, often within a few hours.

Complex Infrastructure Issues: More technical complaints, such as "Street Conditions" or "Water System" issues, show a much wider distribution of resolution times, reflecting the complexity of the repairs involved.

Data Quality Challenges: A significant portion of the work involved cleaning "outliers"—cases where resolution times appeared abnormally high due to data entry delays rather than actual service speed.

Conclusion
This project demonstrates how data cleaning and visualization can turn a massive civic dataset into actionable insights. While NYC is generally efficient at handling high-visibility public nuisances, the data suggests that infrastructure-heavy requests require more specialized resource allocation to speed up completion.
