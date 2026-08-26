# Week 7: Data Pipelines & Automation

## Project Overview

This project focuses on building a simple ETL (Extract, Transform, Load) pipeline using real-time weather data from the OpenWeather API.

The main objective is to collect weather data from different cities, clean and transform the data using Python and Pandas, store the processed data in a CSV file, and perform basic analysis.

## Data Source

The data was collected using the OpenWeather API.

Three cities were selected for this project:

- Djibouti
- Paris
- Istanbul

The following weather information was collected:

- City Name
- Temperature
- Humidity
- Weather Condition
- Wind Speed
- Date and Time

## ETL Process

### 1. Extract

Weather data was extracted from the OpenWeather API using Python and the Requests library.

The API was queried for three cities: Djibouti, Paris, and Istanbul.

The extracted data included temperature, humidity, weather condition, wind speed, and date and time.

### 2. Transform

The extracted data was organized and cleaned using Pandas.

The transformation process included:

- Creating a structured DataFrame
- Checking the dataset structure
- Checking for missing values
- Checking data types
- Rounding numerical values
- Preparing the dataset for analysis

### 3. Load

The transformed dataset was saved as a CSV file:

`weather_data.csv`

This file can be reused for future analysis.

### 4. Basic Analysis

The processed dataset was analyzed to compare weather conditions across the three cities.

The analysis focused on:

- Comparing temperatures
- Identifying the city with the highest humidity
- Comparing weather conditions

## Tools Used

- Python
- Pandas
- Requests
- Google Colab
- OpenWeather API
- GitHub

## Key Findings

Based on the weather data collected:

- Djibouti recorded the highest temperature at **38.04°C**.
- Istanbul recorded the highest humidity at **88%**.
- Djibouti and Istanbul had **clear sky** conditions.
- Paris had **overcast clouds**.
- Djibouti recorded the lowest wind speed among the three cities.

## Project Structure

```text
Week-7-Data-Pipeline/
│
├── Week_7_ETL.ipynb
├── weather_data.csv
└── README.md
