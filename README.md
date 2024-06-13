# Indian Weather Analysis
This project aims to analyze weather data from various locations in India, focusing on temperature and air quality. The analysis includes calculating statistics such as average, maximum, and minimum temperatures, and exploring trends over time.

## Table of Contents
Introduction
Data
Setup
Analysis
Visualizations
Results
Contributing
License
## Introduction
This project involves analyzing weather data from different regions in India. The dataset includes information about temperature and air quality (PM2.5 and PM10 levels). The goal is to gain insights into weather patterns and air quality across various locations and over time.

## Data
The dataset IndianWeatherReport.csv contains the following columns:

location_name: Name of the location
region: The region where the location is situated
temperature_celsius: Temperature in Celsius
air_quality_PM2.5: PM2.5 air quality index
air_quality_PM10: PM10 air quality index
date: Date of the observation
##Setup
To run the analysis, follow these steps:

1. Clone the repository:
   git clone https://github.com/prashn8/indian-weather-analysis.git
2. Navigate to the project directory:
   cd indian-weather-analysis
3. Install the required packages:
   pip install pandas
   pip install numpy
   pip install seaborn mapplotlib
5. Ensure you have the IndianWeatherReport.csv file in the project directory.

## Analysis
The analysis includes the following steps:

1. Data Loading and Cleaning:

  Load the dataset.
  Check for null values and data types.
  Filter data by specific location (e.g., Rewa).
2. Statistical Analysis:

  Calculate average, maximum, and minimum temperatures for specific locations.
  Group data by region and calculate mean temperatures.
  Group data by location and calculate mean air quality indices.
3. Top Locations:
   Identify the top five hottest and coldest locations based on temperature.
## Visualizations
  Various visualizations are created to represent the data and findings:

1. Temperature Over Time for Rewa:

Line plot showing temperature changes over time.
2. Air Quality Across Regions:

Box plot showing PM2.5 air quality across different regions.
3. Temperature by Region:

Box plot showing temperature distribution across regions.
4. Temperature Trend Over Time:

Scatter plot with trend line for temperature over time for Rewa.
5. Air Quality Distribution:

Violin plot showing PM2.5 air quality distribution across regions.
6. Top 10 Hottest Locations:

Pie chart showing the top 10 hottest locations and their temperatures.
## Results
The analysis reveals significant insights into the weather patterns and air quality across different regions in India. For instance, the average, maximum, and minimum temperatures for Rewa, as well as trends over time, provide a detailed understanding of the climatic conditions in that specific location.

## Contributing
Contributions are welcome! Please feel free to submit a pull request or open an issue to discuss any changes or improvements.
