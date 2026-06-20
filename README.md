#  Weather App

*COMPANY*: CODTECH IT SOLUTIONS
*NAME*: ANSH SHARMA
*INTERN ID*:CTIS6655
*DOMAIN*: FULL STACK WEB DEVELOPMENT
*DURATION*: 16 WEEKS
*MENTOR*: NEELA SANTOSH

*Output*

![image alt](https://github.com/ANSH-SHARMA912/API-INTEGRATION/blob/c741b8d6f3137615f0668aaa21a5b6b4d0a6531f/Screenshot%202026-06-20%20133516.png)


A responsive Weather Application built using **HTML, CSS, and JavaScript** that fetches real-time weather information from the **WeatherAPI**. Users can search for any city and instantly view the current weather conditions, including temperature, humidity, wind speed, and weather status.

---

## Project Overview

This project demonstrates **API Integration** by consuming a public weather API and dynamically displaying real-time data on a responsive webpage.

It fulfills the following requirements:

* Fetch data from a public API
* Display data dynamically
* Responsive user interface
* User-friendly search functionality
* Error handling for invalid inputs

---

##  Features

*  Search weather by city name
*  Displays current temperature
*  Shows weather condition
*  Displays humidity
*  Displays wind speed
*  Dynamic weather icons
*  Handles invalid city names
*  Responsive design for desktop and mobile
*  Press **Enter** to search instantly

---

##  Technologies Used

* HTML5
* CSS3
* JavaScript (ES6)
* Fetch API
* WeatherAPI

---

##  Project Structure

```
Weather-App/
│
├── index.html
├── README.md
```

---

##  API Used

**WeatherAPI**

Provides real-time weather information for cities across the world.

API Endpoint:

```
https://api.weatherapi.com/v1/current.json
```

Required Parameters:

| Parameter | Description             |
| --------- | ----------------------- |
| key       | API Key                 |
| q         | City Name               |
| aqi       | Air Quality Information |

Example Request:

```
https://api.weatherapi.com/v1/current.json?key=YOUR_API_KEY&q=Delhi&aqi=yes
```

---

##  How to Run the Project

### Step 1

Clone the repository

```bash
git clone https://github.com/your-username/weather-app.git
```

### Step 2

Navigate into the project folder

```bash
cd weather-app
```

### Step 3

Open the project

Simply open **index.html** in any modern web browser.

No additional installation or dependencies are required.

---

##  Application Preview

The application consists of:

* Search bar for city input
* Search button
* Weather icon
* City and country name
* Temperature
* Weather condition
* Humidity card
* Wind speed card
* Error message for invalid city

---

##  Responsive Design

The webpage is designed to work across:

* Desktop
* Laptop
* Tablet
* Mobile devices

---

##  Workflow

```
User enters city
        │
        ▼
Search Button / Enter Key
        │
        ▼
Fetch Request sent to WeatherAPI
        │
        ▼
Receive JSON Response
        │
        ▼
Extract Weather Details
        │
        ▼
Display Data Dynamically
```

---

##  Error Handling

The application validates user input and displays appropriate messages for:

* Empty input field
* Invalid city name
* API request failure

---

##  Learning Outcomes

Through this project, the following concepts were implemented:

* REST API Integration
* Fetch API
* Asynchronous JavaScript (async/await)
* JSON Parsing
* DOM Manipulation
* Event Handling
* Responsive Web Design
* Error Handling

---

##  Future Enhancements

* 5-Day Weather Forecast
* Dark/Light Theme
* Current Location Weather (Geolocation)
* Weather Search History
* Air Quality Index Card
* Sunrise & Sunset Details
* Temperature Unit Toggle (°C / °F)


