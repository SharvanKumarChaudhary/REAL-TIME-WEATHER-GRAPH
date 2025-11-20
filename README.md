# REAL-TIME-WEATHER-GRAPH
# PROJECT BASED LEARNING (PBL) REPORT
# PROJECT NAME: REAL TIME WEATHERGRAPH
*COURSE NAME*: PYTHON LAB – 5.0CE252E02
*STUDENT NAME*: SHARVAN KUMAR CHAUDHARY
*ROLL NO*: 1/24/SET/BCS/263
*SEMESTER*: 3RD
*SECTION*: D2
*DEPARTMENT & UNIVERSITY*: CSE, SET, MRIIRS
*FACULTY MENTOR*: NEHA BATRA
*DATE OF SUBMISSION*: 20-11-2025


## Introduction:
## The Real-Time Weather Graph System is a Python-based project designed to fetch, analyze, and visualize live temperature data for any city using the OpenWeatherMap API. The project uses external APIs along with data visualization libraries to present weather trends in a clear and graphical format. Each API response contains time-stamped temperature values, which are plotted to understand weather changes over the next few hours or days.

## The main objectives of the project are: 
 • To fetch real-time weather forecast data using API calls.
 • To extract temperature and time information from JSON responses.
 • To plot the temperature variation using line graphs for better visualization.
 This project solves the problem of manually checking weather updates by giving users an          automated and graphical display of temperature forecasts. The expected outcomes include           understanding API integration, JSON data handling, data visualization using                      Matplotlib/Seaborn, and building real-time analytical tools in Python.

## Libraries Used:
 Since the project is developed in Python, the following libraries are used:
  • requests – for making API calls to fetch real-time weather data from OpenWeatherMap
  • matplotlib.pyplot – for plotting the temperature graph
  • seaborn – for enhancing the visual appearance of the graph
  • json (built-in) – for handling and parsing API response data
  • datetime (built-in) – for formatting and managing date/time information (if required)
  No external frameworks were required because the entire functionality, including data fetching   and visualization, is implemented using standard Python libraries.

## Methodology:
The overall workflow of the Real-Time Weather Graph System includes:
  1.	Sending an API request to OpenWeatherMap using the requests library to fetch live weather        forecast data.
  2.	Receiving and parsing the JSON response to extract temperature values and their                  corresponding timestamps.
  3.	Storing the extracted data into separate lists for dates and temperatures.
  4.	Using the matplotlib and seaborn libraries to plot a line graph representing temperature         variation over time.
  5.	Applying graph formatting techniques such as axis labeling, rotation of date labels, and         setting the graph title.
  6.	Testing the system by entering different city names and verifying that the temperature           forecast graph is displayed correctly.

## Implementation:
 The implementation consists of four main parts:
 
  Step 1: Fetching Weather Data (API Call)
    The program sends a request to the OpenWeatherMap API using the requests library.
    The API returns a JSON response containing temperature forecasts and timestamps for the          selected city.

  Step 2: Extracting Temperature and Time Information
    The JSON response is parsed to retrieve:
    • Date and time (dt_txt)
    • Temperature (main['temp'])
    These values are stored into separate lists for plotting.
    
  Step 3: Plotting the Temperature Graph
    Using matplotlib and seaborn, a line graph is created:
    • X-axis shows date & time
    • Y-axis shows temperature in °C
    The graph is formatted using labels, title, marker points, and rotated timestamps for clear      readability.
    
  Step 4: Testing With Multiple Cities
    The program is tested by entering different city names (e.g., Delhi, Mumbai, Chennai).
    Each test verifies that the API returns valid data and the graph successfully updates based       on user input.

Output:
<img width="1480" height="556" alt="Image" src="https://github.com/user-attachments/assets/2cec8ffe-e01b-49ab-b87c-8ba589ea7eac" />
