# ML-LocationBasedAnalysis
Task: Location-Based Analysis of Restaurants

Objective
Perform a geographical analysis of restaurants using location-based attributes such as latitude,
longitude, city, and locality.

Project Description
This project analyzes the spatial distribution and performance of restaurants across different cities
and localities. It combines geospatial visualization with statistical analysis to uncover patterns
related to restaurant concentration, ratings, pricing, cuisine diversity, and service availability

Step 1: Data Cleaning and Preparation
• Loaded the restaurant dataset using Pandas.
• Removed records with missing latitude or longitude values.
• Performed basic statistical analysis on geographical coordinates.
Step 2: Geospatial Visualization
• Calculated the average latitude and longitude to center the map.
• Created an interactive map using Folium.
• Used marker clustering to efficiently visualize large numbers of restaurants.
• Displayed restaurant details such as name, rating, and cuisine in map popups.
Step 3: Location-Based Aggregation
• Grouped restaurants by city and locality to measure concentration.
• Identified top cities and localities based on restaurant count.
• Visualized city-level concentration using bar charts.
Step 4: Statistical Analysis
• Calculated average ratings and price ranges for each city.
• Analyzed cuisine diversity using unique cuisine counts.
• Compared price range versus average rating across cities.
Step 5: Insight Discovery
• Analyzed the relationship between pricing and restaurant ratings.
• Evaluated online delivery availability patterns by locality.
• Identified hidden gem localities with high ratings but low vote counts.

How to Run the Project
• Install required libraries: pandas, folium, matplotlib, seaborn.
• Place the dataset file in the project directory and name it 'Dataset .csv'.
• Run the Python script or Jupyter Notebook.
• Interactive maps and visualizations will be generated automatically.
