# Weather Report App

A simple and user-friendly web application to retrieve and display weather information for a specified city. This application fetches data from the Open-Meteo API, eliminating the need for an API key.

## Features

*   **City Input:** Allows users to enter a city name to get the weather.
*   **Current Weather:** Displays current temperature in Celsius (°C) and Fahrenheit (°F), a textual weather description (e.g., "Clear sky"), wind speed in km/h and mph, and wind direction as both degrees and a textual description (e.g., "North").
*   **2-Day Weather Forecast:** Provides a 2-day forecast including the date and day of the week, high and low temperatures in both Celsius and Fahrenheit, the maximum precipitation probability, and the total precipitation amount in mm for each day.
*   **3-Hour Precipitation (Current Day):** Shows the estimated total precipitation amount in mm for three hours of the current day and time. The time range is displayed using 24-hour nomenclature.
*   **Clear Presentation:** Weather data is presented clearly and legibly.
*   **Error Handling:** Includes robust error handling to display user-friendly messages if the API cannot retrieve data or if the entered city is not found.
*   **Save Report:** If weather data is successfully retrieved, a "Save Report" button appears. Clicking this button generates a text file (`Weather report for [City Name] [Timestamp].txt`) containing the weather report.
*   **User Interface:** Features a clean, modern, and user-friendly design styled with **Tailwind CSS**. The layout is responsive.

## Technologies Used

*   HTML5
*   CSS
*   JavaScript
*   [Open-Meteo API](https://open-meteo.com/) for weather data
*   [Tailwind CSS](https://tailwindcss.com/) for styling

## Usage

1.  Open the html file in your web browser.
2.  Enter the name of a city in the input field.
3.  Click the "Get Weather" button.
4.  The weather information for the entered city, including the current weather and a 2-day forecast, will be displayed.
5.  If the weather data is successfully retrieved, a "Save Report" button will appear. Click this button to save the weather report as a text file.
6.  In case of errors (e.g., city not found, API issues), an appropriate error message will be shown in the web application.

## Data Processing

*   Wind angles are converted to textual descriptions (e.g., 90° to "East").
*   Total precipitation is calculated for each day.
*   The 3-hour precipitation amount for the current day and time is calculated.
*   Temperature is displayed in both Celsius and Fahrenheit.
*   Date and time are formatted consistently.

## Open-Meteo API

This application utilizes the Open-Meteo API ([https://open-meteo.com/](https://open-meteo.com/)) to fetch weather data. This API provides free access to global weather forecasts and historical climate data without the need for API keys, making it convenient for this project.
