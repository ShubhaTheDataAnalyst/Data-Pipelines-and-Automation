# 🌦️ Weather ETL Pipeline using OpenWeather API

## 📌 Project Overview

This project demonstrates a basic ETL (Extract, Transform, Load) pipeline using real-time weather data from the OpenWeather API. The weather data is extracted for multiple cities, transformed into a clean and structured format using Pandas, and loaded into CSV, Excel, and SQLite for future analysis. Basic data analysis and visualizations were also performed to compare weather conditions across cities.

---

## 🎯 Objectives

- Retrieve real-time weather data using the OpenWeather API.
- Clean and transform the extracted data.
- Store the processed data in different formats.
- Perform basic weather analysis.
- Visualize weather data using Python.

---

## 📂 Data Source

- **API:** OpenWeather API
- **Website:** https://openweathermap.org/api

### Data Collected

- City Name
- Temperature (°C)
- Humidity (%)
- Weather Condition
- Wind Speed (m/s)
- Date & Time

---

## 🔄 ETL Process

### Extract

- Created an OpenWeather account.
- Generated an API key.
- Connected to the API using the Requests library.
- Retrieved weather data for seven cities.
- Extracted the required weather fields from the JSON response.

### Transform

- Converted JSON data into a Pandas DataFrame.
- Renamed columns for better readability.
- Converted Date & Time to datetime format.
- Rounded numerical values.
- Checked for missing values.
- Checked for duplicate records.
- Prepared a clean dataset for analysis.

### Load

Saved the processed dataset in:

- CSV File (`weather_data.csv`)

---

## 📊 Data Analysis

Performed the following analysis:

- Compared temperatures across cities.
- Identified the city with the highest humidity.
- Compared weather conditions.
- Calculated the average temperature.
  
- ----- Weather Analysis Summary -----

Temperature Comparison
      City  Temperature (°C)
0    Delhi             36.07
1   Mumbai             28.93
2  Chennai             31.99
3  Kolkata             30.15
4    Kochi             25.51
5   Bhopal             28.77
6   Shimla             21.35

Highest Temperature
Delhi - 36.07 °C

Highest Humidity
Kochi - 88 %

Weather Conditions
      City Weather Condition
0    Delhi         clear sky
1   Mumbai        few clouds
2  Chennai   overcast clouds
3  Kolkata   overcast clouds
4    Kochi   overcast clouds
5   Bhopal  scattered clouds
6   Shimla         clear sky

Average Temperature
28.97 °C

---

## 📈 Visualizations

The following charts were created using Matplotlib:

- Temperature Comparison (Column Chart)
<img width="640" height="480" alt="temperature_chart" src="https://github.com/user-attachments/assets/05c32085-d311-49d5-aa9a-c807998e5c49" />

- Humidity Comparison (Horizontal Bar Chart)
  <img width="640" height="480" alt="humidity_chart" src="https://github.com/user-attachments/assets/be41bdb7-51a2-4525-b479-857bfe02e99e" />

- Weather Condition Distribution (Pie Chart)
<img width="640" height="480" alt="weather condition_chart" src="https://github.com/user-attachments/assets/d293e552-5384-4444-9e70-b60c4f187079" />

- wind speed (column chart)
<img width="640" height="480" alt="wind speed_chart" src="https://github.com/user-attachments/assets/cccc8e37-27d3-4cf9-8c20-8364efa728cd" />

---

## 🛠 Tools & Libraries

- Python
- Pandas
- Requests
- Matplotlib
- OpenWeather API
- Jupyter Notebook

---

## 📌 Key Findings

- Delhi recorded highest temparature among 7 Indian Cities followed by Chennai.
- Kochi recorded highest Humidity.
- Wind Speed in Bhopal is higher than other cities.
- Weather Condition for Maximum cities recorded Mostly Overcast Clouds.
---

## 🚀 Skills Demonstrated

- API Integration
- ETL Pipeline
- Python Programming
- Data Cleaning
- Data Transformation
- Data Analysis
- Data Visualization
- Pandas
- Matplotlib
- GitHub Documentation

---

## 🙏 Acknowledgements

This project was completed as part of the **Week 7 – Data Pipelines & Automation** assignment during the **AnalystLab Africa Data Analytics Internship**.
