# WeatherChecker 🌦️

WeatherChecker is a simple web-based application that displays current weather information for a user-provided city. This project is built with HTML, CSS, and JavaScript and integrates the OpenWeatherMap API to retrieve real-time weather data.

## Features

- Shows the current temperature, humidity, and wind speed of any city.
- Displays a weather icon that matches the current weather condition (e.g., clear, clouds, rain, mist, snow).
- Displays an error message if the city name is invalid or not found.

## Project Structure

- `index.html`: HTML structure of the app, with input for city search and placeholders for displaying weather data.
- `style.css`: Basic styling for a responsive layout.
- `script.js`: JavaScript for handling API requests, displaying weather data, and updating the interface.

## Usage

1. Type a city name in the search bar and click the search button.
2. The app displays the current weather information for that city, including:
   - Temperature in Celsius
   - Humidity percentage
   - Wind speed in km/h
   - Icon representing the weather condition

## API Integration

WeatherChecker uses the [OpenWeatherMap API](https://openweathermap.org/api) to fetch data. You'll need to sign up for an API key and replace it in the code as noted above.

## Error Handling

If the user inputs an invalid city name, an "Invalid city name" message appears, and the weather data section is hidden.

