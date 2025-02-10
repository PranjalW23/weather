# Exp 2: Weather Data Using AJAX

## Overview
This is a real-time weather web application built using HTML, CSS, and JavaScript. It fetches weather data from the OpenWeatherMap API using AJAX and displays it in a user-friendly format.

## Features
- User can enter a city name to get real-time weather information.
- Uses AJAX (Fetch API) to retrieve data from OpenWeatherMap API.
- Displays temperature, humidity, wind speed, pressure, sunrise, sunset, and weather condition.
- Shows corresponding weather icons using symbols (e.g., ☀️ for clear, 🌧️ for rain, etc.).
- Includes a loading indicator while fetching data.
- Bootstrap-based responsive design.

## Technologies Used
- HTML
- CSS (Bootstrap for styling)
- JavaScript (AJAX for API requests)
- OpenWeatherMap API

## How to Use
1. Open the `index.html` file in a browser.
2. Enter a city name in the input field.
3. Click the 'Get Weather' button.
4. The weather details will be displayed on the screen.

## API Configuration
- This project uses the OpenWeatherMap API.
- Replace `apiKey` in the JavaScript file with your own API key from OpenWeatherMap.

## Example API Request
```
https://api.openweathermap.org/data/2.5/weather?q={city name}&appid={API key}&units=metric
```

## Future Improvements
- Add auto-suggestions for city names.
- Display a 5-day weather forecast.
- Improve UI with more styling and animations.

## Author
Developed by Pranjal Wadher
---
### 🔗 **Project Preview**
https://pranjalw23.github.io/weather


